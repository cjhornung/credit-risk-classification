# credit-risk-classification

Goal: Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Credit Risk Analysis Report

The code output indicates that the logistic regression model performs quite well in predicting both the 0 (healthy loan) and 1 (high-risk loan) labels. Here's a breakdown of the key performance metrics:

Balanced Accuracy Score: The balanced accuracy score is 0.952, which is quite high. This metric takes into account the balance between the two classes (healthy loans and high-risk loans) and is a good indicator of overall model performance.

Confusion Matrix:

•	True Positives (TP): 563

•	True Negatives (TN): 18663

•	False Positives (FP): 102

•	False Negatives (FN): 56


The model correctly predicted 563 high-risk loans and 18663 healthy loans, with only 102 healthy loans being misclassified as high-risk loans and 56 high-risk loans being misclassified as healthy loans. This indicates good performance, especially in correctly identifying healthy loans.

Classification Report:

•	Precision: Precision measures the accuracy of the positive class predictions. The precision for predicting high-risk loans is 0.85, which means that out of all the loans predicted as high-risk, 85% were actually high-risk.

•	Recall (Sensitivity): Recall measures the ability of the model to identify all the positive instances correctly. The recall for predicting high-risk loans is 0.91, which means that the model correctly identified 91% of the actual high-risk loans.

•	F1-Score: The F1-score is the harmonic mean of precision and recall and provides a balance between the two. The F1-score for predicting high-risk loans is 0.88, which is a good balance between precision and recall.

•	Support: The number of instances for each class in the test set. There are 18765 healthy loans and 619 high-risk loans.

Overall, the logistic regression model seems to perform well. It has a high accuracy, and the classification report shows a good balance between precision and recall for both classes, with a strong F1-score for the high-risk loans. 

