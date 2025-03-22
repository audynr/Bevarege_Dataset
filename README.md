# Bevarege_Dataset


## Overview

This dataset simulates **realistic sales patterns** in the beverage industry, highlighting important factors such as **regional preferences**, **seasonal fluctuations**, and **customer segmentation**. It covers both **Business-to-Business (B2B)** and **Business-to-Consumer (B2C)** transactions, making it versatile for various analytical projects—ranging from **sales forecasting** to **customer behavior analysis**.

---

## Dataset Structure

| Column Name    | Description                                                                                      |
|----------------|--------------------------------------------------------------------------------------------------|
| **Order_ID**   | Unique identifier for each order. Multiple products can be grouped under the same order.        |
| **Customer_ID**| Unique identifier for each customer. Helps distinguish individual buyers or corporate entities. |
| **Customer_Type** | Indicates whether the customer is **B2B** (business-to-business) or **B2C** (business-to-consumer). |
| **Product**    | Name of the purchased product, e.g., “Coca-Cola” or “Erdinger Weißbier.”                         |
| **Category**   | Product category, e.g., **“Soft Drinks”** or **“Alcoholic Beverages.”**                          |
| **Unit_Price** | Price per unit of the product.                                                                   |
| **Quantity**   | Number of units purchased for the specified product in the order.                                |
| **Discount**   | Discount applied to the product (e.g., 0.1 for 10%). **Discounts are only given to B2B customers.** |
| **Total_Price**| Total price for the product after discounts are applied.                                         |
| **Region**     | Geographic region of the customer, e.g., **“Bayern”** or **“Berlin.”**                           |
| **Order_Date** | Date when the order was placed.                                                                  |

---

## Key Features

1. **Realistic Patterns**  
   - Incorporates regional preferences and seasonal fluctuations typical of beverage sales.

2. **Mixed Customer Segments**  
   - Includes **B2B** and **B2C** transactions to allow for diverse analytical scenarios.

3. **Multiple Product Categories**  
   - Contains different product categories (e.g., soft drinks, alcoholic beverages) for broader insights.

4. **Discount Mechanism**  
   - Only **B2B** customers receive discounts, adding complexity to pricing and margin analysis.

5. **Adaptable for Various Analyses**  
   - Suitable for **sales forecasting**, **market segmentation**, **promotional analysis**, or **customer lifetime value** studies.

---

## Usage Ideas

- **Sales Forecasting**: Use `Order_Date`, `Quantity`, and `Total_Price` to predict future sales trends.
- **Customer Segmentation**: Leverage **`Customer_Type`**, **`Region`**, and **`Category`** to group similar buyers or understand regional preferences.
- **Pricing and Discounts**: Analyze how **discounts** affect `Total_Price` and see if they lead to higher **Quantity** purchased.
- **Seasonal Trends**: Combine **`Order_Date`** with product categories to see if certain beverages sell better in specific seasons.

## Contributing & Feedback

We appreciate any **feedback**, **questions**, or **suggestions** to help us improve this dataset. Feel free to open an issue or share your thoughts directly if you have any ideas on how to make this dataset even more comprehensive and valuable.

---

**Thank you** for using this dataset! We hope it serves as a helpful resource for your projects and encourages deeper exploration into the dynamics of the beverage industry.