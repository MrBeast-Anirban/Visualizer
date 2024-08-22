<h2>1. Selection Sort</h2>

Selection Sort is a simple and intuitive sorting algorithm. It works by repeatedly finding the minimum element (or maximum, depending on sorting order) from the unsorted portion of the array and moving it to the beginning (or end) of the sorted portion.

Algorithm:
Start with the first element of the array.
Find the smallest element in the unsorted portion of the array.
Swap this smallest element with the first unsorted element.
Move the boundary between the sorted and unsorted portions one element to the right.
Repeat steps 2-4 until the entire array is sorted.

Time Complexity:
Best, Average, and Worst Case: O(n^2)
------------------------------------------------------------------------------
2. Bubble Sort

Bubble Sort is another simple sorting algorithm. It repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process continues until no more swaps are needed, indicating that the list is sorted.

Algorithm:
Traverse the array from the start to the end.
Compare each pair of adjacent elements.
If the elements are in the wrong order, swap them.
After each full pass through the array, the largest unsorted element will be in its correct position.
Repeat the process for the remaining unsorted portion of the array until no more swaps are needed.

Time Complexity:
Best Case: O(n) (when the array is already sorted)
Average and Worst Case: O(n^2)
------------------------------------------------------------------------------
3. Insertion Sort

Insertion Sort builds the final sorted array one item at a time. It picks the next item from the unsorted portion and inserts it into its correct position within the sorted portion. This process is similar to how you might sort playing cards in your hands.

Algorithm:
Start with the second element of the array (since a single element is trivially sorted).
Compare this element with the elements before it.
Shift all elements that are larger than the current element one position to the right.
Insert the current element into its correct position.
Move to the next element and repeat the process until the entire array is sorted.

Time Complexity:
Best Case: O(n) (when the array is already sorted)
Average and Worst Case: O(n^2)
------------------------------------------------------------------------------
4. Merge Sort

Merge Sort is a divide-and-conquer algorithm. It divides the array into smaller sub-arrays, sorts each sub-array, and then merges the sorted sub-arrays to produce the final sorted array. It is known for its efficiency and stability.

Algorithm:
Divide the array into two halves.
Recursively apply Merge Sort to both halves.
Merge the two sorted halves to produce the sorted array.
To merge two halves, compare the elements from each half and build a new array in sorted order.

Time Complexity:
Best, Average, and Worst Case: O(nlogn)
------------------------------------------------------------------------------
5. Quick Sort
Description:
Quick Sort is another divide-and-conquer algorithm. It selects a "pivot" element and partitions the array into elements less than the pivot and elements greater than the pivot. It then recursively sorts the sub-arrays.

Algorithm:
Choose a pivot element from the array.
Partition the array into two sub-arrays: elements less than the pivot and elements greater than the pivot.
Recursively apply Quick Sort to both sub-arrays.
Combine the sub-arrays and pivot to get the sorted array.

Time Complexity:
Best and Average Case: O(nlogn)
Worst Case: O(n^2) (when the pivot choices are poor, such as always picking the smallest or largest element)
------------------------------------------------------------------------------
6. Heap Sort
Description:
Heap Sort uses a binary heap data structure. It builds a max heap (or min heap for descending order) from the input data and then repeatedly extracts the maximum (or minimum) element from the heap and places it into the sorted array.

Algorithm:
Build a max heap from the unsorted array.
Swap the root of the max heap with the last element of the heap.
Reduce the heap size by one.
Heapify the root of the heap to restore the max heap property.
Repeat steps 2-4 until the heap is empty and the array is sorted.

Time Complexity:
Best, Average, and Worst Case:  O(nlogn)
