# 🛍️ Amazon Product Review Analysis – DSA Capstone

Hi! I’m Christina Akindino, and this project is one half of my capstone for the DSA Data Analysis Bootcamp. In this case study, I stepped into the shoes of a Junior Data Analyst at a company called **RetailTech Insights**, helping them uncover insights from a dataset of **1,465 Amazon products**.

The goal? Use data to guide smarter product decisions — what sells, what performs well, and what customers really value.

---

## 🎯 Project Goal

To explore and analyze product listings and review data scraped from Amazon. Each row in the dataset represents a product, with attributes like:
- Product name & category
- Actual price vs discounted price
- Ratings and rating count
- Customer reviews (summarized)

My mission was to turn this raw dataset into insights using **Microsoft Excel** — through PivotTables, formulas, and a dashboard.

---

## 🛠 Tools I Used
- Microsoft Excel  
- PivotTables & PivotCharts  
- Calculated Columns (Formulas)  
- Slicers for interactivity  
- Basic data cleaning (LEFT, PROPER, Text-to-Columns)

---

## 🧪 The Process

I started by cleaning the data — removing text clutter, formatting inconsistent names, and building calculated columns that added real business value.

Some of the new columns I created:
- **Discount %** – How much is the price reduced?
- **Potential Revenue** – What would the product earn if every reviewer bought it?
- **High Discount** – A flag to help me identify products with ≥50% discount
- **Price Bucket** – To group products as `<₦200`, `₦200–₦500`, or `>₦500`
- **Weighted Score** – A combo of rating * rating count to highlight popular + well-loved items

---

## 📊 Questions I Answered

Using PivotTables and a few smart formulas, I answered 14 key questions:

1. What’s the **average discount %** per category?
2. How many products are listed under each category?
3. What’s the **total number of reviews** per category?
4. Which products have the **highest average ratings**?
5. What’s the **average actual price vs discounted price** by category?
6. Which products have the **highest number of reviews**?
7. How many products offer **50% discount or more**?
8. What’s the **distribution of ratings** (e.g., how many are rated 3.0, 4.0, etc.)?
9. What’s the **potential revenue** by category?
10. How many products fall into each **price bucket**?
11. Is there a relationship between **rating and discount level**?
12. How many products have **fewer than 1,000 reviews**?
13. Which **categories have the highest discounts**?
14. What are the **top 5 products** based on rating × review count?

---

## 📈 My Dashboard

I pulled everything together into a clean, interactive Excel dashboard. It includes:
- 📊 PivotCharts for top-selling categories and price buckets
- 📌 KPI cards for total revenue and average discount
- ⭐ A scatter chart showing the link (or lack of one!) between discount % and customer rating
- 🔄 Slicers to filter by category and price segment

---

## 🧠 What I Learned

This project reminded me that **numbers don’t speak unless we make them**.  
Some products had great discounts but poor ratings. Others had glowing reviews and zero discount — yet still performed well. Through calculated fields and Pivot magic, I learned how to connect the dots between **pricing**, **popularity**, and **perceived value**.

---

## 📂 Files Included

- `Amazon Case Study.xlsx` – cleaned dataset, all PivotTables, dashboard
- (Optional) `README.md` – you're reading it 😊

---

## 💬 Final Thoughts

This was a fun and practical project. It sharpened my Excel skills and reminded me how much value there is in "simple" analysis when it's done well.

Thanks for reading!

— **Christina Akindino**  
Junior Data Analyst | July 2025  



