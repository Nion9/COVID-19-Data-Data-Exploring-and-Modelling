COVID-19 Data Analysis Project
This repository contains a comprehensive R-based analysis of COVID-19 data, covering data wrangling, exploratory analysis, predictive modeling, and dashboard design. Developed by Minhajul Islam Nion, a final-year Bachelor of Information Technology student at the University of Canberra, this project showcases skills in data analysis, visualization, and statistical modeling—key competencies for data analyst roles.
Overview
The project is divided into four tasks:

Task 1: Data preparation and wrangling, including merging datasets (Countries.csv, Covid19.csv, Recovered.csv, Tests.csv) and adding variables like cumulative cases, active cases, and per-million rates.
Task 2: Exploratory data analysis, including global death toll trends, visualizations of cases/deaths/recoveries, and rankings of countries by metrics.
Task 3: Data-driven modeling, featuring linear regression, Ridge/Lasso regression, and decision trees to predict cumulative cases, with performance comparisons.
Task 4: Insights and dashboard design, proposing an expanded dataset and a user-friendly dashboard to highlight pandemic trends and impacts.

Files

Task1.R: Script for data preparation and wrangling (Task 1).
Task2.R: Script for exploratory data analysis (Task 2).
Task3.R: Script for predictive modeling (Task 3).
Task4.R: Script for dashboard design report and insights (Task 4).
Countries.csv, Covid19.csv, Recovered.csv, Tests.csv: Input datasets (required for execution).
dashboard.png: Visual representation of the proposed COVID-19 dashboard (included in the zip folder).

Setup Instructions

Install R and RStudio:

Download and install R (https://cran.r-project.org/) and RStudio (https://posit.co/downloads/).


Install Required Packages:Run the following in R to install dependencies:
install.packages(c("tidyverse", "lubridate", "ggplot2", "dplyr", "corrplot", "caret", "glmnet", "rpart", "Metrics"))


Download Datasets:

Place Countries.csv, Covid19.csv, Recovered.csv, and Tests.csv in the project directory. These can be sourced from public health repositories (e.g., WHO, Johns Hopkins) if not provided.


Run the Scripts:

Open each .R file in RStudio and run the code sequentially. Ensure the working directory is set to the project folder:setwd("path/to/your/project")





Usage

Task 1: Execute Task1.R to load, merge, and wrangle the data into a master dataframe with new variables (e.g., CumCases, Active, FatalityRate).
Task 2: Run Task2.R to perform exploratory analysis, generating plots (e.g., global cumulative trends, top 10 country comparisons).
Task 3: Use Task3.R to train and compare regression models (linear, Ridge, Lasso, decision tree) for predicting cumulative cases.
Task 4: Review Task4.R for the dashboard design report, including proposed expansions and visualizations (see dashboard.png).

Output

Plots: Saved as PNG files (e.g., covid_cases_line.png, covid_cases_bar.png) in the working directory.
Tables: Model performance comparisons (e.g., RMSE, R-squared) printed in the console or R Markdown output.
Dashboard: A conceptual design in dashboard.png, detailing global trends, regional impacts, and healthcare strain.

Contributing
Feel free to fork this repository, suggest improvements, or add datasets for further analysis. Contact Minhajul Islam Nion at minhajul.nion@example.com for collaboration.
License
This project is for educational purposes and can be used under the MIT License. See LICENSE file for details (to be added if desired).
Acknowledgements

Data sourced from hypothetical CSV files, inspired by public health datasets (e.g., WHO, Johns Hopkins).
Guided by University of Canberra coursework in Data Science and Pattern Recognition.
