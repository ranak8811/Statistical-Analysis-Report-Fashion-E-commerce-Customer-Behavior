# Statistical Analysis Report: Fashion E-commerce Customer Behavior  
**Date:** July 18, 2025  
**Author:** Md. Anwar Hossain  
**Data Source:** retail_fashion_dataset.xlsx (1,000 Transactions)  

## 1. Executive Summary  
This report presents a statistical analysis of customer and transaction data for our fashion e-commerce platform. The analysis aimed to understand customer spending habits, evaluate the impact of our loyalty program and customer demographics on sales, and analyze product return behavior.  

The key conclusion is that while customer spending is predictable and consistent, it is not strongly influenced by traditional demographic factors like age, gender, or annual income. Furthermore, the analysis reveals a critical insight: our current Membership loyalty program is not effectively driving higher spending from premium-tier members. Product return rates do not show a statistically significant link to gender.  

Based on these findings, we recommend:  
- A strategic shift from demographic-based targeting towards a more sophisticated, behavior-driven approach  
- A comprehensive review of the Membership program's value proposition  

## 2. Key Findings  
Our analysis of 1,000 customer transactions yielded the following key findings:  

### Customer Profile:  
- The primary customer base consists of young to middle-aged adults, with an average age of 33 years. The middle 50% of customers are aged between 26 and 39.  
- The business caters to a wide range of income levels, with an average annual income of approximately 797,505 BDT.  

### Purchase Behavior:  
- The average amount spent per transaction is 3,038 BDT. The spending distribution is bell-shaped, indicating that most transactions are clustered around this average, making spending behavior highly predictable.  
- The most popular product categories are Bottoms, and Traditional Wear, with relatively even purchase frequency among them. 'Shoes' is the least purchased category.  
- Credit Card is the most frequently used payment method, followed closely by the mobile payment system bKash.  

### Statistical Insights:  
- There is no statistically significant difference in the average amount spent between male and female customers (p-value = 0.7026).  
- There is no statistically significant difference in the average amount spent across the different Membership tiers (Regular, Silver, Gold, Platinum) (p-value = 0.1200).  
- A multiple linear regression model attempting to predict AmountSpent using demographics and membership data had very poor predictive power (R-squared = 1.3%), confirming that these factors are not strong drivers of transaction value.  

### Return Behavior:  
- There is no statistically significant relationship between a customer's gender and their likelihood of returning a product (p-value = 0.8964).  

## 3. Actionable Insights & Recommendations  

### i) Customer Spending Behavior  
**Insight:** Customer spending is consistent and predictable, clustering around a mean of ~3,038 BDT. However, it is not strongly correlated with customer age or income.  

**Recommendation 1 (Upselling):** Implement strategies to increase the Average Transaction Value (ATV). Set promotional thresholds slightly above the average spend, such as offering "free shipping on orders over 3,500 BDT" or a "10% discount on orders over 4,000 BDT" to encourage customers to add one more item to their cart.  

**Recommendation 2 (Shift to Behavioral Targeting):** Since demographics are poor predictors, the business should enhance data collection to focus on behavioral attributes. Track metrics like products viewed, time spent on page, and cart abandonment rates. Use this data to build a recommendation engine and personalize marketing efforts based on what customers do, not just who they are.  

### ii) Impact of Membership and Demographics on Sales  
**Insight:** The analysis provides strong evidence that the current multi-tiered Membership program is not effective at encouraging higher spending. Platinum and Gold members do not spend significantly more than Regular members.  

**Recommendation 1 (Strategic Program Review):** Conduct an immediate and thorough review of the loyalty program. The program is currently a cost center without a clear return on investment in terms of increased sales from premium members.  

**Recommendation 2 (Enhance Premium Tiers):** The value proposition for Gold and Platinum tiers must be strengthened. Consider introducing benefits that directly encourage spending, such as exclusive access to new collections, higher points multipliers on purchases, or personalized styling services. The goal is to make achieving a higher tier a tangible driver of increased customer value.  

### iii) Return Behavior Analysis  
**Insight:** Product returns are not significantly linked to customer gender.  

**Recommendation 1 (Focus on Universal Causes):** Do not allocate resources to gender-specific return-reduction strategies. Instead, focus on universal drivers of returns.  

**Recommendation 2 (Improve Product Information):** Invest in improving product information across the board. This includes more detailed sizing charts (with model measurements for reference), higher-quality product videos, and customer-submitted photos to provide a more accurate representation of fit and quality, which are common reasons for returns in fashion e-commerce.  
