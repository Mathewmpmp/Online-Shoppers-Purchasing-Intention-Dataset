# Online-Shoppers-Purchasing-Intention-Dataset
  Online Shoppers Purchasing Intention — ML Project
🛒 Online Shoppers Purchasing Intention — ML Project
  This project analyzes and predicts whether an online shopper will generate revenue (i.e., make a purchase) based on their browsing behavior and session characteristics. It uses the Online Shoppers Intention Dataset and applies data preprocessing, feature engineering, and machine learning classification models.

🔍 #Dataset
Source: online_shoppers_intention.csv

Target: Revenue (1 = purchase, 0 = no purchase)

📦 #Workflow
Preprocessing
    Clean and encode categorical features (e.g., Month, VisitorType)
    Apply cyclical encoding for months
    Convert boolean fields to integers
    Handle skewed numeric features with log transformation
    Standardize numerical features

#Modeling

Models used:
  Logistic Regression |Random Forest | XGBoost Classifier 

#Evaluation metrics
  Accuracy
  ROC AUC Score
  Confusion Matrix
  Classification Report
  Visualization
  ROC Curve for all models
  Feature importance from Random Forest

📊 #Output
  Model comparison with evaluation metrics
  Visual insights from ROC curves and feature importance
  Clean, reproducible code with minimal comments for simplicity

🧠 #Techs
  Python | Pandas | NumPy  | Matplotlib | Seaborn |scikit-learn | XGBoost
