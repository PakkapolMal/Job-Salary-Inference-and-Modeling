# DES432: Job Salary Inference & Modeling

## Project Overview
This repository contains a comprehensive statistical analysis of global technology compensation to identify the key drivers of salary using Python. Utilizing a dataset of 250,000 job records, this study applies exploratory data analysis (EDA), hypothesis testing, and Multiple Linear Regression (MLR) to evaluate the impact of experience, education, company size, and specific technical disciplines on earning potential. 

This project fulfills the requirements for **Project 2: Statistical Modeling & Interpretation** in DES432 (Statistics and Data Modeling) at the Sirindhorn International Institute of Technology (SIIT).

## Repository Structure
To ensure full reproducibility, the project is structured as follows:

DES432-Job-Salary-Inference-Modeling/
│
├── data/
│   └── job_salary_prediction_dataset.csv   # Raw Kaggle dataset (250k records)
│
├── notebooks/
│   └── main.ipynb                          # Complete EDA, Inference, and Modeling workflow
│
├── outputs/                                # Saved visualization plots
│   ├── con-univariate.png
│   ├── salary-experience.png
│   ├── salary-education.png
│   ├── salary-company-size.png
│   ├── salary-by-jobs.png
│   ├── MLR-prediction.png
│   └── residual-analysis.jpg
