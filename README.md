# credit-risk-classification

The purpose of this repo is to generate a logistic regression model that can predict the health of a loan based on a number of features. The results and findings of this effort are below, and can also be found in the report-template.md file.

Overview of the Analysis

The purpose of building this model is to enable the ability to predict if a loan is likely to be classified as healthy or high risk based on a number of factors, such as loan size, interest rate, borrower income, debt:income ration, and total debt. To achieve this, defined our features and labels, split the data into training and testing sets (training = 75%, testing = 25%), fit a logistic regression model, and then evaluated the model's performance (see results section for more details). Overall, this is an important model as it will allow us to minimize our risk when making lending decisions.
Results

Healthy Loans:

    Precision: Precision of 1.00 means that when the model predicts a loan as healthy, it is correct 100% of the time.
    Recall: A recall of 0.99 indicates that the model successfully identifies 99% of all actual healthy loans.
    F1-Score: An F1-score of 1.00 indicates a very high accuracy and recall balance for predicting healthy loans.

High risk loans:

    Precision: Precision of 0.85 means that when the model predicts a loan as high-risk, it is correct 85% of the time.
    Recall: A recall of 0.91 shows that the model correctly identifies 91% of all actual high-risk loans.
    F1-Score: An F1-score of 0.88 suggests a good balance between precision and recall for predicting high-risk loans, although there is some room for improvement compared to healthy loans.

Overall:

    Accuracy: The overall accuracy of 0.99 means that 99% of all predictions made by the model are correct, regardless of class.
    Macro Average: The macro average for precision and recall being around 0.92 and 0.95 respectively suggests that the model performs well across both classes without significant bias toward one class.
    Weighted Average: The weighted average F1-score of 0.99 indicates that the model's overall accuracy and balance between precision and recall is very good.

Summary
The model performs exceptionally well in identifying healthy loans with nearly perfect precision and recall. It also performs robustly in predicting high-risk loans, although not as flawlessly as with healthy loans, which is caused by the fact that healthy loans are more common in our dataset than risky loans. The high recall for high-risk loans is particularly important, as it means the model is effective at identifying most of the risky loans, which is a critical objective to ensure that we minimize risk when making lending decisions.
