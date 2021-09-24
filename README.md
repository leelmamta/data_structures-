# Data structures from basics 
## Array 

#### Day1 - Sorting

- Bubble Sort - It can detect if the array is already sorted or not. 
- Selection Sort - It requires minimum number of swaps 
- Insertion Sort 
: is used when array is nearly sorted o(nlogk) . 
- Shell Sort : it is same as insertion sort but the trick is in insertion sort we find place for all the elements in sorted array and start from i = 1 while 
   in shell sort we work based on gap and initialize gap = n/2 and in each pass gap = floor (n/2) <br />
   In last step shell sort work same as insertion sort. <br />
   The worst case time complexity is o(n*log^2(n))
   Best case - o(n) 
   We can improve the complexity by deciding gap 

- Merge Sort : It is divide and conquer based algorithm </br> 
  In merge sort the input is divided into two parts and these are solved recursively . After solvig the subproblems , they are merged by scanning the resultant      sub problems . </br>
     Used : In sorting linked list </br>
    In Quick sort most of the work is done before the recursive calls. Quick Sort starts with the largest subfile and finishes with the small ones and as a result     it needs stack. Moreover , this algorithm is not stable. Merge sort divides the list into two parts ; then eash part is conquered individually . Merge sort       starts with small subfile and finishes with largest one as a result it doesn't need stack. This algorithm is stable. 

- Heap Sort - in-place since the heap and partially sorted array occupy opposite ends of input array. 
- Quick Sort - Not inplace because it is recursive and stores o(logn) activation records on the stack . 
- Tree Sort
- Counting SOrt - it is simply counting frequency of elements but it gives o(n) time if  0<arr[i]<=n 
- Bucket Sort 
- Radix Sort - In this we sort digit by digit , sorting from least significant digit to most significant bit 
</br>
Another method to do k-nearly sorted array to be sorted in o(nlogk) time is divide the array in n/k groups of size k and sort each piece in nlogk time and now merge all the n/k groups . 
Another is Binary heap for k-nearly sorted array . Insert first k elements to the binary heap and then extract min elemeent and enter the new element . Repeat . 

There are some questions in the repository 
#### Day2 - Searching 
##### Linear search 
##### Binary Search 
##### Interpolation search 


## Week 2 : - Stack and queues +interview bit - array + LL + Stack + queue + maths track 



