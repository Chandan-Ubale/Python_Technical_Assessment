# Python Technical Assessment

This repository contains solutions to a Python technical assessment implemented in a Jupyter Notebook (`PythonTechnicalAssessment-1.ipynb`).
The notebook demonstrates core Python programming concepts, data manipulation techniques, and the use of NumPy and pandas.

---

## Tasks Implemented

1. **Palindrome Checker**

   * Implements a function to check whether a given string is a palindrome.
   * Utilizes string manipulation and slicing techniques.
   * Accepts user input and outputs whether the string is a palindrome.

2. **List Comprehension for Squares**

   * Defines a function to generate a list of squares from a given list of numbers.
   * Demonstrates the use of Python list comprehensions.
   * Accepts user input as space-separated integers.

3. **Students DataFrame**

   * Creates a pandas DataFrame containing the names and marks of five students.
   * Filters and displays students who scored more than 80 marks.

4. **Random 5×5 Matrix**

   * Generates a 5×5 NumPy array containing random integers between 1 and 100.
   * Demonstrates NumPy’s random number generation capabilities.

5. **Products DataFrame with Discounts**

   * Creates a DataFrame with columns: *Product Name, Price, Category*.
   * Adds a new column, *Discounted Price*, which is set to 90% of the original price (equivalent to a 10% discount).
   * Filters and displays products priced below 500 after the discount.

---

## Requirements

* Python 3.8 or later
* Jupyter Notebook
* Libraries:

  * pandas
  * numpy

Install the dependencies with:

```bash
pip install pandas numpy jupyter
```

---

## How to Run

1. Clone or download this repository.
2. Launch Jupyter Notebook with the command:

   ```bash
   jupyter notebook
   ```
3. Open the file `PythonTechnicalAssessment-1.ipynb`.
4. Execute the cells sequentially to reproduce the results.

---

## Learning Outcomes

* Practical implementation of string manipulation and palindrome checking.
* Efficient use of list comprehensions in Python.
* DataFrame creation, filtering, and manipulation using pandas.
* Random number generation with NumPy.
* Adding computed columns to DataFrames and applying conditional filters.
