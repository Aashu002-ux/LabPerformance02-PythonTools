# LabPerformance02-PythonTools

1.List: Given a list of numbers, remove duplicates and sort in ascending order.
code:
numbers = [4, 2, 7, 2, 5, 7, 9, 1]
unique_sorted_numbers = sorted(set(numbers))
print("Unique Sorted Numbers:", unique_sorted_numbers)

  note: Removes duplicate numbers from a list and sorts them in ascending order.

2.Set: Find the common elements between two lists using sets.
code:
list1 = {1, 2, 3, 4, 5}
list2 = {3, 4, 5, 6, 7}
common_elements = list1.intersection(list2)
print("Common Elements:", common_elements)

 note: Finds the common elements between two lists using sets.

3.Tuple: Create a tuple of student records (name, age, grade) and sort by grade.
code:
students = [("Ashu", 20, 85), ("Osairis", 22, 78), ("UFO", 21, 92)]
sorted_students = sorted(students, key=lambda x: x[2])
print("Sorted Students by Grade:", sorted_students)

 note: Stores student records in tuples and sorts them based on grades.

4.Dictionary: Count word occurrences in a given text and store them in a dictionary.
code:
text = "apple banana apple orange banana apple"
words = text.split()
word_count = {word: words.count(word) for word in set(words)}
print("Word Count:", word_count)

 note:Counts occurrences of each word in a given text and stores them in a dictionary.

5.NumPy#1: Generate a 5x5 matrix of random integers and compute row-wise sums.
code:
import numpy as np
matrix = np.random.randint(1, 100, (5, 5))
row_sums = matrix.sum(axis=1)
print("Random Matrix:\n", matrix)
print("Row-wise Sums:", row_sums)
 note: Creates a 5×5 matrix of random integers and computes row-wise sums.


