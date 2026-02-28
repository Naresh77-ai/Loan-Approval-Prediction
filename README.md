Problem Statement

Manual loan approval is slow and can be inconsistent due to subjective judgment and the large volume of applications. This project builds a model to predict whether a loan will be Approved or Rejected using applicant demographic, financial, and credit-related features.

Solution / Approach

Developed a Logistic Regression classifier with standard preprocessing (handling missing values and encoding categorical variables). Model performance was evaluated using a confusion matrix, classification report, and ROC–AUC.

Achievement (Results)

Confusion Matrix: TN=283, FP=40, FN=25, TP=506 (slightly more false approvals than false rejections)

F1-score: Rejected=0.90, Approved=0.94; Macro/Weighted F1 = 0.92

ROC–AUC: 0.975 (excellent class separability)
