# PLP-Python-WK-2
#Week Two Assignment: Python List Operations
Overview
This project demonstrates basic list operations in Python as part of a programming assignment. It covers creating, modifying, and manipulating a list through appending, inserting, extending, removing, sorting, and indexing elements. The code is designed to be simple, readable, and educational, aligning with fundamental concepts in data structures for beginners in computer science or software engineering.


#Python 3.x (tested on Python 3.12.3)
No external libraries required; uses built-in list methods only.

%Installation
No installation needed. Simply run the script in a Python environment.
Usage

#Save the code to a file, e.g., week_two_assignment.py.
Execute the script using:
python week_two_assignment.py

The script will perform all operations and print the index of the value 30 as the final output.

Expected output: 3 (the index of 30 after all operations).
Code Explanation
The script performs the following steps:

Create an empty list: Initializes my_list = [].
Append elements: Adds 10, 20, 30, 40 using append(). Result: [10, 20, 30, 40].
Insert value: Inserts 15 at index 1 using insert(). Result: [10, 15, 20, 30, 40].
Extend with another list: Adds [50, 60, 70] using extend(). Result: [10, 15, 20, 30, 40, 50, 60, 70].
Remove last element: Uses pop() to remove 70. Result: [10, 15, 20, 30, 40, 50, 60].
Sort in ascending order: Calls sort(). Result: [10, 15, 20, 30, 40, 50, 60].
Find and print index: Uses index(30) to find position (3) and prints it.
