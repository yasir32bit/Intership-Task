
# Task 01: Exploratory Data Analysis and Visualization of the Iris Dataset

## Objective

The purpose of this task is to perform exploratory data analysis (EDA) on a structured dataset to understand its characteristics, distributions, and relationships between features. This task focuses on developing foundational skills in data inspection, statistical analysis, and data visualization using Python.

---

## Dataset

* **Dataset Name:** Iris Dataset
* **Source:** Seaborn library (built-in dataset)
* **Description:**
  The Iris dataset is a well-known multivariate dataset consisting of measurements from iris flowers belonging to three different species: *Setosa*, *Versicolor*, and *Virginica*.

### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width
* Species (target label)

---

## Tools and Technologies

* **Programming Language:** Python
* **Libraries Used:**

  * Pandas – data loading and manipulation
  * NumPy – numerical operations
  * Matplotlib – data visualization
  * Seaborn – statistical data visualization

---

## Methodology

### 1. Data Loading

* The dataset was loaded using Seaborn and converted into a Pandas DataFrame.

### 2. Data Inspection

* Displayed initial rows using `.head()`
* Checked dataset dimensions and column names
* Verified missing values
* Analyzed data types and structure using `.info()`
* Generated summary statistics using `.describe()`

### 3. Exploratory Data Analysis

* Scatter plots were used to analyze relationships between numerical features.
* Histograms were created to understand feature distributions.
* Box plots were utilized to detect potential outliers.

---

## Key Findings

* The dataset contains **150 observations and 5 attributes**.
* No missing or null values were present.
* Petal-related features show strong differentiation between species.
* Sepal features display overlapping distributions among classes.

---

## Results and Insights

This exploratory analysis provided valuable insights into the structure and characteristics of the Iris dataset. Visualization techniques effectively revealed relationships and patterns, confirming that petal dimensions are highly informative features for classification tasks.

---