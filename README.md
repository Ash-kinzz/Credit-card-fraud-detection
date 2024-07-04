# Credit-card-fraud-detection

**Project Overview**
Credit card fraud is a significant concern for both financial institutions and cardholders. Early detection of fraudulent transactions helps minimise financial losses. This project aims to develop a model that can effectively distinguish legitimate purchases from fraudulent activities based on historical credit card transaction data.

**Model Development**
We implemented a Random Forest model to analyse credit card transactions and classify them as legitimate or fraudulent. Random Forest is an ensemble learning technique that combines the predictions of multiple decision trees, resulting in a more robust and accurate model.

**Addressing Data Imbalance**
A key challenge in credit card fraud data is its inherent imbalance. Legitimate transactions significantly outnumber fraudulent ones. To address this, we employed SMOTE (Synthetic Minority Oversampling Technique). SMOTE creates synthetic samples for the minority class (fraudulent transactions), balancing the dataset and allowing the model to learn more effectively from limited fraud data.

**Algorithm Comparison**
We evaluated the performance of Random Forest alongside other popular classification algorithms, including Logistic Regression and Decision Tree. We compared their ability to detect fraudulent transactions while minimizing false positives (legitimate transactions flagged as fraudulent).

**Why Random Forest?**
Based on our evaluation, Random Forest emerged as the most effective model for this specific task. Here's why:
• Robustness: Random Forest is less prone to overfitting compared to some other algorithms, leading to better performance on unseen data.
• Handling Imbalance: Random Forest performs well even with imbalanced datasets due to its inherent ensemble nature.
• Feature Importance: Random Forest provides insights into the features that play a significant role in fraud detection, aiding in further model improvement.

**Model Performance**
By utilizing SMOTE for oversampling and leveraging the strengths of Random Forest, we achieved a near-perfect F1-score of 0.98 for fraud detection. This metric balances precision (correctly identified fraudulent transactions) and recall (identifying all actual fraudulent transactions). Additionally, SMOTE helped significantly reduce false positives, ensuring a model that minimizes wrongly flagging legitimate transactions.

**Conclusion**
This project demonstrates the effectiveness of Random Forest in conjunction with SMOTE for credit card fraud detection. The model can be further improved by incorporating additional features or exploring advanced techniques like deep learning.
