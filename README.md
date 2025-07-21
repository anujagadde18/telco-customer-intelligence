# Telco Customer Churn Prediction

## 💡 Problem Statement
Predict whether a telecom customer will churn based on service usage, contract details, and demographics.

## 📊 Dataset
- Source: IBM Telco Customer Churn dataset
- Shape: ~7K rows, 21 columns
- Target: `Churn`

## 🧰 Technologies Used
- Python 3.12
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## ⚙️ Workflow
1. Data Cleaning & Encoding
2. Exploratory Analysis
3. Segmentation (Clustering)
4. Model Training (Random Forest)
5. Feature Importance Visualization
6. Evaluation Metrics

## 🎯 Results
- Accuracy: 79%
- Key features: tenure, monthly charges, contract
- Precision for churn class is lower → consider rebalancing

## 📦 Outputs
- `churn_rf_model.pkl`
- `label_encoders.pkl`
- Feature importance plots

## 🔮 Future Work
- Hyperparameter tuning
- Handle class imbalance (SMOTE or class weights)
- Deploy via Streamlit or Flask
- Add SHAP explainability

## 📝 Author
Anuja Jagadde
