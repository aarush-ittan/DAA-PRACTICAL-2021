# DAA-PRACTICAL-2021
DAA practical 2021  

# *ANALYSIS OF ALGORITHM*

Analysis of algorithms is the determination of the amount of time and space resources required to execute it. Usually, the efficiency or running time of an algorithm is stated as a function relating the input length to the number of steps, known as time complexity, or volume of memory, known as space complexity.

# Question 1: Red- Black Tree
  Complexity Analysis:
  Search:- O(log n)
  Insert:-	O(log n)
  Delete:-	O(log n)
 
 Applications:
 
 1. They are used in the K-mean clustering algorithm for reducing time complexity.
 2. Completely Fair Scheduler used in current Linux kernels  
 3. Epoll system call implementation[21] uses red–black trees.


# Question 2: Minimum Spanning Tree
  Complexity Analysis:
  Best Case:O(N logE) 
  Worst Case:O(ElogE) or O(ElogV)
  Average Case:O(ElogE)
  
  Applications:
  
  1. Approximation algorithms for NP-hard problems
  2. Network Design
  3. Cluster Analysis
 
 
 # Question 3: 
 ## Bubble
  Complexity:
  Worst and Average Case Time Complexity: O(n*n).
  Best Case Time Complexity: O(n). 
 
 Application:
 
 1. Bubble sort is often used to introduce the concept of a sorting algorithm.
 2. In computer graphics it is popular for its capability to detect a very small error (like swap of just two elements) in almost-sorted arrays and fix it with just linear complexity (2n). 
 
 ## Selection
 Complexity:
 O(n^2) 

 Application:
 
 1. Selection sort almost always outperforms bubble sort and gnome sort.
 2. Can be useful when memory write is a costly operation
 3. While selection sort is preferable to insertion sort in terms of number of writes (Θ(n) swaps versus Ο(n^2) swaps).
 
 ## Insertion
 Complexity:
 Worst case time complexity: Θ(N^2) 
 Average case time complexity: Θ(N^2) 
 Best case time complexity: Θ(N) 
 
 Application:
 
 1. If the cost of comparisons exceeds the cost of swaps, as is the case for example with string keys stored by reference or with human interaction, then using binary insertion sort may yield better performance.
 2. A variant named binary merge sort uses a binary insertion sort to sort groups of 32 elements, followed by a final sort using merge sort.
 3. If a skip list is used, the insertion time is brought down to O(log n), and swaps are not needed because the skip list is implemented on a linked list structure. The final running time for insertion would be O(n log n).
 
 ## Merge
 Complexity:
 Worst case time complexity: Θ(N log N)
 Average case time complexity: Θ(N log N)
 Best case time complexity: Θ(N log N)
  
  Applications:
  
  1. Merge Sort is useful for sorting linked lists in O(n Log n) time
  2. Merge sort can be implemented without extra space for linked lists
  3. Merge sort is used for counting inversions in a list
  
  ## Quick 
  Complexity:
  Worst case time complexity: Θ(N^2)
  Average case time complexity: Θ(N log N)
  Best case time complexity: Θ(N log N)
  
  Applications:
  
  1. Quick Sort is a cache friendly sorting algorithm as it has good locality of reference when used for arrays
  2. Quick Sort is tail recursive and hence, all tail call optimizations can be done
  3. Quick Sort is an in-place sort that is does not require any extra storage

 
