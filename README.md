# Employee Turnover Prediction Model for Salifort Motors

## Project Overview
In this project, I analyzed employee turnover data for **Salifort Motors**, a fictional company facing high turnover rates. This issue was leading to significant financial strain due to recruitment, training, and development costs. The goal was to build a predictive model using employee attributes like job title, department, number of projects, and average monthly hours to help the leadership team identify at-risk employees and make informed retention strategies.

The project evaluates multiple machine learning models, including **Logistic Regression**, **Decision Tree**, and **Random Forest**, to determine the best approach for predicting employee turnover.

### Dataset
The data was sourced from the **Kaggle HR Analytics and Job Prediction Dataset**, containing information about employee demographics, work performance, and job satisfaction.

## Project Stages
The project follows the **PACE** framework, which consists of four stages:

### 1. Plan: Understanding the Data in Business Context
- Analyze the business problem and its impact on **Salifort Motors**.
- Define the key objective: **predict employee turnover** and provide actionable insights for the HR team.
- Discuss ethical implications of using predictive models in this context.

### 2. Analyze: Exploratory Data Analysis (EDA)
- **Initial Data Exploration**: Understanding the dataset, checking for missing values, duplicates, and outliers.
- **Data Cleaning**: Removing duplicate records and handling missing values.
- **EDA and Visualizations**: Investigating the relationship between different features and employee turnover.
  
  Key insights include:
  - High turnover correlates with longer working hours and a higher number of projects.
  - Employees with more than 6 years at the company are less likely to leave.
  - Burnout and lack of promotions contribute significantly to employee dissatisfaction.

### 3. Construct: Model Building
- **Logistic Regression**: Build a logistic regression model and evaluate its assumptions (e.g., multicollinearity, sample size, outliers).
- **Tree-based Models**: Develop **Decision Tree** and **Random Forest** models to capture nonlinear relationships in the data.
- **Feature Engineering**: Enhance the model's performance by adding meaningful features based on domain knowledge.

### 4. Evaluate: Model Performance and Recommendations
- **Metrics Used**: Precision, Recall, F1-Score, Accuracy, and AUC (Area Under the Curve).
  
  Model results:
  - **Logistic Regression**: Achieved an accuracy of 83%.
  - **Decision Tree**: AUC of 93.8%, accuracy of 96.2%.
  - **Random Forest**: Slightly outperformed Decision Tree with better precision and recall.

### Recommendations:
Based on model results, here are some recommendations for improving employee retention:
- Limit the number of projects an employee can work on at once.
- Promote employees who have been with the company for more than 4 years.
- Offer incentives for longer working hours or reduce the expectation of overtime.
- Clarify company policies regarding workload, overtime, and work-life balance.

## Ethical Considerations
While the model can provide valuable insights, it is important to note the potential for misclassification, such as wrongly predicting that an employee will leave. These considerations must be communicated clearly to stakeholders to avoid unintended consequences.

## Next Steps
- Investigate **data leakage** concerns, especially around the feature "last_evaluation."
- Consider developing a **K-means clustering** model to uncover additional patterns in employee behavior.
- Explore other modeling approaches and compare their effectiveness.

## How to Run This Project
1. Clone this repository to your local machine.
2. Run the Jupyter notebook to explore the dataset, perform EDA, and train the models.
3. Review the final recommendations and evaluate model results.

## Connect with Me
- [GitHub](https://github.com/VenkatRamoju01/)
- [LinkedIn](https://www.linkedin.com/in/venkat-ramoju/)
- [Kaggle](https://www.kaggle.com/venkatramoju)
