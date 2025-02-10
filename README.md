# Credit-Card-Fraud-Detection

# Objective

The objective of this project is to detect fraudulent transactions in a highly imbalanced dataset using supervised machine learning algorithms. 
This system can help financial institutions minimize fraudulent activities and protect users from credit card fraud.

# Problem Statement: 

For many banks, retaining high profitable customers is the number one business goal. Banking fraud, however, poses a significant threat to this goal for different banks. In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

In the banking industry, credit card fraud detection using machine learning is not only a trend but a necessity for them to put proactive monitoring and fraud prevention mechanisms in place. Machine learning is helping these institutions to reduce time-consuming manual reviews, costly chargebacks and fees as well as denials of legitimate transactions.

In this project we will detect fraudulent credit card transactions with the help of Machine learning models. We will analyse customer-level data that has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group.

# Research Question

1. What are the characteristics that differentiate fraudulent credit card transactions from legitimate ones?

2. How can machine learning models handle imbalanced datasets effectively?

3. Which classification algorithm performs best for fraud detection in this dataset?


# Methodology

1. Logistic regression
   
2. Random Forest

  # For data preprocessing 
  
  1. Used Power Transformer to mitigate skewness
     
  2. Used SMOTE to balance the Class imbalance

# Conclusion 

The model Logittic Regression with SMOTE is preferable due to its high F1-score (0.87) for fraud detection, indicating an optimal balance between precision (0.94) and recall (0.82). High precision ensures minimal false positives, reducing unnecessary alerts, while good recall captures most fraud cases, minimizing missed detections. This balance is crucial in fraud detection, where both false positives and negatives have significant consequences. The model’s high accuracy (1.00) further supports its reliability. Overall, its ability to effectively identify fraud while maintaining low error rates makes it the most suitable choice for handling imbalanced datasets in fraud detection scenarios.
