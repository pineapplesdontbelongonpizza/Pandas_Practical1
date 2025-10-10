# Pandas_Practical1
Pandas practical exercises covering Series, DataFrames, data import, statistical analysis, and outlier detection.


## Contents  
- Creating **Series** and **DataFrames**  
- Importing datasets from **CSV, Excel, and SQL**  
- Performing **statistical calculations** (mean, standard deviation, etc.)  
- Handling **missing values**  
- Detecting **outliers using z-scores**  
- Tabular data operations (filtering, indexing, slicing)  

## Tools Used  
- **Python 3.x**  
- **Pandas**  
- **Jupyter Notebook**  

## Purpose  
This repository contains my **Pandas practical exercises**, where I have implemented data handling, cleaning, and analysis using the Pandas library in Python.  This practical is part of my coursework, aimed at learning **data analysis techniques** with Pandas for real-world applications.  


# Pandas_Practica2
Teaching Ratings Dataset — Exploratory Data Analysis and Basic Visualization

Objective:
To perform exploratory data analysis (EDA) on the Teaching Ratings dataset using Python and visualize relationships between teaching evaluation scores and other instructor attributes.

Tools & Libraries Used:
Python (Jupyter Notebook / Anaconda)
pandas
numpy
matplotlib
seaborn

Dataset Description:
File: teacher_ratings.csv
Contains 100 observations and 6 attributes:
age, gender, beauty, eval, tenure, and students

Experiment Steps:
Import dataset
Load the CSV file using pandas.
Display the first few rows and basic information.
Summarize data
Calculate mean, median, minimum, and maximum for the students column.
Data Visualization
Plot histograms and bar charts to explore the distribution of key variables.
Examine how beauty, tenure, and gender affect evaluation scores.

Results & Observations:
The dataset shows variation in student enrollments across instructors.
Visualization suggests minor trends between beauty scores and teaching evaluations.
No strong bias based on gender or tenure was observed.

Conclusion:
Practical 2 successfully demonstrated the use of pandas for data summarization and matplotlib/seaborn for visualization.
You gained hands-on experience in handling datasets and exploring trends visually.



# Pandas_Practical3
Analyzing Teaching Evaluations — Duplicate Handling and Relational Insights

Objective:
To identify duplicate entries, compute key statistics, and visualize complex relationships between instructor characteristics and evaluation scores.

Tools & Libraries Used:
Python (Jupyter Notebook / Anaconda)
pandas
numpy
matplotlib
seaborn

Dataset Description:
File: teacher_ratings_updated.csv
Contains 100 observations and 7 attributes:
prof, age, gender, beauty, eval, tenure, and students
(prof column added to identify duplicate professors)

Experiment Steps:
Duplicate Identification
Use duplicated() to find repeated professor names.
Compute mean and standard deviation for age before and after removing duplicates.
Course Division Analysis
Compare average evaluation scores between lower- and upper-division courses.
Scatter Plots
Visualize the relationship between age and evaluation scores.
Differentiate plots by gender and tenure for multi-variable insights.

Results & Observations:
Some professors appeared multiple times, showing duplicate entries in the dataset.
The mean and standard deviation of age slightly changed after filtering unique professors.
Evaluation scores were mostly consistent across ages, genders, and tenure statuses.

Conclusion:
Practical 3 helped in understanding data cleaning (duplicate handling) and multi-variable visualization.
It reinforced how to interpret relationships between instructor characteristics and evaluation outcomes using scatter plots and grouping techniques.
