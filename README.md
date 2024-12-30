# Bank_Marketing_Prediction
This project focuses on predicting client subscription to term deposit offers based on a publicly available dataset: bank-additional-full.csv. It utilizes data preprocessing, exploratory analysis, and machine learning models to achieve robust predictions.


#Introduction
This project leverages machine learning to classify clients based on their likelihood of subscribing to a term deposit. The models used include:
    - Artificial Neural Networks (ANN)
    - Random Forest
Performance metrics such as accuracy, ROC-AUC scores, and precision-recall curves are employed to evaluate the models.

#Features
-Data cleaning and handling of duplicate/garbage values
-Outlier detection and treatment
-Categorical encoding and feature scaling
-Dataset balancing using Synthetic Minority Oversampling Technique (SMOTE)
-Model training and evaluation with:
   ANN
   Random Forest
-Visualizations: Correlation heatmaps, ROC-AUC, and Precision-Recall curves

#Dataset Overview
The dataset is sourced from UCI Machine Learning Repository. It contains client data collected from a Portuguese banking institution.

#Technologies Used
-Python
-Pandas, NumPy for data manipulation
-Matplotlib, Seaborn for visualization
-scikit-learn, imbalanced-learn for preprocessing and model evaluation
-TensorFlow/Keras for ANN implementation

#Key Steps
1)Data Preprocessing
-Duplicate and garbage value handling
-Encoding categorical variables
-Outlier treatment using IQR method
-Feature scaling with StandardScaler
-Correlation analysis for feature selection

2)Data Balancing
SMOTE is applied to balance the class distribution.

3)Model Implementation
-ANN with dropout and batch normalization for robust learning
-Random Forest with hyperparameter tuning

4) Evaluation
-Comparison using accuracy, ROC-AUC, and Precision-Recall curves

5) Results
ANN achieved an ROC-AUC score of 0.5670.
Random Forest achieved an ROC-AUC score of 0.8864.
Both models demonstrated strong predictive capabilities, with Random Forest providing interpretability via feature importance visualization.

Conclusion
This project successfully implemented machine learning models to predict term deposit subscriptions. The balanced dataset and preprocessing pipeline ensured robust model performance
