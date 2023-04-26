
# Insertion Sort
Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.

![image](https://user-images.githubusercontent.com/125336949/234468073-4acdec40-a3d1-4df6-87fe-284cb1ee6c62.png)

Characteristics of Insertion Sort:

- This algorithm is one of the simplest algorithm with simple implementation
- Basically, Insertion sort is efficient for small data values
- Insertion sort is adaptive in nature, i.e. it is appropriate for data sets which are already partially sorted.

# Complexity Analysis of Insertion Sort:

Time Complexity of Insertion Sort

- The worst case time complexity of Insertion sort is O(N^2)
- The average case time complexity of Insertion sort is O(N^2)
- The time complexity of the best case is O(N).

Space Complexity of Insertion Sort

The auxiliary space complexity of Insertion Sort’s Recursive Approach is O(n) due to the recursion stack.

# Binary Search
Binary Search is defined as a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log N). 

# How to Implement Binary Search?

The basic steps to perform Binary Search are:

- Set the low index to the first element of the array and the high index to the last element.
- Set the middle index to the average of the low and high indices.
- If the element at the middle index is the target element, return the middle index.
- Otherwise, based on the value of the key to be found and the value of the middle element, decide the next search space.
- If the target is less than the element at the middle index, set the high index to middle index – 1.
- If the target is greater than the element at the middle index, set the low index to middle index + 1.
- Perform step 2 repeatedly until the target element is found or the search space is exhausted.

![image](https://user-images.githubusercontent.com/125336949/234405666-cccc850a-42d7-4f81-acda-fb721f6e1704.png)

