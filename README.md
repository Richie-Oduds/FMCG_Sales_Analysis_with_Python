## **Exploratory  Data Analysis on FMCG Sales Dataset**

### **FMCG Dataset – Overview**

This dataset simulates daily-level transactional data for products sold in the Fast-Moving Consumer Goods (FMCG) sector between 2022 and 2024.

This is designed to support analysis of:

- Seasonality and product lifecycle
- Promotion and holiday effects
- Stockouts and inventory dynamics
- Demand forecasting and feature engineering

Each row represents one SKU on a specific day, across different sales channels and region. This project is intended for educational and portfolio-building purposes.

- Link to the dataset we are using for our practice

(https://www.kaggle.com/datasets/beatafaron/fmcg-daily-sales-data-to-2022-2024?select=FMCG_2022_2024.csv)

- The data has been manipulated after it was downloaded from Kaggle. This is because the data didn't have enough information to support our analysis. In order to be able to have a clean and consistent analysis, we added some few informations to the dataset. This eventually will make our analysis an hypothetical analysis.

- Four our columns, each record includes;

- date: Date of the sales record
- sku: Stock Keeping Unit (unique product ID)
- brand: Brand name of the product
- segment: Product segment (e.g., premium, standard, economy)
- category: Product category (e.g., Beverages, Snacks)
- channel: Sales channel (e.g., Retail, E-commerce)
- region: Region where the sale occurred
- pack_type: Packaging type
- price_unit: Price per single unit
- promotion_flag: Whether the sale occurred under promotion (1 = Yes, 0 = No)
- delivery_days: Number of days taken to deliver
- stock_available: Units available in stock
- delivered_qty: Number of units delivered
- units_sold: Total units actually sold

The goal is to understand the company’s performance and uncover insights that can help improve sales strategies and stock management.

**Tutor: Mr Richie**
