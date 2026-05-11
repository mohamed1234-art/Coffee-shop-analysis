# ☕ Coffee Sales Analysis | Excel Project

## 📌 Project Overview

This project focuses on analyzing coffee shop sales data using **Excel** to uncover customer behavior, sales trends, product performance, and operational insights.

The analysis transforms raw transaction data into meaningful business insights that help improve revenue, customer experience, and decision-making.

The project includes:

* Data Cleaning
* Data Modeling
* KPI Analysis
* Trend Analysis
* Customer Behavior Analysis
* Interactive Reporting

---

# 📊 Key Business Metrics

* 💰 Total Sales: **42,627 EGP**
* 🧾 Total Orders: **1,313**
* ☕ Product Types: **8**
* 💵 Average Order Value: **~32.5 EGP**

---

# 📈 Business Insights

## ☀️ Peak Sales Time

Morning sales significantly outperform the rest of the day.

### Insight

The business is heavily driven by:

* Employees
* Students
* Morning routines

### Business Impact

Morning hours require:

* Full staffing
* Faster service
* Strong inventory availability

---

## 📅 Seasonal Trends

### Insights

* 📈 **May** is the highest-performing month
* Strong growth during **March & April**
* Gradual decline from **June → August**

### Business Impact

Summer season negatively impacts hot beverage sales.

---

## 📆 Customer Behavior Analysis

### Insights

* 📌 **Tuesday** is the busiest day
* 📉 **Sunday & Monday** are the slowest days

### Business Impact

Operations and promotions can be optimized based on customer traffic patterns.

---

# ☕ Product Performance Analysis

## 🥇 Best-Selling Products

1. Latte / Americano with Milk
2. Cappuccino
3. Americano

## ⬇️ Lowest-Performing Products

* Espresso
* Cocoa

### Business Impact

Milk-based beverages are the primary revenue drivers.

---

# 💳 Payment Method Analysis

### Insights

* 💳 Card Payments: **93%**
* 💵 Cash Payments: **7%**

### Business Impact

Customers strongly prefer digital payments, improving:

* Transaction speed
* Operational efficiency
* Customer convenience

---

# 🎯 Key Business Conclusions

✔️ The coffee shop is a **morning-driven business**
✔️ Milk-based drinks generate the highest sales
✔️ Seasonal patterns strongly affect performance
✔️ Digital payment adoption is extremely high

---

# 💡 Business Recommendations

## 🔥 Increase Revenue

* Create morning combo offers

  * Coffee + bakery items
* Increase staffing during peak hours
* Ensure product availability during busy periods

---

## ❄️ Reduce Summer Decline

Introduce seasonal cold beverages:

* Iced Latte
* Cold Brew
* Frappuccino

Launch summer promotions and discounts.

---

## ☕ Product Strategy

* Focus marketing campaigns on top-selling products
* Improve low-performing products
* Create bundles to increase product visibility

---

## 💳 Payment Experience

* Maintain fast digital payment systems
* Add modern payment methods:

  * Wallets
  * Contactless payments

---

# 📊 Future Improvements

* Build a customer loyalty program
* Analyze profitability and margins
* Forecast future sales trends
* Add customer segmentation analysis

---

# 🧩 Data Modeling & Star Schema

## 🔹 Data Source Fields

The raw dataset includes:

* `date` → Transaction date
* `datetime` → Full timestamp
* `cash_type` → Payment method
* `card` → Masked card ID
* `money` → Transaction value
* `coffee_name` → Coffee type

---

# 📐 Star Schema Design

## 🟦 Fact Table

### Fact_Data

* ID
* ID_coffee
* ID_payment
* ID_hour
* date
* money

---

## 🟩 Dimension Tables

### Dim_Coffee

* ID_coffee
* coffee_name

### Dim_Payment_Method

* ID_payment
* cash_type

### Dim_Hour

* ID_hour
* Hour
* Label_hour

### Calendar

* Date
* Year
* Month Number
* Month
* MMM-YYYY

---

# 🔗 Relationships

The **Fact Table** sits at the center of the model and connects to all dimension tables using **One-to-Many Relationships**.

---

# 🛠️ Tools & Skills Used

* Microsoft Excel
* Pivot Tables
* Power Query
* Data Cleaning
* Data Modeling
* KPI Analysis
* Business Analysis
* Dashboard Design

---

# 📈 Skills Demonstrated

✅ Data Cleaning
✅ Excel Dashboard Development
✅ Business Intelligence Analysis
✅ KPI Reporting
✅ Trend Analysis
✅ Customer Behavior Analysis
✅ Data Modeling
✅ Star Schema Design

---

# 🚀 Final Conclusion

Data is not just numbers —
it tells the story of customer behavior, operational performance, and business opportunities.

Through this analysis, the coffee shop can make smarter, data-driven decisions to improve revenue, customer satisfaction, and long-term growth.
