# Checkpoint Answers Chapter 1 #
## 1.1 ##
A computer is said to be made up of hardware and software. 

Hardware are the different devices either installed in or connected to the computer. For example the drives, screen, keyboard, and motherboard.

Software is a set of instructions that are interpreted and executed by the hardware.

## 1.2 ##
Five major computer hardware components are  
1. Processor  
2. Memory  
3. Hard drive  
4. Screen  
5. Keyboard   

## 1.3 ##
CPU stands for Central Processing Unit.

## 1.4 ##
One unit used when measuring CPU speed is Hertz.  

## 1.5 ##
A bit is the basic unit of information in computing. A bit can only have one of two values. These values are commonly represented as 0 or 1.  

A byte is a unit of information in computing that most commonly consists of eight bits.  

## 1.6 ##
Memory is special hardware used for holding information while executing a software. RAM stands for Random Access Memory. The name RAM indicates that any part of the memory can be read and written in roughly the same amount of time.  

## 1.7 ##
Memory size is, at the time of writing, often measured in gigabyte (GB).  
  
## 1.8 ##
The unit to measure disk size is, at the time of writing, often measured in gigabyte (GB) or terabyte (TB).  

## 1.9 ##
The difference between memory and a storage device is usually that a memory will lose its content if the computer is powered off as opposed to a storage device where the memory is more or less permanent.  

## 1.10 ##
A CPU only understand instructions written in machine language. Each CPU family uses its own version of the machine language.  
## 1.11 ##
Assembly language is a low-level programming language in which there is a very strong correspondence between the language and the architecture's machine code.  

## 1.12 ##
An assembler translates assembly-language instructions into machine code.  

## 1.13 ##
The main difference between a high-level language and a low level language is that the former is platform independent and written in a more human friendly way.  

## 1.14 ##
A source program is a program written in a high-level language that needs further transformation before the computer can use it.  

## 1.15 ##
An interpreter translates small parts of source code, more or less line by line, into machine code that then are executed by the computer directly.  

## 1.16 ##
A compiler takes one or more files with high level source code and builds a machine language program that is stored in a file. This machine code file is then used at a later stage when the program shall run.  

## 1.17 ##
The difference between a compiler and interpreter is that an interpreter works with translation of source code to machine code in real time while the program is running. An compiler will be finished with the entire translation before the program runs.  

## 1.18 ##
An operating system (OS) is software that manages computer hardware and software resources and provides common services for computer programs. The operating system is an essential component of the system software in a computer system. Application programs usually require an operating system to function.  

Some currently popular operating systems are Windows, Linux, and Android.

## 1.19 ##
An operating system is responsible for handling of input/output devices such as keyboard mouse and screen. An operating system will also often make it possible to run several programs at once by letting each program use the CPU in short intervals and giving each application some memory that the application is allowed to read and write. An operating system is often also responsible for security, preventing unauthorized access to the system.  
 
## 1.20 ##
Multiprogramming allows multiple programs to run simultaneously by sharing the same CPU.  

Multithreading allows a single program to execute multiple tasks at the same time. In a game so can for example one task be responsible for playing sounds. While another task updates the graphics.  

Multiprocessing, or parallel processing, uses two or more processors together to perform subtasks concurrently and then combine solutions of the subtasks to obtain a solution for the entire task.  

## 1.21 ##
Initial development of Java was done at Sun Microsystems and the work was lead by James Gosling.  

Java is currently owned and developed by a company called Oracle.  

## 1.22 ##
A Java applet is a small application which is written in Java and delivered to the users over the Web. The user launches the Java applet from a web page, and the applet is then executed within in a process separate from the web browser itself.  

## 1.23 ##
Java is often used when developing Android applications. 

## 1.24 ##
The Java language specification is a technical definition of the Java programming language’s syntax and semantics.  

## 1.25 ##
JDK is an acronym for Java Development toolKit.  

## 1.26 ##
IDE is an acronym for Integrated Development Environment.  

## 1.27 ##
NetBeans and Eclipse are two different integrated development environments that can be helpful when developing Java programs.   
## 1.28 ##
A keyword is a word that has special meaning to the compiler and can hence not be used for other purposes.  

Example of keywords are:  
- class  
- public  
- static  
- void  

## 1.29 ##
Java is case sensitive.  

All keywords are written in lower case.  

## 1.30 ##
A comment is text in the source code intended for the human developers to document and explain the code.  

The compiler will ignore all comments.  

A comment line is started by writing two slashes and will then continue until the end of the line.  

I paragraph comment can span over multiple lines. This type of comment starts with a slash followed by an asterisk and ends with an asterisk followed by a slash.  

## 1.31 ##
The following statement will display a string on the console:  
```java
System.out.println("A string that will appear on the console.");
```
## 1.32 ##
The output of the following code
```java
public class Test {
	public static void main(String[] args) {
		System.out.println("3.5 * 4 / 2 - 2.5 is ");
		System.out.println(3.5 * 4 / 2 - 2.5);
	}
}
```
will be
```
3.5 * 4 / 2 - 2.5 is  
4.5
```

## 1.33 ##
The Java source file-name extension is ".java".  

The Java bytecode file-name extension is ".class".  

## 1.34 ##
The input to a Java compiler is a source file that shall have the ".java" extension.  

The output of a Java compiler is a bytecode file that will have a ".class" extension.  

## 1.35 ##
The command used to compile a Java program in the console is "javac" followed by the name of the source file.  

## 1.36 ##
The command used to run a Java program in the console is "java" followed byte the name of bytecode file. Note that the ".class" extension shall not be included in the command.  

## 1.37 ##
JVM stands for Java Virtual Machine. This is a program that can translate bytecode into machine code and in this way run a Java program.  

## 1.38 ##
Java can not be run on any machine.  

There must be a JVM installed on a machine if a Java program shall be able to run.  

## 1.39 ##
A NoClassDefFoundError indicates a class file that does not exist. 
   
## 1.40 ##
A NoSuchMethodError can be a indication that the class to be executed does not have a proper main method.  

## 1.41 ##
The following code need to be reformatted according to the programming style and documentation guidelines.  
```Java
public class Test {
	// Main method
	public static void main(String[] args)
	{
		/** Display output */
		System.out.println("Welcome to Java");
	}
}
```

The code is simple enough to read without the comments so these comments, that just crowd the code, can be removed.

Lets also change to end-of-line style block braces throughout the entire code for consistency and because this is the style used in the Java API source code.  

The result after changes will be:
```Java
public class Test {
	public static void main(String[] args) {
		System.out.println("Welcome to Java");
	}
}
```

## 1.42 ##
A syntax error is introduced when writing some code that does not follow the Java syntax rules.  

A runtime error will occur during program execution causing the program to terminate in an uncontrolled way because of some unforeseen event.  

I program with a logical error will compile and run but, does not behave as is should during execution.  

## 1.43 ##
Examples of syntax errors are misspelling of keywords, missing a terminating brace, or not ending a statement with a semicolon.  

Examples of runtime errors are not being able to handle incorrect user input. For example if a number is expected and the user writes "five" instead of 5. Or the user enters 0 and we use this to divide later on.  

Examples of logical errors are using the wrong formula for calculating something. Or not having full understanding of how some language feature actually works.  

## 1.44 ##
Forgetting to put a closing quotation mark on a string will raise a syntax error when compiling the code.  

## 1.45 ##
A program that needs to read integer, but the user enter strings will raise an runtime error, assuming we have not included special code to handle this situation.  

## 1.46 ##
Mistakenly using the wrong code, like calculating the area of a triangle instead of the area of a rectangle, introduces a logical error.  

## 1.47 ##
The following code have errors multiple errors:
```Java
public class Welcome {
	public void Main(String[] args) {
		System.out.println('Welcome to Java!);
	}
}
```
Lets fix the code.  

The name of the method "Main" is misspelled, should be "main".  

The keyword static is missing.  
  
The string in the print statement have a single apostrophe when there should be two quotation marks surrounding the string.  

A fully corrected version looks like this:  
```Java
public class Welcome {
	public static void main(String[] args) {
		System.out.println("Welcome to Java!");
	}
}
```
# Checkpoint Answers Chapter 2 #
**2.1**  
The problem with the original code, presented in the book, is that the string to be printed is split with an end-line. This is not allowed.  

The solution is to use string concatenation. Most development environments will actually insert this automatically for us these days.  

A fixed version of the code looks like this:  
```Java  
public class Test {

	public static void main(String[] args) {
		double i = 50.0;
		double k = i + 50.0;
		double j = k + 1;
		
		System.out.println("j is " + j + " and "
				+ "k is " + k);

	}

}  
``` 

**2.2**  
The Scanner class can be used for getting input from the user. An import of this class is required and the class can then be used in this way:  
```Java
Scanner input = new Scanner(System.in);
double number = input.nextDouble();
```  
The above code expects the user to enter a number. Should the user write something else like 5a so will this cause a so called Exception. This Exception must be handled in the code because the program will otherwise terminate in an uncontrolled manner.  

**2.3**  
There are no performance differences between the following two import statements.
```Java  
import java.util.Scanner;
import java.util.*;
```  

**2.4**  
The following are all valid names for identifiers:  
- miles  
- Test  
- $4  
- apps  
- x  
- y  
- radius  

The following are not valid names for identifiers because all contain characters not allowed to be used in identifiers.  
- a++   
- --a  
- #44  

This identifier name is disqualified in two ways because it starts with a number and uses a # which is not allowed.  
- 4#r 

The following are all keywords and can hence not be used as names for identifiers.  
- class  
- public  
- int  

**2.5**  
The problem with the original code, presented in the book, is that the identifier k is not declared or given a value before it is used.  

A working version of the code:  
```Java  
public class Test {

	public static void main(String[] args) {
		int k = 1;
		int i = k + 2;
		System.out.println(i);
	}

}
```  

**2.6**  
The problem with the original code, presented in the book, is the below line where the variables are declared in an invalid way.  
```Java  
int i = j = j = 2;
```  
A corrected valid code looks like this:
```Java  
int i, j, k;  
i = j = k = 2;
```  

**2.7**  
Using constants is benfical because:  
1. Can be used for replacing a long number with a short simple text in numeroues places in the code, which saves time when coding.  
2. Being able to use a descriptive name makes the code easier to read.  
3. Should the value of the constant need to be changed so will we only need to change the code at a single location.   

Here is an example of declaring a constant in Java:  
```Java  
final int SIZE = 20;
```  
**2.8**  
The following naming conventions are often used in Java code.

Variables and methods are written in lowercase. If a name is made up of several words so are the words pushed together and words following the first word will have the first letter capitalized. For example:  
```Java  
radius, getHeight, numberOfStudents
```  

Class names are written in the same way as variables and methods except that the first letter is capitalized.  

Constants are written all uppercase. An underscore is used to separate the words in constants that contain multiple words.

A constant:  
```Java  
MAX_VALUE
```  

A class:  
```Java
Test
```  

Variables or methods:
```Java  
read, readDouble
```  

**2.9**  
The following code is based on the algorithm that is described in the book.  
```Java  
public class Checkpoint_02_09 {
	
	public static void main(String[] args) {
		double miles = 100;									// step 1
		final double KILOMETERS_PER_MILE = 1.609;			// step 2
		double kilometers = miles * KILOMETERS_PER_MILE;	// step 3
		System.out.println(kilometers);						// step 4
	}

}
```  
The variable kilometers will have the value 160.9 after step 4.  

**2.10** 
The following program will print the max and min values of a number of data types.  
```Java  
public class CheckPoint_02_10 {
	
	public static void main(String[] args) {
		System.out.println("byte max: " + Byte.MAX_VALUE);   
		System.out.println("byte min: " + Byte.MIN_VALUE);
		
		System.out.println("short max: " + Short.MAX_VALUE);   
		System.out.println("short min: " + Short.MIN_VALUE);
		
		System.out.println("int max: " + Integer.MAX_VALUE);   
		System.out.println("int min: " + Integer.MIN_VALUE);
		
		System.out.println("long max: " + Long.MAX_VALUE);   
		System.out.println("long min: " + Long.MIN_VALUE);
		
		System.out.println("float max: " + Float.MAX_VALUE);   
		System.out.println("float min: " + Float.MIN_VALUE);
		
		System.out.println("double max: " + Double.MAX_VALUE);   
		System.out.println("double min: " + Double.MIN_VALUE);
	}

}

```  
Result when running the program:  
```  
byte max: 127  
byte min: -128  
short max: 32767  
short min: -32768  
int max: 2147483647  
int min: -2147483648  
long max: 9223372036854775807  
long min: -9223372036854775808  
float max: 3.4028235E38  
float min: 1.4E-45  
double max: 1.7976931348623157E308  
double min: 4.9E-324  
```  
The program will not answer the question of what type that takes the least amount of memory. But it can be concluded, by studying the numbers above, that it is byte that is cheapest to store, taking only 8 bits of memory.  

**2.11**  
Start by doing the math in your head or on paper and then run below program to verify.  
```Java
public class CheckPoint_02_11 {

	public static void main(String[] args) {
		System.out.println("56 % 6 = " + 56 % 6);   
		System.out.println("78 % -4 = " + 78 % -4);
		System.out.println("-34 % 5 = " + -34 % 5);
		System.out.println("-34 % -5 = " + -34 % -5);
		System.out.println("5 % 1 = " + 5 % 1);
		System.out.println("1 % 5 = " + 1 % 5);
	}

}  
```  
Result from the program:  
```  
56 % 6 = 2  
78 % -4 = 2  
-34 % 5 = -4  
-34 % -5 = -4  
5 % 1 = 0  
1 % 5 = 1  
```
  
**2.12**  
The weekday 100 days after a Tuesday can be calculated using the modulo operator.  

Tuesday is day 2 in the week, and there are 7 days in a week. We want the day after 100 days. The calculation of this will be:  
```  
(2 + 100) % 7 = 4
```  
The result is 4 indicating the fourth day in a week, meaning that the answer is Thursday.

**2.13**  
The result of integer division will always be an integer. Eventual fraction will be truncated away. This means that 25 / 4 becomes 6 instead of 6.25.  

A common way to achieve floating-point number division, that preserves the decimal part, is to add a dummy decimal 0. The result of for example 25.0 / 4 will become 6.25.  

**2.14**  
The following code  
```Java  
public class CheckPoint_02_14 {

	public static void main(String[] args) {
		System.out.println(2 * (5 / 2 + 5 / 2));
		System.out.println(2 * 5 / 2 + 2 * 5 / 2);
		System.out.println(2 * (5 / 2));
		System.out.println(2 * 5 / 2);
	}

}
```  
produces this output  
```  
8  
10  
4  
5  
```  

**2.15**  
The following code is valid   
```Java  
public class CheckPoint_02_15 {

	public static void main(String[] args) {
		System.out.println("25 / 4 is " + 25 / 4);
		System.out.println("25 / 4.0 is " + 25 / 4.0);
		System.out.println("3 * 2 / 4 is " + 3 * 2 / 4);
		System.out.println("3.0 * 2 / 4 is " + 3.0 * 2 / 4);
	}

}
```  
and produces this output  
```  
25 / 4 is 6
25 / 4.0 is 6.25
3 * 2 / 4 is 1
3.0 * 2 / 4 is 1.5
```  

**2.16**  
A statement to display 2<sup>3.5</sup> can be written like this  
```Java  
System.out.println(Math.pow(2, 3.5));
```  

**2.17**  
A statement that returns a floating point result of mr<sup>2</sup>, where m and r are integers, can be written  like this  
```Java  
System.out.println(1.0*m*Math.pow(r, 2));  
```  

**2.18**  
A float have 7 to 8 significant digits.  

A double have 15 to 17 significant digits.  

**2.19**  
All of the following values are correct literals.  
```
12.3, 12.3e+2, 23.4e-2, -334.4, 20.5, 39F, 40D  
```
All values are treated as double, except 39F that is considered to be float since it is marked with a F.  

**2.20**  
`52.534` can optionally be written as `5.2534e+1`, `0.52534e+2`, or `525.34e-1`. But it can not be written as `5.2334e+0` because this would mean `5.2534e`.  

**2.21**  
`5_2534e+1` is a valid double literal.  
`_2534` is not a valid literal because it begins with an underscore, it would however be a valid variable name.  
`5_2` is a valid int literal.  
`5_` is not a valid literal because it ends with an underscore.  

