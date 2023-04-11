# a-very-specific-structure
Let’s go over this hello.cpp program line by line:

// This program outputs the message "Hello World!" to the monitor
This is a single-line comment that documents this code. The compiler will ignore everything after // to the end of the line. Sometimes, you will find this comment to include the author’s name or document what the code does.
#include <iostream>
This is known as a pre-processor directive. It instructs the compiler to locate the file that contains code for a library known as iostream. This library contains code that allows for input and output, such as displaying data in the terminal window or reading input from your keyboard.

int main() {
  // Statements
}
Every C++ program must have a function called main(). A function is basically a sequence of instructions for the computer to execute. This main() function houses all of our instructions for our program. This is where we will be writing our code.
std::cout << "Hello World!\n";
This code uses a method known as cout (pronounced “see out”) to send the text “Hello World!” to the terminal for output.

return 0;
The return statement is used to end a function. If the program reaches this statement, returning a value of 0 is an indication to the operating system that the code executed successfully. This line of code is optional.

C++ programs permit judicious use of white space (tabs, spaces, new lines) to create code that is easier to read. The compiler completely ignores the white space, with a small exception concerning if statements that will be covered later. It is highly recommended that you make use of white space to indent and separate lines of code to aid in the readability of your source code files.
