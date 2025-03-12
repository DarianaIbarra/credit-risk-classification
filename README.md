**The instructions for this Challenge are divided into the following subsections:**

- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Write a Credit Risk Analysis Report

**Split the Data into Training and Testing Sets**
Open the starter code notebook and use it to complete the following steps:

- Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

**Create a Logistic Regression Model with the Original Data**
Use your knowledge of logistic regression to complete the following steps:

- Fit a logistic regression model by using the training data (X_train and y_train).
- Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
- Evaluate the model’s performance by doing the following:

   - Generate a confusion matrix.
   - Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

**Write a Credit Risk Analysis Report**
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

- An overview of the analysis: Explain the purpose of this analysis.
- The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
- A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.


The purpose of this analysis is to develop and evaluate the accuracy of a data model designed to predict applicants' ability to repay in peer-to-peer lending services.

Model performance metrics:
- Balanced accuracy: 95.25% → Considering both sensitivity (recovery rate or true positives) and specificity (true negative rate), the model achieves a balanced accuracy of 95.30%.
- Accuracy: 92.1% → Indicates that 92.1% of the positive predictions made by the model were correct.
- Recovery score: 95.1% → Means that the model correctly identified 95.1% of the true positive values within the total positive predictions.
  
**Model evaluation and recommendation:**
  
 The implementation of this model is strongly recommended, as it offers an exceptional accuracy of more than 95% in predicting borrowers' repayment capacity. Its high level of accuracy not only optimizes lending decisions, but also allows for a precise adjustment of the business risk profile. This guarantees a stable capital flow, minimizes the risk of defaults and strengthens lenders' profitability, ensuring business sustainability and growth in the financial sector.


