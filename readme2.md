# Background

A Direct-to-Consumer (D2C) fashion brand selling clothing, accessories, footwear, and outerwear across the United States has grown to nearly **3,900 customers**. While the business collects rich transactional and behavioral data, it lacks a structured approach to understanding **who its most valuable customers are**, **how much revenue depends on promotions**, and **which customers should be retained through pricing versus experience**.

Without these insights, promotional campaigns are applied broadly, increasing marketing costs while potentially eroding margins and attracting short-term bargain hunters instead of long-term loyal customers.

This project demonstrates how analytics can convert customer data into strategic business decisions using **Python** and **SQL**

---

# Problem Statement

Using only transactional and behavioral customer data, the objective was to:

* Identify the brand's highest value customer segments.
* Measure how dependent current revenue is on discounts and promo codes.
* Understand which customer behaviors predict long-term loyalty.
* Identify geographical and product category opportunities.
* Build a data backed retention strategy that reduces promotional dependency **without negatively impacting sales**.

---

# Key Business Questions

This project answers the following business questions:

* Who are genuinely loyal customers versus customers who only purchase during promotions?
* What customer behaviors are associated with long-term value?
* Which product categories and regions create repeat customers?
* Which customer segments should continue receiving promotions?
* What does the brand's ideal customer profile look like?


---

# 📊 Key Insights

### 📌 Promotions are subsidizing already loyal customers

Nearly **46.1% of the brand's most loyal customers** still receive discounts or promo codes despite already exhibiting strong purchase frequency and long purchase histories. This indicates that a significant portion of promotional spend is reducing margins without materially increasing retention. 

---

### 📌 Organic loyalty is the strongest predictor of long-term customer value

Customers who combine:

* High purchase frequency
* Strong purchase history
* High review ratings
* No promotional dependency

represent the brand's highest-quality customers and generate sustainable long-term value. 

---

### 📌 Premium experiences outperform discounts

The highest-value customers consistently preferred:

* Credit Card payments
* Express or Next Day Air shipping
* Clothing and Accessories
* High review ratings
* Purchasing without discounts

These customers prioritize convenience and product experience over promotional offers. 

---

### 📌 Blanket promotions reduce profitability

Promotions should not be applied uniformly across the customer base. Instead, promotional investment should be concentrated on acquisition and re-engagement while gradually reducing discounts for customers who already exhibit strong loyalty. 

---

# 💡 Business Recommendations

## 1. Implement a Promotional Sunset Strategy

Rather than removing promotions immediately, introduce a phased rollout:

* **Phase 1:** Remove promotional eligibility for the highest-tenure loyal customers (>40 previous purchases).
* **Phase 2:** Expand the program to the remaining loyal customers while replacing discounts with experiential benefits such as express shipping, early access to collections, or loyalty recognition.
* **Phase 3:** Redirect the promotional budget toward acquiring new customers and re-engaging high-potential standard customers.

This strategy improves profitability while minimizing churn risk through controlled experimentation and continuous monitoring. 

---

## 2. Focus acquisition on the Ideal Customer Profile

The analysis identified an **Organic High-Value Customer** profile:

* Age: **37–52 years**
* Primary Category: **Clothing**
* Secondary Category: **Accessories**
* Preferred Payment: **Credit Card**
* Preferred Shipping: **Express / Next Day Air**
* Review Rating: **Above 4.0**
* More than **25 previous purchases**
* No dependence on promotions

Marketing campaigns should prioritize acquiring more customers with similar characteristics rather than maximizing short-term promotional conversions. 

---

## 3. Shift promotional investment toward long-term growth

Instead of using discounts as the default retention strategy:

* Invest in customer experience.
* Use promotions selectively for customer acquisition and reactivation.
* Replace discounts for loyal customers with premium service benefits.
* Measure success using repeat purchase rate, average order value, and churn after promotion removal. 

---

# 📈 Business Impact

This project demonstrates how customer analytics can support strategic decision-making by:

* Identifying genuinely loyal customer segments.
* Measuring revenue dependence on promotions.
* Reducing unnecessary promotional spending.
* Improving customer acquisition targeting.
* Supporting long-term customer retention through evidence-based recommendations.

---

# 🛠️ Tech Stack

* **Python** – Data Cleaning, Feature Engineering & Exploratory Analysis
* **SQL** – Customer Segmentation & Business Analytics
* **Tableau** – Executive Dashboard & Business Intelligence

---

# 📂 Repository Structure

```text
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   ├── data_preparation.ipynb
│   └── feature_engineering.ipynb
│
├── sql/
│   └── customer_segmentation.sql
│
├── dashboard/
│   └── Customer_Value_Dashboard.twbx
│
├── reports/
│   ├── Problem_Statement.pdf
│   └── Retention_Playbook.pdf
│
└── README.md
```

---

## 🚀 Skills Demonstrated

* Customer Segmentation
* Business Analytics
* SQL for Decision Support
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization (Tableau)
* Executive Dashboard Design
* Business Strategy & Retention Analytics
* Product Thinking
* Data Storytelling

---

This version reads like a consulting case study rather than a class project. It starts with the business context, frames the analytical challenge, explains the workflow, presents key findings, and finishes with actionable recommendations—making it well suited for recruiters reviewing your GitHub portfolio.
