# DAA-PRACTICAL-2021
DAA practical 2021  

ANALYSIS OF ALGORITHM

Analysis of algorithms is the determination of the amount of time and space resources required to execute it. Usually, the efficiency or running time of an algorithm is stated as a function relating the input length to the number of steps, known as time complexity, or volume of memory, known as space complexity.

# Question 1: Red- Black Tree
  Complexity Analysis:
  Search:- O(log n)
  Insert:-	O(log n)
  Delete:-	O(log n)
 
 Applications:
 
 a) They are used in the K-mean clustering algorithm for reducing time complexity.
 b) Completely Fair Scheduler used in current Linux kernels  
 c) Epoll system call implementation[21] uses red–black trees.


# Question 2: Minimum Spanning Tree
  Complexity Analysis:
  Best Case:O(N logE) 
  Worst Case:O(ElogE) or O(ElogV)
  Average Case:O(ElogE)
  
  Applications:
  
  a) Approximation algorithms for NP-hard problems
  b) Network Design
  c) Cluster Analysis
 
 
 # Question 3: 
 ## Bubble
  Complexity:
 a) Worst and Average Case Time Complexity: O(n*n).
 b) Best Case Time Complexity: O(n). 
 
 Application:
 
 a) Bubble sort is often used to introduce the concept of a sorting algorithm.
 b) In computer graphics it is popular for its capability to detect a very small error (like swap of just two elements) in almost-sorted arrays and fix it with just linear complexity (2n). 
 
 ## Selection
 Complexity:
 O(n^2) 

 Application:
 
 a)Selection sort almost always outperforms bubble sort and gnome sort.
 b)Can be useful when memory write is a costly operation
 c)While selection sort is preferable to insertion sort in terms of number of writes (Θ(n) swaps versus Ο(n^2) swaps).
 d)This can be important if writes are significantly more expensive than reads, such as with EEPROM or Flash memory, where every write lessens the lifespan of the memory.
 
 ## Insertion
 Complexity:
 Worst case time complexity: Θ(N^2) 
 Average case time complexity: Θ(N^2) 
 Best case time complexity: Θ(N) 
 
 Application:
 
 a)If the cost of comparisons exceeds the cost of swaps, as is the case for example with string keys stored by reference or with human interaction, then using binary insertion sort may yield better performance.
 b)A variant named binary merge sort uses a binary insertion sort to sort groups of 32 elements, followed by a final sort using merge sort.
 c)If a skip list is used, the insertion time is brought down to O(log n), and swaps are not needed because the skip list is implemented on a linked list structure. The final running time for insertion would be O(n log n).
 
 ## Merge
 Complexity:
 Worst case time complexity: Θ(N log N)
 Average case time complexity: Θ(N log N)
 Best case time complexity: Θ(N log N)
  
  Applications:
  
  a)Merge Sort is useful for sorting linked lists in O(n Log n) time
  b)Merge sort can be implemented without extra space for linked lists
  c)Merge sort is used for counting inversions in a list
  
  ## Quick 
  Complexity:
  Worst case time complexity: Θ(N^2)
  Average case time complexity: Θ(N log N)
  Best case time complexity: Θ(N log N)
  
  Applications:
  
  a)Quick Sort is a cache friendly sorting algorithm as it has good locality of reference when used for arrays
  b)Quick Sort is tail recursive and hence, all tail call optimizations can be done
  c)Quick Sort is an in-place sort that is does not require any extra storage

 
