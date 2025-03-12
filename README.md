# Amazon Sales Analysis

## Overview
This project aims to analyze Amazon sales data to extract meaningful insights into sales trends, customer behavior, and product performance. By leveraging data analytics and machine learning, we explore various factors that influence sales and provide predictive insights using linear regression.

## Features
- **Data Cleaning & Preprocessing**: Handling missing values, removing duplicates, and standardizing data formats.
- **Reviewer Data Extraction & Analysis**: Examining the impact of customer reviews and ratings on sales performance.
- **Exploratory Data Analysis (EDA)**: Identifying sales trends, seasonal patterns, and category-wise performance.
- **Visualization**: Using Matplotlib and Seaborn to generate insightful graphs and heatmaps.
- **Predictive Modeling**: Implementing a linear regression model to forecast sales based on key variables.
- **Actionable Insights**: Deriving business recommendations from data-driven observations.

## Technologies Used
- **Programming Language**: Python
- **Libraries & Frameworks**:
  - Data Manipulation: Pandas, NumPy
  - Data Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn

## Dataset
- The dataset consists of Amazon sales records, including:
  1. product_id - The ID number for the product.
  2. product_name - The name of the product.
  3. category - The category of the product.
  4. discounted_price - The price of the product after the discount.
  5. actual_price - The original price of the product.
  6. discount_percent - A percentage of the actual price that's been discounted.
  7. rating - The average rating of the product (0-5 stars).
  8. rating_count - The number of customers who rated the product.
  9. about_product - A description of the product.
  10. user_id - The user ID of the a reviewer.
  11. user_name - The user name of the reviewer.
  12. review_id - The ID number for a review.
  13. review_title - The title of a review.
  14. review_content - The content of a review.
  15. img_link - A link to the image of the product.
  16. product_link - A link to the product page.

## Results & Insights
- **Key Findings:**
  - Identified best-selling product categories and subcategories.
  - Determined the correlation between customer reviews and sales performance.
  - Found that the discounted price of a product is strongly correlated with its actual price.
- **Predictive Analysis:**
  - Implemented a **linear regression model** to predict the **discounted price** based on the **actual price** of a product.
  - Applied a **train-test split** to improve model accuracy.
  - Identified **key factors** influencing price adjustments and discount strategies.
- **Business Recommendations:**
  - Optimize discount strategies by analyzing price fluctuations.
  - Use customer ratings to drive product pricing decisions.

## Future Enhancements
- Implement advanced machine learning models for better sales forecasting.
- Integrate sentiment analysis for customer reviews.
- Automate data updates using web scraping or API integration.

## License
This project is licensed under the MIT License.

