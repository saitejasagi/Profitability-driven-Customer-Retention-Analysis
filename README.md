# Profitability-driven-Customer-Retention-Analysis
## Stratification of customers using Customer Lifetime Value (CLV) calculations and Machine Learning

**Definition of Customer Lifetime Value & Why do we need to look at CLV?**

Customer lifetime value (CLV) is the amount of value a customer contributes to business over their lifetime. CLV calculation starts with a new customer’s first purchase and is calculated until the customer churns. 

Understanding CLV can help a business answer these critical questions:
    1. How much can we comfortably spend on marketing and sales for customer acquisition?
    2. How much should we spend on customer service to retain an existing customer?
    3. Who are our most valuable customers and how can we better target this demographic for future sales?   
    
Remember, not all customers are equally valuable. For most businesses, a small cohort of specific customers is generally the most profitable. Assessing the CLV can allow the business to dedicate more resources towards the acquisition and retention of high-value customers – thereby increasing profits overall.

One of the most valuable applications is using CLV to frame a better understanding of customer acquisition cost (CAC). The CLV: CAC ratio reveals a lot about the health of the business model.

**How to calculate Customer Lifetime Value?**

Measuring CLV requires looks at the length of the customer lifespan ( How many years is a customer will be with the company ), retention rate, customer churn rate, and the average profit margins per customer.

There are several different ways to calculate CLV, including the simple and traditional formulas that we will look at today.

CLV can also be historic or predictive depending on the data used.    
       1. Historic CLV is the sum of all profits from a customer’s past purchases. This number is based on existing customer data from a specific period of time.        
       2. Predictive CLV allows you to project how much revenue a customer will generate for your business over the course of the customer relationship. This is considered a more complete method of assessing CLV. The predictive model uses transaction history and behavioral patterns to determine the current value of a customer and to forecast how customer value will evolve with time. As you collect more data to include in this calculation, the value will become increasingly accurate.        
The second method has been used for this project.

**Formula**

The simple approach can be used if a customer’s annual profit contribution remains somewhat consistent. The most basic way to determine CLV is to add up the revenue earned from a customer (annual revenue multiplied by the average customer lifespan) minus the initial cost of acquiring them.

CLV=(Annual revenue per customer * Customer relationship in years) – Customer acquisition cost    
If the annual sales /profit margin per customer is not relatively flat, a more in-depth CLV equation is needed. This traditional version of the formula takes the rate of discount into consideration and provides a more detailed understanding of how CLV can change over the years. The detailed CLV equation breaks down the individual costs and profits of each year.

CLV= (Gross margin * Retention rate) / [1+ Rate of discount]    
This traditional method allows for fluctuations in customer revenue over time and each year is adjusted by a rate of discount to account for inflation. A discount rate of 10% is commonly used by SaaS companies.
We in this project -  
            * are using a simplified CLV formula.
            * are predicting only annual numbers.
            * are assuming that next year's annual prediction are the same values for the next 3 years and that our future value is      adequately estimated using only 3 future years.
Reference text used from - https://www.propellercrm.com/blog/customer-lifetime-value-clv

