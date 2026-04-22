# Arbitrary Precision Calculator

This project implements an Arbitrary Precision Calculator using the C programming language. The calculator performs arithmetic operations on very large integers that exceed the storage capacity of standard C data types.

Instead of built-in numeric types, numbers are represented using linked lists where each node stores a single digit. This approach enables handling integers of virtually unlimited size.

The project demonstrates concepts of dynamic memory management, data structures, and algorithm design for high precision computation.

Features:
- Supports very large integer arithmetic
- Addition of large numbers
- Subtraction handling with borrow propagation
- Multiplication of large integers
- Linked list based number representation
- Dynamic memory allocation
- Digit-by-digit computation

Technologies Used:
- C Programming Language
- Data Structures
- Linked Lists
- Dynamic Memory Allocation
- Algorithm Design
- GCC Compiler
- Linux Environment

Project Structure:
arbitrary_precision_calculator/
main.c  
add.c  
subtract.c  
multiply.c  
list_operations.c  
header.h  
README.md  

Compilation:
gcc *.c -o ap_calculator

Execution:
./ap_calculator

Working Principle:
Large integers are stored as linked lists where each node contains a digit. Arithmetic operations are performed digit by digit similar to manual mathematical calculations. Carry and borrow propagation mechanisms ensure accurate results even for extremely large numbers.

Learning Outcomes:
- Linked list implementation
- Memory management in C
- Handling numbers beyond primitive data types
- Algorithm optimization
- Modular program design

Future Improvements:
- Division operation support
- Negative number handling
- Floating point precision
- Expression evaluation support
- GUI interface

Author:
Aswathi E P  
Embedded Systems Engineer  

GitHub: https://github.com/aswathi-gopinath  
LinkedIn: https://www.linkedin.com/in/aswathi-ep-by0256  

License:
Educational and learning purpose project.
