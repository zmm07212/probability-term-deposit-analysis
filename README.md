# Smarter Outreach: Predicting Bank Marketing Campaign Success

Using data and machine learning to help Client B target the right customers and improve marketing campaign performance.

---

## The Business Problem

Client B runs large-scale digital marketing campaigns to promote term deposits, but most customers do not subscribe. This leads to wasted time and resources, as marketing teams are contacting customers who are unlikely to convert. If the bank continues using a broad, untargeted approach, it will miss opportunities to improve efficiency and increase conversion rates

## The Data

The dataset contains 45,211 client records and 17 variables describing customer demographics, financial information, and details from previous marketing campaigns. The target variable indicates whether a client subscribed to a term deposit; the outcome is highly imbalanced, with about 88% of customers not subscribing and only about 12% subscribing. The data also contains missing values in several columns, most notably poutcome and contact, which will need to be addressed before modeling. Overall, the dataset provides a strong sample size for analysis, but some preprocessing will be required to handle missing data and prepare the variables for predictive modeling.

## Key Discoveries

- **Older customers are more likely to subscribe:**  While most customers fall between their 30s and 50s, those who subscribe tend to be slightly older, suggesting a stronger interest in long-term savings products.

- **Customers with higher balances convert more often:** Subscribers generally have higher account balances, indicating that financial capacity plays a key role in a customer’s decision to commit to a term deposit.

- **Longer conversations drive successful conversions:** Customers who subscribe consistently have much longer call durations, highlighting the importance of engagement and effective communication during marketing calls.

- **Past campaign success is the strongest predictor:** Customers who previously responded successfully to a campaign are far more likely to subscribe again, making them the highest-value targets for future outreach.

- **Campaign timing has a major impact on results:** Subscription rates vary significantly by month, with some months outperforming others, while high-volume months like May show relatively low conversion rates.

- **Customers without loans are more likely to subscribe:** Customers with no existing loan obligations convert at higher rates, suggesting that financial flexibility increases the likelihood of committing to a savings product.

## Visualizing the Story

<!-- Embed your most compelling chart. Pick the ONE visual that best captures your main finding. -->

![Description of your chart](your_chart_filename.png)

*[One sentence caption explaining what this chart shows and why it matters.]*

## Prediction Model

[2-3 sentences. How well can we predict the outcome? Translate accuracy into real-world terms.]

<!--
Tip: Translate model metrics into business impact.
Instead of "The model achieved 78% accuracy..."
Try: "Our model correctly flags 8 out of 10 at-risk bookings, giving the hotel front desk team
enough lead time to proactively reach out and offer flexible rebooking options."
-->

## Recommendations

1. **[Action]:** [Why this action, based on your data. Estimated impact.]
2. **[Action]:** [Why this action, based on your data. Estimated impact.]
3. **[Action]:** [Why this action, based on your data. Estimated impact.]

## Tools & Techniques

Python | Pandas | Scikit-Learn | Matplotlib | Seaborn | Gaussian Naive Bayes | Google Colab

---

*This project was completed as part of ISOM 835: Predictive Analytics at Suffolk University\'s
Sawyer Business School.*
'''
