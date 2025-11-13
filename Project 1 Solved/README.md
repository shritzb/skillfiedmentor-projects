# 🏦 Bank Marketing Data Analysis & Inspection

This repository contains a **data analysis and inspection project** based on the **Bank Marketing Dataset**, aimed at understanding customer behavior and predicting whether a client will subscribe to a term deposit.
The project is divided into two Jupyter notebooks — one for **exploratory inspection** and another for **in-depth solution and visualization**.

## 📁 Repository Structure

```
├── Bank_Marketing_Inspection_test.ipynb      # Initial inspection and exploratory analysis
├── Bank_Marketing_Inspection_solution.ipynb  # Detailed solution with analysis, visualizations & insights
├── bankmarketing.csv                         # (Optional) Dataset file if available
└── README.md                                 # Project documentation
```

## 🎯 Objective

The main goal of this project is to:

* Explore and clean the **Bank Marketing dataset**
* Analyze customer and campaign characteristics
* Visualize key patterns influencing **term deposit subscriptions**
* Build a foundational understanding for future **predictive modeling**


## 📊 Dataset Overview

The dataset (`bankmarketing.csv`) contains information collected from marketing campaigns of a Portuguese banking institution.
Each row represents a customer contacted through a direct marketing campaign (via phone).

**Key features include:**

* **Demographics:** age, job, marital status, education, etc.
* **Financial:** balance, housing, loan, etc.
* **Campaign-related:** contact type, duration, previous outcome, etc.
* **Target Variable:** `y` — whether the client subscribed to a term deposit (`yes`/`no`)


## ⚙️ Methodology

### 🔹 1. Data Loading & Inspection

* Loaded the dataset using **Pandas**
* Checked for missing values and data types
* Explored summary statistics for numerical and categorical variables

### 🔹 2. Exploratory Data Analysis (EDA)

* Analyzed distribution of the target variable
* Computed correlation among numerical features
* Visualized relationships using **Seaborn** and **Matplotlib**

### 🔹 3. Key Insights

* Dataset is **imbalanced**, with most clients not subscribing to deposits
* Some variables (like contact duration, previous outcomes) show strong association with subscription rates
* Demographic and financial patterns indicate potential segmentation opportunities


## 📈 Visualizations

* **Target Distribution:** Count and percentage of term deposit subscriptions
* **Correlation Heatmap:** Relationship among numerical variables
* **Feature-wise Analysis:** Visual understanding of patterns affecting customer decisions


## 🧩 Technologies Used

| Tool / Library       | Purpose                          |
| -------------------- | -------------------------------- |
| **Python**           | Core programming language        |
| **Pandas**           | Data handling and analysis       |
| **NumPy**            | Numerical computation            |
| **Matplotlib**       | Data visualization               |
| **Seaborn**          | Statistical plots & heatmaps     |
| **Jupyter Notebook** | Interactive analysis environment |


## 🧠 Conclusion

This project sets the groundwork for **predictive modeling** on customer behavior in banking campaigns.
Key takeaways include:

* Identification of imbalance and feature importance
* Creation of a clear data pipeline for further modeling
* Establishment of visualization-driven insights into marketing effectiveness

Next steps could involve:

* Feature engineering & encoding
* Model training (Logistic Regression, Random Forest, etc.)
* Evaluation using precision-recall and ROC metrics
