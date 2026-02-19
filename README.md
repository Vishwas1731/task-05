# task-05

Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to extract meaningful insights using statistical methods and data visualization. The goal is to understand patterns, relationships, and trends that influenced passenger survival.

🎯 Objectives

Analyze the structure and quality of the dataset

Identify missing values and data types

Explore distributions of key features

Visualize relationships between variables

Summarize important factors affecting survival

🛠 Tools & Technologies

Python

Pandas

Matplotlib

Seaborn

📂 Dataset

Source: Titanic Dataset

Rows: 891

Columns: 12

Key features include:

Survived

Pclass

Sex

Age

Fare

Embarked

🔍 Methods Used
1. Statistical Exploration

.info() – dataset structure and missing values

.describe() – statistical summary

.value_counts() – frequency distribution

2. Visualizations

Histograms (Age, Fare)

Boxplots (Fare vs Survival)

Scatterplots (Age vs Fare)

Pairplot (feature relationships)

Heatmap (correlation matrix)

📊 Key Observations

Most passengers were between 20–40 years old.

Fare distribution is highly right-skewed with a few extreme outliers.

Survivors had a higher median fare than non-survivors.

First-class passengers showed much higher survival rates than third-class passengers.

Female passengers survived at a much higher rate than male passengers.

Age showed a weak relationship with survival compared to class and fare.

🔗 Relationships & Trends

Pclass vs Survival: Strong negative correlation

Fare vs Survival: Positive correlation

Age vs Survival: Weak correlation

Survivors cluster more in high-fare and first-class groups

Socioeconomic factors strongly influenced survival

🧠 Summary of Findings

Passenger class and fare are the most important predictors of survival.

Gender plays a significant role in survival outcomes.

Age has a smaller impact compared to class and fare.

Visual analysis confirms statistical trends found in the data.
