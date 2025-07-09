📖 **Scenario-Based Data Modeling Question**

**Scenario:** Online Food Delivery Platform

You’re hired as a **Data Engineer** for a company like Zomato/Swiggy/Uber Eats.
The company wants to build a Data Mart for analytics and reporting.

The platform involves:

1) Customers placing orders from various restaurants.
2) Each order may contain multiple menu items.
3) Restaurants belong to one or more categories (like South Indian, Chinese, Fast Food, etc.)
4) Orders can be cancelled or delivered
5) The company runs promotions (offers) which may apply to orders.
6) They also need to track customer feedback with ratings and comments post-delivery.

**Business requirements:**

1) Track total sales per restaurant, per day.
2) Analyze which menu items sell the most in each city.
3) Track customer ordering frequency and average order value.
4) Track the effectiveness of promotions.
5) Get average delivery time per restaurant and per city.
6) Keep history of changes in restaurant categories and menu prices.

📌 **Tasks for You:**

1) Identify Fact and Dimension tables.
2)Draw out the Star or Snowflake schema for this system.
3) Explain Slowly Changing Dimensions (SCD) scenario for this model.
4) Decide on grain of the Fact table.
5) **Optional:** Suggest any Factless Fact tables if needed.
