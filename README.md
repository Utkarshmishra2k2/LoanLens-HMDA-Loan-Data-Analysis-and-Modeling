# 🚀 **LoanLens: Scalable Loan Data Analysis and Modeling**

## 📊 **Project Overview**
**LoanLens** is a large-scale data analysis and machine learning project designed to process and model loan data from the **Hyderabad Metropolitan Development Authority (HMDA)**. It combines the scalability of **PySpark** with the flexibility of **Pandas** to efficiently handle and analyze massive datasets.  

The project tackles the challenge of large-scale data processing by implementing a **25% sampling strategy** using PySpark, significantly reducing computational overhead while preserving data quality. It then applies machine learning techniques to predict loan amounts, providing valuable insights into lending patterns.

---

## ⚙️ **Tech Stack**
- **Programming Languages:** Python (PySpark & Pandas)  
- **Data Processing:** PySpark for large-scale handling, Pandas for refined analysis  
- **Machine Learning:** Random Forest Regressor with Grid Search CV for hyperparameter tuning  
- **Visualization:** Plotly for interactive histograms, KDE plots, and correlation heatmaps  
- **Model Interpretation:** SHAP for feature importance analysis  

---

## 🔥 **Key Features**
### ✅ **Efficient Big Data Handling**
- Utilizes **PySpark** to process large-scale loan data efficiently.  
- Applies **25% random sampling** to reduce dataset size without compromising statistical relevance.  

### 📊 **Data Preprocessing**
- **Missing value imputation:** Uses median for numerical and mode for categorical features.  
- **Feature Engineering:** Creates loan-to-income and loan-to-property ratios.  
- **Outlier Handling:** Applies statistical techniques to detect and mitigate outliers.  

### 🤖 **Machine Learning Pipeline**
- **Random Forest Regressor** model for loan amount prediction.  
- **Grid Search CV** for hyperparameter optimization.  
- **Model evaluation metrics:** MSE, RMSE, MAE, R², and Adjusted R².  
- **SHAP values** for feature importance interpretation.  

### 📈 **Data Visualization**
- **Plotly visualizations:** Interactive histograms, KDE plots, boxplots, and correlation heatmaps.  
- **Residual plots** for model diagnostics.  

---

## 🛠️ **Installation & Execution**
 **Clone the repository:**  
```bash
git https://github.com/Utkarshmishra2k2/LoanLens-HMDA-Loan-Data-Analysis-and-Modeling.git
```
## 🛠️ **Project Structure**
```
LoanLens/
├── data/                   # Dataset files
├── notebooks/              # Jupyter Notebooks for EDA and model training
├── pyspark_pipeline.py     # PySpark script for large-scale data processing
├── pandas_pipeline.py      # Pandas script for refined analysis and ML modeling
├── model_metrics.json      # JSON file storing model evaluation metrics
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies
```

## 🛠️ **Usage**
 - Financial Analysis: Gain insights into loan distribution, income-to-loan ratios, and lending patterns.
 - Modeling and Prediction: Use the trained model to predict loan amounts and evaluate lending risk.
 - Scalable Data Processing: Handle massive datasets efficiently using PySpark’s distributed computing power.


