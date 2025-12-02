# Jumia Product Performance Analysis Dashboard

Jumia Kenya is one of the largest online marketplaces in Kenya, offering a wide range of products including electronics, groceries, home appliances, home decor, beauty products, and fashion. Jumia Kenya has rapidly grown in products, subscribers, and vendors, becoming part of the pan-African Jumia group.

This repository contains an Excel dashboard that analyzes a dataset of 115 products from Jumia Kenya to understand how discounts, customer reviews, and ratings influence online shopping trends.

---

## Dataset Overview

The raw dataset had several issues that needed cleaning for accurate analysis:

- Missing values in reviews and ratings replaced with 0 for completeness.
- Prices converted from text to numeric format.
- Discounts converted from string to numeric values.
- Ratings extracted from textual formats (e.g., "4.5 out of 5") to numeric.
- Reviews standardized to numeric values.
- Duplicate entries removed.

### Data Enrichment

To enhance the dataset for better insights, the following steps were performed:

- Categorized products by ratings:
  - *Poor*: ratings below 3
  - *Average*: ratings between 3 and 4
  - *Excellent*: ratings 4.5 and above
- Categorized discounts:
  - *Low Discount*: below 20%
  - *Medium Discount*: 20% - 40%
  - *High Discount*: above 40%
- Calculated absolute discount amount (Old Price - Current Price).

---

## Key Insights

- **Average price:** Ksh 1,181
- **Average discount:** ~36.8%
- **Highest discount:** 64%
- **Lowest discount:** 1%
- **Total reviews analyzed:** 723
- **Average product rating:** ~2

### Discount Analysis

- Products with very high discounts often have low review counts, indicating price cuts alone don’t guarantee engagement.
- Medium discounts (20%-40%) attract more reviews than very high discounts.
- Discounts are more effective when paired with higher product ratings.

### Ratings and Reviews Analysis

- Higher-rated products tend to have more reviews and higher engagement.
- Poorly rated products have fewer reviews and often receive high discounts, suggesting quality issues rather than pricing problems.

### Products

- Bottom 5 lowest-rated products are mainly home decor and bags with high discounts and poor ratings, implying quality concerns.
- Top 5 highest-rated products have excellent ratings and medium to high discounts, demonstrating that better ratings and reviews correlate with higher sales.

---

## Conclusion

The analysis shows that discounting alone does not drive sustainable sales growth or customer loyalty. Despite significant discounts, customer experience on Jumia remains poor based on ratings and reviews.

**Recommendations for Jumia:**

- Incentivize customer reviews by offering vouchers, loyalty points, or discount coupons for verified feedback.
- Shift from price-driven competition to a value-driven strategy by improving product quality.
- Highlight high-rated categories, optimize discount ranges, and build trust through customer reviews to boost conversions and long-term loyalty.

---

## Files

- `dashboard.xlsx` — The Excel dashboard containing the interactive analysis and visualizations.

---


