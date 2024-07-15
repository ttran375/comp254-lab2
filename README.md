# Week 10 Lab Exercises

## Exercise 1: Comparator Interface

Create a class that describes Employee objects. Declare the following instance variables:

- `private String fullName;`
- `private String socialInsuranceNumber;`
- `private Date hireDate;`

Provide comparison functionalities by implementing the *Comparator* interface. Use the employee’s *hire date* to compare employees. Test your implementation.

## Exercise 2: UnsortedPriorityQueue

Using the *Comparator* implementation from Exercise 1, create an unsorted priority queue. Add several employee objects, list all entries, print the key of the first entry, and print the entry with the minimal value.

All this code should be in the main method of the *UnsortedPriorityQueue.java* class.

## Exercise 3: SortedPriorityQueue

Using the *Comparator* implementation from Exercise 1, create a sorted priority queue. Add several employee objects, list all entries, print the key of the first entry, and print the entry with the minimal value.

All this code should be in the main method of the *SortedPriorityQueue.java* class.

## Exercise 4: Heaps, Bottom-Up Heap Construction

Construct a heap for the following list:

| 23 | 34 | 28 | 51 | 32 | 17 | 25 |
|----|----|----|----|----|----|----|

In this exercise, insert the keys in the given order using breadth-first and then fix it.

Draw all the steps as illustrated in the video example.

## Exercise 5: Heap-Sort

Perform the heap-sort algorithm on the heap from Exercise 4 and print the results. To do this, write the code in the main method of the *HeapPriorityQueue.java* class. Instantiate a `HeapPriorityQueue` object, populate the heap with keys from Exercise 4, then write a loop that uses the `removeMin` method to return the sorted keys.
