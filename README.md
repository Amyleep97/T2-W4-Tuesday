# T2-W4-Tuesday

# CS Fundamentals Big O Notation

# Introduction

- An algorithm's Big-O notation is determined by how it responds to different sizes of a given dataset. For instance how it performs when we pass to it 1 element vs 10,000 elements. 
- Big-O puts the number of steps in the spotlight. The hardware factor is taken out of the equation. Therefore we are not talking about run time, but about time complexity.
- Estimating the growth of the function without having to worry about constant multiplier or smaller order terms.
- Used extensively to estimate the number of operations an algorithm will use as its inputs grows.
- Can be used to compare two algorithms to determine which one is more efficient as the size of the inputs grows.

# Worst case scenario

- The Big-o notation takes a pessimistic approach to performance and refers to the worst case scenario.
- [12, 56, 3, 31, 56, 24, 6,75]

Searching for 24 -> 6 steps
Searching for 56 -> 2 steps
...

- Big O Notation -> 8 steps 
- If the array contains 300 elements -> 300 steps
- As the size of the array grows, the steps of the algorithm grow as well. 

# O(1)

- O(1) means that the algorithm takes the same number of steps to execute regardless of how much data is passed in. It describes an algorithm that will always execute same amount of steps regardless of the size of the input data set. 
- Fastest complexity, if yours says O(1) it will execute it the fastest.

### Example:

![O(1) example](https://github.com/user-attachments/assets/d255daae-3222-456e-8e1a-1ce5953d29b6)

