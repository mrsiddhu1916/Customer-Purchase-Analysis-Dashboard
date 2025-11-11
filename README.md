# Customer-Purchase-Analysis-Dashboard(Interactive Dashboard Using Power Bi)

## Interactive dashboards and analysis to monitor customer purchase-analysis portfolio KPIs, identify risk pockets, and drive data-backed lending decisions.

## Project Summary
This project focuses on analyzing customer shopping behavior across 10 major shopping malls in Istanbul between 2021 and 2023. The goal is to understand how gender, age, product categories, and payment methods influence customer purchasing decisions and overall revenue generation.

## 🧾 Dataset Information
The dataset includes shopping information from **10 shopping malls** and multiple customer segments.

| Attribute | Description |
|------------|-------------|
| `invoice_no` | Unique transaction ID |
| `customer_id` | Unique customer ID |
| `gender` | Gender of the customer |
| `age` | Age of the customer |
| `category` | Product category purchased |
| `quantity` | Number of units purchased |
| `price` | Unit price (in Turkish Lira - ₺) |
| `payment_method` | Mode of payment (Cash, Credit, Debit) |
| `invoice_date` | Date of transaction |
| `shopping_mall` | Mall where the purchase was made |

---
## ⚙️ Tools & Technologies
- **MySQL** – for data querying and analysis  
- **Power BI** – for data visualization and dashboard creation  
- **Excel** – for data cleaning and preprocessing  
- **Python (optional)** – for automation and formatting  

---

## 🧮 Problem Statements

1️⃣ **How is the shopping distribution according to gender?**  
2️⃣ **Which gender did we sell more products to?**  
3️⃣ **Which gender generated more revenue?**  
4️⃣ **Distribution of purchase categories relative to other columns?**  
5️⃣ **How is the shopping distribution according to age?**  
6️⃣ **Which age category did we sell more products to?**  
7️⃣ **Which age category generated more revenue?**  
8️⃣ **Distribution of purchase categories relative to other columns?**  
9️⃣ **Does the payment method have a relation with other columns?**  
🔟 **How is the distribution of the payment method?**

---

## 📈 Key Performance Indicators (KPIs)

The following KPIs were designed to measure overall shopping performance, customer demographics, and revenue contribution across malls, genders, and age groups.

| KPI | Description | Formula / Metric | Example Result |
|------|--------------|------------------|----------------|
| 🧾 **Total Transactions** | Total number of invoices or sales transactions | COUNT(invoice_no) | 99.46K |
| 👥 **Total Customers** | Unique customers who made at least one purchase | COUNT(DISTINCT customer_id) | 99.46K |
| 📦 **Total Quantity Sold** | Total items purchased across all transactions | SUM(quantity) | 298.71K |
| 💰 **Total Revenue** | Total revenue generated from all sales | SUM(price * quantity) | ₺251.51M |
| 👩‍🦰 **Female Contribution %** | Revenue share from female customers | (Female Revenue / Total Revenue) * 100 | 59.7% |
| 👨 **Male Contribution %** | Revenue share from male customers | (Male Revenue / Total Revenue) * 100 | 40.3% |
| 👵 **Top Age Group by Revenue** | Age group contributing the most revenue | Age category with MAX(SUM(price * quantity)) | 51+ (₺91M) |
| 👕 **Top Product Category** | Category with the highest total revenue | Category with MAX(SUM(price * quantity)) | Clothing (₺114.9M) |
| 💳 **Top Payment Method** | Most used payment type | Payment method with MAX(COUNT(*)) | Cash (45%) |
| 🏬 **Top Performing Mall** | Mall generating the highest sales | Shopping mall with MAX(SUM(price * quantity)) | Mall A (₺38M) |

---
## Dataset Used
- <a href="https://github.com/mrsiddhu1916/Customer-Purchase-Analysis-Dashboard/blob/main/Customer_Data.csv" >Dataset</a>

## 📊 Key Insights
- Female customers accounted for **~60%** of total sales and generated higher revenue.  
- **Senior (51+)** customers contributed the highest sales volume and revenue.  
- **Clothing** was the top-selling category, followed by **Shoes** and **Technology**.  
- **Cash payments** dominated at 45%, while **credit card** usage is steadily increasing.  
- **Shopping malls in urban areas** had higher purchase frequency.

---
## 💡 Business Recommendations
- Focus marketing efforts on **female** and **senior** segments.  
- Launch **cashback/loyalty programs** to encourage digital payments.  
- Strengthen promotions in **clothing** and **technology** categories.  
- Use **data-driven targeting** for better customer retention.

---
## 🎨 Dashboard Theme
- **Theme:** Peach/Pink Corporate  
- **Background Color:** `#FFF2F0`  
- **Title Color:** `#78283C`  
- **KPI Colors:** Coral Pink `#FF6F61`, Gold `#F4B942`, Light Blue `#A0C4FF`  

---

## 🏁 Conclusion
This project provides a complete **Customer Purchase Behavior Analysis** using Excel and SQL and Power BI.  
It helps businesses understand demographic patterns, optimize product offerings, and improve marketing strategies based on real data insights.

---

## 📂 Author
**Siddardha Kamepalli**  
_Data Analyst | SQL | Power BI | Python | Excel_



