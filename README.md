# Netflix-Data-Analysis-

📊 Netflix Data Analysis Project

This project performs an end-to-end exploratory data analysis (EDA) on a Netflix movies dataset using Python. The goal is to clean, preprocess, analyze, and visualize movie data to extract meaningful insights about genres, popularity, ratings, and release trends.

🔧 Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

🚀 Project Workflow

1️⃣ Data Loading & Inspection

Imported dataset using Pandas

Explored structure using .head(), .info(), .describe()

Checked for duplicates and null values


2️⃣ Data Cleaning & Preprocessing

Converted Release_Date to datetime format

Cleaned and converted numerical columns (e.g., Vote_Count)

Dropped unnecessary columns such as:

Overview

Original_Language

Poster_Url

Handled invalid or missing values


3️⃣ Feature Engineering

Categorized Vote_Average into meaningful groups:

Not_popular

Below_average

Average

Popular

Split multi-genre entries into individual rows using list transformation and dataframe explosion


4️⃣ Exploratory Data Analysis (EDA)

Analyzed:

Genre distribution

Rating distribution

Popularity trends

Most popular movies

Year-wise release patterns


5️⃣ Data Visualization

Count plots for genres and vote categories

Histogram for release year distribution

Styled visualizations using Seaborn


📈 Key Insights

Identified the most common genres on Netflix

Observed how ratings are distributed across movies

Found the most popular movie based on popularity score

Analyzed trends in movie releases over time


🎯 Purpose of the Project

This project demonstrates:

Practical data cleaning skills

Feature engineering

Exploratory data analysis techniques

Data visualization best practices

Real-world dataset handling
