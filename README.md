# Predicting Student Math Scores

## Overview
This project aims to evaluate and compare the performance of various regression models in predicting student math scores. The dataset used contains features related to students' demographics, educational background, and scores in other subjects. We implemented and tested several regression algorithms to identify the most effective model for predicting math scores.

## Dataset
The dataset used in this project is `stud.csv`, which includes the following columns:
- `gender`: Gender of the student
- `race_ethnicity`: Ethnic background of the student
- `parental_level_of_education`: Highest education level attained by the student's parents
- `lunch`: Type of lunch the student receives
- `test_preparation_course`: Whether the student completed a test preparation course
- `math_score`: Math score of the student (target variable)
- `reading_score`: Reading score of the student
- `writing_score`: Writing score of the student

## Installation
To run this project, you need to have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- catboost
- xgboost

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn catboost xgboost