**2.22**  
Examples of arithmetic expressions written in Java.  
**a.**     
```Java  
4 / (3 * (r + 34)) - 9 * (a + b * c) + (3 + d * (2 + a)) / (a + b * d)
```  
**b.**  
```Java  
5.5 * Math.pow(r + 2.5, 2.5 + t)
```  
**2.23**  
The current time is obtained by calling 
```
System.currentTimeMillis()
```
that give the number of milliseconds passed since 01-01-1970, 00:00:00 GMT.  

It is then just some arithmetic calculations that is needed to transform this value to hours, minutes, and seconds. There is an detailed example program in the book that do these calculation, so there is no need to repeat them here.  

**2.24**  
The following program  
```Java  
public class CheckPoint_02_24 {
	
	public static void main(String[] args) {
		double a = 6.5;
		
		a += a + 1;
		System.out.println(a);
		
		a = 6;
		a /= 2;
		System.out.println(a);
	}

}
```
will output
```
14.0  
3.0    
```

**2.25**  
**a.**  
An expression can be used as a statement, just by adding a semicolon, if it has a side effect. This means that `i + 1;` is not a valid statement, but `i++;` is a valid statement because it has the side effect that it changes the value of i.  
**b.**  
`x++` can as explained above, be used as a statement.  
**c.**  
It is true that the statment `x = x + 5` is also an expression.  
**d.**  
The statment `x = y = x = 0` is legal.  

**2.26**  
The following program    
```Java  
public class CheckPoint_02_26 {

	public static void main(String[] args) {
		int a = 6;
		int b = a++;
		System.out.println(a);
		System.out.println(b);
		a = 6;
		b = ++a;
		System.out.println(a);
		System.out.println(b);
	}

}  
```
will output  
```  
7  
6  
7  
7  
```  
**2.27**  
Different types of values can be used together.  

An automatic conversion will happen when a value is assigned to a variable of a type that have a larger range.  

It is also possible to assign a value to a variable that have smaller range. This can cause loss of information so a cast must be used to indicate that we are aware of what we are doing. We will then need to somehow keep control over the ranges so that no vital information is lost in the process.  

**2.28**  
The fractional part of a double value will be truncated when casting to an int.  

Casting does not change the variable being cast.  

**2.29**  
The following program  
```Java  
public class CheckPoint_02_29 {

	public static void main(String[] args) {
		float f = 12.5F;
		int i = (int)f;
		System.out.println("f is " + f);
		System.out.println("i is " + i);
	}

}
```  
will output  
```  
f is 12.5
i is 12
```  

**2.30**  
Changing `(int)(tax * 100) / 100.0` to `(int)(tax * 100) / 100` in Listing 2.8 of the book, will cause int division to be used instead of double division. This will mean that all decimals will be truncated away. So a run of the program can then look like this  
```
Enter purchase amount: 197.55  
Sales tax is $11  
```

**2.31**  
The following program  
```Java   
public class CheckPoint_02_31 {

	public static void main(String[] args) {
		double amount = 5;
		System.out.println(amount / 2);
		System.out.println(5 / 2);
	}

}
```
will output  
```
2.5  
2  
```  

**2.32**  
The following code snippet shows how to write a slightly more advanced arithmetic expression that involves square root among other things.  
```Java  
(-b + Math.sqrt((Math.pow(b, 2) - 4 * a * c))) / (2 * a)  
```  

**2.33**  
Running the program ComputeChange, from book listing 2.10, with the input 1.99 produces the following output.  
```  
Your amount 1.99 consists of  
 1 dollars  
 3 quarters  
 2 dimes  
 0 nickels  
 4 pennies  
``` 

**2.34**  
It is not allowed to declare a variable as int and then later redeclare it as double.  

**2.35**  
Numbers are stored with a limited numbers of digits. When a variable is assigned a value that is too large (in size) to be stored, it causes overflow. An integer overflow is when a variable of type int overflows.  

Just as with integer arithmetic, floating point arithmetic operations can cause overflow.  

**2.36**  
An overflow will not cause a runtime error.  

**2.37**  
Round off errors are introduced because some numbers are stored as approximations off the exact mathematical value.   

There are no round-off errors caused by integer operations. The exception to this rules is that values can be truncated when doing division but this does not really count as an round off error.  

Floating-point operations will frequently cause round-off errors.  

# Checkpoint Answers Chapter 3 #
## 3.1 ##
Examples of relational operators are:
```
<    less than  
<=   less than or equal to  
>    greater than  
>=   greater than or equal to  
==   equal to  
!=   not equal to
```  

## 3.2 ##
Below are some Boolean expressions with comments about the resulting values.  
```
x = 1  
(x > 0)   // true  
(x < 0)   // false
(x != 0)  // true
(x >= 0)  // true
(x != 1)  // false
```  

## 3.3 ##
It is now allowed to cast from an boolean to an int in Java, neither is it allowed to cast from an int to an boolean.  

This means that the following program will not compile.  
```Java  
public class CheckPoint_03_03 {

	public static void main(String[] args) {
		boolean b = true;
		i = (int)b;					// error
		
		int i = 1;
		boolean b = (boolean)i;		// error
	}

}

```  
##3.4##
An if statement that assigns 1 to x if y is greater than 0:  
```Java
if(y > 0)  
	x = 1;  
```  
##3.5##
An if statement that increases pay by 3% if score is greater than 90:  
```Java  
if(score > 90)  
	pay *= 1.03;  
```  

##3.6##
An if statement that increases pay by 3% if score is greater than 90 and otherwise increases pay by 1%.  
```Java  
if(score > 90)  
	pay *= 1.03;
else
	pay *= 1.01;
```   

##3.7##
**(a)**  
There is a logical error in this code for this checkpoint. The output will when number is 30 be:  
```
30 is even.  
30 is odd.
```
When number is 35 so will the output be:  
```
35 is odd.  
```
**(b)**  
The second version of the code is corrected and will when number is 30 output:
```  
30 is even.
```
When number is 35 so will the output, as in the first verison, be:  
```
35 is odd.  
```

##3.8##
There will be no output if x = 3 and y = 2.  

The ouput will be `z is 7` if x = 3 and y = 4.  

The ouput will be `x is 2` if x = 2 and y = 2.  

