# Flipkart Customer Support EDA & ML Project

## 📌 Project Overview
This project focuses on analyzing Flipkart’s customer support interaction data to understand key factors influencing customer satisfaction and to build a machine learning model that predicts Customer Satisfaction (CSAT) scores.

The project demonstrates an end-to-end data analytics and machine learning workflow, including data cleaning, exploratory data analysis (EDA), hypothesis testing, feature engineering, model building, and deployment readiness.

---

## 🎯 Project Objectives
- Analyze customer support interaction data to identify patterns and trends
- Understand factors affecting customer satisfaction (CSAT)
- Perform detailed Exploratory Data Analysis (EDA) with meaningful visualizations
- Apply statistical hypothesis testing to validate insights
- Build and compare multiple machine learning models
- Select the best-performing model for CSAT prediction
- Prepare the model for real-world deployment

---

## 🧰 Tools & Technologies Used
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**
- **Joblib (Model Saving)**
- **GitHub**

---

## 📊 Dataset Description
The dataset contains records of Flipkart customer support interactions.

### Key Features:
- Channel Name (Inbound / Outbound)
- Issue Category & Sub-category
- Order Details
- Item Price
- Connected Handling Time
- Agent Name, Supervisor, Manager
- Agent Tenure & Shift
- Customer Satisfaction Score (CSAT)

**Target Variable:**  
- CSAT Score (Customer Satisfaction Score)

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was conducted to understand the structure and quality of the dataset. The following steps were performed:

- Dataset loading and inspection
- Missing value and duplicate value analysis
- Data cleaning and wrangling
- Univariate, bivariate, and multivariate analysis (UBM Rule)
- Creation of 15+ meaningful visualizations
- Correlation analysis and pair plots

### Key Insights:
- Inbound interactions dominate customer support traffic
- Order-related and product-related issues are most common
- Experienced agents receive higher CSAT scores
- Longer handling times negatively impact customer satisfaction
- Agent tenure, supervision, and management influence CSAT

---

## 🧪 Hypothesis Testing
Statistical hypothesis testing was performed to validate EDA findings:

- Impact of agent experience on CSAT
- Effect of handling time on CSAT
- Influence of interaction channel on CSAT

Tests used:
- Independent T-Test
- One-Way ANOVA

---

## ⚙️ Feature Engineering & Preprocessing
- Missing value imputation using median
- Outlier handling using IQR method
- Categorical encoding using Label Encoding
- Feature scaling using StandardScaler
- Train-test split (80:20)
- Imbalance analysis (no resampling required)

Text preprocessing steps were skipped as the dataset is not NLP-based.

---

## 🤖 Machine Learning Models
Three classification models were implemented and evaluated:

1. **Logistic Regression** (Baseline Model)
2. **Decision Tree Classifier**
3. **Random Forest Classifier**

### Model Evaluation:
- Accuracy
- Confusion Matrix
- Classification Report
- Evaluation metric score charts

### Hyperparameter Tuning:
- GridSearchCV was used to optimize all models

---

## 🏆 Final Model Selection
The **Random Forest Classifier** was selected as the final model due to:
- Highest accuracy among tested models
- Better handling of non-linear relationships
- Reduced overfitting through ensemble learning
- Built-in feature importance for explainability

---

## 🔍 Model Explainability
Feature importance analysis showed that the most influential features are:
- Agent Tenure
- Connected Handling Time
- Issue Category
- Interaction Channel
- Agent Shift

---

## 🚀 Deployment Readiness
- The final model was saved using `joblib`
- The saved model was reloaded and tested on unseen data
- The model is ready for deployment in a real-time environment

---


---

## 📈 Business Impact
This project helps Flipkart:
- Improve customer support efficiency
- Identify key drivers of customer satisfaction
- Optimize agent training and shift planning
- Reduce handling time and improve service quality
- Enable data-driven decision-making

---

## 🏁 Conclusion
This project successfully combines EDA and machine learning to analyze customer support data and predict customer satisfaction scores. The insights and predictive model can significantly enhance customer experience and operational effectiveness.

---

## 👤 Author
**Imtiaz Ahmed Mohammad**

---

## ⭐ Acknowledgment
This project was completed as part of an Internship Project of #NATIVE ENGINEERING

