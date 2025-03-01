# Telecom-Customer-Churn
# Telecom Customer Churn Analysis

## 📌 Project Overview
This project analyzes customer churn in a telecom company using **Python and Tableau**. The goal is to identify key factors contributing to churn, build predictive models, and provide actionable insights for customer retention.

## 📂 Project Structure
```
📁 Telecom-Customer-Churn-Analysis
│── 📜 README.md  (Project Documentation)
│── 📜 telecom_churn_analysis.py  (Python Script for Data Analysis & ML Model)
│── 📜 churn_dashboard.twb  (Tableau Dashboard - Visual Insights)
│── 📂 data
│   ├── WA_Fn-UseC_-Telco-Customer-Churn.csv  (Dataset)
```

## 📊 Data Overview
The dataset consists of **7,043 customer records** with **21 attributes**, including:
- **Demographics**: Gender, Senior Citizen, Partner, Dependents
- **Service Details**: Phone Service, Internet Service, Streaming, Security, etc.
- **Billing Information**: Contract Type, Monthly Charges, Payment Method
- **Churn**: Whether the customer left the company

## 🔍 Analysis Approach
### **1️⃣ Data Preprocessing (Python)**
✔ Convert `TotalCharges` from object to numeric & handle missing values.  
✔ Encode categorical variables for machine learning.  
✔ Split dataset into training and test sets.

### **2️⃣ Exploratory Data Analysis (Python & Tableau)**
✔ Identify churn distribution across contract types, payment methods, and service types.  
✔ Visualize key churn trends using Tableau.

### **3️⃣ Predictive Modeling (Python)**
✔ Train **Random Forest Classifier** to predict churn.  
✔ Evaluate model accuracy, precision, and recall.  
✔ Identify top features affecting churn.

### **4️⃣ Interactive Dashboard (Tableau)**
✔ Create interactive dashboards to explore customer churn insights.  
✔ Identify high-risk customer segments.  
✔ Provide strategic recommendations for retention.

## 📌 Key Findings & Recommendations
- **Customers with Month-to-Month contracts have the highest churn** → Offer contract incentives.
- **Fiber Optic users churn the most** → Improve service quality & pricing strategies.
- **Electronic check payments lead to higher churn** → Encourage alternative payment methods.
- **High Monthly Charges ($81-$110) correlate with churn** → Introduce loyalty discounts.

## 🚀 How to Run the Project
### **🔹 Running the Python Script**
```bash
pip install pandas numpy seaborn scikit-learn matplotlib
python telecom_churn_analysis.py
```

### **🔹 Viewing the Tableau Dashboard**
1. Open `churn_dashboard.twb` in Tableau.
2. Explore interactive insights & customer segmentation.

## 🤝 Contributing
Feel free to fork this repository and contribute improvements!

## 📩 Contact
🔹 **Author**: Deborah Deva Kirubai M  
🔹 **LinkedIn**: https://linkedin.com/in/deborah-deva-kirubai-m  
🔹 **GitHub**: https://github.com/Debbie2810

