# Python List Operations

This script demonstrates basic list operations in Python.

## Script Overview

The script performs the following operations:
1. Creates an empty list
2. Appends elements (10, 20, 30, 40)
3. Inserts value 15 at the second position
4. Extends the list with [50, 60, 70]
5. Removes the last element
6. Sorts the list in ascending order
7. Finds and prints the index of value 30

## Code

```python
# Create an empty list called my_list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert value at second position
my_list.insert(1, 15)

# Extend with another list
my_list.extend([50, 60, 70])

# Remove last element
my_list.pop()

# Sort the list
my_list.sort()

# Find and print index of 30
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)

# Print final list
print("Final list:", my_list)