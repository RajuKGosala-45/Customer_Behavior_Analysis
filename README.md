# Customer_Behavior_Analysis
Data Analytics Project showcasing Customer behavior analysis using Python, SQL and PowerBI.
#  End-to-End Customer Shopping Behavior Analysis

##  Overview
This project explores **customer shopping behavior** using transactional retail data to uncover spending patterns, product preferences, and subscription trends.  
It demonstrates an end-to-end data analytics workflow involving **Python (EDA & Cleaning)**, **SQL (PostgreSQL/MySQL)**, **Power BI**, and **Gamma** for reporting and presentation.

The goal is to help businesses enhance **customer segmentation**, **marketing strategies**, and **revenue outcomes** through data-driven insights.

---

## 📂 Dataset Summary
| Property | Description |
|-----------|--------------|
| **Rows** | 3,900 |
| **Columns** | 18 |
| **Type** | Transactional retail data |
| **Database Used** | MySQL |
| **Key Attributes** | Customer_ID, Age, Gender, Location, Subscription_Status, Item_Purchased, Category, Purchase_Amount, Season, Discount_Applied, Promo_Code_Used, Review_Rating, Shipping_Type |

###  Feature Highlights
- **Demographics:** Age, Gender, Location  
- **Behavioral Patterns:** Frequency of purchases, previous orders, discount usage  
- **Transaction Details:** Amount, category, review ratings, shipping type  
- **Subscription Insight:** Comparison of subscribers vs. non-subscribers  

---

##  Tools & Technologies
- **Python:** Data loading, cleaning, feature engineering, and EDA  
- **SQL (PostgreSQL/MySQL):** Querying, aggregations, and insights generation  
- **Power BI:** Interactive dashboard creation  
- **Gamma:** Automated business report and PPT generation  

---

## ⚙️ Project Steps

### 1️⃣ Data Preparation (Python)
- Imported dataset using `pandas.read_csv()`.  
- Cleaned null values (37 missing review_ratings imputed using median per category).  
- Standardized column names (snake_case).  
- Created new features like `age_group` and `purchase_frequency_days`.  
- Dropped redundant columns and validated categorical/numeric consistency.  
- Loaded cleaned data into PostgreSQL using **SQLAlchemy**.

### 2️⃣ SQL Analysis (Business Queries)
Key analytical SQL queries performed:
1. Revenue by Gender  
2. High-Spending Discount Users  
3. Top 5 Products by Rating  
4. Shipping Type Comparison (Standard vs. Express)  
5. Subscribers vs. Non-Subscribers  
6. Discount-Dependent Products  
7. Customer Segmentation (New, Returning, Loyal)  
8. Top 3 Products per Category  
9. Repeat Buyers & Subscriptions  
10. Revenue by Age Group  

### 3️⃣ Dashboard Development (Power BI)
Built an interactive dashboard visualizing:
- **Revenue Breakdown:** by gender, subscription, and age group  
- **Product Performance:** top-rated and best-selling categories  
- **Customer Segments:** new, returning, and loyal customers  
- **Discount & Shipping Insights:** cost vs. performance comparisons  

📊 **Dashboard Features:**
- Dynamic filters for season, category, and location  
- Drill-through options for detailed product insights  
- KPIs for Total Revenue, Avg. Purchase Value, Repeat Buyer %  

### 4️⃣ Presentation & Reporting (Gamma)
- Automated report summarizing workflow, insights, and recommendations  
- PPT visual storytelling for business communication  

---

## 📈 Results & Insights

### Key Insights
- Female customers generated slightly higher total revenue  
- Express shipping users spent **25% more** on average  
- Subscribers showed higher **lifetime value (LTV)**  
- Discount-heavy categories reduced profit margins  
- Loyal customers provided the most consistent revenue stream  

### Business Recommendations
1. **Boost Subscriptions** with exclusive deals for high-value customers  
2. **Enhance Loyalty Programs** with tier-based benefits  
3. **Optimize Discount Strategy** — focus on low-performing items  
4. **Promote Top-Rated Products** in marketing campaigns  
5. **Target Key Demographics** (ages 25–40, fast-shipping users)

---

## 🧾 Project Outcomes
| Area | Outcome |
|-------|----------|
| **Data Cleaning** | Improved data quality and consistency |
| **SQL Analysis** | Derived 10+ actionable business insights |
| **Dashboard** | Created an executive-level Power BI report |
| **Business Impact** | Identified high-value customer segments & cost-saving opportunities |

---

## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/customer-shopping-analysis.git
   cd customer-shopping-analysis
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook EDA_and_Cleaning.ipynb
   ```
4. **Execute SQL queries**
   - Import `cleaned_data.csv` into MySQL/PostgreSQL  
   - Run queries from `SQL_Analysis.sql`
5. **View Power BI Dashboard**
   - Open the `.pbix` file in Power BI Desktop  
6. **View Gamma Report**
   - Access the `.gamma` file or link for the final presentation  

---

##  Key Learnings
- End-to-end analytics using Python, SQL, and BI tools  
- Data-driven decision-making through storytelling dashboards  
- Experience in building **real-world business intelligence pipelines**
