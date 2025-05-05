# churn-dataset-logisticRegression
In this project, the dataset related to customer churn in a telecommunications company has been analyzed. The company's goal is to identify customer behavior patterns and understand the reasons behind churn to develop effective strategies for reducing customer attrition.

Evaluation of the Model Using Logistic Regression:
The initial logistic regression model was applied to the data, but it exhibited low prediction accuracy and a high error rate.

Confusion Matrix Analysis:
The model correctly predicted 7 customers as churners (1), but incorrectly classified 8 customers as non-churners (0).

Out of 25 customers who did not actually churn, the model correctly identified 18, but misclassified 7 as churners (1).

Overall accuracy = 62%, indicating that the model still does not perform optimally.

Evaluation Metrics Calculation:
Jaccard Score: Initially 0.54, and after adjusting the solver (solver='sag'), it improved to 0.64.

Log Loss: Initially 0.63, and after the adjustment, it reached 0.64, showing only slight improvement.

Conclusion:
Changing the solver parameter in logistic regression has led to some improvement, but the model still requires further optimization.
