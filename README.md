# Aim: To study and implement C++ decision making statements Loops
# Software Required :
Visual Studio
# Theory:
Different Types of Loops
C++ provides three types of loops that works the same, but are preferred in different use cases:

1. <ins>For Loop</ins>:
   
The for loop is an entry-controlled loop, which means that it checks whether the test condition is true before executing the statements inside it.
The various parts of the for loop are:

+ Initialization: Initialize the variable to some initial value.
+ Test Condition: This specifies the test condition. If the condition evaluates to true, then body of the loop is executed. If evaluated false, loop is terminated.
+ Update Expression: After the execution loop's body, this expression increments/decrements the loop variable by some value.
All these together is used to create a logic and flow of the loop.

<img width="900" height="500" alt="Screenshot 2025-07-25 162955" src="https://github.com/user-attachments/assets/f7ad2c73-e333-4f0d-9065-172f90f5eb74" />


2.<ins>While Loop:</ins>

The while loop is also an entry-controlled loop which is used in situations where we do not know the exact number of iterations of the loop beforehand.

In for loop, we have seen that the number of iterations is known beforehand, i.e. the number of times the loop body is needed to be executed is known to us and we create the condition on the basis of it. But while loops execution is solely based on the condition.

<img width="800" height="500" alt="Screenshot 2025-07-25 163014" src="https://github.com/user-attachments/assets/8baa14b9-dd88-422f-800d-fe4ca678fa1f" />

3. <ins>Do-While Loop</ins>

The do-while loop is an exit-controlled loop which means the condition is checked after executing the body of the loop. So, in a do-while loop, the loop body will execute at least once irrespective of the test condition.


<img width="900" height="500" alt="Screenshot 2025-07-25 163338" src="https://github.com/user-attachments/assets/3be14645-3fce-42d3-8764-3ee92f1bfb2e" />

Infinite Loops:

An infinite loop (sometimes called an endless loop) is a piece of coding that lacks a functional exit so that it repeats indefinitely. An infinite loop occurs when a condition is always evaluated to be true.

Nesting of Loops:

Nesting of loops refers to placing one loop inside another. The inner loop is executed completely for each iteration of the outer loop. This is useful when you need to perform multiple iterations within each iteration of a larger loop, such as iterating over a two-dimensional array or performing operations that require more than one level of iteration.

# Implementation:
The Logic and conditional flow of the statements were seen through the following programs :
+ Printing even numbers from 1 to 10
+ reversing of integer values
+ Simple login through password
+ Patterns(Star Patterns, Floyd's series)
# Conclusion:
Through the programs , The logic and operation of loops in C++ has been studied.
