# Experiment-10
## Program 1
## Aim
Declare and initialize pointers of different data types and print the following values (Repeat for float and char data types)

## Software used
Visual Studio Code

## Theory
In C++, a pointer is a variable that holds the memory address of another variable. To declare a pointer, you specify the type of the variable it will point to, followed by an asterisk (*). Pointers need to be initialized with the address of a variable, which is obtained using the address-of operator (&). They are essential for dynamic memory management, handling arrays, and passing arguments efficiently to functions.

## Output
![image](https://github.com/user-attachments/assets/3d441e82-56e8-4f97-88bf-faac36aa04b3)

## Conclusion
We learned about pointers in C++.

## Program 2
## Aim
Access array using pointer and without using pointer variable

## Software used
Visual Studio Code

## Theory
In C++, pointers can be utilized to access array elements. When an array is declared, its name functions as a pointer to the array's first element. By using pointer arithmetic, you can navigate through the array by incrementing the pointer to access subsequent elements. This approach is particularly useful for processing arrays within functions or managing dynamic memory.

## Output
![image](https://github.com/user-attachments/assets/2742299b-8300-4fe5-9293-c83a7bc0d52b)

## Conclusion
We learned how pointers work in arrays.

## Program 3
## Aim
Swap the numbers using call-by-value

## Software used
Visual Studio Code

## Theory
In the call-by-value mechanism, when a function is called, a copy of the actual arguments is passed to the function. The function works with these copies, and any modifications to the parameters inside the function do not affect the original variables outside the function. Call by value is simple and safe, as it prevents accidental changes to the original data, but it can be inefficient when passing large data structures.

## Output
![image](https://github.com/user-attachments/assets/9524f5d5-1d6e-452d-bdbe-176bd1a9c916)

## Conclusion
We learned about the call-by-value operation in C++.

## Program 4
## Aim
Swap the numbers using call-by-reference.

## Software used
Visual Studio Code

## Theory
In the call-by-reference mechanism, instead of passing a copy of the arguments, the function receives references (or pointers) to the original variables. Any changes made to the parameters inside the function will directly affect the original variables. This method is more efficient for large data structures and allows functions to modify the caller's variables, but it requires caution to avoid unintended side effects.

## Output
