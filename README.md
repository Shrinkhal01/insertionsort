Insertion Sort:

Insertion Sort is a simple sorting algorithm that builds the final sorted array one element at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort. However, it performs well for small datasets or lists that are nearly sorted.

Algorithm Steps:

Start with the second element (assuming the first element is already sorted).
Compare the current element with its adjacent element.
If the current element is smaller, swap it with the previous element, and repeat this process until the current element is in its correct position.
Move on to the next element and repeat steps 2-3 until the entire array is sorted.
Key Characteristics:

Time Complexity: O(n^2) in the worst case.
Space Complexity: O(1) as it doesn't use extra space, it sorts in-place.
Stable Sorting: Yes, it maintains the relative order of equal elements in the sorted output.
