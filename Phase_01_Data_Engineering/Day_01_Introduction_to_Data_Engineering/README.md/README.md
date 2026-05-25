# Codeboosters Tech Internship

## Data Engineering + GenAI Internship Program

### Intern Name
Vishal

## Day 1 Topics Covered

- Introduction to Data Engineering
- Types of Data
  - Structured Data
  - Semi-Structured Data
  - Unstructured Data
- Pandas Basics
- DataFrame Operations
- Data Filtering
- GroupBy and Aggregation
- Sorting Data
- Creating New Columns
- Saving Data using CSV
- GitHub Repository Setup

## Tools and Technologies Used

- Python
- Pandas
- Google Colab
- GitHub

---

## Dataset Used

student_performance.csv

---

## Files in This Repository

- README.md
- Day1.ipynb
- student_performance.csv
- output.csv

## Pandas Commands Practiced

```python
import pandas as pd

df.head()
df.tail()
df.shape
df.describe()
df.isnull().sum()

df.groupby('department')['math_score'].mean()

df.sort_values(by='math_score')

df.to_csv('output.csv', index=False)
