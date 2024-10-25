# Web-Traffic-Analytics-ML-Model

The Jupyter Notebook contains a detailed exploration of classifying website visitors using logistic regression. Here is an overview of its contents and features:

### Description
The notebook focuses on building a logistic regression model to classify website visitors as either new or returning. It uses Google Analytics sample data and BigQuery for data analysis and feature engineering. The project emphasizes understanding user behavior patterns through descriptive analytics and logistic regression modeling.

### Features

1. **Data Import and Setup**:
   - Utilizes the `bigquery` library to import sample data from Google Analytics.
   - Sets up necessary configurations and initializes the project environment.

2. **Data Preprocessing**:
   - Cleans and preprocesses the imported data.
   - Performs feature engineering to prepare data for model training, including handling missing values and encoding categorical variables.

3. **Exploratory Data Analysis (EDA)**:
   - Conducts descriptive statistics to understand the distribution and relationships within the data.
   - Visualizes data using various plots to identify patterns and trends, focusing on metrics like bounce rates and session counts.

4. **Model Building**:
   - Implements logistic regression to classify website visitors.
   - Splits data into training and testing sets to evaluate the model's performance.
   - Tunes hyperparameters to optimize the model.

5. **Model Evaluation**:
   - Evaluates the model using metrics such as accuracy, precision, recall, F1 score, log loss, and ROC AUC.
   - Analyzes the confusion matrix to understand the classification results.

6. **BigQuery Analysis**:
   - Uses SQL queries in BigQuery to perform further data analysis.
   - Analyzes traffic sources and bounce rates to gain insights into user behavior.

7. **Results and Conclusion**:
   - Summarizes the findings from the logistic regression model and the descriptive analysis.
   - Discusses limitations and provides recommendations for future work.

8. **Visualization**:
   - Employs libraries like `matplotlib` and `seaborn` to create informative visualizations.
   - Displays key metrics and model performance visually for better understanding.

### Additional Details
- The notebook includes various markdown cells that document the workflow, explain the code, and interpret the results.
- It uses a mix of Python and SQL for data analysis and model building, highlighting the integration of different tools and techniques in data science projects.

This comprehensive approach ensures a thorough analysis and provides a clear understanding of the process and results, making it a valuable resource for anyone interested in logistic regression and website visitor classification.
