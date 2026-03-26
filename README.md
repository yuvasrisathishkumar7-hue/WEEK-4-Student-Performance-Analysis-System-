Student Performance Analysis System (Synthetic Data)
Project Overview

The Student Performance Analysis System is a data analytics project designed to simulate and analyze academic performance using synthetically generated student data. It follows a structured analytical approach to extract meaningful insights that support academic evaluation and decision-making.

The project demonstrates the application of exploratory data analysis (EDA), statistical techniques, and data visualization to understand patterns in student performance across key factors such as attendance, internal assessment, department, and demographic attributes.

Objectives
Generate a realistic synthetic dataset representing student academic records
Perform data preprocessing to ensure accuracy, consistency, and reliability
Analyze student performance using statistical and exploratory techniques
Identify high-performing and low-performing students
Compare performance across departments, gender, and academic years
Examine relationships between key variables such as attendance and marks
Present insights using structured visualizations
Dataset Description

A synthetic dataset of 250 student records was created to simulate real-world academic data.

Features
Feature	Description
Student_ID	Unique identifier for each student
Name	Student name
Gender	Male or Female
Department	CSE, IT, ECE
Year	1st, 2nd, 3rd
Maths	Marks in Mathematics
Science	Marks in Science
English	Marks in English
Attendance (%)	Attendance percentage (50–100)
Internal Marks	Internal assessment score (0–25)
Methodology
Data Generation

Synthetic data was generated using Python libraries with controlled distributions to ensure realistic academic patterns.

Data Preprocessing
Verified data types and dataset structure
Ensured consistency across all fields
Prepared data for analysis
Exploratory Data Analysis
Applied descriptive statistics such as mean, median, and standard deviation
Derived additional metrics including total marks, average marks, and grade classification
Performance Analysis
Identified top-performing students based on overall scores
Detected low-performing students based on defined thresholds
Conducted comparative analysis across departments, gender, and academic years
Relationship Analysis
Evaluated correlation between attendance and academic performance
Analyzed the impact of internal marks on final scores
Studied relationships between subject-wise performance
Visualization

Used graphical techniques to improve interpretability:

Bar charts
Pie charts
Histograms
Scatter plots
Tools and Technologies
Python
pandas
numpy
matplotlib
seaborn
Faker
Jupyter Notebook
Key Findings
Higher attendance is associated with better academic performance
Internal assessment marks significantly influence overall results
Performance varies across departments and academic years
Subject-wise analysis highlights strengths and areas for improvement
Visualizations help identify trends and patterns effectively
Project Execution
git clone https://github.com/your-username/student-performance-analysis.git
cd student-performance-analysis
jupyter notebook

Open the notebook:
WEEK_4_Student_Performance_Analysis_System.ipynb

Project Structure
├── data/
│   └── dataset.csv
├── notebooks/
│   └── WEEK_4_Student_Performance_Analysis_System.ipynb
├── README.md
Future Enhancements
Integrate machine learning models for performance prediction
Develop interactive dashboards using Streamlit or Power BI
Automate the data pipeline for scalability
Deploy as a web-based application
Incorporate real-world datasets for validation

______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________--
Author
Yuvasri.S
