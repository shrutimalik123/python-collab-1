# python-collab-1
Data Science Readiness Portfolio: Daily Python Exercises

This repository is dedicated to my daily Python coding practice, focusing on skills required for the CVS Health Data Scientist role. Each script addresses a specific core competency (e.g., data manipulation, statistical analysis, model training, MLOps simulation).

Goal: To build a practical portfolio demonstrating proficiency in Python, SQL concepts (simulated with Pandas), Machine Learning frameworks, and MLOps practices.

Day 1: Simple Data Profiler 

Focus Skill: Data Cleaning, Handling Missing Values, Basic Descriptive Statistics, and Feature Engineering using Pandas and NumPy.

Summary

This script simulates loading messy patient data (claims, vitals, demographics). It performs two critical preprocessing steps:

Imputation: Fills missing Age values using the mean of the available data.

Categorical Handling: Fills missing Diagnosis_Code with a standard UNKNOWN placeholder.

Feature Generation: Creates a new, derived feature: Mean Arterial Pressure (MAP) from Systolic and Diastolic Blood Pressure readings.

Output Snapshot

The script provides a clear demonstration of data quality checks and feature creation, which is the foundational work for predictive modeling.

(Future Step: Integrate a SQLite database connection here to showcase actual SQL query capabilities.)

Next Steps:

Day 2: Advanced Data Slicing and Aggregation (Simulating Cohort Analysis)

Day 3: Simple Scikit-learn Model Training (Predictive Modeling)

Day 4: Simulating MLOps Logging with MLFlow (Experiment Tracking)
