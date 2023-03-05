# Activities

## Task 1

Refer to the following link. Explain how the Knapsack Algorithm works:
https://monicagranbois.com/knapsack-algorithm-visualization/
answer:DONE in class

## Task 2

Refer to the following link. What are the difference between the brute force and the optimized solutions to the Knapsack problem.
https://www.educative.io/blog/0-1-knapsack-problem-dynamic-solution
the answer: The most obvious solution to this problem is brute force recursive. This solution is brute-force because it evaluates the total weight and value of all possible subsets, then selects the subset with the highest value that is still under the weight limit.
While this is an effective solution, it is not optimal because the time complexity is exponential. we should use this solution if we’re asked for a recursive approach. It can also be a good starting point for the dynamic solution
we optimize our recursive solution through the addition of top-down dynamic programming to handle the overlapping subproblems.
Since we have two changing values (capacity and currentIndex) in our recursive function knapsackRecursive(), we can use a two-dimensional array to store the results of all the solved sub-problems. As mentioned above, we need to store results for every sub-array (i.e. for every possible index i) and for every possible capacity c.
This is the optimal solution for the knapsack problem in both time and space complexity. Since brute force takes much bigger time and space.

## Task 3

There are different implementations of the stair case problem in the following link:
https://www.enjoyalgorithms.com/blog/climbing-stairs-problem

Compare the time and space complexity of the different approaches
the answer:
Comparison of time and space complexities

Brute force recursive approach: Time = O(2^n), Space = O(n)
Using bottom-up approach of DP: Time = O(n), Space = O(n)
Using the Fibonacci sequence: Time = O(n), Space = O(1)
Binet’s method of matrix exponentiation: Time = O(logn), Space = O(1)

## Task 4: Individual (at home)

- Difference between divide and conquer and dynamic programming
  the answer:
  Dynamic Programming (DP) is defined as a technique that solves some particular type of problems in Polynomial Time. Dynamic Programming solutions are faster than the exponential brute method and can be easily proved their correctness.
- State some application of dynamic programming
  the answer:
  Dynamic programming is used to solve optimization problems. It is used to solve many real-life problems such as,
  (i) Make a change problem
  (ii) Knapsack problem
  (iii) Optimal binary search tree

- Difference between recursion vs dynamic programming
  the answer:
  In dynamic programming, problems are solved by breaking them down into smaller ones to solve the larger ones, while recursion is when a function is called and executed by itself. While dynamic programming can function without making use of recursion techniques, since the purpose of dynamic programming is to optimize and accelerate the process, programmers usually make use of recursion techniques to accelerate and turn the process efficiently.
  When a function can execute a specific task by calling itself, receive the name of the recursive function. In order to perform and accomplish the work, this function calls itself when it has to be executed.
  Using dynamic programming, you can break a problem into smaller parts, called subproblems, to solve it. Dynamic programming involves solving the problem for the first time, then using memoization to store the solutions.
  Therefore, the main difference between the two techniques is their intended use; recursion is used to automate a function, whereas dynamic programming is an optimization technique used to solve problems.
  Recursive functions recognize when they are needed, execute themselves, then stop working. When the function identifies the moment it is needed, it calls itself and is executed; this is called a recursive case. As a result, the function must stop once the task is completed, known as the base case.
  By establishing states, dynamic programming recognizes the problem and divides it into sub-problems in order to solve the whole scene. After solving these sub-problems, or variables, the programmer must establish a mathematical relationship between them. Last but not least, these solutions and results are stored as algorithms, so they can be accessed in the future without having to solve the whole problem again.
- Difference between Top down and bottom up approaches to dynamic programming
  the answer:
  1. Top-Down(Memoization):
     Break down the given problem in order to begin solving it. If you see that the problem has already been solved, return the saved answer. If it hasn’t been solved, solve it and save it. This is usually easy to think of and very intuitive, This is referred to as Memoization.

2. Bottom-Up(Dynamic Programming):
   Analyze the problem and see in what order the subproblems are solved, and work your way up from the trivial subproblem to the given problem. This process ensures that the subproblems are solved before the main problem. This is referred to as Dynamic Programming.

- How to solve a Dynamic Programming Problem?
  the answer: To dynamically solve a problem, we need to check two necessary conditions:

Overlapping Subproblems: When the solutions to the same subproblems are needed repetitively for solving the actual problem. The problem is said to have overlapping subproblems property.
Optimal Substructure Property: If the optimal solution of the given problem can be obtained by using optimal solutions of its subproblems then the problem is said to have Optimal Substructure Property.

Steps to solve a Dynamic programming problem:
Identify if it is a Dynamic programming problem.
Decide a state expression with the Least parameters.
Formulate state and transition relationships.
Do tabulation (or memorization).

> Refer to the [links](#links) section below

## Links

- https://cpp.sh/
- [Recursion vs dynamic programming](https://www.geeksforgeeks.org/introduction-to-dynamic-programming-data-structures-and-algorithm-tutorials/)
- [How to solve a Dynamic Programming Problem ?](https://www.geeksforgeeks.org/solve-dynamic-programming-problem/)
