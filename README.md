# Loan Approval Prediction and Visualization Project

## 📝 Project Overview
This project integrates **Machine Learning** and **Power BI** to **predict loan approvals** and provide **interactive visualizations** for detailed analysis.  
Built using **Python (Pandas, NumPy, Scikit-learn)** for model development and **Power BI** for dashboard visualization, it helps financial institutions analyze patterns and make **data-driven loan approval decisions**.

---

## ⚙️ Key Features

### 🔎 Machine Learning
- **Algorithm Used:** Random Forest Classifier
- **Target Variable:** Loan_Status (Approved / Not Approved)
- **Preprocessing Steps:**
  - Filled missing values (LoanAmount, Credit_History, etc.)
  - Applied Label Encoding for categorical variables
  - Feature Scaling on numeric columns
- **Model Performance:**
  - **Accuracy:** 76.4%
  - **Precision:** 75.2%
  - **Recall:** 95%
  - **F1-Score:** 83.9%

---

### 📊 Dashboard Features (Power BI)
- **Overview Metrics:** Total Applications, Approved Loans, Approval Rate, Average Loan Amount
- **Interactive Filters:** Property Area, Credit History, Education, Income Category
- **Loan Amount vs Income Scatter Plot:** Visualizes the relationship between income and approved loan amounts
- **Income & Dependents Analysis:** Shows how family size and income affect approval chances
- **Time Series Trends:** Tracks loan amount trends by Year, Quarter, and Month
- **Approval Rate Breakdown:** Donut charts by income category for easy comparison

---

## 🗼️ Screenshots & Explanations

1️⃣ **Main Dashboard** → View of total applications, approval rate, average loan amount.
![image](https://github.com/user-attachments/assets/dfe5babc-f4de-4d9e-aea8-6965cc1f8aa2)

2️⃣ **Loan vs Income Plot** → See income trends affecting approval.  
![image](https://github.com/user-attachments/assets/d56fa39e-bc4f-4a22-b219-a81a4532ba46)

3️⃣ **Trend Charts** → Analyze how approvals change over months and years.
![image](https://github.com/user-attachments/assets/ec7a834c-c52b-4d2d-82b8-00b45445f3e5)

---

## ✅ Usefulness
- Helps loan managers and analysts understand approval trends.
- Provides **AI-based approval predictions** for better decision-making.
- Offers **interactive, filterable visuals** for granular analysis.

---

## 🚀 Step-by-Step Guide (For Beginners)

### 📁 1. Dataset
- Use **Loan Prediction Dataset** (Kaggle / public dataset of your choice).
- Includes: Loan_ID, Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, LoanAmount, Credit_History, Property_Area, Loan_Status.

### 🖥️ 2. Machine Learning (Python)
1. Clean missing data.
2. Encode categorical columns (LabelEncoder/OneHotEncoder).
3. Feature scaling using StandardScaler.
4. Train-test split (80:20).
5. Apply **Random Forest Classifier**.
6. Evaluate: Accuracy, Precision, Recall, F1-Score.

### 📊 3. Power BI
1. Import **preprocessed dataset with predictions** into Power BI.
2. Create cards, slicers, scatter plots, bar charts, donut charts, and line charts.
3. Format visuals for clarity and interactivity.
4. (Optional) Publish to **Power BI Service** or share `.pbix` via GitHub/Drive.

---

## 📂 Files Included
- `Loan_Prediction_Model.ipynb` → ML model training and evaluation
- `Loan_Approval_Dashboard.pbix` → Power BI interactive report
- `loan_dataset.csv` → Cleaned dataset with predictions
- `/images/` → Dashboard screenshots
- `README.md` → This file

---


---

## 📈 Future Enhancements
- Add feature importance visualizations for model explainability.
- Integrate with live data APIs.
- Deploy predictive model as a web service for real-time predictions.
