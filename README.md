# AML_Fraud
Accurate, Real Time, Fraud Classification for Finances. 

Approach

1. Data Preparation

  Cleaned and preprocessed 2,797 transaction records.
  
  Engineered features from raw attributes (transaction amount, frequency, and customer behavior patterns).
  
  Handled class imbalance via resampling techniques (SMOTE / class weighting).

2. Modeling

  Evaluated multiple algorithms: Logistic Regression, Random Forest, and Neural Networks.
  
  Selected a Neural Network classifier for its superior recall and precision.
  
  Applied cross-validation to reduce overfitting and validate robustness.

3. Evaluation

  Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.
  
  Final model achieved 99.6% accuracy and strong recall on minority fraud class.
  
  Visualized results with confusion matrices, ROC curves, and feature importance plots.

4. Tools & Libraries

  Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
  
  ML Techniques: Feature Engineering, Cross-validation, Resampling (SMOTE), Neural Networks
  
  Environment: Jupyter Notebook

5. Results

  99.6% accuracy with high recall → minimized false negatives (critical for fraud detection).
  
  Produced actionable insights on key fraud indicators (e.g., abnormal transaction frequency).
  
  Delivered a framework adaptable for deployment in real-world financial systems.
  
6.  Next Steps

  Integrate with a real-time pipeline (Kafka + Spark Streaming).
  
  Deploy model via Flask API or AWS Lambda for production inference.
  
  Extend dataset to millions of transactions for scalability testing.
