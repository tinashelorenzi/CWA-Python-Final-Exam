## Python Exam Problems

### Problem 1: Roman to Integer Conversion
`problem1.py`

Write a Python function `roman_to_int(roman_str)` that converts a Roman numeral represented as a string `roman_str` to an integer. The input will be a valid Roman numeral containing characters from the set {'I', 'V', 'X', 'L', 'C', 'D', 'M'}. The function should return the corresponding integer value. Here are some examples:

- Input: "III", Output: 3
- Input: "IV", Output: 4
- Input: "IX", Output: 9
- Input: "LVIII", Output: 58
- Input: "MCMXCIV", Output: 1994

### Problem 2: Find Duplicate Element
`problem2.py`

Write a Python function `find_duplicate(nums)` that takes a list of integers `nums` as input and returns the first duplicate element found in the list. If there are no duplicates, return -1. The function should return the duplicate element. Here are some examples:

- Input: [1, 2, 3, 4, 2], Output: 2
- Input: [3, 1, 5, 6, 4], Output: -1
- Input: [1, 2, 3, 4, 5], Output: -1

### Problem 3: Valid Anagram Check
`problem3.py`

Write a Python function `is_valid_anagram(s, t)` that takes two strings `s` and `t` as input and returns True if `t` is an anagram of `s`, and False otherwise. An anagram is a word or phrase formed by rearranging the letters of another, such as "cinema" formed from "iceman". The function should ignore capitalization and consider spaces. Here are some examples:

- Input: s = "anagram", t = "nagaram", Output: True
- Input: s = "rat", t = "car", Output: False
- Input: s = "Listen", t = "Silent", Output: True

### Problem 4: Fibonacci Sequence
`problem4.py`

Write a Python function `fibonacci(n)` that takes an integer `n` as input and returns the first `n` numbers of the Fibonacci sequence. The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones, starting with 0 and 1. For example:

- Input: 5, Output: [0, 1, 1, 2, 3]
- Input: 8, Output: [0, 1, 1, 2, 3, 5, 8, 13]

### Problem 5: Matrix Multiplication
`problem5.py`

Write a Python function `matrix_multiply(A, B)` that takes two lists representing matrices `A` and `B` as input and returns their matrix product if the dimensions are compatible. Each matrix is represented as a list of lists, where each inner list represents a row of the matrix. The function should return the matrix product if the number of columns in `A` is equal to the number of rows in `B`. Otherwise, return None. For example:

- Input: A = [[1, 2], [3, 4]], B = [[5, 6], [7, 8]], Output: [[19, 22], [43, 50]]
- Input: A = [[1, 2, 3], [4, 5, 6]], B = [[7, 8], [9, 10], [11, 12]], Output: None

