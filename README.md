# BigBasket Product Analysis


**Author:** Niranjan  
**Date:** 5 May 2025  

---

## Project Background

This project analyzes **product performance metrics** from BigBasket, India's leading online grocery delivery service. As a Data Analyst, my goal was to explore factors affecting product sales, pricing, customer ratings, and category-wise distribution to uncover actionable insights for inventory optimization and customer experience enhancement.

BigBasket (Supermarket Grocery Supplies Pvt. Ltd.), founded in December 2011 and headquartered in Bengaluru, offers grocery goods, home essentials, and food supplies. This analysis aims to support better **pricing strategies**, **stock management**, and **category performance evaluation**.

---

## Dataset Description

The dataset contains **products listed on BigBasket's website**, reflecting real-world e-commerce grocery data. It includes:

- Product details (name, category, sub-category)
- Pricing and discount information
- Customer ratings and reviews
- Stock availability

Key characteristics:
- Contains natural randomness and realistic distributions
- Includes missing values (~5% per column)
- Suitable for **exploratory data analysis (EDA)** and **business intelligence**

---

## Data Structure

| Column Name           | Description                                                               |
|-----------------------|---------------------------------------------------------------------------|
| Product_Name          | Name of the product (e.g., "Apple - Washington")                          |
| Category              | Main product category (e.g., "Fruits & Vegetables")                       |
| Sub_Category          | Sub-category (e.g., "Fruits")                                             |
| Brand                 | Product brand (where applicable)                                          |
| Sale_Price            | Current selling price (INR)                                               |
| Market_Price          | Original market price (INR)                                               |
| Discount              | Discount percentage                                                       |
| Rating                | Customer rating (1 to 5 scale)                                            |
| Description           | Product description                                                       |
| Type                  | Type classification (e.g., "Organic")                                     |

---

## Executive Summary

### Key Highlights

- **Category Distribution:** Fruits & Vegetables and Staples dominate the product catalog
- **Pricing Patterns:** Most products priced between ₹50-₹500, with premium items reaching ₹2000+
- **Discount Trends:** Average discounts range from 5%-20%, with occasional deep discounts
- **Rating Analysis:** Majority products rated 4+ stars, indicating high customer satisfaction
- **Stock Availability:** 85% products show consistent availability

---

## Data Cleaning Steps

- ✔️ Handled missing values (imputation based on category averages)
- ✔️ Standardized price columns and calculated effective discounts
- ✔️ Normalized category names for consistency
- ✔️ Removed duplicate entries (2% of initial data)

---

## Next Steps

- **Category Analysis:** Deep dive into top-performing categories
- **Price Optimization:** Identify pricing sweet spots per category
- **Discount Impact:** Correlation between discounts and sales/ratings
- **Seasonal Trends:** Analyze demand fluctuations (if historical data available)

---

## Assumptions & Caveats

- Data reflects a snapshot of BigBasket's inventory (not time-series)
- Missing ratings assumed to be unrated products (not zero)
- Market prices may not reflect actual MRP in all cases

---

## 📬 Contact

For queries or collaborations:  
- **Email:** niranjan991100@gmail.com  
- **LinkedIn:** [Niranjan's Profile](https://www.linkedin.com/in/niranjan-k-a83517229/)