![](https://github.com/HenrikSamuelsson/Introduction_to_Java_Programming/blob/master/Chapter_03/Resources/check_point_03_08.png)

##3.9##
There will be no output if x = 2 and y = 3.  

The ouput will be `x is 3` if x = 3 and y = 2.  

The ouput will be `z is 6` if x = 3 and y = 3.  

##3.10##
The problem with the code in this checkpoint is that only D or F will be printed. D will be printed whenever score is 60 or more, F is printed if score is less than 60.  

The score comparisons shall be done in descending order for this code to work as intended.  

##3.11##
a, b, and c are equivalent.  

b and c are correctly indented.  

##3.12##
```Java
boolean newLine = count % 10 == 0;
```

##3.13##
Both a and b are correct and will do the same thing. The code in b is the preferred way because it shows that the statements are related.  

##3.14##
**(a)**  
This code will always check for both even numbers and numbers that is a multiple of 5.

The output when using number 14, 15, and 30 will be:
```
14 is even  
15 is a multiple of 5
30 is even  
30 is a multiple of 5
```  

**(b)**  
This code will check if a number is even. If the number is odd so will an additional check be done that checks if the number is a multiple of 5.  

The out put when using number 14, 15, and 30 will be:
```  
14 is even  
15 is a multiple of 5
30 is even  
```  

##3.15##
Math.random() will generate a random double value between 0.0 and 1.0, excluding 1.0.  

Examples of possible values when using Math.random() are 0.5, 0.0, 0.234.  

##3.16##
**(a)**  
Generates an int in the 0 to 19 interval:  
```
int a = (int)(Math.random() * 20);    
```  

**(b)**  
Generates an int in the 10 to 19 interval:  
```
int b = 10 + (int)(Math.random() * 10);    
```  

**(c)**  
Generates an int in the 10 to 50 interval:  
```
int c = 10 + (int)(Math.random() * 41);    
```  

**(d)**  
Generates an int that is 0 or 1:  
```
int d = (int)(Math.random() * 2);    
```  

##3.17##
The two statements in this checkpoint are equal. The first one is better since it is shorter.  

##3.18##
```Java  
x = 1  

(true) && (3 > 4)      // false  
!(x > 0) && (x > 0)    // false  
(x > 0) || (x < 0)	   // true  

(x != 0) || (x == 0)   // true  
(x >= 0) || (x < 0)    // true  
(x != 1) == !(x == 1)  // true  
```  

##3.19##
**(a)**  
```Java  
(num > 1) && (num < 100)  
```  
**(b)**  
```Java  
(num > 1) && (num < 100) || (num < 0)  
```  

##3.20##
**(a)**  
```Java  
(x - 5 < 4.5) && (-(x - 5) < 4.5)
```  
**(b)**  
```Java  
(x - 5 > 4.5) || (-(x - 5) > 4.5)
``` 

##3.21##
Assume that x and y are int type variables.  

Examples of legal Java expressions:  
```Java  
x /= y  
```     

Examples of illegal Java expressions.
```Java  
x > y > 0  
x = y && y  
x or y  
x and y  
(x != 0) || (x = 0) 
```  

##3.22##
Yes.  

##3.23##
Call the following expression p:  
```  
x >= 50 && x <= 100  
```  
p is false when x is 45   
p is true when x is 67  
p is false when x is 101  

##3.24##
The output will be  
```
(x < y && y < z) is true  
(x < y || y < z) is true  
!(x < y) is false  
(x + y < z) is true  
(x + y > z) is false  
```  

##3.25##
Boolean expression that evaluates to true if age is greater than 13 and less than 18.  
```Java  
age > 13 && age < 18  
```  

##3.26##
Boolean expression that evaluates to true if weight is greater than 50 pounds or height is greater than 60 inches.  
```Java  
weight > 50 || height > 60
```  

##3.27##
Write a Boolean expression that evaluates to true if weight is greater than 50 pounds and height is greater than 60 inches.  
```Java  
weight > 50 && height > 60
```  

##3.28##
Write a Boolean expression that evaluates to true if either weight is greater than 50 pounds or height is greater than 60 inches, but not both.  
```Java  
(weight > 50 && !(height > 60)) || (!(weight > 50) && height > 60)  
``` 
My opinion is that the other answer, that can be found on the book web site, is wrong on this one.  

##3.29##
The following data types are allowed to be used as a switch variable:  
- char  
- byte  
- short  
- int  
- String  

Omitting a break statement will cause a fall-through causing the code in the next case to be to executed.  

A switch statement can be converted to an equivalent if statement.    

A switch statement can make the code easier to read comparing to using deeply nested if statements.  

##3.30##
```Java  
public class CheckPoint_03_03 {

	public static void main(String[] args) {
		int x, y;

		x = 3;
		y = 3;
		switch (x + 3) {
		case 6:
			y = 1;
		default:
			y += 1;
		}
		System.out.println("After switch statement y = " + y);
		
		// rewrite switch to an equivalent if-else variant
		y = 3; 	// set y to original value
		if(x + 3 == 6)
			y = 1;
		y += 1;
		System.out.println("After if statement y = " + y);
	}

}
```  
y is 2 after the switch statement.  

##3.31##
```Java  
public class CheckPoint_03_31 {

	public static void main(String[] args) {
		int x = 1, a = 3;
		
		// first version with an if-else statement
		if (a == 1)
			x += 5;
		else if (a == 2)
			x += 10;
		else if (a == 3)
			x += 16;
		else if (a == 4)
			x += 34;

		System.out.println("After if-else x = " + x);
		
		x = 1;	// set x to original value before switch statement
		
		// second version with a switch statement
		switch (a) {
		case 1:
			x += 5;
			break;
		case 2:
			x += 10;
			break;
		case 3:
			x += 16;
			break;
		case 4:
			x += 34;
			break;
		}
		
		System.out.println("After switch x = " + x);
	}

}
```  
x is 17 after the switch statement.  

A flowchart for the switch statement is shown below.  

![](https://github.com/HenrikSamuelsson/Introduction_to_Java_Programming/blob/master/Chapter_03/Resources/checkpoint_03_31.png?raw=true)

##3.32##
```Java  
switch (day) {
case 0:
	System.out.println("Sunday");
	break;
case 1:
	System.out.println("Monday");
	break;
case 2:
	System.out.println("Tuesday");
	break;
case 3:
	System.out.println("Wednesday");
	break;
case 4:
	System.out.println("Thursday");
	break;
case 5:
	System.out.println("Friday");
	break;
case 6:
	System.out.println("Saturday");
	break;
}
```  

##3.33##
The output will be:  
```  
sorted  
```  

##3.34##
```Java  
ticketPrice = ages >= 16 ? 20 : 10;  
```  

##3.35##
**(a)** 
```Java   
if (x > 10)
	score = 3 * scale;
else
	score = 4 * scale;
```  
**(b)**  
```Java  	
if (income > 10000)
	tax = income * 0.2;
else
	tax = income * 0.17 + 1000;
```  
**(c)**
```Java    
if (number % 3 == 0) 
	System.out.println(i);
else
	System.out.println(j);
```  

##3.36##
```Java  
1 == (int) (Math.random() * 2) ? 1 : -1;
```  

##3.37##
The precedence of the the Boolean operators is (listed from high to low):
- NOT `!`    
- XOR `^`  
- AND `&&`   
- OR `||`  

The expression `true || true && false` will be evaluated as follows.  
```
true || (true && false)  
true || false
true
```
The expression `true && true || false` will be evaluated as follows.  
```  
(true && true) || false  
true || false  
true
```  

##3.38##
It is true that all the binary operators except =, +=, -=, *=, /=, %= are left associative.  

##3.39##
```  
2 * 2 - 3 > 2 && 4 – 2 > 5  
4 - 2 > 2 && 4 - 2 > 5  
2 > 2 && 2 > 5  
false && false  
false  
```  

```
2 * 2 - 3 > 2 || 4 – 2 > 5  
4 - 3 > 2 || 4 – 2 > 5  
1 > 2 || 2 > 5  
false || false  
false     
```  

##3.40##
`(x > 0 && x < 10)` is the same as `((x > 0) && (x < 10))`  

`(x > 0 || x < 10)` is the same as `((x > 0) || (x < 10))`  

`(x > 0 || x < 10 && y < 0)` is the same as  `(x > 0 ||(x < 10 && y < 0))`  

# Checkpoint Answers Chapter 4 #
##4.1##
**(a)**  
```  
Math.sqrt(4)   // 2.0  
```  
**(b)**  
```  
Math.sin(2 * Math.PI)    // -2.4492935982947064E-16  
```  
**(c)**  
```  
Math.cos(2 * Math.PI)    // 1.0  
```  
**(d)**
```  
Math.pow(2, 2)    // 4.0  
```  
**(e)**  
```  
Math.log(Math.E)   // 1.0  
```  
**(f)**  
```  
Math.exp(1)    // 2.718281828459045  
```  
**(g)**  
```  
Math.max(2, Math.min(3, 4))    // 3  
```  
**(h)**  
```  
Math.rint(-2.5)    // -2.0  
```  
**(i)**  
```  
Math.ceil(-2.5)    // -2.0  
```  
**(j)**  
```  
Math.floor(-2.5)    // -3.0   
```  
**(k)**  
```  
Math.round(-2.5f)   // -2  
```  
**(l)**  
```  
Math.round(-2.5)    // -2  
```  
**(m)**  
```  
Math.rint(2.5)    // 2.0  
```  
**(n)**  
```  
Math.ceil(2.5)    // 3.0  
```  
**(o)**  
```  
Math.floor(2.5)    // 2.0  
```  
**(p)**  
```  
Math.round(2.5f)    // 3  
```  
**(q)**  
```  
Math.round(2.5)    // 3    
```  
**(r)**  
```  
Math.round(Math.abs(-2.5))   // 3  
```  

##4.2##
The argument for trigonometric methods is an angle in radians.  

##4.3##
```Java  
// convert 47 degrees to radians  
double angle = Math.toRadians(47);  
```  

##4.4##
```Java  
// convert pi / 7 radians to degrees  
double angle = Math.toDegrees(Math.PI / 7);  
```  

##4.5##
**(a)**  
```Java  
int i = 34 + (int)(Math.random() * 22);  
```  
**(b)**  
```Java  
int j = (int)(Math.random() * 1000);
```  
**(c)**  
```Java  
double k = 5.5 + (int)(Math.random() * 50);  
```  

##4.6##
There is one package that is automatically imported into any Java program, this package is called java.lang.  

One of the classes that belongs to the java.lang package is the Math class. This means that the Math methods can be used directly without the need for explicit import.  
 
##4.7##
```Java  
Math.log(Math.exp(5.5));    // evaluates to 5.5  
```  
```Java  
Math.exp(Math.log(5.5));    // evaluates to 5.5  
```		
```Java  
Math.asin(Math.sin(Math.PI / 6));    // evaluates to 0.5235987755982988 = pi / 6  
```  
```Java  
Math.sin(Math.asin(Math.PI / 6));    // evaluates to 0.5235987755982988 = pi / 6  
```  
##4.8##
```Java  
System.out.println((int)'1');	// prints 49
System.out.println((int)'A');	// prints 65
System.out.println((int)'B');	// prints 66 
System.out.println((int)'a');	// prints 97
System.out.println((int)'b');	// prints 98
```  
```Java  
System.out.println((char)40);	// prints (
System.out.println((char)59);	// prints ;
System.out.println((char)79);	// prints O
System.out.println((char)85);	// prints U	
System.out.println((char)90);	// prints Z
```  
```Java
System.out.println((char)0x40);	// prints @
System.out.println((char)0x5A);	// prints Z
System.out.println((char)0x71);	// prints q
System.out.println((char)0x72);	// prints r
System.out.println((char)0x7A);	// prints z 
```  

##4.9##
Examples of correct character literals:
```Java  
'l'  
'\u3fFa'  
'\b'  
'\t'  
```  
Example of incorrect character literal, because the Unicode representation is too long:
```Java  
'\u345dE'
```  

##4.10##
```Java  
System.out.println('\\');	// prints \
System.out.println('"');	// prints "
```  

##4.11##
```Java  
int i = '1';  
```  
equals  
```Java  
int i = 49;  
```  
because the ASCII code for 1 is 49, i will hence become 49.  

```Java  
int j = '1' + '2' * ('4' - '3') + 'b' / 'a';  
```  
equals  
```Java  
int j = 49 + 50 * (52 - 51) + 98 / 97;  
```  
that evaluates to j becoming 100.  

```Java  
int k = 'a';  
```  
equals  
```Java  
int k = 97;  
```  
because the ASCII code for a is 97, k will hence become 97.  

```Java  
char c = 90;  
```  
equals  
```Java  
char c = 'Z';  
```  
because the 90 equals Z in the ASCII table, c will hence hold the value Z.  

##4.12##
Some examples that illustrate casting.  
```Java  
// i will be set to 65
char c = 'A';  
int i = (int)c;  
```  
```Java 
// i will be set to 1000 
float f = 1000.34f;  
int i = (int)f;  
```  
```Java  
// i will be set to 1000
double d = 1000.34;  
int i = (int)d;  
```  
```Java  
// c will be set to 'a'
int i = 97;  
char c = (char)i;  
```  

##4.13##
```Java    
public class Test {  

	public static void main(String[] args) {  
		char x = 'a';  
        char y = 'c';  
		
		// prints b  
        System.out.println(++x);
        
		// prints c because the increment is done after usage  		
		System.out.println(y++);

		// prints -2 beacuse there is an auto conversion to int before the subraction  
        System.out.println(x - y);
   	}

}
```

##4.14##
```Java  
// c will become a lower case character in the range a to z  
char c = (char)(97 + Math.random() * 26);  
```  

##4.15##
```Java  
System.out.println('a' < 'b');	// true  
System.out.println('a' <= 'A');	// false   
System.out.println('a' > 'b');	// false  
System.out.println('a' >= 'A');	// true  
System.out.println('a' == 'a');	// true
System.out.println('a' != 'b');	// true
```  

##4.16##
```Java
String s1 = "Welcome to Java";  
String s2 = "Programming is fun";  
String s3 = "Welcome to Java";  
```   
Assuming the above lines will cause the following expressions to become the value indicated in the comments.  
```Java  
s1 == s2	// false  
```  
```Java  
s2 == s3	// false  
```  
```Java  
s1.equals(s2)	// false
```  
```Java   
s1.equals(s3)	// true
```  
```Java   
s1.compareTo(s2)	// a positive int
```  
```Java   
s2.compareTo(s3) 	// a negative int  
```  
```Java   
s2.compareTo(s2)	// 0
```  
```Java   
s1.charAt(0)	// W
```  
```Java  
s1.indexOf('j')		// -1 
```  
```Java  
s1.indexOf("to")	// 8
```  
```Java	
s1.lastIndexOf('a')		// 14    
```  
```Java  
s1.lastIndexOf("o", 15)		// 9
```  
```Java  
s1.length()  // 15
```  
```Java  
s1.substring(5)		// me to Java
```  
```Java  
s1.substring(5, 11)  // me to   
```  
```Java  
s1.startsWith("Wel")  // true
```  
```Java  
s1.endsWith("Java")  // true
```  
```Java  
s1.toLowerCase()	// welcome to java  
```  
```Java  
s1.toUpperCase()	// WELCOME TO JAVA    
```  
```Java  
s1.concat(s2)	// Welcome to JavaProgramming is fun
```  
```Java  
s1.contains(s2)		// false
```  
```Java  
"\t Wel \t".trim()	// Wel  
```  

##4.17##
Suppose that s1 and s2 are two strings.  

The following are all examples of correct string manipulations in Java.  
```Java  
String s = "Welcome to Java";  
String s3 = s1 + s2;  
s1 == s2  
s1.compareTo(s2);  
int i = s1.length();  
```  
On the other hands so are the following all incorrect.  
```Java  
String s3 = s1 - s2;    
s1 >= s2  
char c = s1(0);  
char c = s1.charAt(s1.length());  
```  

##4.18##
```Java  
public class CheckPoint_04_18 {

	public static void main(String[] args) {
		System.out.print("a)\t");	System.out.println("1" + 1);
		System.out.print("b)\t");	System.out.println('1' + 1);
		System.out.print("c)\t");	System.out.println("1" + 1 + 1);
		System.out.print("d)\t");	System.out.println("1" + (1 + 1));
		System.out.print("e)\t");	System.out.println('1' + 1 + 1);

	}

}
```  
Above program will output:  
```  
a)    11
b)    50
c)    111
d)    12
e)    51
```  

##4.19##
```Java  
public class CheckPoint_04_19 {

	public static void main(String[] args) {
		String a = 1 + "Welcome " + 1 + 1;
	    String b = 1 + "Welcome " + (1 + 1);
	    String c = 1 + "Welcome " + ('\u0001' + 1);
	    String d = 1 + "Welcome " + 'a' + 1;
	    
		System.out.println(a);
		System.out.println(b);
		System.out.println(c);
		System.out.println(d);
	}

}
```  
Above program will output:  
```  
1Welcome 11
1Welcome 2
1Welcome 2
1Welcome a1
```  

##4.20##
**(a)**
```Java  
boolean isEqual = s1.equals(s2);  
```    
**(b)**
```Java  
boolean isEqual = s1.equalsIgnoreCase(s2);  
```    
**(c)**
```Java  
int x = s1.compareTo(s2);  
```    
**(d)**
```Java  
int x = s1.compareToIgnoreCase(s2);  
```    
**(e)**
```Java  
boolean b = s1.startsWith("AAA");  
```    
**(f)**
```Java  
boolean b = s1.endsWith("AAA");  
```    
**(g)**
```Java  
int x = s1.length();  
```    
**(h)**
```Java  
char x = s1.charAt(0);  
```    
**(i)**
```Java  
String s3 = s1 + s2;  
```    
**(j)**
```Java  
String s3 = s1.substring(1);  
```    
**(k)**
```Java  
String s3 = s1.substring(1, 5);  
```    
**(l)**
```Java  
String s3 = s1.toLowerCase();  
```    
**(m)**
```Java  
String s3 = s1.toUpperCase();  
```    
**(n)**
```Java  
String s3 = s1.trim();  
```    
**(o)**
```Java  
int x = s1.indexOf('e');
```    
**(p)**
```Java  
int x = s1.lastIndexOf("abc");
```  

##4.21##
We will get the answer by adding the first numbers in Set1, Set3, and Set4:
```  
1 + 4 + 8 = 13
```  

##4.22##
The format specifier for outputting a boolean is %b.  

The format specifier for outputting a character is %c.  

The format specifier for outputting a decimal is %d.  

The format specifier for outputting a boolean is %f.  

The format specifier for outputting a string is %s.  

##4.23##
**(a)**    
```Java
System.out.printf("%5d %d\n", 1, 2, 3);
```
Erroneous code because there are three items to be printed but only two format specifiers.  

**(b)**    
```Java  
System.out.printf("%5d %f", 1);
```  
Erroneous code because there are two format specifiers but only one item to be printed.   

**(c)**    
```Java  
System.out.printf("%5d %f\n", 1, 2);  
```  
Erroneous code because an int item is combined with a float format specifier.  

**(d)**    
```Java  
System.out.printf("%.2f\n%0.3f\n", 1.23456, 2.34);   
```  
Erroneous because second format specifier tries to set the width to zero and this is not allowed.  

**(e)**    
```Java  
System.out.printf("%08s\n", "Java");  
```  
Erroneous because of the 0 in the format specifiers that need to be removed.  

##4.24##
```Java  
public class CheckPoint_04_24 {
	
	public static void main(String[] args) {
		System.out.println("(a)"); 
		System.out.printf("amount is %f %e\n", 32.32, 32.32);
	    System.out.println();
	    
	    System.out.println("(b)");
		System.out.printf("amount is %5.2f%% %5.4e\n", 32.327, 32.32);
		System.out.println();
		    
		System.out.println("(c)");
		System.out.printf("%6b\n", (1 > 2));
		System.out.println();
		    
		System.out.println("(d)");
		System.out.printf("%6s\n", "Java");
		System.out.println();
		    
		System.out.println("(e)");
		System.out.printf("%-6b%s\n", (1 > 2), "Java");
		System.out.println();
		    
		System.out.println("(f)");
		System.out.printf("%6b%-8s\n", (1 > 2), "Java");
		System.out.println();
		    
		System.out.println("(g)");
		System.out.printf("%,5d %,6.1f\n", 312342, 315562.932);
		System.out.println();
		    
		System.out.println("(h)");
		System.out.printf("%05d %06.1f\n", 32, 32.32);
	}

}
```
Above program will print the following (note that it was run on computer with Swedish locale settings for displaying numbers, might differ a bit on machines in other countries).  
```Java  
(a)
amount is 32,320000 3,232000e+01

(b)
amount is 32,33% 3,2320e+01

(c)
 false

(d)
  Java

(e)
false Java

(f)
 falseJava    

(g)
312 342 315 562,9

(h)
00032 0032,3
```  

# Checkpoint Answers Chapter 5 #
## 5.1 ##
The condition count < 100 is always true at point A.  

The condition count < 100 can be both true and false at point B.  

The condition count < 100 is always false at point C.  

## 5.2 ##
The problem with initializing guess to zero is that the number that shall be guessed will sometimes be zero. This will cause the while to not even run one iteration and the player will never get to guess the number.  

## 5.3 ##
**(a)**  
The loop body will be run an infinite number of times. There will be no output because i is 1 all the time.

**(b)**  
The loop body will be run an infinite number of times. There will be no output because i is 1 all the time.

**(c)**  
The loop body will be run nine times and the output will be:  
```Java  
3  
5  
7  
9  
```  

## 5.4 ##
The variable max will hold the largest number entered and number will hold the last number entered so the output will be:  
```Java  
max is 5  
number 0  
```  

## 5.5 ##
This program will start with x equal to 80000000 and x is then increased by one again and again until it overflows after reaching 2147483647, x will be -2147483648 after the overflow. The while loop will now terminate and the output will be:  
```Java  
x is -2147483648  
```  

## 5.6 ##
The program in this checkpoint will take numbers as input and keep track of the biggest number in the variable called "max". The last entered number is stored in the variable called "number".  

The output when running the program with the input  
```
2 3 4 5 0  
```  
will be:  
```  
max is 5  
number 0  
```   

## 5.7 ##
A do-while loop will always execute the body of the loop at least one time, this is not true for a while loop.  

The code from the checkpoint rewritten using a do-while loop:  
```Java  
Scanner input = new Scanner(System.in);
int sum = 0;
int number;
do {
	System.out.println("Enter an integer (the input ends if it is 0)");
	number = input.nextInt();
	sum += number;
} while (number != 0);
```  

##5.8 ##
```Java  
for (int i = 0; i < 10; ++i) {  
	sum += i;
}
```  
```Java  
for (int i = 0; i < 10; i++) {  
	sum += i;
}
```  
The above two loops will result in the same value in sum. This is so because the control variable i will have identical value, when used in the loop-continuiation-condition, regardless of ++i or i++ is used to increment i.  

##5.9##
The three parts usually present in a for loop control section are  
1. Initial action used to initialize control variables.  
2. Loop continuation condition that controls if the body of the loop will run or not, will usually be based on the control variables.  
3. After iteration action which usually will alter the value of the control variable.  

A loop that prints the numbers for 1 to 100:  
```Java  
for (i = 1; i <= 100; i++) {
	System.out.println(i);
}
```  

##5.10##
```Java  
import java.util.Scanner;

public class CheckPoint_05_10 {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		int number, sum = 0, count;
		for (count = 0; count < 5; count++) {
			number = input.nextInt();
			sum += number;
		}
		System.out.println("sum is " + sum);
		System.out.println("count is " + count);
	}
	
}
```  
The program in this checkpoint will sum integers until the control variable in the loop reaches the value five 5. This means that if the input to the program is  
```
2 3 4 5 0  
```  
so will the output be  
```  
sum is 14  
count is 5
```  

##5.11##
The loop in this check point will iterate indefinitely and repeat the execution of the instructions in the body on each iteration.  

##5.12##
A variable that is declared in a for loop control section can not be used after the loops exists.  

##5.13##
A for loop, a while loop, and a do-while loop, that all do the same thing.  
```Java  
long sum = 0;
for (int i = 0; i <= 1000; i++)
	sum = sum + i;
```  
```Java  
long sum = 0;
int i = 0;
while (i <= 1000) {
	sum += i;
	i++;
}
```  
```Java  
long sum = 0;
int i = 0;
do {
	sum += i
	i++;
} while (i <= 1000);
```  

##5.14##
**(a)**  
n iterations  
**(b)**  
n + 1 iterations  
**(c)**  
n - 5 iterations  
**(d)**  
(n-5)/3 iterations, rounded upwards if n-5 is not divisible by 3.  

n equal to 12 will for example result in  
```  
(12 - 5) / 3 = 7 / 3 = 2.33
``` 
which shall be rounded upwards resulting in 3 loop iterations.  

##5.15##
A for loop can be converted into a while loop.  

Some benefits of for loops are:  
- For certain type of problem, a for loop can be easier to construct and easier to read than the corresponding while loop.  
- It is a very good (perhaps the best) choice for counting loops.	 
- All the control variables are nicely collected into one place when using for loops.  

##5.16##
A while loop can always be converted into a for loop.  

Below follows an illustration where a given while loop have been converted into a corresponding for loop.  
```Java  
int i = 1;  
int sum = 0;  
while (sum < 10000) {  
	sum = sum + i;  
	i++;  
}  
```  
```Java  
sum = 0;  
for (int i=1; sum < 1000; i++) {  
	sum = sum + i;  
}
```  
##5.17##
Fixed version of the code in this checkpoint follows.  Had to guess a little on some of the fixes since there was no specification and instead just a piece of semi-random nonsense code.  
```Java  
public class Test {
	public static void main(String[] args) { // missing static
		int sum = 0; // sum was not defined in original code
		for (int i = 0; i < 10; i++)	// removed a semicolon here
			sum += i;

		int j = 10; // j was not defined
		int i = 5; // i was not defined
		if (i < j) // removed a semicolon
			System.out.println(i); // added missing semicolon
		else
			System.out.println(j);

		while (j < 10) // removed semicolon
		{
			j++;
		}

		do {
			j++;
		} while (j < 10); // added semicolon
	}
}
```  

##5.18##
**(a)**  
The problem with this code is a missing semicolon after the do-while loop at row 8.  
**(b)**  
The problem with this code is that the semicolon at line 3 shall be removed.  

##5.19##
When i is 0, the println statement is executed 0 times.  
When i is 1, the println statement is executed 1 time.   
When i is 2, the println statement is executed 2 times.  
.  
.  
.   
When i is 9, the println statement is executed 9 times.   
 
So, the total is  
```
0 + 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 = 45  
```  

##5.20##
**(a)**  
Output:
```  
0 0 1 0 1 2 0 1 2 3  
```  
**(b)**  
Output:
```  
****
****
2 ****
3 2 ****
4 3 2 ****
```  
**(c)**  
Output:
```  
1xxx2xxx4xxx8xxx16xxx
1xxx2xxx4xxx8xxx
1xxx2xxx4xxx
1xxx2xxx
1xxx
```  
**(d)**  
Output:
```  
1G
1G3G
1G3G5G
1G3G5G7G
1G3G5G7G9G
```  

##5.21##
The suggested optimization is incorrect since it will not spot the gcd when entering two identical numbers. 

##5.22##
The code will not compile if we remove the cast. This is because the code is semi dangerous since information might be lost when we convert an int to a char. An int can hold a wider range of numbers than a char.  

But no information will be lost in this case because the numbers are always small enough to fit in a char. 

So there is no problem with our code but we still need to make a cast to a char to indicate to compiler that we are aware of what we are doing.  

##5.23##
The loop will in each iteration divide the variable "decimal" by 16. The result will be truncated since this is how integer division works in Java. The execution stops when "decimal" is 0.  

Assume that "decimal" starts at 245:  
```
245 / 16 = 15
15 / 16 = 0
```  
There will hence be 2 iterations in this case.  

Assume that "decimal" starts at 3245:  
```
3245 / 16 = 202
202 / 16 = 12
12 / 16 = 0
```  
There will hence be 3 iterations in this case.  

##5.24##
The keyword break can be used in a loop to exit the loop.  

The keyword continue is used in a loop to terminate the current iteration and move execution directly to the loop control section.  

The keyword break is used in the following code:   
```Java  
int balance = 10;
while (true) {
	if (balance < 9)
    	break;
    balance = balance - 9;
}

System.out.println("Balance is " + balance);
```  
Balance will become 1 after the first iteration. This causes a break out of the loop and the output will be:  
```  
Balance is 1
```  
The keyword continue is used in the following code:  
```Java  
int balance = 10;
while (true) {
    if (balance < 9)
		continue;
    balance = balance - 9;
}

System.out.println("Balance is " + balance);
```  
The loop in this second example will never end because continue is mistakenly used instead of break.  

##5.25##
The problem with the while loop version (see the book) is that the varible called "i" will not be incremented as it should when it is divisible by three. This is because the continune will cause an jump to the beginning of the loop.  

We need to add the increment of "i" in one extra place:  
```Java   
int i = 0; 
while (i < 4) {
	if (i % 3 == 0) {
		i++; 
		continue;
	} 
	sum += i;
	i++;
}  
```  

##5.26##
The program TestBreak in Listing 5.12 rewritten so that the break is no longer used:  
```Java  
public class TestBreak {

	public static void main(String[] args) {
		int sum = 0;
		int number = 0;

		while (number < 20 && sum < 100) {
			number++;
			sum += number;
		}

		System.out.println("The number is " + number);
		System.out.println("The sum is " + sum);
	}

}
```  

The program TestContinue in Listing 5.13 rewritten so that the continue is no longer used:  
```Java  
public class TestContinue {
	
	public static void main(String[] args) {
		int sum = 0;
		int number = 0;

		while (number < 20) {
			number++;
			if (number != 10 && number != 11)
				sum += number;
		}

		System.out.println("The sum is " + sum);
	}
	
}
```  

##5.27##
**(a)**  
The second print statement will be executed after the break. The output will be:  
```
1
2
1
2
2
3
```  

**(b)**  
The increment of j will be executed after the continue. The output will be:  
```  
1
2
1
2
2
3
```  


# Checkpoint Answers Chapter 6 #
## 6.1 ##
Some of the benefits of using methods are:  
- Faster development time by reuse of code  
- Reduces complexity of the code  
- Makes the code easier to maintain  

## 6.2 ##
A number of properties about a given method need to be decided before it can be defined:  
- What modifiers are suitable
- The type of the value, if any, that shall be returned
- The name of the method
- What parameters are needed as data for the method to be able to do its work
- What the method is intended to do and how it shall do it

When all of the above decisions have been made so can the method be defined. An example of a method definition looks like this:  
```Java  
public static int max(int num1, int num2) {  
	if (num1 > num2)  
		return num1;   
	else  
		return num2;  
}  
```  
The keywords public and static are examples of modifiers. The following int indicates that the method will return an int after being executed. The name of the method is max and it takes two int's as data parameters.

The part between the braces is the body of the loop and it this part that does the actual work. In this case so will it be checked which of the parameters that is biggest and the value of this parameter is returned to the caller of the method.  

A method is invoked by using the name of the method combined with the same number and type of actual parameter values as in the definition of the method.  

An invocation of the max method can for example look like this:  
```Java  
int biggestNumber = max(15, 42);  
```  
## 6.3 ##
The body of the max method can be shortened by the use of the conditional operator.  
```Java  
return ( num1 > num2 ) ? num1 : num2;  
```   
## 6.4 ##
A call to a method with a void return type is always a statement itself. A call to a value-returning method can also be a statement by itself.  
## 6.5 ##
The return type of the main method is void.  
## 6.6 ##
Omitting a return statement in a value-returning method will cause a syntax error.  

It is possible to have a return statement in a void function, this will end the execution of the method.  

It is a syntax error to have a void function return a value.  
## 6.7 ##
The term parameter is used to refer to the list of variables in a method declaration.  

The term argument refers to the actual values that are passed in when the method is invoked.  

A method signature is made up of the name and the parameter list of a given method. Note that the return type is not part of the method signature.  
## 6.8 ##
**(a)**  
```Java  
public static double getCommission(double SalesAmount, double commissionRate)
```  
**(b)**  
```Java  
public static void displayCalendar(int mont, int year)
```  
**(c)**  
```Java  
public static double squareRoot(double num)
```  
**(d)**  
```Java  
public static boolean isEven(int num)
```  
**(e)**  
```Java  
public static void displayMessage(String message, int count)
```  
**(f)**  
```Java  
public static double monthlyPayment(double loanAmount, int years, double interestRate)
```  
**(g)**  
```Java  
public static char toUpperCase(char letter)
```  
## 6.9 ##
```Java  
public class Test {
	public static method1(int n, m) {
		n += m;
		method2(3.4);
	}

	public static int method2(int n) {
		if (n > 0) 
			return 1;
		else if (n == 0) 
			return 0;
		else if (n < 0) 
			return -1;
	}
}
```
There are multiple errors in the above code.  

The return type for method1 is missing, it shall be void.

The type of the second parameter in method1 is missing, it shall most likely be of type int.  

The second method, named method2, is in method1 invoked with a double argument but the parameter of method2 is of typ int. This causes an syntax error, this can be fixed by changing the method signature of method2.  

The compiler will think that it is possible for method2 to not return any value in some situations. Remove the last if to make the code compile without changing the behavior. 

A fully corrected code look like this:
```Java  
public class Test {
	public static void method1(int n, int m) {
		n += m;
		method2(3.4);
	}

	public static int method2(double n) {
		if (n > 0)
			return 1;
		else if (n == 0)
			return 0;
		else
			return -1;
	}
}
```  
## 6.10 ##
```Java  
public class Test {
	public static double method(double i, double j) {
		while (i < j) {
			j--;
		}

		return j;
	}
}
```  
## 6.11 ##
The arguments passed to a method must be passed in the same order as in the method signature and the types of all argument must be compatible to the formal parameters in the method signature.  

An argument can have the same name as a formal parameter, this is for example a valid program:  
```Java  
public class CheckPoint_06_11 {
	
	public static void main(String[] args) {
		int i = 5;
		int j = 10;
		printSum(i, j);
	}
	
	public static void printSum(int i, int j) {
		System.out.println(i + j);
	}
	
} 
```  
## 6.12 ##
There is a mistake when calling the method. The order of the two parameters have been mixed up.  

Another mistake is in the the body of nPrintln where n is declared even though n is used as an name for one of the formal parameters.  
## 6.13 ##
By definition, pass by value means you are making a copy in memory of the actual parameter's value that is passed in. All work done in the method is then done on this copy.  

**(a)**  
Output is:    
```
0
```
It is only the local copy that is altered by the method, the original is left unchanged.  

**(b)**  
Output is:  
```  
2  
2 4  
2 4 8  
2 4 8 16  
2 4 8 16 32  
2 4 8 16 32 64  
```  

**(c)**  
Output is:  
```
Before the call, variable times is 3  
n = 3  
Welcome to Java!  
n = 2  
Welcome to Java!  
n = 1  
Welcome to Java!  
After the call, variable times is 3    
```  
What happens is that the value of the variable times is copied to n. The value of n is then changed but the value of times stays unchanged.  

**(d)**  
Output is:  
```  
  
1  
2 1  
2 1  
4 2 1  
i is 5  
```  
## 6.14 ##
Stack content just before the max-method is invoked:  
```
|           |
| max     0 |
-------------
```

Stack content just entering the max-method, we use more stack now because max need to store some data:  
```
|           |
| max     0 |
| value2  2 |
| value1  1 |
-------------
| max     0 |
-------------
```

Stack content just before return from the max-method, that now have done some writing in the memory:
```    
|           |
| max     0 |
| value2  2 |
| value1  1 |
-------------
| max     0 |
-------------
```  

Stack content after return from the max-method, the memory needed by the max-method is now free again:  
```
|           |
| max     0 |
-------------
```
## 6.15 ##
Method overloading in Java occurs when two or more methods in the same class have the exact same name but different parameters.  

It is allowed to have identical method names, as long as the parameter types are sufficintly different.  

It is not allowed to have overloaded methods where the difference is just based on return types or modifiers.  

# 6.16 #
Both methods defined in this check point have the exact same signature, this is not allowed since there is no way to know which of the methods to invoke.  

# 6.17 #
**(a)**  
The second method will be invoked in this case.  

**(b)**  
The second method will be invoked in this case.  

**(c)**  
The first method will be invoked in this case.  

# 6.18 #
A local variable in Java is a variable that is declared within the body of a method. This variable can be used variable only within that method. Other methods in the class are not even aware that the variable exists.  

# 6.19 #
The scope of a local variable starts from its declaration and continues to the end of the block that contains the variable.  

# Checkpoint Answers Chapter 7 #
## 7.1 ##
An array reference variable is declared by the use of brackets. For example, the following code declares a variable myList that references an array of double elements.
```Java  
double[] myList;
```  
An array reference variable is used as a handle to access the content of the array, but just creating this variable will not allocate any space in memory for the array. Memory for the array is allocated by using the keyword new. If we need to be able to store 10 doubles so shall we write like in the following code.
```Java  
myList = new double[10];
```  
If we know the values that shall go in the array before it is created so is it also possible to use a shorthand notation. This is called an array initializer that will allocate memory and create the array reference.
```Java
double[] myList = {1.9, 2.4, 3.4, 3.5, 1.0, 5.7, 3.1, 1.1, 8.7, 4.6};  
```  
## 7.2 ##
The memory needed for an array is allocated when the array is created, by the use of the new keyword or using an array initializer.  
## 7.3 ##
The code in this check point will output:  
```  
x is 60
The size of numbers is 30
```  
The size of an array can not be changed after it is set.  
## 7.4 ##
**(a)**  
True  

**(b)**  
False  

**(c)**  
True  

**(d)**  
False  
## 7.5 ##
The following are both valid ways to define an array:  
```Java  
double d[] = new double[30];  
float f[] = {2.3, 4.5, 6.6};  
```  
## 7.6 ##
Each element in an array is associated with an index that can be used for accessing the element.  

Example:  
```Java  
int i[] = {1, 5, 8, 2};
int myInt = i[1];	// myInt becomes 5
```  
## 7.7 ##
The type of an array index is int.  

The lowest index of an array is 0.  

The third element of an array named a is represented by `a[2]`.  
## 7.8 ##
**(a)**  
```Java
double[] listA = new double[10];
```

**(b)**  
```Java  
listB[listB.length() - 1] = 5.5;
```

**(c)**  
```Java  
System.out.println(listC[0] + listC[1]);
```

**(d)**  
```Java  
int sum = 0;
for (int e : listD) {
	sum += e;
}
```

**(e)**  
```Java  
int min = listE[0];
for (int e : listE) {
	if (e < min) {
		min = e;
	}
}
```

**(f)**  
```Java  
System.out.println(listF[(int)(Math.random()listF.length)]);
```

**(g)**  
```Java  
double[] ListG = {3.5, 5.5, 4.52, 5.6};
```  
## 7.9 ##
Attempts to access an array element with an invalid index will cause an ArrayIndexOutOfBoundsException to be thrown.    
## 7.10 ##
The creation of the array is wrong, the line 
```Java
double[100] r;  
```  
should be  
```Java  
double[] r = new double[100];
```  

The usage of length in the header of the for loop should be   
```Java
r.length  
```  

There is a semicolon after the for loop that shall be removed.  

The array assignment expression uses parentheses where it should be square brackets.  

The call to the random function misses parentheses.  

A completely corrected program looks like this:  
```Java  
public class Test {
	public static void main(String[] args) {
		double[] r = new double[100];
 
       for (int i = 0; i < r.length; i++)
         r[i] = Math.random() * 100;
     }
}
```

## 7.11 ##
The first loop will in the first iteration copy the value of `list[0]` to `list[1]`. Which means that both `list[0]` and `list[1]` will be 1. The second iteration will the copy the value of `list[1]` to `list[2]`. This continues and by the end of the first loop so will the every value in list be set to 1.  

The second loop just prints the content of the array, the output will hence be  
```  
1 1 1 1 1 1  
```
  
## 7.12 ##
No the new version of the code, presented in the check point, will not work since it would be possible to get the same card more than once.  

## 7.13 ##
The following code will copy the content of the array called "source" to the other array called "target".  
```Java  
int[] source = {3, 4, 5};
int[] target = new int[3];
System.arraycopy(source, 0, target, 0, source.length);
```  

## 7.14 ##
The following code will not really resize the array.  
```Java  
int[] myList;
myList = new int[10];

	.
	.
	.

// Sometime later you want to assign a new array to myList
myList = new int[20];
```
What happens it that the reference is moved so that it references another part of the memory, that is big enough to hold 20 elements. This means that the 10 first elements will no longer be the same unless they are somehow copied.   

## 7.15 ##
The problem is that the content is swapped two times so wo will end up with the same order of elements as we started with.  

The trick to fix the problem is to stop the for loop when we have reached the midpoint of the array. A fixed version looks like this.  
```Java  
int[] list = {1, 2, 3, 5, 4};
for (int i = 0, j = list.length - 1; i < list.length / 2; i++, j--) {
	// Swap list[i] with list[j]
	int temp = list[i];
	list[i] = list[j];
	list[j] = temp;
}
```
  
## 7.16 ##
Arrays are passed as references when used as arguments to methods. This reduces the amount of information that needs to be passed. Note that this means that if the method changes the content of the array so will this also affect corresponding array content existing outside of the method block.  

## 7.17 ##
**(a)**  
```Java  
public class Test {
	public static void main(String[] args) {
		int number = 0;
		int[] numbers = new int[1];
		m(number, numbers);
		System.out.println("number is " + number + " and numbers[0] is "
				+ numbers[0]);
	}

	public static void m(int x, int[] y) {
		x = 3;
		y[0] = 3;
	}
}
```  
The program from above will output:
```  
number is 0 and numbers[0] is 3  
```  

**(b)**  
```Java  
public class Test {
	public static void main(String[] args) {
		int[] list = { 1, 2, 3, 4, 5 };
		reverse(list);
		for (int i = 0; i < list.length; i++)
			System.out.print(list[i] + " ");
	}

	public static void reverse(int[] list) {
		int[] newList = new int[list.length];
		for (int i = 0; i < list.length; i++)
			newList[i] = list[list.length - 1 - i];
		list = newList;
	}
}
```  
The program from above will output:  
```  
1 2 3 4 5
```  
The reason that the output is not reversed is that the reference called "list" used inside the reverse method is a copy of the "list" in the main method, these two references are not the same even tough they have the same name.

"list" inside reverse will reference memory where the content is in deed reversed when we reach the end of method. But the other "list" in main will still reference another chunk of memory whit unaltered content.  

## 7.18 ##
TODO - Skipping this one because it means to much work right now.  

## 7.19 ##
Each of the following code snippets are incorrect.  

```Java
public static void print(String... strings, double... numbers)  
```  
The problem with above code is that it is only allowed to have a single variable-length parameter.  

```Java  
public static void print(double... numbers, String name)
```  
The problem with the above is that a variable-length parameter is only allowed to be placed last int the parameter list.  

```Java  
public static double... print(double d1, double d2)
```  
The problem with the above code is that it is not allowed to return a variable-length type from a method.  

## 7.20 ##
The printMax method from Listing 7.5 can be invoked like this  
```Java  
printMax(1, 2, 2, 1, 4);
printMax(new double[]{1, 2, 3});
```  
but not like this
```Java  
printMax(new int[]{1, 2, 3}); 
```  
because the types does not match and there is no automatic conversion in this case.  

## 7.21 ##
Replace  
```Java  
(low + high) / 2  
```  
with  
```Java  
(-low + high) / 2 + low
```
  
## 7.26 ##
The java.util.Arrays.sort method is overloaded so that it can be used to sort arrays of any primitive type except boolean. This sort method will not create a new method, the elements will be sorted into the array that is given as argument to the method.  

## 7.29 ##
These are all valid ways to declare the main method  
```Java
public static void main(String[] args)
public static void main(String args[])
public static void main(String[] x)
public static void main(String x[])  
```  
The name of the parameter does not matter and there are two ways of placing the square brackets when declaring an array in Java.  

This is not a valid ways to declare main since the public access modifier must be applied to make the method visible to the world
```Java 
static void main(String x[])
```  

## 7.30 ##
**(1)**  
```  
Number of strings is 4  
I  
have  
a  
dream  
```  

**(2)**  
```  
Number of strings is 1  
1 2 3  
```  

**(3)**  
```  
Number of strings is 0  
```  

# Checkpoint Answers Chapter 8 #
## 8.1 ##
A two-dimensional array that hold int values and is of size 4-by-5 is created like this:  
```Java  
int[][] matrix = new int[4][5];
```  

## 8.2 ##
The rows in a two-dimensional array can have different lengths, arrays with this property is known as ragged arrays.  

## 8.3 ##
```Java  
int[][] array = new int[5][6];
int[] x = {1, 2};
array[0] = x;
System.out.println("array[0][1] is " + array[0][1]);
```
The above code will set array[0][0] to 1 and array[0][1] to 2. So the output will be:  
```  
array[0][1] is 2
```  

## 8.4 ##
Examples of valid statements:  
```Java  
int[][] y = new int[3][];
int[][] z = {{1, 2}};
int[][] m = {{1, 2}, {2, 3}};
```  
Examples of invalid statements:  
```Java  
int[][] r = new int[2]; 
int[] x = new int[];
int[][] n = {{1, 2}, {2, 3}, };
```  

## 8.5 ##
```Java  
int[][] array = {{1, 2}, {3, 4}, {5, 6}};
for (int i = array.length - 1; i >= 0; i——) {
	for (int j = array[i].length - 1; j >= 0; j——)
 		System.out.print(array[i][j] + " ");
 	System.out.println();
}
```  
The above code setups a two dimensional array with 3 rows and 2 columns. It will then print the content of the array "in reverse". The output will be:  
```  
6 5  
4 3  
2 1  
```  

## 8.6 ##
```Java   
int[][] array = { { 1, 2 }, { 3, 4 }, { 5, 6 } };
int sum = 0;
for (int i = 0; i < array.length; i++)
	sum += array[i][0];
System.out.println(sum);
```  
The above code setups a two dimensional array with 3 rows and 2 columns. The sum of all the elements in the first column will then be calculated (1 + 3 + 5) and the result is printed. The output will hence be:  
```  
9  
```  

## 8.7 ##
The method called m1 will take a two dimensional array as input and check the number of rows and columns. The result of the check is returned in an array where the row count is placed first and then follows the column count.

The method is tested with a 2 by 4 array so the output will be: 
``` 
2
4
```  

## 8.8 ##
A declaration of a three dimensional array:
```Java  
int[][][] a = new int[4][6][5];  
```  

## 8.9 ##
Assume that we have the following declaration:  
```Java 
int[][][] x = new char[12][5][2];  
```  

This array will in total hold 120 elements because 12 times 5 times 2 is 120.  

The value of  
```Java  
x.length  
```  
will be 12 because the outermost array can hold 12 elements.

The value of  
```Java  
x[2].length  
```  
will be 5 because this refers to the array in the "second dimension".

The value of  
```Java  
x.length[0][0]  
```  
will be 2 because this is a reference to the "third dimension" and these are all arrays of size 2.  

## 8.10 ##
```Java  
int[][][] array = {{{1, 2}, {3, 4}}, {{5, 6}, {7, 8}}};  
System.out.println([0][0][0]);  
System.out.println([1][1][1]);  
```  
The above code will declare an three-dimensional array of size 2-by-2-by-2. The "first" and "last" elements in the array are then printed, so the output will be:  
```  
1
8
```  

# Checkpoint Answers Chapter 9 #
## 9.1 ##
Objects of the same type are defined using a common class. A class is a template, blueprint, or contract that defines what an object’s data fields and methods will be.  

An object is an instance of a class. It is possible to create many instances of a class.  

## 9.2 ##
A class is defined by the use of the class keyword followed by the name of the class. For example:
```Java  
public class MyClass {  
	// constructors, class variables, and methods goes here  
}  
```  

## 9.3 ##
A reference variable for an object is declared by the use of the class name followed by the name of the object. For example:  
```Java  
MyClass mc;  
```  

## 9.4 ##
The new keyword in combination with a class constructor is used to create an object. For example:  
```Java  
MyClass mc = new MyClass();  
```  

## 9.5 ##
Constructors are special methods that are used to create objects of an class.  

An ordinary method will have a return type but constructors does not, not even void.  

## 9.6 ##
A default constructor, is provided automatically only if no constructors are explicitly defined in the class.  

## 9.7 ##
The member access operator, also known as the dot-operator, is used to access data fields or invoke methods on an object.  

## 9.8 ##
An anonymous object does not have any reference variable referencing it. These type of objects have short life time and will go away immediately after doing its assigned task.  

## 9.9 ##
A NullPointerException will occur when trying to use a reference that points to no location in memory (null) as though it were referencing an object.  

## 9.10 ##
An array is an object. An array can hold elements that are themself objects. The default values of elements in an array will be the same as the data fields of ordinary objects:
- 0 for numeric primitive types  
- false for boolean  
- '\u0000' for char  
- null for elements that are objects  

## 9.11 ##
**(a)**
```Java  
public class ShowErrors {

	public static void main(String[] args) {
		ShowErrors t = new ShowErrors(5);
	}

}
```
This code is incorrect because there is no constructor available that takes an int.  

**(b)**
```Java  
public class ShowErrors {

	public static void main(String[] args) {
		ShowErrors t = new ShowErrors();
		t.x();
	}

}
```
This code is incorrect because there is no member method called x in the ShowErrors class.

**(c)**
```Java  
public class ShowErrors {

	public void method1() {
		Circle c;
		System.out.println("What is radius " + c.getRadius());
		c = new Circle());
	}

}
```
This code will cause a NullPointerException at runtime because c is used in the print statement before it is created.

**(d)**
```Java  
public class ShowErrors {

	public static void main(String[] args) {
		C c = new C(5.0);
		System.out.println(c.value);
	}
	
}

class C {
	int value = 2;
}
```
This code is incorrect because the class C have no constructor that takes a double as argument.  

## 9.12 ##
The problem with the code in this checkpoint is that an object is constructed with a default constructor that takes no arguments. But there is no such constructor for the class A.  

There is always a default constructor, that takes no arguments, as long as we do not provide any constructor of our own. But as soon as we add one or more constructors in the code so is this default constructor removed.  

## 9.13 ##
Member variables of type boolean get the default value false so the code in this checkpoint will result in the output:  
```
false  
```  

## 9.14 ##
A Date object is created like this:  
```Java  
java.util.Date date = new java.util.Date();  
```  

The current time (including the date) can be displayed by the use of the toString method: 
```Java  
System.out.println(date.toString());
```  

## 9.15 ##
A Point2D is created by using a constructor that takes an x-coordinate and a y-coordinate, like this:
```Java  
double x = 4.0;  
double y = 5.5;  
Point2D p = new Point(x, y);  
```  

There is a member method called distance in the Point2D class that can be used to get the distance between two points.  
```Java  
double d = p1.distance(p2));	// get distance between p1 and p2
```  

There is a member method called midpoint in the Point2D class that can be used to get the point between two points.  
```Java  
Point2D mp = p1.midPoint(p2)); 
```  

## 9.16 ##
The class Date and the class Random are included in the java.util package.    

The class Point2D is included in the javafx.geometry package.  

The class System and the class Math are included in the java.lang package.  

Note that there are different versions of the above classes from different versions of Java so it is possible to find more or less similar classes with the same names in other packages.  

## 9.17 ##
Suppose that we have a class called F that looks like this:  
```Java  
public class F { 
	int i:
	static String s;
    
	void imethod() {
	}

	static void smethod() {
	}
```  
Then suppose that we have f that is an instance of F. The following statements are then legal:
```Java  
System.out.println(f.i);
System.out.println(f.s);
f.imethod();
f.smethod();
System.out.println(F.s);
F.smethod();
```  
But the following statements are illegal because instance members cannot be used without an actual  instance of the class.  
```Java  
System.out.println(F.i);  
F.imethod();
```  

## 9.18 ##
```Java  
public class Test { 
	int count; 
	
	public static void main(String[] args) { 
		// ...
	}
	
	public int getCount() { 
		return count;
	}
	 
	public static int factorial(int n) { 
		int result = 1;
		for (int i = 1; i <= n; i++)
  			result *= i; 
	return result;
	}

}
```  

## 9.19 ##
It is not possible to invoke an instance method or reference an instance variable from a static method.  

It is possible to invoke a static method or reference a static variable from an instance method.  

There are two problems with the code from this checkpoint. First problem is that method1 cannot be invoked inside main becaus main is static and method1 is not defined as static. Second problem is that c is not accessible from method2 because c is not static. 

(There is a third problem regarding that the class Circle is not defined or imported but we ignore this.)  
  
## 9.20 ##
An accessor method is used to get private data from from an object.  

A mutator method is used to set private data in an object.  

The naming convention for accessor methods is getDataFieldName for non-boolean values and isDataFieldName for boolean values.  

The naming convention for mutator method is setDataFieldName.  

## 9.21 ##
Benefits of encapsulation:  
- The fields of a class can be made read-only or write-only.  
- A class can have total control over what is stored in its fields.  
- The users of a class do not know how the class stores its data. A class can change the data type of a field and users of the class do not need to change any of their code.  

## 9.22 ##
There is no problem with the code from this checkpoint. It is possible to access the private variable because it is done from within the class.  

## 9.23 ##
Primitive types are copied when passed as a parameter to a method. This means that the method that takes the value will work with a copy and there can be an original value that is guaranteed to be unaltered no matter what the method does with the parameter.  

Reference types are not copied when passed as a parameter to a method. Instead so will a reference to the location in the memory be copied and given as parameter to the method. This reference is then used inside the method to look up the object. This means that if the method writes to the object so will these changes affect the object also in the scope outside of the method.  

The output of the program in this checkpoint will look like this:  
```  
count 101
times 0
```  
The myCount object is sent as a reference and will be altered also outside of the method but times is copied and the changes will not be noticed outside of the method.  

## 9.24 ##
Output:  
```  
After swap1: circle1 = 1.0 circle2 = 2.0  
After swap2: circle1 = 2.0 circle2 = 1.0  
```  
The method called swap1 does not work as intended. This is because the swap is done on references to the circle objects that are copies of the references outside of the method. This means that the swap works inside the method but the original references used when printing afterwards have not been swapped.  

## 9.25 ##
**(a)**  
```  
a[0] = 1 a[1] = 2
```  
Pass by value so no swap outside of the method.  
  
**(b)**  
```  
a[0] = 2 a[1] = 1
```  
The parameter will be a reference to the array so will swap also outside of the method.  

**(c)**  
```  
e1 = 2 e2 = 1
```  

**(d)**  
```  
t1's i = 2 and j = 1
t2's i = 2 and j = 1
```  
The member i is static so it is shared between all T instances and increased each time an instance is created. The member j is unique for each instance.  

## 9.26 ##
**(a)**  
```  
null
```  
A new Date instance is created in m1 but date outside of m1 is never set to reference this variable.  

**(b)**  
```  
1234567
```  
Almost the same situation as in part (a). There are two different references called date that will reference two different Date instances.  

**(c)**  
```  
7654321
```  
There is only one Date instance this time and it is altered in m1.  

**(d)**  
```  
1234567
```  
Again two different references variables, both called date. The one local to m1 is set to null in m1 but this will not affect the one outside in main.  

## 9.26 ##
The problem with the code in this checkpoint is that no Date instances are being created. All that is created is an array that can be used to store 10 dates. The first element in the array is then accessed but it will be null since there is nothing there yet.  

## 9.28 ##
There are three requirements that must be met for a class to be immutable:  
1. All data fields shall be private.
2. There can not be any mutator methods for the data fields.
3. No methods is allowed to return a reference to a data field that is mutable, because this reference could be use to make changes.   

## 9.29 ##
A class where all the data field are private and of primitive types, and the class does not contain any setter methods, implies that the class is immutable.  

## 9.30 ##
The following class is not immutable.  
```Java  
public class A {
	private int[] values;
	
	public int[] getValues() {
		return values;
	}
}
```  
The reason for the class not being immutable is that the method getValues returns a reference that can be used to alter the content of the member variable called values.  

## 9.31 ##
The output will be:  
```
i + j is 23
k is 2
j is 0
```
The first line of output will use the variable i from main and the local variable j that is 2. The plus will in this case be interpreted as string concatenation instead of arithmetic addition.  

The second line of output is based on the i from main and the static class variable called j.  

The third line of output is based on the static class variable called j.  

## 9.32 ##
Within an instance method or a constructor, this is a reference to the current object — the object whose method or constructor is being called. You can refer to any member of the current object from within an instance method or a constructor by using this.  

## 9.33 ##
There are some problems with the following code:  
```Java
public class C {
	private int p;
	
	public C() {
		System.out.println("C's no-arg contstructor invoked");
		this(0);
	}
	
	public C(int p) {
		p = p;
	}
	
	public void setP(int p) {
		p = p;
	}
}  
```
A constructor call must be the first statement in a constructor. There are two assignments where p is assigned to p which have no effect.  

A corrected version of the code looks like this:    
```Java  
public class C {
	private int p;
	
	public C() {
		this(0);
		System.out.println("C's no-arg contstructor invoked");
	}
	
	public C(int p) {
		this.p = p;
	}
	
	public void setP(int p) {
		this.p = p;
	}
}
```  
Another strange thing with this class is that p is never ever used for anything buts lets ignore this and move on in life.  

## 9.34 ##
The problem is that m2 tries to set the member called id by using the class directly. This will not work since we must use an instance of the class instead of the class itself.  

The code would work if the member id was declared as static. But then it would only be one id for all instances which is probably not the intention.

# Checkpoint Answers Chapter 10 #
## 10.1 ##
The Loan class would not be made immutable just by removing the setter methods. The getLoanDate method would still return a reference to an object and this reference could be used to change parts of the Loan class.  

## 10.2 ##
The BMI class is immutable. There are no setter methods, and there is only possible to get references to String objects which is a type of object that is immutable.

## 10.3 ##
The relationship among classes is often divided into four different groups based on characteristics of the relation. The name of these groups are:  
1. Inheritance  
2. Aggregation  
3. Association  
4. Composition  

## 10.4 ##
Aggregation implies a relationship where the child can exist independently of the parent. Example: Class (parent) and Student (child). Delete the Class and the Students still exist.  

Composition implies a relationship where the child cannot exist independent of the parent. Example: House (parent) and Room (child). Rooms don't exist separate to a House.  

Association is a weaker form of relationship that indicates that a class uses another class by parameter or return type.  

## 10.5 ##
The UML notation for aggregation is an unfilled diamond symbol at the owner (aggregation) class. Composition is indicated in the same way but with a filled diamond symbol.  

## 10.6 ##
Aggregation and composition are closely related. Hence so are they usually not differentiated in the book. Both are called composition for simplicity.  

## 10.7 ##
A wrapper class is one of eight classes provided in the java.lang package to provide object methods for the eight primitive types. Wrapper classes are used to represent primitive values when an Object is required. All of the primitive wrapper classes in Java are immutable.  

## 10.10 ##
An Integer is created that will have the value 3. The value is then printed so 3 will be printed. The value 3 is then compared to 4 which will return -1. The result of the comparison is then also printed.  

The printed output will hence be:  
```  
3  
-1  
```
  
## 10.11 ##
No extra parameter means that the number will be interpreted as a decimal number. Extra parameter in the form of 10 also means that decimal interpretation. Extra parameter in the form of 16 means that the number will be interpreted as being written with hexadecimal base.  
```   
10  
10  
16  
11  
11  
17  
```  

## 10.12 ##
Autoboxing is the automatic conversion that the Java compiler makes between the primitive types and their corresponding object wrapper classes. 

The opposite automatic conversion of an object of a wrapper type to its corresponding primitive value is called unboxing.

The following are all valid examples of autoboxing and unboxing:  
```  
Integer x = 3 + new Integer(5);
Integer x = 3;
Double x = 3.0;  
int x = new Integer(3);
int x = new Integer(3) + new Integer(4);
```  
This example is not valid because the types does not match up in the correct way:    
```  
Double x = 3;  
```  
But it can be fixed by introduction of a cast:  
```  
Double x = (double) 3;   
```  

## 10.13 ##
A cast will be used to convert the double into an int int the first print, the decimal part will be truncated away.

3.5 is less than 4.5 so the compareTo method will return -1.

The output will hence be:  
```  
3  
-1  
```

## 10.14 ##
The output will be:  
```  
x is 3  
y is 7  
z is 10  
```  

## 10.15 ##
Assume the we create strings in the following way:  
```Java  
String s1 = "Welcome to Java";  
String s2 = s1;  
String s3 = new String("Welcome to Java");  
String s4 = "Welcome to Java";  
```  
The results of the following expressions is indicated by comments in the code.  
```Java  
s1 == s2	// true, both variables will reference the same object  
s1 == s3	// false, same content but not the same objects  
s1 == s4	// true, an interned string
s1.equals(s3)	// true
s1.equals(s4)	// true
"Welcome to Java".replace("Java", "HTML")	// Welcome to HTML
s1.replace("o", "T")	// WelcTme tT Java
s1.replaceAll("o", "T")	// WelcTme tT Java
s1.replaceFirst("o", "T")	// WelcTme to Java
s1.toCharArray()	// an array holding the characters in the string "Welcome to Java"
```  

## 10.14 ##
There are two ways to create a String:  
```Java  
String s = "Welcome to Java";
```
```Java  
String s = new String("Welcome to Java");
```  
The first one is better because it creates an interned String that will be shared if more strings with the same value are created later on. This will save memory and be faster because using the new operator is expensive.  

## 10.26 ##
The main difference between StringBuffer and StringBuilder is that StringBuffer is synchronized and StringBuilder is not.   

This means that StringBuilder will be faster but it can not be used if two or more threads needs to share it.  


# Checkpoint Answers Chapter 11 #
## 11.1 ##
A subclass is usually not a subset of a superclass. Subclasses will usually add functionality and details that are not present in the superclass thus extending the superclass.  

## 11.2 ##
The keyword extends is used when defining a subclass.  

For example:  
```Java  
public class MountainBike extends Bicycle {
	
	// ...
	// ...
	// ...

}
```  

## 11.3 ##
Single inheritance means that a class may only inherit from one particular class.  

Multiple inheritance is a feature of some object-oriented computer programming languages in which an class can inherit characteristics and features from more than one  parent class.  

Multiple inheritance is not supported by the Java programming language.  

## 11.5 ##
The syntax for calling a superclass constructor that takes no parameters is:  
```Java  
super();  
```  
The syntax with parameters is:  
```Java  
super(parameter list);  
```  
This will cause a call to a constructor with matching parameter list in the superclass.

Invocation of a superclass constructor must be on the first line in the subclass constructor.  

It is possible to omit the explicit call of a superclass constructor. The compiler will in this case insert a call to the no-argument superclass constructor.  

## 11.6 ##
The no-arg constructor of a superclass will not be called if another constructor is called explicitly by the subclass.  

## 11.7 ##
It is not possible to override a method that is declared private in the superclass.  

## 11.8 ##
It is not possible to override a static method defined in a superclass.  

It is still possible to have another static method, with the same name, in a subclass but this method will not override the method in the superclass, it will hide it.  

This is a bit tricky read more [here](http://docs.oracle.com/javase/tutorial/java/IandI/override.html "here").  

## 11.9 ##
The keyword super is used to explicitly invoke the constructor of a superclass.  

## 11.10 ##
The keyword super in combination with the dot operator is used to invoke an overridden superclass method from a subclass.  
```Java  
super.method()  
```

## 11.11 ##
A corrected version of the code for this checkpoint looks like this:  
```Java  
public class Circle {
	private double radius;

	public Circle(double radius) {
		this.radius = radius;
	}

	public double getRadius() {
		return radius;
	}

	public double getArea() {
		return radius * radius * Math.PI;
	}
}

class B extends Circle {
	private double length;

	B(double radius, double length) {
		super(radius);
		this.length = length;
	}

	@Override
	public double getArea() {
		return super.getArea() * length;
	}
}
```  

## 11.12 ##
Method overloading means making multiple versions of a method based on differences in the signature.  

Method overriding means defining a new version of a method in a subclass of a superclass. Overridden methods have the same signature and return type as the original. 

## 11.13 ##
A method in a subclass that have the same signature, and same return type, as a method in its superclass is said to be overriden.  

## 11.14 ##
Having methods with the same signature but different return types in a subclass and its superclass is not allowed and will cause a syntax error.  

## 11.15 ##
A method in a subclass that have the same name as a method in its superclass but with different parameter types is said to be overloaded.  

## 11.16 ##
Using the @Override annotation will take advantage of the compiler checking that makes sure that there is an actual overriding of an existing method. This check will catch mistakes of misspelling a method name or not correctly matching the parameters.  

Another benefit is that this annotation functions as documentation, making the intention of the code easier to understand.  

## 11.17 ##
A good definition of polymorphism can be found in [The Java Tutorials](https://docs.oracle.com/javase/tutorial/java/IandI/polymorphism.html "The Java Tutorials").
> The dictionary definition of polymorphism refers to a principle in biology in which an organism or species can have many different forms or stages. This principle can also be applied to object-oriented programming and languages like the Java language. Subclasses of a class can define their own unique behaviors and yet share some of the same functionality of the parent class.  

When an method is overridden in subclass so is it up to the JVM to figure out at runtime which specific method to invoke. This concept is called dynamic binding.  

## 11.18 ##
Method matching is the process of deciding what version of an overloaded method to invoke. This is done at compile time by the compiler and the choice is based on the signature of the overloaded methods.  

Method binding is the process of finding the method to invoke when using inheritance. A method may be implemented in several classes part of an inheritance chain. The JVM dynamically binds the implementation of the method at runtime, decided by the actual class of the object referenced by the variable.  

## 11.19 ##
It is (of course) possible to assign an array of type Object like this:  
```Java  
Object o = new Object[50];
```
Since all other classes inherits from Object so is it also possible to do assignments of the following kind:   
```Java  
Object[] o = new Integer[50];
```  
```Java  
Object[] o = new String[50];
```
It is on the other hand not possible to assign an primitive type to an Object variable this means that the following code will not compile.
```Java  
Object[] o = new int[50];	// Type mismatch: cannot convert from int[] to Object[]  
```  

## 11.24 ##
The following statement is true.     
> You can always successfully cast an instance of a subclass to a superclass.  

The following statement is false.  
> You can always successfully cast an instance of a superclass to a subclass.  

## 11.25 ##
**(a)**  
```Java  
(circle instanceof GeometricObject)		// true  
(object instanceof GeometricObject)		// true  
(circle instanceof Circle)			// true  
(object instanceof Circle)			// false  
```  

**(b)**  
The code will compile because cast from subclass to superclass is always allowed.  

**(c)**  
The code will compile but there will be runtime exception when executing the program.  

## 11.28 ##
Every object have both a toString and an equals method because these methods are defined in the class Object and all classes inherits from this class.  

Examples of how to invoke these methods:  
```Java  
object1.equals(object2)
```
```Java  
object1.toString()  
```  

The default versions of these methods are rather crude and should often be overridden in the subclass to get more useful versions.  

## 11.30 ##
**(a)**
Creation of an ArrayList for storing double values:  
```Java  
ArrayList <Double> doubleList = new ArrayList<>();
```  

**(b)**  
Append an on object to a list:
```Java  
doubleList.add(5.0);
```  

**(c)**  
Insert an object at the beginning of the list:
```Java  
doubleList.add(0, 1.0);	// index 0 is the start of the list
```  

**(d)**  
Number of objects in the list:
```Java  
doubleList.size();    
```  

**(e)**  
Removal of a given object in the list:
```Java  
doubleList.remove(5.0);	// removes the first occurence found of 5.0 in the list
```  

**(f)**  
Removal of the last element in the list:
```Java  
doubleList.remove(doubleList.size() - 1);
```  

**(g)**  
Check whether a given element is in the list:
```Java  
doubleList.contains(1.0);	// checks if the number 1.0 is in the list
```  

**(h)**  
Retrieve an object at a specified index in the list:   
```Java  
doubleList.get(0);	// returns what the first element in the list is
```  

## 11.31 ##
There are multiple issuses with the below code.
```Java  
ArrayList<String> list = new ArrayList<>();
list.add("Denver");
list.add("Austin");
list.add(new java.util.Date());
String city = list.get(0);
list.set(3, "Dallas");
System.out.println(list.get(3));
```  
A Date object is attempted to be added to the ArrayList, this will not work because the list is setup to hold String objects.  

Index 3 is attempted to be set to Dallas but it will not be possible since the list only holds two elements when this statement is executed at runtime.  

An attempt to get the element at index 3 is done. This will not work because there is no element at this location when this statement is executed at runtime.  

## 11.33 ##
What happens is that the method with the signature    
```Java  
remove(int index)  
```  
is called with the argument 1. This will remove the value at index 1, the value 2 is stored here so this will be removed.  

If instead the value 1 shall found int the list and be removed so can the method with the signature  
```Java  
remove(Object)
```   
be called by writing like this
```Java  
remove(new Integer(1));
```  

## 11.34 ##
```Java  
ArrayList<Double> list = new ArrayList<>();
list.add(1);
```  
The above code will not work because the add function takes an Double Object as argument but an int is provided. There is no auto boxing from int to Double so the code will not compile.  

The code can be fixed by writing like this
```Java  
list.add(1.0);
```  
or like this  
```Java  
list.add(new Double(1));  
```  

## 11.35 ##
The asList method does not support primitive types and there is no autoboxing for arrays. This is why the code from the book does not work. A corrected version is shown below.  
```Java  
Integer[] array = {3, 5, 95, 4, 15, 34, 3, 6, 5};  
ArrayList<Integer> list = new ArrayList<(Arrays.asList(array));  
```  

## 11.36 ##
The max method in the Collections class can not be used with an array as argument. The array need to be converted to an ArrayList that is an type allowed to be used as an argument.  
```Java  
Integer[] array = {3, 5, 95, 4, 15, 34, 3, 6, 5};
ArrayList<Integer> list = new ArrayList<(Arrays.asList(array));
System.out.println(java.util.Collections.max(list));
```  

## 11.37 ##
A class can by default access another class in the same package, but classes outside of the package will not be able to access it by default. This means that if this is the desired level of visibility so shall the accessibility modifier simply be omitted.  

## 11.38 ##
The keyword protected is used as an accessibility modifier to setup so that a class in a different package cannot access the class, but its subclasses in any package can access it.  

## 11.39 ##
If the question marks are replaced by blanks, can class B be compiled? Yes, default access means visibility between classes in the same package.  
    
If the question marks are replaced by private, can class B be compiled? No, private means that the int called i and the method called m can only be used from within the class.  

If the question marks are replaced by protected, can class B be compiled? Yes, B inherits from A so B can used protected members from A.  

## 11.40 ##
If the question marks are replaced by blanks, can class B be compiled? No, B is not in the same package as A so if i and m from class A will not be visible to B if default access is set.  

If the question marks are replaced by private, can class B be compiled? No, i and m will not be visible outside of class A if they are set to private.  
 
If the question marks are replaced by protected, can class B be compiled? Yes, B inherits from A so there is no problem to access protected variables in A.  

## 11.41 ##
The keyword final is used to prevent classes from being extended. It is also used to prevent methods form being overridden.  

## 11.42 ##
**(a)**  
True.  

**(b)**  
False, only true if the subclass extends the class with the protected members.  

**(c)**  
True.  

**(d)**  
True.  

**(e)**  
False.  

**(f)**  
False.  



# Checkpoint Answers Chapter 12 #
## 12.1 ##
Exceptions provide the means to separate the details of what to do when something out of the ordinary happens from the main logic of a program. This separation can, if used right, simplify the code making it easier to understand and maintain.  

## 12.2 ##
The following statement will throw an exception because of the division with zero.  
```Java  
System.out.println(1 / 0);  
```
Division of doubles will on the other hand not throw an exception when dividing by zero. This is because the specification that Java follows specifies that this event shall return a special indicator indicating infinity.  
```Java
System.out.println(1.0 / 0);    
```
The above line will not throw an exception. The output from a test run was:
```  
Infinity  
```  
## 12.3 ##
```Java  
long value = Long.MAX_VALUE + 1;  
System.out.println(value);  
```  
The above code will add one to a long variable that already holds the biggest value that can be fitted into a long. This will cause a wrap around that may or may not be seen as an error depending on how the design of program is intended to work. This will not cause throwing of an exception in the current version of Java.  

## 12.4 ##
The JVM will stop executing the ordinary code when an exception occurs and end the program execution, unless there is special code written just to handle the exception.  

Exception handling code is written in a two block structure with a try block that holds the ordinary code and a following catch block that shall catch and take care of eventual exceptions thrown in the try block.  
```Java  
try {
	// ordinary code in  
	// this block that might  
	// throw an exception  
}  
catch (Exception ex){
	// handling of exceptions  
	// in this follow up block  
}
```  

## 12.5 ##
Output if value is 30:  
```  
value is too small
Continue after the catch block
```  
Output if value is 50:
```  
Continue after the catch block
```  

## 12.7 ##
The java.lang.Throwable class is the superclass of all errors and exceptions in the Java language. Only objects that are instances of this class, or one of its subclasses, are thrown by the JVM or can be thrown by the Java throw statement.  

The classes Error and Exception are both subclasses of Throwable. 
- The Error class is used by the JVM when a system error occurs. For example that there is no more available memory.   
- The Exception class is for exceptions caused by the program. These types of exceptions can be caught and handled by the code.  

## 12.9 ##
It is often not possible to anticipate how an exception shall be handled since it depends on how the the program that uses the class is constructed. This is why the exception is thrown up in the call stack so that the user of the class can choose how to handle the exception. The main purpose of declaring the exception is hence to inform the user of the class what exceptions can be thrown so that they can be handled appropriately.  

An exception is declared by the use of the keyword throws in the method declaration. Multiple exceptions are declared by separating them with commas.  
```Java  
public void writeList() throws IOException, IndexOutOfBoundsException {  
	// method body omitted for brevity  
}
```  

## 12.10 ##
Checked exception is a property of the exception classes. Anything that is a subclass of Exception except for RuntimeException and its subclasses is a checked exception.  

The code will not compile unless checked exceptions are caught or declared to be thrown in the method signature. There are no such demands regarding unchecked exceptions.  

## 12.11 ##
The keyword throw is used to throw an exception. There can only be one exception in a single throw statement.  

Example statement that throws an exception:  
```Java  
throw new EmptyStackException();
```  

## 12.12 ##
The keyword called throw is used to throw an Exception from a method or static block.  

The keyword throws is used in method declarations to denote what types of exceptions possibly can be thrown by the method.  

## 12.13 ##
Assume that we have the following try catch block.  
```Java  
try {  
	statement1;
	statement2;
	statement3;
}
catch (Exception1 ex1) {
}
catch (Exception2 ex2) {
}

statement4;
```  
Now assume that an exception is caused by statement2.  

Under the above assumptions so will statement3 not be executed. And statement4 will be executed if and only if the thrown exception is caught in one of the catch blocks.  

## 12.14 ##
The code in this checkpoint will try to access an element with an index that is outside of the range of valid indexes. This will cause an IndexOutOfBoundsException. This type of exception is a subclass of RuntimeException. The output when running the code will hence be:  
```  
RuntimeException  
```  
## 12.15 ##
The method that is invoked will cause an ArithmeticException to be thrown. Nothing is printed inside the method because the exception is thrown before the actual printing starts. The try block will be excited directly without execution of the print statement inside the try block. There is then a following catch for ArithmeticException that will print:  
```  
ArithmeticException  
```  
## 12.16 ##
The code inside the method will cause an  StringIndexOutOfBoundsException that is a subclass of RuntimeException. This exception is caught in method itself. The main method then continues its normal execution flow.  

The output will be:  
```  
RuntimeException in method()  
After the method call  
```  
## 12.17 ##
The Throwable.getMessage() method is used for retrieving the detailed message describing the exception associated with a given Throwable instance.  

## 12.18 ##
The member method called printStackTrace in the Throwable class is a very useful tool for diagnosing an Exception. It indicates what happened and where in the code this happened by printing information about the content of the stack when the exception occurred.  

## 12.19 ##
The presence of a try-catch block will not impose any overhead when no exception occurs.  

## 12.20 ##
The code will possibly throw a checked exception. This means that the exception must be caught in the code or so must it be declared that the code can throw an exception.

Below is a fixed version that declares the throwing of the exception.  
```Java  
public void m(int value) throws Exception {
	if (value < 40)
		throw new Exception("value is too small");
}
```  

## 12.21 ##
If no exception occurs so will both statement4 and statement5 be executed.  

If the exception is of type Exception1 so will both statement4 and statement5 be executed.  

If the exception is not of type Exception1 so will statement4 be executed but not statement5.  

## 12.22 ##
The method presented in the checkpoint will work but can be expensive to run if many of the input strings are on the incorrect form since this will then cause overhead when the exception is caught.  

If it is desired to have code without exceptions so can the solution be based on the use of regular expression.  
```Java  
public static boolean isNumeric(String token) {
	return token.matches("-?\\d+(\\.\\d+)?");
}
```  
Another possible solution could be based around checking each character in the string to see if it is a number.  
```Java  
public static boolean isNumeric(String token) {
	for (char c : token.toCharArray()) {
		if (!Character.isDigit(c))
			return false;
	}
	return true;
}
```  
Note that it is tricky to write a method that covers all possible cases of numeric input. The first solution will for example fail if the locale decimal indicator is set to anything else than a dot. The second solution will only accept numbers, decimal points or minus signs will be rejected.  

## 12.23 ##
Suppose that statement2 causes an exception in the following code.
```Java  
try {
	statement1;
	statement2;
	statement3;
}
catch (Exception1 ex1) {
}
catch (Exception2 ex2) {
	throw ex2;
}
finally {
	statement4;
}
statement5;
```  
If no exception occurs so will both statement4 and statement5 be executed.  

If the exception is of type Exception1 so will both statment4 and statment5 be executed.  

If the exception is of type Exception2 so will statement4 be executed but statment5 will not be executed.  

If the exception is not Exception1 nor Exception2, so will statement4 be executed but statement5 will not be executed.  

## 12.24 ##
The output would be:
```  
java.lang.Exception: New info from method1  
 	at ChainedExceptionDemo.method1(ChainedExceptionDemo.java:16)  
 	at ChainedExceptionDemo.main(ChainedExceptionDemo.java:4)
```  

## 12.25 ##
A custom exception class is defined by extending Exception or a subclass of Exception. 

## 12.26 ##
An exception of type Exception will be thrown in method(). This exception is caught in method and then re-thrown out to main.  
The resulting output will be  
```  
Exception in method()  
Exception in main
```   

## 12.27 ##
A file object is attempted to be created like this  
```Java  
new File("c:\book\test.dat");  
```  
but there is a problem. It has been forgotten that a backslash cannot be used directly in a string, it has special meaning and must be accompanied by an extra backslash.  

A corrected version looks like this:  
```Java  
new File("c:\\book\\test.dat);
```   

## 12.28 ##
The class called File have several member methods that can be used to get properties about files on a system.  

The exist() methods checks if a file exists.  

Files or directories can be deleted with the delete() method.  

Renaming of files is done with renameTo() method.  

The size of a a file is retrieved with the length() method.  

File(pathname: String) can be used for creation of both directories and files.  

## 12.29 ##
The file class is not intended for I/O.   

Creation of a File object does mean that a file will be created on the disk.  

## 12.30 ##
A PrintWriter for writing data to a file is created like this  
```Java  
PrintWriter output = new PrintWriter(file);  
```  
There are multiple things that can go wrong when using PrintWriter so we must either handle these problems or at least inform the user of our class that things can go wrong. This is way the main method in Listing 12.13 is declared with throws Exception.  

Listing 12.13 closes the file at the end by the use of the close() method. Data may not get saved properly in the file if this step is omitted.  

## 12.31 ##
The program from this checkpoint will store the following text in a file called temp.txt.  
```  
amount is 32,320000 3,232000e+01
amount is 32,3200 3,2320e+01
 false
  Java
```  
## 12.32 ##
Example of using the concept try with resources.  
```Java  
public class Checkpoint_12_32 {

	public static void main(String[] args) throws Exception {
		try (java.io.PrintWriter output = new java.io.PrintWriter("temp.txt");) {
			output.printf("amount is %f %e\r\n", 32.32, 32.32);
			output.printf("amount is %5.4f %5.4e\r\n", 32.32, 32.32);
			output.printf("%6b\r\n", (1 > 2));
			output.printf("%6s\r\n", "Java");
		}
	}

}
```  
## 12.33 ##
A Scanner that takes input from a file is created in the following way.  
```Java  
Scanner input = new Scanner(file);  
```  
The throws Exception declaration in listing 12.15 is needed because the code have no functionality for handling exceptions. It is the up to the user of the code to decide how the eventual exceptions shall be handled. The throws exception declaration functions as documentation for both the user and the compiler that the exceptions shall be handled by another part.  

If the close() method is not invoked, the problem will run fine. But it is a good practice to close the file to release the resource on the file. The compiler will also probably give us a warning.  

## 12.35 ##
The line separator is not the same on all platforms.  

Some examples of different line separators  
- Windows: `\r\n`  
- Mac (OS 9-): `\r`  
- Mac (OS 10+): `\n`  
- Unix/Linux: `\n`  

## 12.36 ##
The Scanner will repeatedly read the entered data  
- intValue holds 45  
- doubleValue contains 57.8  
- line contains ' ', '7 ', '8 ', '9'  

## 12.37 ##
The Scanner will repeatedly read the entered data  
- intValue contains 45  
- doubleValue contains 57.8  
- and line is empty  

The reason that line is empty is that the 
token-reading method nextDouble() reads in 57.8 and stops at the delimiter, which in this case is a line separator (the Enter key). The nextLine() method ends after reading the line separator and returns the string read before the line separator. Since there are no characters before the line separator, line is empty.  

## 12.38 ##
Creation of a Scanner object for reading text from an URL is done in the following way.  
```Java  
URL url = new URL("www.google.com/index.html");  
Scanner input = new Scanner(url.openStream());  
```  

## 12.39 ##
One problem with the WebCrawler program is that it is possible that listOfPendingsURLs can hold duplicate URLs. This will happen if a link is not in listOfTraversedURLs and the link appears more than one time in a given page.  

# Checkpoint Answers Chapter 13 #
## 13.1 ##
**(a)**
```Java    
class A {
	abstract void unfinished() {
	}
}
```  
Not legal code because an abstract method have a body. Another problem is that A is not abstract but it contains an abstract method.  

**(b)**  
```Java
public class abstract A {
	abstract void unfinished();
}
```
Not legal because the first use of the abstract keyword is misplaced, shall be placed before the keyword class.   

**(c)**  
```Java
class A {
	abstract void unfinished();
}
```
Not legal, the class must be abstract if the method shall be abstract.  

**(d)**  
```Java
abstract class A {
	protected void unfinished();
}
```
Not legal since there is no body for the non abstract method.  

**(e)**  
```Java  
abstract class A {
	abstract void unfinished();
}
```  
Legal code.
  
**(f)**  
```Java  
abstract class A {
	abstract int unfinished();
}
```   
Legal code.

## 13.2 ##
Abstract classes prevents a developer from instantiating the base class, because a developer has marked it as having missing functionality.  

It also provides compile-time safety so that you can ensure that any classes that extend your abstract class provide the bare minimum functionality to work, and you don't need to worry about putting stub methods that inheritors somehow have to magically know that they have to override a method in order to make it work.  

Read more at: [StackExchange - Why should I declare a class as an abstract class?](http://programmers.stackexchange.com/questions/96947/why-should-i-declare-a-class-as-an-abstract-class)  

## 13.3 ##
**(a)**  
An abstract class can be used just like a non-abstract class except that you cannot use the new operator to create an instance from the abstract class.  

**(b)**  
An abstract class can be extended.  

**(c)**  
A subclass of a non-abstract superclass can be abstract.  

**(d)**  
A subclass can override a concrete method in a superclass to define it as abstract.  

**(e)**  
An abstract method cannot be static.  

## 13.4 ##
There will be an attempt, at runtime, to create a Double object out of an Number object. But this will not work because the Number object is in based on an Integer object.  

## 13.5 ##
The code from this checkpoint will fail at runtime because a Double object is attempted to be stored where an Integer object is supposed to be stored.  

## 13.6 ##
```Java  
public class Test {
	public static void main(String[] args) {
 		Number x = 3;
 		System.out.println(x.intValue());
		System.out.println(x.doubleValue());
 	}
}
```  
The above code will output:  
```  
3  
3.0  
``` 
 
## 13.7 ##
The problem with the code in this checkpoint is that x is of type Number and the method compareTo(Integer) is undefined for the type Number.  

## 13.8 ##
This checkpoint is about the same code that was discussed in checkpoint 13.7. The problem with the code is now tried to be fixed with a cast. There is however a mistake made when introducing the cast. A corrected working version can be seen below.  
```Java  
public class Test {
	public static void main(String[] args) {
		Number x = new Integer(3);
		System.out.println(x.intValue());
		System.out.println(((Integer) x).compareTo(new Integer(4)));
	}
}
```  
## 13.9 ##
It is not possible to create an Calendar object using the Calendar class. This is so because Calendar is an abstract class.  

## 13.10 ##
The add method in the Calendar class is abstract.  

## 13.11 ##
A calendar set to the current time can be created in the following way.  
```Java  
Calendar calendar = new GregorianCalendar();  
```  

## 13.12 ##
```Java  
// c is a Calendar instance  
c.get(Calendar.YEAR)	// get the year  
c.get(Calendar.MONTH)	// get the month  
c.get(Calendar.DATE)	// get the date  
c.get(Calendar.HOUR)	// get the hour  
c.get(Calendar.MINUTE)	// get the minute  
c.get(Calendar.SECOND)	// get the second  
```  

## 13.13 ##
Suppose A is an interface. It is then **not** possible to create an instance using `new A()`.  

## 13.14 ##
Suppose A is an interface. It is then possible to declare a reference variable x with type A.  
```Java  
A x;	// valid code  
```  

## 13.15 ##
**(a)**  
```Java  
interface A {
	void print() { };
}
```  
The above interface is not correct because the (implicitly) abstract member method have an body.  

**(b)**  
```Java  
abstract interface A extends I1, I2 {
	abstract void print() {};
}
```  
The above interface is not correct for exactly the same reason as in (a). Note A can extend I1 and I2 assuming that these are them self interfaces.   

**(c)**  
```Java  
abstract interface A {
	print();
}
```  
The above interface is not correct because the return type of the method is missing.  

**(d)**  
```  
interface A {
	void print();
}  
```  
The above is a valid interface.  

## 13.16 ##
The problem with the code is that the public specifier is missing. The class B shall look like this:  
```Java  
public class B implements A {
	public void m1() {
		System.out.println("m1");
	}
}
```  
All methods defined in an interface are public. This means that when a class implements the interface so must all methods be declared public. The visibility cannot be reduced afterwards.  

## 13.17 ##
If a class implements Comparable so can the object of the class invoke the compareTo method.  

## 13.18 ##
The correct method header for the compareTo method in the String class is:
```Java  
public int compareTo(String o)  
```  

## 13.19 ##
```Java  
Integer n1 = new Integer(3);  
Object n2 = new Integer(4);  
System.out.println(n1.compareTo(n2));  
```  
The above code will not compile because the method compareTo(Integer) in the type Integer is not applicable for the arguments (Object).  

## 13.20 ##
By implementing the Comparable interface for a class so can objects of the class be passed to a method that requires a Comparable type. This would not be possible by just implementing a member method called compareTo.    

## 13.21 ##
The code in this checkpoint will not work because the class tries to use the sort method but this will only work if the compareTo method from the Comparable interface is present. Having the class Person implement the Comparable interface would fix the problem.  

## 13.22 ##
A precondition for for invocation of the `clone()` method to clone an object is that the class of the object implement the interface `java.long.Cloneable`.  

The `Date` class implements `Cloneable`.  

## 13.24 ##
The object called `date1` is a shallow copy of the object `date`. The object called `date2` is on the other hand a deep copy of `date`.

This means that `date == date1` will evaluate to true but `date == date2` will evaluate to false. 

`date.equals(date2)` will evaluate to true.  

The output of the code in this checkpoint will hence be:  
```
true  
false  
true    
```  

## 13.25 ##
`list1` is just a shallow copy of `list` so any changes made to `list` will affect the content of `list1`.  

`list2` is a deep copy of `list` constructed by cloning `list`. Following changes of `list` will hence not affect `list2`.

Output when running the code from this checkpoint will be:  
```  
true
false
list is [New York, Atlanta]
list1 is [New York, Atlanta]
list2.get(0) is New York
list2.size() is 1
```  

## 13.26 ##
The problem is that `clone()` is not visible when y shall be defined.  

Override `clone()` and make it public, and have the class `GeometricObject` implement `Java.lang.Cloneable` to fix this problem.  

## 13.27 ##
One major advantage with interfaces is that a class can can only inherit from one superclass but it can extend multiple interfaces.  

Say that we have the interfaces:
- AirConditioning  
- Light  
- Door  
- Lock  
- Radio  
- Speedometer  

Then assume that we have the classes House, Car, Bicycle. All these classes could then possible implement several of the above interfaces but likely not all. A Bicycle will for example probably have a lights and a lock but not a door.  

Interfaces makes it possibly to bind things that are less tightly bound to an Object. Things that can be applied in multiple different situations.  

## 13.28 ##
An abstract class is a class that is declared with the keyword abstract, it may or may not include abstract methods. Abstract classes cannot be instantiated, but they can be sub-classed.  

An interface is a collection of abstract methods. A class implements an interface, thereby inheriting the abstract methods of the interface.  

Stole this part from the [The Java Tutorials - Abstract Method and Classes](https://docs.oracle.com/javase/tutorial/java/IandI/abstract.html) that discusses the differenses between intefacees and abstract classes.  
> Abstract classes are similar to interfaces. You cannot instantiate them, and they may contain a mix of methods declared with or without an implementation. However, with abstract classes, you can declare fields that are not static and final, and define public, protected, and private concrete methods. With interfaces, all fields are automatically public, static, and final, and all methods that you declare or define (as default methods) are public. In addition, you can extend only one class, whether or not it is abstract, whereas you can implement any number of interfaces.  

## 13.29 ##
**(a)**  
An interface is compiled into a separate bytecode file.  
**(b)**  
An interface can not have static methods.  
**(c)**  
An interface can extend one or more interfaces.  
**(d)**  
An interface cannot extend an abstract class.  
**(e)**  
An abstract class can extend an interface.  

## 13.30 ##
A rational number with the value -2 / 6 = -1 / 3 is created. The numerator is -1 and the denominator is 3. The integer representation will be truncated to 0. The double representation will be -0.333333333...

The output of the code in this checkpoint will be:  
```  
-1  
3  
0  
0.333333333333  
```  
## 13.31 ##
The problem is that r2 is of type Object and this type of class does not have a method called compareTo.  

## 13.32 ##
The problem is that the parameter for the compareTo method is of the wrong type. Shall be of type Rational but r1 is of type Object.  

# Checkpoint Answers Chapter 14 #
## 14.1 ##
The initial version of the GUI library was known as the Abstract Windows Toolkit (AWT). Maps Java code to each operating system's real GUI system. Limited to lowest common denominator among the supported system's.  

After AWT came another version called Swing. Paints all GUI components by itself instead of relying on the underlying operating system. 

Swing is now being replaced by a third version called JavaFX. JavaFX aims to be better suited for today's systems with for example multi-touch support.  

## 14.2 ##
Some reasons for that this book does not teach AWT or Swing:  
1. JavaFX is considered to be the easiest to learn for beginners.  
2. JavaFX is well designed, based around solid object oriented thinking.  
3. JavaFX is the GUI library is the one that is being actively developed by Oracle. Swing will not get any further updates.  

## 14.3 ##
A JavaFX main class is defined by extending the Application class.  
```Java  
public class MyJavaFX extends Application  
```  
The signature of the start method in the application class is:  
```Java  
public void start(Stage primaryStage)
```  
A Stage is a construct that functions as a base window for JavaFX content. An application can have multiple Stages.

A Stage object called primary stage is automatically created by the JVM when the application is launched.

A Stage object is displayed by invoking the show method.    
```Java  
Stage stage = new Stage();  
  
// ...  
// setup of the stage here  
// ...  

stage.show();  
```  
It is possible to prevent the user from resizing a stage.
```Java  
stage.setResizable(false);  
```  

The instruction `Application.launch(args)` is needed in development environments with limited support for JavaFX. This can be replaced by `launch(args)`, because the JavaFX main class is a subtype of Application.  

## 14.4 ##
The output of the program in this exercise is:  
```  
launch application  
Test constructor is invoked  
start method is invoked  
```  

## 14.5 ##
There are some different constructors that can be used to create a Scene.  

Creation of a Scene for a specific root Node.  
```Java  
Scene(Parent root)
```

Creation of a Scene for a specific root Node with a specific size.  
```Java  
Scene(Parent root, double width, double height)  
```  

See the documentation for more examples of constructors for creation of Scene instanses.  

A Scene is set on a Stage by invoking a member method called:  
```  
setScene(Scene value)  
```  

A circle is placed in a Scene by first placing the circle in a pane. This pane can then be placed in the Scene.  

## 14.6 ##
A pane is a form of container for content called nodes.  

A node is a component that have a visual representation and can hence be displayed in a GUI.  

A node can be placed into a pane:
```Java  
pane.getChildren().add(node)  
```  

It is not possible to place a Shape or ImageView into a Scene. These must be placed on for example a pane and this pane can then be placed in the Scene.  

A control or a pane can be place into a scene when constructing a Scene using `new Scene(Parent, width, height)` or `new Scene(Parent)`. Parent is the superclass for Control and Pane.  

## 14.7 ##
There are several constructor variants that can be used to create a Circle.
```Java  
Circle()	// creates an empty instance
Circle(double radius)	// specified radius   
Circle(double centerX, double centerY, double radius)	// specified position and radius  
Circle(double x, double y, double r, Paint fill)	// specified position, radius and fill
Circle(double radius, Paint fill)	// specified radius and fill  
```  
The methods for setting the center of a Circle instance is:    
```Java  
void setCenterY(double value)
```  
The method for setting the radius of a Circle instance is:
```Java  
void setRadius(double value)    
```  
The method for setting the stroke color of a Circle instance is:
```Java  
public final void setStroke(Paint value)      
```  
The method for setting the fill color of a Circle instance is:  
```Java  
public final void setFill(Paint value)      
```  
## 14.8 ##
A binding property is used to bind with a source object. Any changes to the source will be reflected in the bound target.  

A binding property is an instance of of the interface Property.  

A source object is an instance of the inteface  ObservableValue.  

The binding object types for int, long, float, double, and boolean are IntegerProperty, LongProperty, DoubleProperty, and BooleanProperty.  

The classes Integer and Double are not subtypes of ObservableValue. Hence, they cannot be used as a source object in a binding.  

## 14.9 ##
The naming convention that shall be used is as follows.  

The getter method is:  
```Java  
public int getAge()
```  
            
The setter method is:  
```Java  
public void setAge(int age)
```  
            
The property getter is
```Java  
public IntegerProperty ageProperty()
```  

## 14.12 ##
The border color of a node can be set by the use of a style. Here is an example of how to set the border color to red.  
```Java  
node.setStyle("-fx-border: red");  
```  
In i similar way so can the text color of some element be set to a color of choice.  
```Java  
text.setStyle("-fx-fill: red");
```  

## 14.13 ##
Elements such as pane, text, or button can be rotated.  

Rotation of a button 15 degrees counterclockwise is done in the following way.  
```Java  
button.setRotate(-15);  
```  

## 14.14 ##
There are various constructors or static methods that can be used to create a Color. The following constructor creates a Color with the specified red, green, blue, and opacity values.  
```Java  
Color(double red, double green, double blue, double opacity)  
```  
The following attempt to create a Color is incorrect because all parameters shall be in the range from 0.0 to 1.0.  
```Java  
new Color(1.2, 2.3, 3.5, 4)		// error
```  
Higher values supplied to the above constructor means lighter colors so when creating two colors, `c1 = new Color(0, 0, 0, 1)` and `c2 = new Color(1, 1, 1, 1)` so will c2 be lihter than c1.  

Invoking `c.darker()` will not change the color value in c, instead so will a new darker color object, based on c, be returned.  

## 14.15 ##
A Color object with a random color can be created in the following way.  
```Java  
new Color(Math.random(), Math.random(), Math.random(), 1)  
```  
## 14.16 ##
Setting the fill color of a circle can be achieved with either the setFill method or the setStyle method.  
```Java  
c.setFill(Color.BLUE)
c.setStyle("-fx-fill: blue")
```  
## 14.17 ##
Creation of a Font object with font name Courier, size 20, and weight bold.  
```Java  
font("Courier", FontWeight.BOLD, 20)  
```  

## 14.18 ##
The available fonts on a system can be found with `Font.getFamilies()` that return a list of strings for font names.  

## 14.19 ##
An Image is created from a URL like this.
```Java  
new Image(URL)  
```  
An Image is created from a file name in a similar way.  
```Java  
new Image(filename)   
```
  
## 14.20 ##
An ImageView can be created from an Image, or directly from a file or a URL.  
```Java  
new ImageView(image)  
```  

## 14.21 ##
An Image can be set to multiple ImagViews, but one ImageView can only be displayed on time.  

## 14.22 ##
The pane types Pane, StackPane, FlowPane, GridPane, BorderPane, HBox and VBox have identical methodology for adding nodes.  
```Java  
pane.getChildren.add(node)  
```  
The BorderPane is a special case, the methods setTop, setBottom, setLeft, setRight, and setCenter shall be used when adding nodes to this type of pane.  

A node is removed from a pane in the following way.  
```Java  
pane.getChildren().remove(node)  
```  
## 14.28 ##
Example code that shows how to rotate a text.  
```Java  
Text text = new Text("Checkpoint 14.28");  
StackPane pane = new StackPane();  
pane.getChildren().add(text);  
text.setRotate(15);  
```  

# Checkpoint Answers Chapter 15 #
## 15.1 ##
An event source object is an object that can fire an event. 

An event object holds information about an event.  

The relationship between a source object and an event is that the event is an object created by the source.  

## 15.2 ##
Button is a subclass of Node, therefore, it can fire all the events that Node can fire. Among the event that can be fired are MouseEvent, KeyEvent, and ActionEvent.  

## 15.24 ##
A timer is setup that will launch a redraw of the ball every 50 ms. The ball is moved a small distance on each redraw.  

## 15.25 ##
The direction of the ball is reversed by multiplying the control variables dx and dy by -1.  

## 15.26 ##
Pressing the mouse button while on the ball pane will cause the animation to pause. The animation is paused until the mouse button is released.  

## 15.27 ##
```Java  
ballPane.requestFocus();  
```  
The above line of code is taken from the BounceBallControl class in the book. The purpose of this line is to set focus on this node and that this node's top-level ancestor become the focused window. This is necessary for receiving events when the arrow up-key and arrow down-key are pressed.  

## 15.28 ##
```Java  
animation.setCycleCount(Timeline.INDEFINITE);  
```  
The above line of code is taken from the BallPane class in the book. It sets the Timeline animation to be repeated for an indefinite number of times. Without this line so would the animation only be repeated once.  

# Checkpoint Answers Chapter 16 #
## 16.1 ##
A label with a node but without a text is created in a two step process. First create Label with the no-arg constructor, then set the labels graphic property to a node.  

## 16.2 ##
The following code shows how to adjust the label so that it is placed on the right of its node.  
```Java  
label.setContentDisplay(ContentDisplay.LEFT);  
```  

## 16.3 ##
Usage of `\n` makes it possible to divide a label text into multiple lines.  

## 16.4 ##
It is possible to underline a text in a label by setting an underline property.  
```Java  
label.setunderLine(true);  
```  

## 16.5 ##
A button with a text (Left) and a node (in this case an image) is created in the following way.  
```Java  
Button btLeft = new Button("Left", new ImageView("left.gif"));  
```  
The class Button is a subclass of Labeled so Button can invoke all the methods in Labeled.  

## 16.6 ##
The `getPane()` method and the member `Text` in Listing 16.2 are declared as protected because they are intended to be used in subclasses later on in the book.  

## 16.7 ##
The method `setOnAction(handler)` is used to set a handler for processing a button-clicked action.  


# Checkpoint Answers Chapter 17 #
## 17.1 ##
A text file can be thought of as a sequence of characters and a binary file can be thought of as a sequence of bits. 

Take for example the number 199 that will in a text file be stored as '1','9','9' but with each character coded according to some standard such as the Unicode standard or the ASCII standard.  

If 199 is stored as binary so will it instead be stored in some form of hex format possibly as 0xC7.  

## 17.2 ##
Common classes to use when reading or writing file data are Scanner and PrintWriter.  
```Java  
// Reading from temp.txt  
Scanner input = new Scanner(new File("temp.txt"));  
System.out.println(input.nextLine());  
input.close();  
```  
```Java  
// Writing to temp.txt  
PrintWriter output = new PrintWriter("temp.txt");  
output.print("Java 101");  
output.close();  
```  

## 17.22 ##
A File object is used to check if a file exists.  
```Java  
File sourceFile = new File("temp.bin");  
if (sourceFile.exists())  
	System.out.println("File temp.bin exists.");  
else  
	System.out.println("File temp.bin does not exist.");  
```  

## 17.23 ##
The read method will return -1 when the end of a file is reached.  
```Java  
if (r = input.read()) == -1)  
	System.out.println("No more data to read in the file.");  
```  

# Checkpoint Answers Chapter 18 #
## 18.1 ##
A recursive method is the one that calls itself.  

An infinite recursion is the one that never stops. This is an error usually caused by a missing base case or by a faulty inductive step.  
# Checkpoint Answers Chapter 19 #
## 19.1 ##
**(a)**  
The below code will compile, but will fail at runtime.
```Java  
ArrayList dates = new ArrayList();
dates.add(new Date());
dates.add(new String());
```  

**(b)**  
The below code will not compile. The compiler will spot that a String is added to a list of Date objects.
```Java  
ArrayList<Date> dates =
new ArrayList<>();
dates.add(new Date());
dates.add(new String());
```  
## 19.4 ##
The generic definition for `java.lang.Comparable` in the Java API.
```Java  
package java.lang;  

public interface Comparable<T> {
	public int compareTo(T o) { }
}
```  

## 19.6 ##
A generic class can have multiple generic parameters.  

## 19.8 ##
A generic method is declared by placing the generic type immediately after the keyword static in the method.  

Example:  
```Java  
public static <T> void print(T[] list) {
	for (int i = 0; i < list.length; i++)
		System.out.print(list[i] + " ");
	System.out.println();
}
```  
A generic method can be invoked just like a regular method. The compiler will figure out the actual type.  

Example:  
```Java  
String[] strings = {"London", "Paris", "New York", "Austin"};  
print(strings);  
```  

## 19.9 ##
A bounded generic type specifies that the accepted generic types must be subclasses of a given class.  


# Checkpoint Answers Chapter 20 #
## 20.1 ##
A data structure is a particular way of organizing data in a computer so that it can be used efficiently. Data structures can implement one or more particular abstract data types, which are the means of specifying the contract of operations and their complexity. In comparison, a data structure is a concrete implementation of the contract provided by an abstract data type.  

# Checkpoint Answers Chapter 21 #
## 21.10 ##
A HashSet is a good choice when needing to store unordered non-duplicate elements.  

# Checkpoint Answers Chapter 22 #
## 22.1 ##
The constant factor is ignored in big O notation, because it has no impact on the growth rate of the time complexity function.  

A non-dominating term is ignored in Big O notation, because as the input size grows, the dominating term grows much faster than the non-dominating term. Ignoring the non-dominating term will introduce an error in the estimation but keeps things much cleaner.  

## 22.2 ##
**(a)**  
O(n^3)  
 
**(b)**  
O(n^3)  
  
**(c)**  
O(n^3)  
  
**(d)**  
O(2^n)  

**(e)**  
O(n^2 * 2^n)  


# Checkpoint Answers Chapter 23 #
## 23.1 ##
Insertion sort works the same way as one would sort a hand of cards, i.e. starting with an empty left hand and the cards in the deck face down on the table. One card at a time is then dealt from the table and inserted into the correct position in the left hand. To find the correct position for a card, it is compared with each of the cards already in the hand, from right to left.  

The time complexity for insertion sort is O(n^2).   

## 23.4 ##
Bubble sort will repeatedly step through the list to be sorted, compares each pair of adjacent items and swaps them if they are in the wrong order. The pass through the list is repeated until no swaps are needed, which indicates that the list is sorted.  

The time complexity for a bubble sort is O(n^2).  

## 23.7 ##
Quicksort is a divide and conquer algorithm. Quicksort first divides a large array into two smaller sub-arrays: the low elements and the high elements. Quicksort can then recursively sort the sub-arrays.  
  
The steps are:

1. Pick an element, called a pivot, from the array.  
2. Reorder the array so that all elements with values less than the pivot come before the pivot, while all elements with values greater than the pivot come after it (equal values can go either way). After this partitioning, the pivot is in its final position. This is called the partition operation.  
3. Recursively apply the above steps to the sub-array of elements with smaller values and separately to the sub-array of elements with greater values.  

The time complexity for a merge sort is O(nlogn).  

## 23.14 ##
The return value will be null when invoking the remove method if the heap is empty.  

## 23.21 ##
Bucket sort is not suitable for sorting strings.  

# Checkpoint Answers Chapter 24 #
## 24.1 ##
MyList extends Iterable which means that if we have list that is an instance of MyList, so can we get an iterator for list using list.iterator().  

# Checkpoint Answers Chapter 25 #
## 25.4 ##
The time complexity of inserting an element to a binary tree is O(n).  

## 25.8 ##
The time complexity of deleting an element from a binary tree is O(n).  

## 25.10 ##
The displayTree method will be invoked 0 time if the tree is empty.  

The displayTree method will be invoked 100 times if the tree has 100 nodes.  

# Checkpoint Answers Chapter 26 #
## 26.1 ##
AVL trees are a form of BST tree but always well-balanced. In an AVL tree, the difference between the heights of two subtrees for every node is 0 or 1.  

The balance factor of a node is the height of its right subtree minus the height of its left subtree.  

A node is said to be balanced if its balance factor is -1, 0, or 1.  

A node is said to be left-heavy if its balance factor is -1.  

A node is said to be right-heavy if its balance factor is +1.  

## 26.4 ##
AVLTreeNode defines the data field `height`, that stores the height of the node.   

AVLTreeNode inherits from TreeNode so it will also have the data fields `left` and `right`, that points to the left and right subtree. 
