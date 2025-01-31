#Part 1: Big Real Numbers
**Overview**
In this part, we developed the BigReal class to handle precise operations on large real numbers, similar to BigInteger and BigDecimal classes. The goal was to implement and validate a robust system for handling and operating on real numbers.

**Features**
_Design Separation:_
The class is split into a header file (for declarations) and an implementation file (for definitions).
This ensures modular and maintainable code.
_Input Validation:_
Validates string inputs to ensure they represent real numbers.
_Implemented Operators:_
Relational Operators: <, >, ==
Input/Output Operator: <<
Arithmetic Operators: +, -

**how to run**
Include the BigReal header and implementation files in your project.
Compile the project and use the operators (<, >, ==, +, -, <<) as required.
Pass real numbers either as strings or other supported formats to validate and process them.

#Part 2 : 
**Overview**
This part focuses on designing a simulator for the Vole machine and its language, capable of simulating the machine's operation and running programs. we depend on oop concepts like like classes, inheritance, encapsulation, abstraction and polymorphism.

**Features**
_Menu Interface:_
Provides the user with a menu of choices for interacting with the simulator.
_Program Loading:_
Allows users to load a new program from a file.
_Instruction Fetching and Execution:_
Fetches instructions step by step into the Instruction Register (IR).
Validates each instruction to ensure it is a valid step.
Executes the valid instructions.
_Status Display:_
Displays the status of:
Registers
Program Counter (PC)
Instruction Register (IR)
Memory
Screen
The status can be displayed either after each step or at the end of program execution.
Output is displayed in a text format for clarity.

