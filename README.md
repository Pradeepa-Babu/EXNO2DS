# EXNO2DS


NAME: PRADEEPA B

REF NO: 25017224

DATE: 21/02/2026




# AIM:

To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT
    import numpy as np   # Import NumPy library

# Creating 1D array

```
arr1 = np.array([1, 2, 3, 4, 5])

# Creating 2D array
arr2 = np.array([[10, 20, 30], 
                 [40, 50, 60]])

print("1D Array:\n", arr1)
print("\n2D Array:\n", arr2)

```

```
# Create array using arange and reshape
arr3 = np.arange(1, 13).reshape(3, 4)

print("Reshaped Array:\n", arr3)
```

<img width="1229" height="950" alt="Screenshot 2026-02-21 220913" src="https://github.com/user-attachments/assets/0969fb24-fc11-4a6f-a14f-4aeadffabe2e" />

```
# Indexing
print("First Row:", arr3[0])
print("Element at row 2 col 3:", arr3[1,2])

# Slicing
print("First two rows:\n", arr3[0:2])

```

```
print("Mean:", np.mean(arr3))
print("Median:", np.median(arr3))
print("Standard Deviation:", np.std(arr3))
print("Minimum:", np.min(arr3))
print("Maximum:", np.max(arr3))

```
```
print("Sum of rows:", np.sum(arr3, axis=1))
print("Sum of columns:", np.sum(arr3, axis=0))
```
<img width="1027" height="945" alt="Screenshot 2026-02-21 220929" src="https://github.com/user-attachments/assets/f7af5373-8d42-4ef0-b117-7ff7d1bf3df9" />

```
print("Array + 5:\n", arr3 + 5)
print("Array * 2:\n", arr3 * 2)
```
<img width="1367" height="865" alt="Screenshot 2026-02-21 220936" src="https://github.com/user-attachments/assets/ce95e4d0-06d0-4533-92bd-8ce01a28ec17" />



# RESULT


In this task, various NumPy array operations such as array creation, reshaping, indexing, slicing, statistical calculations, axis-based operations, and arithmetic operations were successfully performed.
