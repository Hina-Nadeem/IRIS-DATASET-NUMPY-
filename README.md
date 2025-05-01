# 🌸 Iris Dataset Analysis with NumPy

This repository contains a set of exercises and solutions demonstrating data analysis using **NumPy** on the famous [Iris Dataset]. 

## 📂 Dataset
The dataset used is in CSV format and contains the following columns:
- **SepalLength**
- **SepalWidth**
- **PetalLength**
- **PetalWidth**
- **Class** (species name)

## 🧠 Tasks Covered

### ✅ Task 1: Load the Dataset
- Loaded the CSV using `np.genfromtxt()` or `np.loadtxt()` (skipping the header).
- Extracted numerical feature columns into a separate NumPy array.
- Printed the shape of the final feature array.

### ✅ Task 2: Basic Array Operations
- Computed **mean**, **max**, and **min** for each feature column.
- Calculated **standard deviation** and **variance**.
- Applied **Z-score normalization** on the dataset.

### ✅ Task 3: Indexing and Slicing
- Extracted **Sepal Length** column.
- Retrieved values for the **first 10 flowers**.
- Filtered flowers where **Petal Length > 1.5**.

### ✅ Task 4: Advanced Operations
- Computed the **Euclidean distance** between the first two samples.
- Counted how many flowers have **Sepal Width greater than the mean**.
- Performed **element-wise multiplication** between two feature columns (e.g., SepalLength × PetalLength).

### ✅ Task 5: Array Reshaping and Stacking
- Reshaped the array into **batches of size 30**.
- Horizontally stacked two feature columns.
- Created a **boolean mask** to filter flowers where **Petal Width < 0.5**.

## 🛠️ Tools Used
- Python
- NumPy

## 📁 File Structure
- `iris_analysis.py`: Main script performing all tasks using NumPy.
- `iris.csv`: Dataset file (you can download from [Kaggle](https://www.kaggle.com/datasets/uciml/iris) or UCI).
- `README.md`: This documentation.


