%%writefile README.md
# Technical Support Data Analysis

## Overview
This project analyses technical support data to uncover patterns in problem types, resolution times, and warranty claims using Machine Learning.

## Dataset
The dataset contains the following features:

| Column | Description |
|---|---|
| PROBLEM_TYPE | Category of technical issue reported |
| no_of_cases | Number of cases per problem type |
| Avg_pending_calls | Average number of pending calls |
| Avg_resol_time | Average time taken to resolve an issue |
| recurrence_freq | How often the problem recurs |
| Replace_percent | Percentage of cases requiring replacement |
| In_warranty_percent | Percentage of cases within warranty |
| Post_warranty_percent | Percentage of cases after warranty expiry |

## Goal
- Identify the most common and recurring technical problems
- Understand resolution time patterns across problem types
- Analyse warranty vs post-warranty issue distribution

## Tools Used
- Python
- Jupyter Notebook
- K-means
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
