package com.company;

public class Main {

    public static void main(String[] args) {


    }
}

        // EXERCISE 4


// Question 1
/*  What is an operator? What are unary, binary, and ternary operator? Give an example
of each type of operator in Java.
 */
/*  ANSWER
1. An Operator is a symbol that performs a specific kind of operation with one, two or three operands, which produces a result.
2. Unary Operator - This is an operator that takes just one operand. E.g Unary plus
   Binary Operator - This is an operator that takes two operands. E.g Assignment operator
   Ternary Operator = This is an operator that takes three operands
 */

// Question 2
/*What is the difference between prefix, postfix, and infix operators? Give an example
of such operators in Java.
 */
/* ANSWER
1. prefix operator appears before operand e.g ++r;
   postfix operator appears after operand e.g r--;
   infix operator appears in between the operands e.g r = 2 + 2;
 */

// Question 3
/* What are arithmetic operators, what types of operands do they take, and what type
of results do they produce?
 */
/* ANSWER
Arithmetic operators are operators that takes numeric values as its operand and performs an arithmetic operation
 */

// Question 4
/*Name two operators in Java that take only boolean operands and produce a
boolean value.
 */
/* ANSWER
1. &     Logical AND
2. |     Logical OR
 */

// Question 5
/* What is the difference between the two operators: = and ==?
 */
/* ANSWER
the first operator (=) is called an assignment variable which assigns a value to a variable, while,
the second operator (==) is used to signify equal to
 */

// Question 6
/* Consider the following snippet of code:
        boolean done;
        //Some code goes here
        //your-code-goes-here;
Using a boolean logical operator, invert the current value stored in the done
variable. That is, write a statement that will assign true to the done variable if its
current value is false and false if its current value is true.
 */
/* ANSWER
       boolean b = false;
        b ^= true;
        b ^= false;
 */

// Question 7
/* Consider the following snippet of code:
int x = 23;
int y = ++x % 3;
What will be the value of y after this snippet of code is executed?
 */
/* ANSWER
22
 */

// Question 8
/* Consider the following snippet of code:
int x = 23;
x = x++ % x;
What will be the value of x after this snippet of code is executed? Explain your
answer with steps performed explaining how the value of x changes during the
execution of the second statement.
 */
/* ANSWER
Compile time Error;
Duplicate Local Variable x
 */

// Question 9
/*
Explain why the following snippet of code does not compile.
int x = 10;
boolean yes = (x = 20);
 */
/* ANSWER
it couldn't convert from int to boolean
 */

// Question 10
/*
What will be the value assigned to the variable named yes when the following
snippet of code is executed:
int x = 10;
boolean yes = (x == 20);
 */
/* ANSWER
false
 */

// Question 11
/* What will be the value of y when the following snippet of code is executed:
int x = 19;
int y = x > 10 ? 69 : 68;
 */
/* ANSWER
69
 */

// Question 12
/* You have a short variable named x, which is declared and initialized as follows:
short x = -19;
You want to assign 19 to x using the following statements, both of which do not compile:
x = -x;
x = -1 * x;
How will you rewrite these two statements to make them compile? What is wrong
with the following statement that attempts to fix the compile-time error in these
statements, but fails to assign 19 to x?
x -= x;
 */
/* ANSWER

 */

// Question 13
/* What will be the output when the following snippet of code is executed:
boolean b = true;
String str = !b +" is not " + b;
System.out.println(str);
 */
/* ANSWER
false is not true
 */

// Question 14
/* What will be the output when the following snippet of code is executed:
boolean b = true;
String str = (b ^= b) + " is " + b;
System.out.println(str);
 */
/* ANSWER
The Operator - is undefined for the argument type(s) boolean
 */

// Question 15
/* What will be the output when you execute the following snippet of code:
int x = 10;
int y = x++;
int z = ++x;
System.out.println("x = " + x + ", y = " + y + ", z = " + z);
 */
/* ANSWER
x = 12, y = 10, z = 12
 */

// Question 16
/* Complete the second statement using the ternary operator (?:) and the bitwise
AND operator (&) that will make a message "x is odd". Your code must contain
of the following tokens in any order: x, &,==, ?, :, "odd", and "even". You may use
additional tokens as needed.
int x = 19;
String msg = your-code-goes-here ;
System.out.println("x is " + msg);
 */
/* ANSWER
int x = 19;
int even = 1;
int odd = 0;
even & odd;


 */

// Question 17
/*Which of the following assignments will fail to compile and why?
int i1 = 100;
int i2 = 10.6;
byte b1 = 90;
byte b2 = 3L;
short s1 = -90;
float f1 = 12.67;
float f2 = 0.00f;
double d1 = 12.56;
double d2 = 12.78d;
boolean bn1 = true;
boolean bn2 = 0;
char c1 = 'A';
char c2 = "A";
char c3 = 0;
char c4 = '\u0000';
 */
/* ANSWER
int 12 = 10.6;
byte b2 = 3L;
float f1 = 12.67;
boolean bn2 = 0;
char c2 = "A";
 */

// Question 18
/* Write down the value assigned to the declared variable in each of the following
statements. If a statement generates a compile-time error, explain the reason
behind the error and, if possible, provide a solution to fix the error.
int i1 = 10/4;
int i2 = 10.0/4.0;
int i3 = 0/0;
long l1 = 10/4;
long l2 = 10.0/4.0;
float f1 = 10/4;
float f2 = 10.0/4.0;
double d1 = 10/4;
double d2 = 10.0/4.0;
double d3 = 0/0;
double d4 = 0/0.0;
double d5 = 2.9/0.0;
 */
/* ANSWER
1.  int i2 = 10.0/4.0     - double can't be assigned to int
    long l2 = 10.0/4.0      - double can't be assigned to long
    float f2 = 10.0/4.0      - double can't be assigned to float
2.  int i2 = 10/4;
    long l2 = 10/4;
    float f2 = 10F/4F;
 */

// Question 19
/*
Complete the following snippet of code that will assign a 2's complement of x to y.
You must use the bitwise operator.
int x = 19;
int y = your-code-goes-here;
 */
/* ANSWER
int x = 19;
int y = (~x + 1) + x;
 */

// Question 20
/*
What will be the output of the following snippet of code:
int x = 19;
int y = (~x + 1) + x;
System.out.println(y);
 */
/* ANSWER
0
 */
