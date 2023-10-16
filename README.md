# sport_sql
# Project Overview: Analyzing Online Sports Clothing Sales

This project dives into the product data of an online sports clothing company with the aim to identify strategies for revenue improvement. The analyses cover a range of aspects including pricing, reviews, discounts, and product descriptions. The database is organized across several tables such as `info`, `finance`, `reviews`, `traffic`, and `brands` each containing different types of data related to the products.

## Key Findings:

1. **Missing Values Analysis**: 
   - The dataset consists of 3,179 products.
   - Only the `last_visited` column has more than 5% missing values.

2. **Pricing Analysis (Nike vs Adidas)**:
   - Adidas products generate more revenue across all price categories compared to Nike.
   - Adidas also offers more discounts on its products, unlike Nike which offers no discounts.

3. **Reviews and Revenue Correlation**:
   - A strong positive correlation was found between the number of reviews and the revenue generated.

4. **Product Description Analysis**:
   - No clear pattern was observed between the length of product descriptions and the ratings they received.

5. **Monthly Reviews Analysis**:
   - The first quarter of the year has the highest number of product reviews. 

6. **Product Type Performance**:
   - Footwear makes up around 85% of the stock with a median revenue of over $3,000.
   - Clothing products have a lower median revenue of $503.82.

7. **Visualization**:
   - A visualization has been created on Looker to further illustrate these findings.

## Recommendations:

1. **Discount Strategy**: 
   - Experiment with discount strategies, possibly reducing discounts on Adidas products or introducing discounts on Nike products.

2. **Encouraging Reviews**:
   - Encourage more customer reviews through various incentives, especially during the last three quarters of the year.

3. **Product Stock**:
   - Consider adjusting the stock to have a larger proportion of higher revenue-generating products like footwear.

4. **Content Guidelines**:
   - Although no clear pattern was found between description length and ratings, further investigation could be carried out to optimize product listings.

This project provides a foundational understanding of the data, upon which more advanced analyses and A/B testing could be performed to further refine the company's marketing and sales strategies.
