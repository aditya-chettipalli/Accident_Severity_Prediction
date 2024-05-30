# Accident Severity Prediction 
## Introduction
The recent increase in traffic accidents and their negative effects on public safety is a growing issue. Statistics show that both the number and severity of accidents are rising, so it's important to address these challenges proactively. This requires a comprehensive approach that includes exploring and understanding the problem, as well as taking proactive measures using predictive modeling and advanced data analytics.

## Problem Description
This project focuses on the complexities and challenges associated with traffic accidents, highlighting the critical importance of utilizing data-driven insights and solutions. It emphasizes the need to understand and mitigate the intricate nature of traffic accidents, considering the wide range of contributing factors. Key aspects include:

Understanding and addressing the various factors influencing traffic accidents.

Discussing data collection methods, data integrity issues, and dataset gaps.

Analyzing the impact of road infrastructure and safety measures on accident rates.

Exploring geographical variability and accident hotspots.

## Description of the Data
The dataset, obtained from Kaggle, includes detailed records of traffic accidents across 49 states in the United States from 2016 to 2022. It combines information from law enforcement agencies, transportation departments, and traffic cameras/sensors. The dataset consists of 47 columns and millions of records, covering a wide range of accident-related information, including:

Identification (ID)
Source
Severity
Start_Time, End_Time
Geographical Coordinates
Distance(mi)
Description
Street, City, County, State, Zip code
Weather Information
Road Features
Traffic Conditions
Twilight Information
# Methodology
## Data Cleaning and Preprocessing
Handling Missing Values: Replaced null values with 0 or the mean value for specific columns.

Feature Selection: Removed unnecessary columns.

Transforming Categorical Data: Converted 'True/False' data to '1/0' format.

Data Splitting

The dataset was split into training and testing subsets with an 80:20 ratio to ensure comprehensive model assessment.


Predictive Analysis

Various classification algorithms were implemented using PySpark, Spark SQL, and Python's scikit-learn and MLlib libraries, including:

Logistic Regression
GBT Classifier (Gradient-Boosted Trees)
Random Forest
Decision Tree
Exploratory Data Analysis (EDA)
After data cleaning and preprocessing, key statistics were visualized:

Accident Distribution by Streets, Cities, and States: Identified areas with higher accident occurrences.
Road Conditions and Accident Occurrences: Analyzed the correlation between road conditions and accident frequency.
Mapping Accident Hotspots: Used the Folium library to create interactive maps displaying accident locations and hotspots.
## Results
Model performance was evaluated using metrics like accuracy, precision, recall, and F1-score. Key findings include:

Gradient Boosted Tree Model
Accuracy: 90%
Precision: 0.90
Recall: 1.0
F1 Score: 0.95

Random Forest and Decision Tree Models

Accuracy: 74%
Precision: 0.75
Recall: 0.98
F1 Score: 0.85

## Key Findings and Insights
Accident Contributors: Various factors like weather conditions and road infrastructure significantly affect accidents.

Accident Trends: Identifying accident-prone areas and severity levels helps develop preventive measures.

Data-Driven Decision Making: Provides crucial information for policymakers and law enforcement.

