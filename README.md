# Customer Shopping Behavior Analysis
Analyzing cutomer shopping behavior

## 📌 Project Overview
[cite_start]This project analyzes the shopping habits and preferences of 3,900 customers across various product categories[cite: 3]. [cite_start]By examining transactional data, the goal is to uncover key patterns in spending, product preferences, and customer loyalty to guide strategic business decisions and marketing efforts[cite: 4].

[cite_start]The analysis follows a full data lifecycle: from initial **data cleaning and preparation** in Python, to **advanced querying** in SQL, and finally to **visual storytelling** through an interactive Power BI dashboard[cite: 14, 110, 111, 145].

---

## 🛠️ Tools & Technologies Used
* [cite_start]**Python (Pandas):** Used for data cleaning, handling missing values, and feature engineering[cite: 15, 92, 96].
* [cite_start]**PostgreSQL:** Used for structured data analysis and answering specific business questions[cite: 111, 112].
* [cite_start]**Power BI:** Used to create an interactive dashboard for visualizing trends and KPIs[cite: 144, 145].
* [cite_start]**SQLAlchemy:** Used to connect the Python environment with the PostgreSQL database[cite: 110].

---

## 📊 Key Insights & Findings
The analysis revealed several actionable insights regarding customer interaction:

* [cite_start]**Revenue Drivers:** Male customers generated significantly higher total revenue ($157,890) compared to female customers ($75,191)[cite: 119, 122].
* [cite_start]**Customer Loyalty:** The majority of the customer base is classified as **"Loyal"** (3,116 customers), followed by **"Returning"** (701) and **"New"** (83) segments[cite: 136].
* [cite_start]**Subscription Impact:** Approximately 27% of customers are subscribers[cite: 157]. [cite_start]Non-subscribers actually have a slightly higher average spend ($59.87) than subscribers ($59.49)[cite: 132].
* [cite_start]**Product Performance:** **Clothing** is the top category by revenue [cite: 162][cite_start], with **Blouses** and **Jewelry** being among the most frequently purchased items[cite: 18, 141].
* [cite_start]**Age Groups:** **Young Adults** represent the highest revenue-contributing age group at $62,143[cite: 143].

---

## 📈 What Was Done
1.  [cite_start]**Data Preparation:** Cleaned the dataset by checking for null values and imputing missing **Review Ratings** using the median rating of each product category[cite: 92, 93].
2.  [cite_start]**Feature Engineering:** Created an `age_group` column for better demographic marketing and mapped text-based purchase frequencies to numerical values for easier analysis[cite: 100, 101].
3.  [cite_start]**Business Intelligence:** Used SQL to identify high-spending discount users, compare shipping types, and determine which products are most "discount-dependent"[cite: 123, 129, 133].
4.  [cite_start]**Dashboard Creation:** Developed a visual dashboard featuring high-level KPIs like **Average Purchase Amount ($59.76)** and **Average Review Rating (3.75)**[cite: 151, 152].

[Image of a retail customer behavior dashboard showing sales trends and demographics]
