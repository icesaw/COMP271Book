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
