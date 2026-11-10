
# Student Performance Data Analysis

## Project Overview

This project explores student academic performance using Python. The dataset contains students' math, reading, and writing scores, along with information about their gender, race/ethnicity group, parental education level, lunch type, and test preparation course status.

The goal of this project is to identify patterns in student performance, compare academic scores across subjects, and explore how different student characteristics relate to academic outcomes.

## Project Objectives

- Explore and understand the structure of the dataset.
- Analyze math, reading, and writing scores using descriptive statistics.
- Visualize score distributions using histograms, bar charts, box plots, and scatter plots.
- Examine correlations between academic subjects.
- Identify students with the highest overall averages.
- Classify math performance into different score categories.
- Compare test preparation course completion across genders.
- Explore student distributions across race/ethnicity groups.
- Examine relationships between parental education, test preparation, and lunch type.

## Technologies and Libraries

- Python – Programming language used for data analysis.
- Pandas – Data manipulation and analysis.
- NumPy – Numerical calculations.
- Matplotlib – Data visualization.
- Jupyter Notebook – Environment used to develop and document the analysis.

## Dataset

This project uses the **Students Performance in Exams** dataset from Kaggle.

**Dataset Source:** [Student Performance in Exams – Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

The dataset contains 1,000 student records and the following information:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

### Downloading the Dataset

To run this project on your computer:

1. Visit the [Kaggle dataset page](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).
2. Download the dataset as a ZIP file.
3. Extract the downloaded ZIP file.
4. Locate the CSV file named `StudentsPerformance.csv`.
5. Place the CSV file in the same folder as the Jupyter Notebook.

Dataset filename: `StudentsPerformance.csv`

The notebook loads the dataset using:

```python
import pandas as pd

df = pd.read_csv("StudentsPerformance.csv")
```

## Analysis Performed

### 1. Data Exploration

- Examined dataset dimensions and column names.
- Checked data types and missing values.
- Checked for duplicate records.

### 2. Academic Performance Analysis

- Calculated average, median, minimum, and maximum scores.
- Examined score distributions across subjects.
- Compared score variation using standard deviation.
- Identified students with the highest overall averages.
- Created math performance categories.

### 3. Relationships Between Subjects

- Used scatter plots to examine relationships between academic subjects.
- Calculated correlation coefficients.
- Compared score distributions using box plots.

### 4. Student Characteristics

- Examined test preparation completion by gender.
- Explored race/ethnicity group distributions.
- Compared average academic scores across parental education levels.
- Examined test preparation and lunch type across parental education groups.

## Repository Contents

| File | Description |
|---|---|
| `Student_Performance_Data_Analysis.ipynb` | Jupyter Notebook containing the complete analysis, code, and visualizations. |
| `StudentsPerformance.csv` | Dataset used for the analysis. |

## Key Learning Outcomes

Through this project, I gained practical experience with:

- Exploring and understanding datasets using Pandas.
- Performing numerical calculations with NumPy.
- Creating data visualizations using Matplotlib.
- Filtering, grouping, and comparing data.
- Calculating descriptive statistics and correlations.
- Identifying patterns and interpreting analytical results.
- Presenting data analysis in a Jupyter Notebook.

## Future Improvements

- Explore additional statistical techniques.
- Investigate more relationships between student characteristics and academic performance.
- Develop more detailed visualizations.
- Expand the analysis using additional datasets.

---

Author: Zarin Sadaf Khan

Project Type: Beginner Data Analysis Project

Field: Data Science
