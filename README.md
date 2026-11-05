# Netflix Titles – Data Exploration & Analysis Using Pandas

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This repository contains my hands-on Pandas assignment, completed as part of the **45-Day Python with AI & Data Analytics Program at CodroidHub**.

The objective of this assignment was to explore, understand, and analyze the Netflix Movies and TV Shows dataset using Python and the Pandas library.

Through this assignment, I practiced essential data exploration techniques, understood dataset structures, examined data types, performed statistical analysis, and explored basic memory optimization techniques.

## 🎯 Objectives

- Understand how to load CSV datasets using Pandas.
- Explore rows and columns of a dataset.
- Identify data types and dataset structure.
- Generate descriptive statistical summaries.
- Analyze categorical data.
- Understand missing values.
- Practice basic data handling and memory optimization.

## 📂 Dataset Information

**Dataset:** Netflix Movies and TV Shows

| Attribute | Details |
|---|---|
| Total Records | 8,807 |
| Total Columns | 12 |
| Numeric Columns | 1 |
| Object Columns | 11 |
| File Format | CSV |
| Dataset File | `netflix_titles.csv` |

## 🛠️ Technologies Used

- **Python** – Programming language.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical computing.
- **Jupyter Notebook** – Interactive coding environment.
- **Anaconda** – Python development environment.

## 📚 Concepts & Pandas Methods Practiced

### 1. Importing Libraries and Loading Data

Used Pandas to import the dataset from a CSV file.

```python
import pandas as pd

df = pd.read_csv("netflix_titles.csv")
```

### 2. Exploring Dataset Records

Practiced methods to view and understand dataset records.

```python
df.head()
df.tail()
df.sample()
```

- `head()` – Displays the first five rows.
- `tail()` – Displays the last five rows.
- `sample()` – Displays random records.

### 3. Understanding Dataset Structure

Used DataFrame attributes and methods to understand the dataset.

```python
df.shape
df.columns
df.index
df.dtypes
df.info()
```

- `shape` – Returns the number of rows and columns.
- `columns` – Displays column names.
- `index` – Displays row index information.
- `dtypes` – Identifies data types of columns.
- `info()` – Provides a summary of the DataFrame.

### 4. Statistical Analysis

Practiced descriptive statistics and numerical analysis.

```python
df.describe()
df.min()
df.median()
```

- `describe()` – Generates descriptive statistical information.
- `min()` – Returns minimum values.
- `median()` – Calculates median values.

### 5. Categorical Data Analysis

Explored categorical columns and frequency distributions.

```python
df["type"].value_counts()
df["type"].idxmax()
```

- `value_counts()` – Counts occurrences of unique values.
- `idxmax()` – Returns the index label of the maximum value.

### 6. Data Handling and Memory Optimization

Practiced copying DataFrames and examining memory consumption.

```python
df_copy = df.copy()

df.memory_usage(deep=True)
```

Also explored converting suitable columns into categorical data types:

```python
df["type"] = df["type"].astype("category")
```

This technique can reduce memory consumption when a column contains a limited number of repeated values.

## 🔍 Key Learning Outcomes

Through this assignment, I improved my understanding of:

1. Loading and exploring real-world datasets.
2. Working with Pandas DataFrames.
3. Understanding rows, columns, and data types.
4. Performing basic statistical analysis.
5. Analyzing categorical information.
6. Understanding memory usage and data type optimization.
7. Executing and documenting Python code in Jupyter Notebook.

## 📁 Repository Structure

```text
ASSIGENMENT-/
│
├── Gurjar assigenment 1.ipynb
├── netflix_titles.csv
└── README.md
```

*Note: The file structure above represents the expected project organization. Adjust filenames if your repository uses different names.*

## ⚙️ How to Run This Project

**Step 1:** Clone the repository.

```bash
git clone https://github.com/gurjaraman9143-creator/ASSIGENMENT-.git
```

**Step 2:** Navigate to the project directory.

```bash
cd ASSIGENMENT-
```

**Step 3:** Install the required libraries.

```bash
pip install pandas numpy jupyter
```

**Step 4:** Launch Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open `Gurjar assigenment 1.ipynb` and execute the cells.

Make sure `netflix_titles.csv` is available in the correct directory.

## 🎓 Learning Program

**Program:** 45-Day Python with AI & Data Analytics

**Organization:** CodroidHub

**Assignment:** Pandas – Netflix Dataset Exploration

## 👨‍💻 Author

**Aman Gurjar**

BCA Student | Python & Data Analytics Learner

GitHub: [@gurjaraman9143-creator](https://github.com/gurjaraman9143-creator)

---

⭐ If you find this repository useful, feel free to explore the notebook and follow my learning journey.

**Learning by Doing | Building Skills Through Practical Projects 🚀**
