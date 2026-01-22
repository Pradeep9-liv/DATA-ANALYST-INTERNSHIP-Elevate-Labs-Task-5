# DATA-ANALYST-INTERNSHIP-Elevate-Labs-Task-5

# Student Performance Dataset – Data Cleaning & Feature Engineering

## Data Dictionary

| Column Name | Description |
|------------|-------------|
| school | School attended by the student (GP: Gabriel Pereira, MS: Mousinho da Silveira) |
| sex | Student's gender (F: Female, M: Male) |
| age | Student's age (in years) |
| address | Home address type (U: Urban, R: Rural) |
| famsize | Family size (LE3: ≤3 members, GT3: >3 members) |
| Pstatus | Parent's cohabitation status (T: Living together, A: Apart) |
| Medu | Mother's education level (0–4) |
| Fedu | Father's education level (0–4) |
| Mjob | Mother's job |
| Fjob | Father's job |
| reason | Reason for choosing the school |
| guardian | Student's guardian |
| traveltime | Home to school travel time |
| studytime | Weekly study time |
| failures | Number of past class failures |
| schoolsup | Extra educational support (yes/no) |
| famsup | Family educational support (yes/no) |
| paid | Extra paid classes (yes/no) |
| activities | Extra-curricular activities (yes/no) |
| nursery | Attended nursery school (yes/no) |
| higher | Wants to take higher education (yes/no) |
| internet | Internet access at home (yes/no) |
| romantic | In a romantic relationship (yes/no) |
| famrel | Quality of family relationships (1–5) |
| freetime | Free time after school (1–5) |
| goout | Going out with friends (1–5) |
| Dalc | Workday alcohol consumption (1–5) |
| Walc | Weekend alcohol consumption (1–5) |
| health | Current health status (1–5) |
| absences | Number of school absences |
| G1 | First period grade (0–20) |
| G2 | Second period grade (0–20) |
| G3 | Final grade (0–20) |
| avg_grade | Average grade calculated from G1, G2, and G3 |
| performance_level | Performance category based on average grade (High / Medium / Low) |
| pass_status | Pass or Fail status derived from average grade |


## Overview
This project focuses on cleaning, preparing, and transforming the Student Performance (Portugal) dataset for analysis and modeling. The dataset contains demographic, social, and academic information of students, including grades across multiple evaluation periods.

## Dataset Source
- Student Performance Dataset (Portugal)
- Source: UCI Machine Learning Repository / Kaggle

## Objectives
- Load and explore the dataset in a reproducible environment
- Identify and handle missing values and duplicate records
- Optimize data types for analysis
- Perform feature engineering to enhance analytical value
- Export a cleaned dataset for reuse

## Data Cleaning Steps
1. Loaded the dataset into Google Colab using pandas.
2. Explored data structure using `.head()` and `.info()`.
3. Checked for missing values and confirmed data completeness.
4. Verified absence of duplicate records.
5. Converted categorical object columns to `category` datatype.
6. Created new features such as average grade, performance level, and pass/fail status.
7. Exported the cleaned dataset to CSV format.

## Feature Engineering
- **avg_grade**: Average of G1, G2, and G3 grades.
- **performance_level**: Categorized as High, Medium, or Low based on average grade.
- **pass_status**: Derived using average grade to represent overall academic performance.

## Output
- `student-por-cleaned.csv` – Cleaned and transformed dataset ready for analysis or modeling.
