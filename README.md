# 📊 Data Analyst Internship Portfolio (Oasis Infobyte) – Ujjwal Karki

Welcome to my project repository developed during my internship, where I applied core data analysis and machine learning skills across three real-world problems: data cleaning, regression modeling, and fraud detection. These projects demonstrate my ability to handle raw data, engineer features, build models, and think critically about real-time applications and scalability.

---

## 🔹 Project 1: Airbnb NYC – Data Cleaning

**Objective:**  
Clean and prepare Airbnb listings data for analysis by addressing inconsistencies, missing values, outliers, and duplicates.

**Key Steps:**
- Checked for missing values and filled or left them strategically (e.g., 0 for `reviews_per_month`, `NaT` for `last_review`)
- Identified and removed duplicate rows
- Standardized column names and string data
- Detected and optionally removed outliers using IQR method

**Tech Stack:**  
`Pandas`, `NumPy`, `Seaborn`, `Matplotlib`

📁 [`Project Notebook`](./L1P3_Cleaning_Data/main.ipynb)

---

## 🔹 Project 2: House Price Prediction – Linear Regression

**Objective:**  
Build a linear regression model to predict house prices using a cleaned numerical dataset.

**Key Steps:**
- Performed EDA and correlation analysis to select impactful features
- Split data into training and testing sets
- Trained a model using `LinearRegression` from `sklearn`
- Evaluated using metrics like Mean Squared Error (MSE) and R²
- Visualized prediction results with scatter plots and line charts

**Tech Stack:**  
`Pandas`, `Scikit-learn`, `Seaborn`, `Matplotlib`

📁 [`Project Notebook`](./L2P1_House_Price_Prediction_LR/main.ipynb)

---

## 🔹 Project 3: Fraud Detection – Logistic Regression

**Objective:**  
Detect fraudulent transactions using a binary classification model and evaluate under class imbalance conditions.

**Key Steps:**
- Detected fraud as an anomaly class in highly imbalanced data
- Used Logistic Regression to train a lightweight and scalable model
- Applied `StandardScaler` for feature normalization
- Evaluated model using **AUPRC** instead of standard AUC due to the imbalance
- Designed a strategy for real-time monitoring (using APIs like Flask/FastAPI) and discussed scalability through batch/cloud deployment

**Tech Stack:**  
`Pandas`, `Scikit-learn`, `StandardScaler`, `Precision-Recall metrics`

📁 [`Project Notebook`](./L3P2_Fraud_Detection/main.ipynb)

---

## 🚀 Skills Demonstrated

- 🧹 Data Cleaning & Preprocessing  
- 📈 Regression & Classification Modeling  
- 📊 Data Visualization & Interpretation  
- 📦 Model Evaluation & Deployment Thinking  
- ⚙️ Feature Engineering  
- 🌐 Real-Time & Scalable Design Thinking

---

## 📽️ Project Video Scripts

Each project is accompanied by a short explanation video which you can find in my Linked In. The videos cover:
- Project objectives
- Technical steps
- Insights and learnings

---

## 📬 Contact

**Ujjwal Karki**  
📍 Kathmandu | 📧 [LinkedIn](https://www.linkedin.com/in/ujjwal-karki-871b592a9/)  
This repo was created as part of my internship deliverables and showcases my end-to-end data analysis workflow.

---

