# Loan-Elgibility-Prediction

Project Description

This project represents a comprehensive data science workflow aimed at predicting loan eligibility. The process involves exploratory data analysis (EDA) to understand key patterns, thorough data preprocessing, and the application of machine learning models to build a predictive solution. The goal is to derive actionable insights from the dataset and provide a robust framework for making loan decisions.


Technologies Used

Python: The core programming language.

pandas: For data manipulation and cleaning.

seaborn & matplotlib: For data visualization and creating informative plots.

Plots and charts: Used to plot the values of the loan status and income_annum by comparing with eduction and cibil score features using box plot, histogram and count plot charts .

Train and test data: Splited the data into train and test data and predicted the loan elgibility.

Decision trees and different models: Used to find the accuracy of the dataset using Decision Tree, Gaussian, Naive Bayes, Gradient boosting, Extreme Gradient Boosting (XGB) and Categorial Boosting used for predictive modeling.

Maps: Predicted the actual and predicted values using heatmap, confusion matrix and implemented Single Decision Trees


Project Structure

─ Loan_elgibility_prediction_dataset.csv  # The raw input dataset
─ loan_eligibility_predictor.py           # The main data science script
─ decision_tree_plot                      # A visualization of the decision process
─ confusion_matrix                        # A visualization of the model's performance
─ README.md                               # This file


Follow these steps to set up and run the project:

Clone the repository:
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name

Install dependencies:
pip install pandas catboost seaborn matplotlib

Run the script:
python loan_eligibility_predictor.py


Data Analysis and Modeling

This project follows a structured data science pipeline:

Data Preprocessing: The raw data is cleaned by handling missing values and ensuring all features are in the correct format. A key step involves converting string and categorical data into a numerical format suitable for modeling.

Exploratory Data Analysis (EDA): The data is analyzed to find relationships and patterns between variables, such as the correlation between Cibil_score and Loan_status.

Predictive Modeling: Decision Tree, Gaussian, Naive Bayes, XGB, Gradient Boosting and CatBoost are trained on the prepared data. The models learn to predict loan eligibility based on the input features.

Model Evaluation: The performance of the models is evaluated using accuracy scores and a confusion matrix to understand their effectiveness in predicting both approved and rejected loans.


Visualizations

Key visualizations are generated to provide insights and summarize the findings:

Decision Tree Plot: Visualizes the internal logic of a simple Decision Tree model, offering an interpretable view of the most important decision factors.

Confusion Matrix: A heatmap that clearly illustrates the model's predictive performance, showing where the model succeeded and where it failed.


Conclusion

The project successfully demonstrates a complete data science workflow for a classification problem. By comparing multiple models and visualizing their results, it provides a comprehensive overview of how to select and evaluate a model for predicting loan eligibility.
