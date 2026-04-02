# 📊 Customer Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL-green)
![Power BI](https://img.shields.io/badge/Tool-PowerBI-yellow)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Overview
This project performs an **end-to-end data analysis** on customer shopping behavior using transactional data from **3,900 purchases**.

The goal is to extract meaningful insights into:
- Customer segments  
- Spending patterns  
- Product preferences  
- Subscription behavior  

Designed to demonstrate a **real-world data analytics workflow** using Python, SQL, and Power BI.

---

## 📂 Dataset
- **Records:** 3,900  
- **Features:** 18  

### 🔑 Key Attributes:
- **Demographics:** Age, Gender, Location, Subscription Status  
- **Purchases:** Item, Category, Amount, Season, Size, Color  
- **Behavior:** Discounts, Purchase Frequency, Review Rating, Shipping Type  

### ⚠️ Data Issues:
- 37 missing values in **Review Rating**
- Handled using **median imputation (category-wise)**

---

## 🛠️ Tech Stack

| Tool        | Purpose                     |
|------------|----------------------------|
| Python     | Data Cleaning & EDA        |
| Pandas     | Data Manipulation          |
| PostgreSQL | SQL Analysis               |
| Power BI   | Dashboard Creation         |
| Gamma      | Presentation               |

---

## 🔍 Workflow

### 🧩 1. Data Loading
- Imported dataset using Pandas  
- Used `.info()` and `.describe()` for inspection  

### 🧹 2. Data Cleaning
- Handled missing values  
- Converted column names to `snake_case`  
- Removed redundant column `promo_code_used`  

### ⚙️ 3. Feature Engineering
- Created `age_group`  
- Derived `purchase_frequency_days`  

### 📊 4. Exploratory Data Analysis (EDA)
- Identified trends and patterns  
- Visualized insights using charts  

### 🗄️ 5. SQL Analysis
Performed business queries:
- Revenue by gender  
- High-spending discount users  
- Top-rated products  
- Shipping type comparison  
- Subscriber vs non-subscriber analysis  
- Customer segmentation  
- Top products per category  
- Revenue by age group  

### 📈 6. Dashboard
- Built interactive Power BI dashboard  
- Includes KPIs, filters, and trend analysis  

![Customer Behavior Dashboard](/Images/customer_behaviour_dashboard.png)
---

## 📊 Key Insights

- Male customers generate higher revenue  
- Express shipping users spend more on average  
- Non-subscribers contribute higher total revenue  
- Majority of customers are loyal  
- Some products are highly discount-driven  

---

## 💡 Business Recommendations

- Promote subscription benefits  
- Implement loyalty programs  
- Optimize discount strategies  
- Highlight top-rated products  
- Target high-value customer segments  

---
## ▶️ How to Run

### 1. Clone Repository
```bash
git clone https://github.com/HarishKumar2211/customer-shopping-analysis.git
cd customer-shopping-analysis
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Python Analysis
```bash
jupyter notebook
```

### 4. SQL Setup
Import dataset into PostgreSQL
Run queries from /sql folder

### 5. View Dashboard
Open .pbix file in Power BI Desktop


## 📁 Project Structure

```bash
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── reports/
├── presentation/
├── requirements.txt
└── README.md

```
## Future Improvements

- Automate ETL pipeline
- Deploy dashboard online
- Integrate real-time data


## Author

Harish Kumar

- **GitHub:** [https://github.com/HarishKumar2211](https://github.com/HarishKumar2211)
- **LinkedIn:** [Harish Kumar S K](https://www.linkedin.com/in/harish-kumar-s-k-32a273310/)
