# Wavecon-Telecom-Customer-Churn-Analysis
In the world of telecom, Wavecon company faced a challenge: customers were leaving, and they needed answers. Armed with Power BI and a thirst for insights, I embarked on a journey of data discovery.

**Objective:**
My mission was clear: understand why customers were leaving and how to stop them. With Power BI's help, I dived deep into my data to uncover the truth.

**Analysis:**
1. **Churned Customers Revenue:**
   I needed to know the financial impact of customers leaving. So, I used DAX's `SUMX` function to calculate the revenue from churned customers, painting a clear picture of the cost of churn.

2. **Churned Percentage as Key Performance Indicator (KPI):**
   Keeping it simple, I created a key performance indicator (KPI) using DAX's `DIVIDE` function to calculate the churned percentage each month. This straightforward measure kept me focused on the big picture.

3. **Revenue Generated Over Months:**
   Using DAX's `SUMX` function again, I tracked revenue month by month. This helped me spot trends and plan ahead, ensuring I was always one step ahead of the game.

4. **Average Monthly Charges:**
   With DAX's `AVERAGEX` function, I analyzed the average monthly charges for both churned and non-churned customers. This gave me insights into customer spending habits and pricing strategies.

5. **Impact of Internet Type on Churn:**
   I wanted to know if different internet types affected churn. So, I used DAX's `FILTER` function to segment customers by internet type and `SUMX` to calculate churn rates. This showed me if service quality played a role in customer loyalty.

6. **Churn Rate in Monthly Contracts:**
   I wondered if customers with monthly contracts were more likely to leave. Using DAX's `COUNTX` and `FILTER` functions, I analyzed churn rates for different contract types, uncovering insights into customer commitment and loyalty.

7. **Referral Count by Churned Customers:**
   I explored the power of referrals in bringing in new customers. With DAX's `COUNTX` and `FILTER` functions, I calculated referral counts for churned customers, revealing the influence of word-of-mouth in customer acquisition.

8. **Detailed Reasons for Customer Churn:**
   Finally, I delved into the reasons behind customer churn. Using DAX's functions like `CALCULATE` and `FILTER`, I analyzed customer feedback and transaction data to identify key drivers of churn, empowering me to take targeted action.

**Key Insights:**
Through my data-driven journey, I uncovered:
- The true cost of customers leaving, shining a light on the financial impact of churn.
- A simple yet powerful KPI for tracking churned percentage, keeping me focused on retention efforts.
- Revenue trends over time, guiding my strategic planning and decision-making.
- Insights into customer spending habits and pricing strategies, helping me optimize my offerings.
- The impact of service quality and contract types on customer loyalty, informing my retention strategies.
- The influence of referrals in customer acquisition, highlighting the importance of word-of-mouth marketing.
- The key drivers of churn, empowering me to take targeted action and improve customer satisfaction.

Armed with these insights, I set out to conquer churn and build a loyal customer base for years to come.
