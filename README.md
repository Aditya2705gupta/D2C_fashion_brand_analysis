# D2C_fashion_brand_analysis


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

# Key Insights

### 1. High Promotional Dependency

Approximately **46.1% of loyal customers still purchase using discounts or promo codes**, indicating that a significant portion of promotional spend is subsidizing customers who would likely purchase without incentives. 



### 2. Organic Loyalty Exists

A subset of customers demonstrates strong repeat purchasing behavior, high review ratings, and no reliance on promotions. These customers represent the brand's highest-value segment and provide the strongest long-term profitability. 



### 3. Promotions Are Not the Primary Driver of Retention

Customers with long purchase histories and frequent buying behavior continue purchasing regardless of discounts. This suggests that blanket promotional strategies reduce margins without materially improving retention. 



### 4. Ideal Customers

The highest value customers characteristics:

* Are **37–52 years old**
* Primarily purchase **Clothing**
* Frequently buy **Accessories**
* Prefer **Credit Card** payments
* Choose **Express or Next Day Air** shipping
* Maintain **review ratings above 4.0**
* Have **25+ previous purchases**
* Rarely rely on promotions 

---

# Business Recommendations

## 1. Implement a Promotional Sunset Strategy

Gradually reduce discounts for highly loyal customers who already demonstrate consistent purchasing behavior.

### Proposed Rollout

**Phase 1**

* Remove promotional eligibility from the highest-tenure loyal customers (>40 previous purchases).

**Phase 2**

* Expand to the remaining loyal customers.
* Replace discounts with loyalty benefits such as:

  * Express shipping
  * Early access to new collections
  * Loyalty recognition

**Phase 3**

* Reinvest saved promotional budget into:

  * Customer acquisition
  * Re-engaging high-potential standard customers

This phased approach minimizes churn risk while improving profitability. 

---

## 2. Acquire More Organic High-Value Customers

Focus acquisition efforts on customer profiles that naturally demonstrate long-term value instead of short-term promotional responsiveness.

Recommended strategy:

* Target customers aged **37–52**
* Lead with **Clothing** and **Accessories**
* Promote premium shipping rather than discounts
* Prioritize audiences likely to leave high review ratings
* Avoid leading acquisition campaigns with promotional offers 

---

## 3. Shift Marketing Budget Toward Long-Term Value

Instead of increasing promotional spending across all customers:

* Invest more in acquiring high-value customer segments.
* Build loyalty through customer experience rather than price reductions.
* Use promotions selectively for customer acquisition and reactivation.

---

## 4. Continuously Monitor Retention Metrics

Track:

* Repeat purchase rate
* Average order value
* Churn after promotion removal
* Revenue contribution by customer segment

These metrics provide early warning signals and help evaluate the effectiveness of the promotional strategy
