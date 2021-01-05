package com.company;

public class Main {

    public static void main(String[] args) {
    }
}
	// Solution to Exercise 4

        // Question 1
        /* What is an identifier in Java? What can an identifier consist of? List five valid and
        five invalid identifiers in Java.*/
     //ANS -:  An identifier in Java is a sequence of characters with unlimited length. It consists of different characters. Module, package class, variable, method,

        // Question 2
        /*What are keywords, reserved keywords, and restricted keywords in Java? Is an
underscore a keyword in Java?*/
        // Keywords are words that have predefined meanings in the java programming language. Reserved keywords are keywords reserved for future use, while, restricted keywords are keywords that has special meaning when used in specific places and in other
        //places they are not treated as keywords. An underscore iss a keyword in Java.

        // Question 3
        /*What is a data type? What is the difference between a primitive data type and a
        reference data type?*/
        // A data type is a data representation, which determines how the values are stored. Primitive data type represent atomic, indivisible values. while, reference data types represents references of objects in memory

        // Question 4
        /*List the names of all eight primitive data types supported by the Java programming
language. List their size in bytes.*/
        /* byte - 8
        int - 32
        char - 16
        long - 64
        double - 64
        boolean
        float - 32
        short - 16
         */

        // Question 5
        /*What are literals? List two literals of each primitive type in Java.*/
        /* Literals are constant that can be represented directly in source code.
        byte - nil
        long - 25L, 031L
        int - 25, 01000
        short - nil
        char - 'A', '5'
        double - 8D, 8.
        boolean - true, false
        float - 8F, 8.F
         */

        // Question 6
        // What is the shortest numeric primitive type in Java? What is the range of its values?//
        /*
        byte - -128 to 127
         */

        // Question 7
        /*Consider the following two variable declarations:
        byte small = 10;
        int big = 99;
        How will you assign the value in the big variable to the small variable?
         */
        /* small = byte(big);
         */

        // Question 8
        //Why do you need to use a cast when you assign a variable of a bigger size to a variable of smaller size, for example, assigning an int variable to a byte variable?
        /*Based on their size, the compiler sees that you are assigning a bigger variable to a smaller variable and there is a potential of loss of data.
         */

        // Question 9
        //Name two primitive data types in Java whose values can be floating-point numbers
        /* float
        double
         */

        // Question 10
        // If you declare a variable of the boolean type, what are the two possible values it can have?
        /* True
        false
         */

        // Question 11
        /* Can you cast a boolean value to an int type, as shown in the following statement?
            boolean done = true;
            int x = (int) done;
            What happens when you compile this snippet of code?
         */
         /*Unresolved compilation problem:
        Cannot cast from boolean to int
          */

        // Question 12
        // Are the boolean literals true and false the same as integers 1 and 0?
        // No

        // Question 13
        // Name an unsigned numeric data type in Java.
        // Char

        // Question 14
        //Name the four different formats of writing the literals of char data types. Give two examples of each
        /*
        As a character enclosed in single quotes - 'A'
        As a character escape sequence - '\n'
        As a Unicode escape sequence - '\u0041'
        As an octal escape sequence- '\174'
         */

        // Question 15
        /*
        How do you represent a backslash (\) and a double quote (") as char literals in Java? Write code to declare two char variables named c1 and c2. Assign a
        backslash character to c1 and a double quote character to c2.
         */
         /*   '\\', '\"'
            char c1 = '\\';
            char c2 = '\"';
            */


        // Question 16
        /*
        What are 1's and 2's complements of binary numbers? Compute the 1's and 2's
        complements of the binary number 10111011.
         */
        //


        // Question 17
        /*17. Why does the following line of comment in a Java program not compile? \u000A is
            a Unicode code value for linefeed.
                    char c = '\u000A';
         */
        //it has more thn two zeros

        // Question 18
        //How many zeros are supported by float and double data types?
        //



        // Question 19
        /*What is NaN? How many NaNs are supported by float and double types in Java?
        Differentiate between a quiet NaN and a signaling NaN. What types of NaNs are
        supported by Java—quiet NaNs, signaling NaNs, or both?
                */
        /* NaN stands for “Not-a-Number.” NaN is the result of arithmetic operations that do not have meaningful results
        2. one each
        3. A quiet NaN, when encountered as an operand in an arithmetic expression, quietly produces another quiet NaN as the result, while, a signaling NaN is encountered as an operand in an arithmetic expression, an invalid operation
            exception is signaled and a quiet NaN is delivered as the result
        4. A quiet NaNs
         */

        // Question 20
        // What are denormals or denormalized floating-point numbers?
        //When the biased exponent is 0 and the significand is non-zero, it denotes a denormalized number


        // Question 21
        /*What are the different rounding modes for floating-point numbers? What rounding
        modes are supported by Java?
         */
        /*
       1.    • Round toward zero
        • Round toward positive infinity
        • Round toward negative infinity
        • Round toward nearest

        2. Rounding toward nearest
         */


        // Question 22
        /*
        What are little-endian order and big-endian order? What endian-order does Java
        use to encode the multi-byte binary data in class files?
         */
        /*
        1.  little-endian is the "natural" order, where the less significant byte comes before more a significant byte in memory, while,
             big-endian is the order where the more significant byte comes before the less significant part.
        2.   big-endian
         */
