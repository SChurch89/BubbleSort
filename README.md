# BubbleSort
This code implements the bubble sort algorithm, a simple sorting algorithm that repeatedly steps through the list to be sorted, compares adjacent elements, and swaps them if they are in the wrong order. Here's a breakdown of the code:

Initialization of the Array: The intArray is initialized with seven integers, some of which are negative.

Outer Loop (Sorting Loop): The outer loop runs from the last index of the array down to the first. It represents the portion of the array that is still unsorted. The variable lastUnsortedIndex keeps track of the boundary between the sorted and unsorted parts of the array.

Inner Loop (Comparison Loop): The inner loop runs from the beginning of the array to lastUnsortedIndex, and it's used for comparing adjacent elements in the array.

Comparison and Swap: If the current element (intArray[i]) is greater than the next element (intArray[i + 1]), they are in the wrong order, and the swap method is called to exchange their positions in the array.

The Swap Method: The swap method takes in the array and the indices of two elements (i and j) and swaps their positions in the array. If i and j are the same, no swap is needed, and the method returns early. Otherwise, the method uses a temporary variable temp to hold one of the values during the swap.

Printing the Sorted Array: After the sorting is complete, a final loop prints the elements of the sorted array to the console.

The resulting output of the code will be the sorted version of the intArray, printed line by line. In this case, the sorted array will be:


-22
-15
1
7
20
35
55
The bubble sort algorithm has a time complexity of 


O(n^2) in the worst case, making it less efficient for large lists compared to more advanced sorting algorithms like quicksort or mergesort.
