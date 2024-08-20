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

# O(N)

- An algorithm that is O(N) will take as many steps as there are elements of data. So when an array increases in size by one element, an O(N) algorithm will increase by one step. 
  
### Example:

![O(N) Example](https://github.com/user-attachments/assets/db866f27-8a88-404c-bc74-a3b7c3cbec68)

# O(N²)

- O(N²) represents an algorithm whose performance is directly proportional to the square of the size of the input data set. It is generally quite slow: If the input array has 1 element it will do 1 operation, if it has 10 elements it will do 100 operations, and so on. 
- Two nested loops are usually O(N²)
- Takes the longest.

### Example : 

![O(N²) Example](https://github.com/user-attachments/assets/d088eae5-aee6-4490-92bb-37db7e8fbae6)

# Olog(N)

- It describes an algorithm that its number of operations increases by one each time the data is increased by a certain fold.
- In binary search case, O(logN) describes an algorithm that its number of operations increases by one each time the data is doubled.
- Binary search:
    - Open the dictionary the middle to check the word you are looking for. 
    - If our words is alphabetically more significant, look in the right half, else look in the left half. 
    - Divide the remainder in half again, and repeat steps 2 and 3 until we find our word. 
    - The quickest.
    - Find lowest value then highest.
### Example:

![O(logN)](https://github.com/user-attachments/assets/95139458-ddcd-407e-9d5f-31050b801b3b)

- O(N logN) A log linear algorithm of this complexity class is doing log(N) work N times and therefore it's performance is slightly worse than O(N). Many practical algorithms belong in this category (from sorting, to pathfinding, to compression)
- O(2n) = Exponential growth means that the algorithm takes twice as long for every new element added. Poor performance. 
- O(N!) - Factorial This class of algorithms has a run time proportional to the factorial of the input size. 
Very poor performance.

O(1) < O(logN) < O(N) < O(N logN) < O(N²) < O(2n) < O(N!)

### Diagram:

![Big o notation diagram](https://github.com/user-attachments/assets/c2b6a39b-f38c-413b-9de4-46ea15fcbe3e)

# Binary Search Example:

![binary search example](https://github.com/user-attachments/assets/28baf6ec-a525-48b0-980b-9f8d62f24a44)



1:05:05