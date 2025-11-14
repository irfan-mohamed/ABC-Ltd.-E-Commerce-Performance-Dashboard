# ABC-Ltd.-E-Commerce-Performance-Dashboard

## Objective
To consolidate, clean, and model 8 distinct e-commerce CSV files into a 4-page Power BI dashboard. The project aims to uncover actionable insights across executive, logistics, marketing, and seller management functions to drive business performance.

## Dataset
Source: 8 CSV files (CUSTOMERS, ORDERS, ORDER_ITEMS, ORDER_PAYMENTS, ORDER_REVIEW_RATINGS, PRODUCTS, SELLERS, GEO_LOCATION)

Number of rows/columns: The model integrates multiple tables, including ORDERS (~96k rows), ORDER_ITEMS (~112k rows), and CUSTOMERS (~99k rows).

Key columns: order_id, customer_unique_id, product_id, seller_id, order_purchase_timestamp, order_delivered_customer_date, price, review_score, payment_type.

## Folder Structure
BRD/

FRD/

Data/

Visuals/

PowerBI/

Reports/

Scripts/

## Steps to Reproduce
1. Assess & clean dataset
2. Design dashboard mockups
3. Build Power BI dashboard & data model
4. Export reports & prepare Analysis Report

## Key Insights / Learnings
- Seller Performance Skew : Seller performance is not evenly distributed.Most of all 
sellers have 50 or fewer orders. A small  number of sellers represents the Top order 
receiving (more than  200 orders), making them critical partners. 
- Revenue vs. Quality Correlation On Sellers : The "Seller Performance Quadrant" 
(scatter plot) visually confirms a correlation between Total Revenue and Average Review 
Score. This identifies high revenue generators that have high average review scores. 
- Marketing Misalignment : The orders seasonality graph reveals that customer 
purchasing activity peaks time (approx. 10 AM - 10 PM) and helps to find specific days 
trends. This is a critical insight for marketing teams. 
- Logistics Delivery Time: The analysis proves the primary operational delay is shipping. 
The Avg. Days To Transit is the largest contributor to total fulfillment time. 
