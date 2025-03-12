# PRACTICENP_PD
IT CONSISTS OF THE PRACTICE QUESTIONS FOR NUMPY AND PANDAS
NumPy (Numerical Python)
NumPy is a powerful library for numerical computing in Python. It provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these data structures efficiently.

🔹 Key Features of NumPy:

ndarray (N-dimensional array): Core data structure for handling numerical data.
Vectorized Operations: Faster computations compared to traditional Python loops.
Broadcasting: Allows operations on arrays of different shapes without explicit loops.
Mathematical & Statistical Functions: Includes functions for linear algebra, Fourier transforms, random number generation, and more.
Integration with Other Libraries: Works well with Pandas, Matplotlib, and SciPy.
🔹 Example Usage:

python
Copy
Edit
import numpy as np

# Creating an array
arr = np.array([1, 2, 3, 4, 5])

# Performing operations
print(arr * 2)  # Output: [ 2  4  6  8 10]
Pandas
Pandas is a high-level data manipulation and analysis library built on top of NumPy. It provides flexible data structures like Series and DataFrame to handle structured data efficiently.

🔹 Key Features of Pandas:

DataFrame & Series: Intuitive data structures similar to tables in SQL or Excel.
Data Cleaning: Handling missing values, filtering, and transforming data.
Data Aggregation & Grouping: groupby(), agg(), and pivot tables.
Powerful Indexing: Supports multi-level indexing for complex data operations.
Integration with Other Libraries: Works well with Matplotlib, Seaborn, and Scikit-learn.
🔹 Example Usage:

python
Copy
Edit
import pandas as pd

# Creating a DataFrame
data = {'Name': ['Alice', 'Bob', 'Charlie'], 'Age': [25, 30, 35]}
df = pd.DataFrame(data)

# Accessing data
print(df.head())  # Shows the first few rows
Key Differences:
Feature	NumPy	Pandas
Data Type	Homogeneous (same type)	Heterogeneous (multiple types)
Structure	Arrays, Matrices	DataFrames, Series
Operations	Fast mathematical computations	Data manipulation & analysis
Use Case	Numerical computing, linear algebra	Data wrangling, analysis, and visualization
Which One to Use?
Use NumPy when working with numerical data, performing mathematical operations, or needing performance optimization.
Use Pandas when handling structured/tabular data, performing data analysis, or working with real-world datasets (e.g., CSV files).
