# 📊 Telecom-Churn-Prediction-KPI-Tracking-Dashboard
This project is an end-to-end data analytics and machine learning pipeline designed to proactively identify telecom customer attrition and visualize retention metrics. Using Python, SMOTE, and XGBoost to forecast attrition probabilities. Integrated these predictive insights into an interactive Power BI dashboard using DAX .

## 🚀 Overview
This project is an end-to-end data analytics and machine learning pipeline designed to proactively identify telecom customer attrition and visualize retention metrics. By bridging the gap between predictive modeling and business intelligence, this system not only forecasts which customers are highly likely to churn but also equips stakeholders with an interactive dashboard to explore the underlying causes and target high-risk segments. 

## ⚙️ Pipeline Architecture & Key Features

*   **🔍 Exploratory Data Analysis (EDA) & Preprocessing:** Processed raw telecom data using Python and Pandas. Handled edge cases (such as missing values in total charges for new customers), analyzed skewed distributions, and mapped feature correlations using Matplotlib and Seaborn to prepare the data for modeling.
*   **🧠 Predictive Machine Learning:** Addressed severe target class imbalance using the SMOTE (Synthetic Minority Oversampling Technique) algorithm. Trained and evaluated multiple tree-based classification models, including Random Forest and XGBoost, utilizing 5-fold cross-validation to ensure model reliability. 
*   **🔗 Business Intelligence Integration:** Serialized the optimal ML model to generate individual churn probability scores for the dataset. These predictions were ingested into Power BI, where Power Query was used for further data transformation and DAX (Data Analysis Expressions) was utilized to calculate core KPIs.
*   **📈 Interactive Power BI Dashboard:** Engineered a dynamic reporting interface featuring KPI cards (Total Customers, Churn Rate, Average Charges), risk-band tree maps, and retention donut charts. The dashboard allows business teams to slice data by contract types, tenure, and predicted churn risk to formulate targeted retention strategies.
*   **🌐 Real-Time Application Deployment:** Deployed a lightweight Streamlit web application that operationalizes the saved machine learning model. This interface allows customer success agents to manually input live customer metrics and instantly receive a binary churn prediction alongside a probability confidence score.

## 💻 Tech Stack
*   **Programming & Scripting:** 🐍 Python, 🧮 DAX
*   **Data Manipulation & EDA:** 🐼 Pandas, 📊 Matplotlib, 📉 Seaborn
*   **Machine Learning:** 🤖 Scikit-learn (Label Encoding, Classification Metrics), 🌲 XGBoost, ⚖️ Imbalanced-learn (SMOTE)
*   **Business Intelligence:** 🏢 Power BI, ⚙️ Power Query
*   **Model Deployment:** 🚀 Streamlit, 📦 Pickle

## 🎯 Business Impact
This dual-approach system transforms reactive data into proactive strategy. Instead of merely reporting historical churn, it scores active customers for flight risk and provides a clear visual narrative, enabling targeted interventions, optimized pricing strategies, and improved customer lifetime value.
