# Java-Practice
These are the practices I have done while learning Java as a self-taught programmer. 'cause of that it is possible that there can be some inconsistencies or missing points between practices; if you notice some, feel free to get in contact with me. I also seperated the practices into different levels. There is no official categorization so it is my own categorization, don't tak those so seriously. If you are a beginner, you should have a look and try to solve these basic practices:-)

The list of practices are below:

# 1.1 Hello World!

**Problem: Writing `Hello World!` to Terminal screen.**

As you would guess, the first thing to do when learning a new programming language is to write `Hello World!` to the beloved terminal screen. It is important to learn using terminal screen as a basic UI to have in contact with the people using your program. Also, the most basic program structure is used in this practice.

Important points are the `public class HelloWorld()` and `public static void main(String args[])` inside main class. These are the main driver code to run the program. Inside the main function, we use `System.out.println()` method to write something on the terminal screen. I will go in the details of the keywords used in main method and class will be given in the coming problems. Also some of the key syntax rules in Java are that the function and class scopes are declared inside curly brackets `{ }`. Also, if there is no curly bracket at the end of the line, a semicolon `;` is used at the end.

# 1.2 Basic Variables

**Problem: By using the variable types `integer`,`character`,`String`,`boolean` and `double` create variables and print all of them by using `System.out.println()`.**

This practice teaches how to create variables and assign values into these variables. In Java, to create a variable, firstly the designation of the variable type is written. As written above, the most basic variable types are `integer`,`character`,`String`,`boolean` and `double`. The designations and explanations are below.

`int` / Integer --> Whole number values are stored. 

`char` / Character --> Letters, numbers and other symbols can be stored in Unicode. You can use this [link](https://home.unicode.org/) to get more information about Unicode. Only a single value can be stored and data should be surroundedd with single apostrophe `'`.

`String` / String --> It is a bunch of `char` data combined. Useful to store sentences and writings. Supports Unicode. Data should be surrounded with double apostrophe `"`.

`boolean`/ Boolean --> Holds only the values `true` and `false`. Is used for comparison and useful when using if else statements.

`double`/ Double --> Decimal numbers can be stored in double values. Between whole and decimal, a point `.`is put such as `5.23`.

A variable can be initialized as below:
`varType varName = data`
Example: `int myVar = 0`
