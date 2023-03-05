# Activities

## Task 1

- Refer to the following link. Discuss how the
  Recursive Factorial works:
  https://www.cs.usfca.edu/~galles/visualization/RecFact.html
- Refer to the following link. Discuss how the Recursive Fibonacci works:
  https://www.cs.usfca.edu/~galles/visualization/DPFib.html

  DONE in the class

## Task 2

There are `n` stairs, a person standing at the bottom wants to reach the top. The person can climb either 1 stair or 2 stairs at a time. There is a simple implementations in `./src/` folder. Discuss how the code works.
DONe in the class

## Task 3

- There are `n` stairs, a person standing at the bottom wants to reach the top. The person can climb either 1 stair or 2 stairs or **3 stairs** at a time. Write a program that counts the number of ways, the person can reach the top. You can use the following program as a starter `./src/staircase1.cpp`. Also the link below might useful:
  https://www.includehelp.com/cpp-programs/stair-case-program-to-solve-the-staircase-problem.aspx
  done in the class

## Task 4: Individual (at home)

- What are the pros/cons of recursive over iterative Programming?
  the answer:
  Recursive programs provide compact and clean code. A recursive program is a simple way of writing programs. There are some inherent problems like factorial, Fibonacci sequence, towers of Hanoi, tree traversals, etc. which require recursion for solving.

In other words, they are solved efficiently with recursion. They can also be solved with iterative programming using stacks or other data structures but there are chances to become more complex to implement.

Problem-solving powers of recursive as well as iterative programming are the same. However, recursive programs take more memory space as all the function calls need to be stored on the stack until the base case is matched.

Recursive functions also have a time overhead because of too many function calls and return values.

- Difference between recursion and induction.
  the answer:
  1.Recursion is the process in which a function is called again and again until some base condition is met.
  Induction is the way of proving a mathematical statement.
  2.Recursion is the way of defining in a repetitive manner. Induction is the way of proving.
  3.Recursion starts from nth term till the base case. Induction starts from the initial till (n+1)th term.
  4.Recursion has two components: Base condition; Recursive step. Induction has two steps:Base step;Inductive step
  5.Recursion: We backtrack at each step to replace the previous values with the answers using the function. Induction: We just prove that the statement is true for n=1. Then we assume that n = k is true. Then we prove for n=k+1.
  6.Recursion: No assumptions are made. Induction: The assumption is made for n= k
  7.Recursive function is always called to find successive terms. Induction: Here statements or theorems are proved and no terms are found.
  8.recursion: It can lead to infinity if no base condition is given. Induction: there is no concept of infinity.

> Refer to the [links](#links) section below.

## Links

- https://cpp.sh/
- [Difference Between Recursion and Induction](https://www.geeksforgeeks.org/difference-between-recursion-and-induction/)
- [Recursion vs Iterative Programming](https://www.softwaretestinghelp.com/recursion-in-cpp/)
