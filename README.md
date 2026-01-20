🚴‍♂️ Bike Sales Dataset
3 years of synthetic retail data (2021-2023) – ready for forecasting, market-basket & customer-segmentation exercises.# Sales-Dashboard

1.🎯 Key Columns
Orders
order_id, customer_id, product_id, store_id, order_date, quantity, unit_price, discount_pct, total_sales
Customers
customer_id, gender, age_group, city, state, member_since
Products
product_id, brand, model, category (Mountain / Road / Hybrid / Accessories), color, unit_cost, launch_year
Stores
store_id, store_name, city, state, opened_date, sqft

2.📊 Quick Stats
Total revenue: $18.4 M
Avg order value: $620
Top-selling brand: Trek (31 %)
Seasonal peak: May–Jul (35 % of annual sales)
Online vs In-store: 42 % / 58 %

3.🚀 Usage Ideas
Time-series forecasting (prophet, ARIMA, LSTM)
RFM customer segmentation
Market-basket analysis (accessories upsell)
Price-elasticity & promo lift
Geo-dashboard in PowerBI / Tableau / Superset

4.🔍 Data Integrity
No missing keys or negative quantities
Prices & costs inflation-adjusted to 2023 USD
Customer birth-dates shifted ±30 days for privacy
Generated with Faker + custom rules; no real PII.

5.📄 License
MIT – feel free to fork, extend, or add your own models.

6. Screenshot / Demos
Show what the dashboard looks like.
Example:
