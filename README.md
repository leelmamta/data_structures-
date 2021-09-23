# Data structures from basics 
## Array 

#### Day1 - Sorting

- Bubble Sort 
- Selection Sort 
- Insertion Sort 
: is used when array is nearly sorted . 
- Shell Sort : it is same as insertion sort but the trick is in insertion sort we find place for all the elements in sorted array and start from i = 1 while 
in shell sort we work based on gap and initialize gap = n/2 and in each pass gap = floor (n/2) <br />
In last step shell sort work same as insertion sort. <br />
The worst case time complexity is o(n*log^2(n))
Best case - o(n) 
We can improve the complexity by deciding gap 

- Merge Sort : It is divide and conquer based algorithm </br> 
In merge sort the input is divided into two parts and these are solved recursively . After solvig the subproblems , they are merged by scanning the resultant sub problems . </br>
Used : In sorting linked list </br>
In Quick sort most of the work is done before the recursive calls. Quick Sort starts with the largest subfile and finishes with the small ones and as a result it needs stack. Moreover , this algorithm is not stable. Merge sort divides the list into two parts ; then eash part is conquered individually . Merge sort starts with small subfile and finishes with largest one as a result it doesn't need stack. This algorithm is stable. 

- Heap Sort 
- Quick Sort 
- Tree Sort
- Counting SOrt - it is simply counting frequency of elements but it gives o(n) time if  0<arr[i]<=n 
- Bucket Sort 
- Radix Sort - In this we sort digit by digit , sorting from least significant digit to most significant bit 

There are some questions in the repository 
#### Day2 - Searching and Rotation 
#### Day3 - Arrangement Rearrangement & Order Statistics
#### Day4 - Matrix 
#### Day5 - Optimization Problems 

## Linked List 
#### Day6 - Complete LL 
## Stack 
#### Day7 - Stack 
## queues 
#### Day8 - queues 
## Trees 
#### Day 9 , 10 , 11 , 12 
## Graph 
#### Day 13 14 15 16 
## Dynamic Programming 
#### Day 17 18 19 20 


