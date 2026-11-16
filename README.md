# AI-impact-on-students
Student GPA Prediction Using Linear Regression

Project Overview

This project uses Machine Learning to predict students' Post-Semester GPA based on their previous GPA, AI usage, traditional study hours, and primary AI use case.

Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

Dataset

The dataset contains 50,000 student records.

Features Used

- "Pre_Semester_GPA"
- "Weekly_GenAI_Hours"
- "Traditional_Study_Hours"
- "Primary_Use_Case"

Target Variable: "Post_Semester_GPA"

Steps Performed

1. Loaded the dataset using Pandas.
2. Performed basic data analysis.
3. Converted "Primary_Use_Case" into numerical columns using One-Hot Encoding.
4. Removed one dummy column to avoid the Dummy Variable Trap.
5. Selected input features ("X") and target ("y").
6. Split the dataset into 80% training and 20% testing.
7. Trained a Linear Regression model.
8. Predicted students' Post-Semester GPA.
9. Evaluated the model using R² score.

Model Results

- R² Score: 0.8839
- Example Predicted GPA: 3.60

The R² score indicates that the model explains approximately 88.39% of the variation in Post-Semester GPA on the test dataset.

Conclusion

This project demonstrates how Linear Regression and One-Hot Encoding can be used to predict student academic performance using numerical and categorical features.
