# 📊 Customer Behavior Analytics Project

A complete end-to-end data analytics project analyzing customer behavior and purchasing patterns.  
The project covers **Python EDA**, **data cleaning**, **SQL analysis using MySQL**, and a fully interactive **Power BI dashboard**.

---

## 📘 Overview
The goal of this project is to understand how different customer groups behave in terms of:
- Purchase amounts  
- Subscription status  
- Product category preferences  
- Age-wise revenue contribution  
- Customer distribution  

This analysis helps businesses identify high-value segments, optimize marketing strategies, and improve customer experience.

---

## 📂 Dataset
The dataset contains detailed customer information, including:

- `customer_id`  
- `gender`  
- `age_group`  
- `category`  
- `purchase_amount`  
- `review_rating`  
- `subscription_status`  
- `shipping_type`  

File used: **customer_behavior.csv**

---

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **MySQL Server:** SQL queries for deeper analysis  
- **Power BI Desktop:** Dashboard creation  
- **Excel (optional):** Quick review and formatting  
- **Jupyter Notebook / VS Code**

---

## 🚀 Steps Followed

### **1. Data Loading (Python)**
- Loaded dataset using Pandas  
- Verified data types, structure, and record counts  

### **2. Exploratory Data Analysis (EDA)**
- Summary statistics  
- Distribution of customers by gender, age, and category  
- Revenue and review rating analysis  
- Outlier detection and pattern identification  

### **3. Data Cleaning**
- Handled missing values  
- Removed duplicates  
- Normalized inconsistent category entries  
- Converted data types  
- Created new calculated columns (if required)

### **4. SQL Analysis in MySQL**
Performed SQL queries such as:
- Customer count by gender and category  
- Revenue by age group  
- Top purchasing segments  
- Subscription vs non-subscription spend  
- Category-wise purchase frequency  

### **5. Power BI Dashboard Development**
Created an interactive dashboard containing:
- Total Customers  
- Average Purchase Amount  
- Average Review Rating  
- Subscription Status Distribution  
- Revenue by Category  
- Sales by Category  
- Revenue by Age Group  
- Filters for Subscription, Gender, Category, Shipping Type  

Dashboard Preview:  
*(Insert your dashboard image here)*  
`![Customer Behavior Dashboard](Customer_Behavior_Dashbord.png)`

---

## 📈 Key Results & Insights
- Clothing is the highest revenue-generating category  
- Young Adults contribute the highest purchase amount  
- 73% of customers are not subscribed  
- Review rating averages around **3.75**  
- Accessories and Clothing categories drive most of the sales  

---


pip install pandas numpy matplotlib seaborn
