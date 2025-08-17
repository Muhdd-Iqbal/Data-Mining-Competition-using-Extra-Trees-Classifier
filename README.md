# Data-Mining-Competition-using-Extra-Trees-Classifier

This is notebook that used for ICONFEST Competition 2020. My team achieved "Best of Three Data Mining" in this competition.
This notebook is used to analyze and create a model to predict drive safety for Online Driver (Apps) when customer order and use the service.

------------------------------------------------------------------------------------------
Methodology:
- Data Preparation
- Data Exploration and Data Visualization
- Feature Engineering
- Resampling Data (SMOTE) because imbalanced data
  <img width="334" height="151" alt="image" src="https://github.com/user-attachments/assets/11ffd1d0-ff55-424e-8075-3d65ab1a9620" />

- Split Data for Training and Testing for data validation.
- Data Modeling
  Machine Learning: Extra Trees Classifier Model with Stratified k Fold.
  Machine Learning algorithm used for classifying classes with an estimator that fits a number of random decision trees on various sub-samples
  of the dataset and uses averaging to improve prediction accuracy and control overfitting. We used this method because our data is imbalanced.

  <img width="557" height="235" alt="image" src="https://github.com/user-attachments/assets/ebd1d7ad-4273-4f8c-8365-63c65d1c1f8d" />

- Data Evaluation
  AUC
  <img width="451" height="375" alt="image" src="https://github.com/user-attachments/assets/f9deadd6-8d65-4371-84d9-12a858dae4b5" />

  F1-Score
  <img width="535" height="102" alt="image" src="https://github.com/user-attachments/assets/c0df3d5f-3890-4b40-a287-58bd3157c524" />

