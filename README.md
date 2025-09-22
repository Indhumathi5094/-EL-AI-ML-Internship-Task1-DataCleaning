# Task 1: Data Cleaning & Preprocessing

## 📌 Objective
Learn how to clean and prepare raw data for Machine Learning.

## 🛠️ Tools Used
- Python
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📂 Dataset
- Titanic Dataset (from Kaggle )
- Shape: 891 rows × 7 columns

## 🔑 Steps Performed
1. Data Cleaning → Dropped PassengerId column.
2. Handling Nulls → Filled missing Age with median, Embarked with mode.
3. Encoding → Converted categorical columns (Sex, Embarked) into numeric.
4. Feature Scaling → Standardized Age & Fare using StandardScaler.
5. Outliers → Visualized with boxplots and removed using IQR method.

## 📊 Results
- Cleaned dataset ready for ML modeling.
- Null values handled.
- Features scaled & encoded properly.
