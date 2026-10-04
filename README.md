# Student Performance Analytics System

A NumPy-based data analysis project that analyzes student performance using data stored in a CSV file.

## Project Overview

The Student Performance Analytics System analyzes student marks across multiple subjects and provides useful insights such as subject-wise averages, student averages, pass percentage, student consistency, and overall ranking.

The project demonstrates how NumPy can be used for practical data analysis.

## Objectives

- Analyze student performance using NumPy.
- Calculate subject-wise average, highest, and lowest marks.
- Calculate individual student averages.
- Identify the top-performing student.
- Identify students who failed.
- Calculate the overall pass percentage.
- Identify the hardest subject based on average marks.
- Analyze student consistency using standard deviation.
- Rank students based on their average marks.

## Dataset

The dataset contains the following columns:

| Column | Description |
|---|---|
| Student_ID | Unique identifier for each student |
| Maths | Marks obtained in Maths |
| Physics | Marks obtained in Physics |
| English | Marks obtained in English |
| Computer_Science | Marks obtained in Computer Science |

All subjects are scored out of 100.

## Technologies Used

- Python
- NumPy
- CSV
- Google Colab

## NumPy Concepts Used

- NumPy arrays
- Array indexing
- Array slicing
- `shape`
- `size`
- `dtype`
- `mean()`
- `max()`
- `min()`
- `std()`
- `argmax()`
- `argmin()`
- `argsort()`
- Boolean masking
- `axis`
- `np.loadtxt()`

## Analysis Performed

### 1. Dataset Analysis

Determined the number of students, number of subjects, total values, data type, and selected student and subject marks.

### 2. Subject Analysis

Calculated the average, highest mark, and lowest mark for every subject.

### 3. Student Analysis

Calculated the average marks of every student and identified the top-performing student.

### 4. Pass/Fail Analysis

Used a pass mark of 70 to identify passed and failed students and calculated the overall pass percentage.

### 5. Subject Difficulty

Identified the hardest subject based on the lowest subject average.

### 6. Student Consistency

Used standard deviation to measure how consistently each student performed across subjects.

### 7. Student Ranking

Ranked students from highest to lowest based on their average marks.

## Results

| Metric | Result |
|---|---|
| Total Students | 5 |
| Total Subjects | 4 |
| Top Student | Student 103 |
| Top Student Average | 93.25 |
| Students Passed | 4 |
| Students Failed | 1 |
| Pass Percentage | 80% |
| Hardest Subject | Maths |
| Hardest Subject Average | 75.00 |

## Project Structure

```text
student-performance-analytics/
│
├── Student_Performance_Analytics.ipynb
├── students.csv
└── README.md
