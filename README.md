# Churn-Analysis

📊 Executive Summary – Customer Churn Analysis
This analysis examines 7,043 customer records from a telecommunications service provider to understand the factors driving customer churn, which refers to customers discontinuing their service. The dataset includes demographics, service usage patterns, account details, and payment methods.


🔄 **Churn Rate Overview**

•	Churned Customers: 26.5% of the total customer base has churned.
•	Retained Customers: 73.5% are still active.
•	This represents a high churn rate, signaling an opportunity for strategic retention efforts.


👥 **Demographic Factors**

1. Senior Citizens and Churn
•	16% of customers are senior citizens.
•	Among them, a significantly higher percentage have churned compared to non-senior customers.
•	Insight: Older customers may face technical, financial, or engagement-related issues that lead to higher churn.
2. Tenure Duration
•	The median tenure is around 29 months, with values ranging from 0 to 72 months.
•	Customers with tenure under 12 months show the highest churn rate, particularly those in their first 1–2 months.
•	In contrast, long-term customers (50+ months) show strong retention.
•	Insight: The onboarding experience and initial service satisfaction are critical to customer loyalty.


📦 **Contract Type and Churn Risk**

Contract Type	% of Customers	% Who Churned
Month-to-Month	~55%	~43%
One-Year Contract	~22%	~11%
Two-Year Contract	~23%	~6%

•	Month-to-month customers are over 7x more likely to churn than those on two-year contracts.
•	Insight: Contract length has a strong inverse correlation with churn — longer commitments increase retention.


🌐 **Service Usage Patterns**

Internet & Phone Services
•	InternetService:
o	Fiber optic is the most popular but also has the highest churn rate.
o	DSL customers churn less.
o	No internet service users have low churn, likely because they use only basic services.
•	PhoneService: Over 90% of customers have it, with relatively low impact on churn.

Add-On Features Adoption & Churn Trends
Service Feature	% With Service	Churn Behavior
OnlineSecurity	~30%	Lower churn when active
OnlineBackup	~35%	Lower churn when active
TechSupport	~29%	Significantly reduces churn
StreamingTV	~40%	Mixed impact
StreamingMovies	~38%	Mixed impact

•	Optional features like OnlineSecurity and TechSupport are associated with lower churn rates, but adoption is low.
•	Insight: There is room to increase adoption of these value-added services to improve retention.


💳 **Payment Methods and Billing**

Payment Method	% of Customers	Churn Rate
Electronic Check	~34%	Highest churn (~45%)
Mailed Check	~17%	Lower churn (~15%)
Credit Card (auto)	~22%	Lowest churn
Bank Transfer (auto)	~27%	Very low churn
•	Customers using Electronic Check have a much higher churn rate, while those using automatic payments (Credit Card/Bank Transfer) tend to stay.
•	Insight: Churn correlates with manual billing, possibly due to perceived inconvenience, missed payments, or demographic traits.


💰 **Charges & Churn**

•	Monthly Charges range from $18 to $119.
•	Customers with higher monthly charges (especially those >$80/month) show greater churn tendency, particularly if they're also on month-to-month contracts.
•	Insight: High costs without long-term commitment may create dissatisfaction or drive competitive switching.


✅ **Strategic Recommendations**

1.	Improve Early Engagement: Focus on customers within their first 3 months. Offer onboarding support, personalized plans, and satisfaction check-ins.
2.	Encourage Long-Term Contracts: Offer discounts or loyalty rewards to convert month-to-month customers into 1 or 2-year plans.
3.	Promote Value-Added Services: Bundle OnlineSecurity, TechSupport, and OnlineBackup with core services to increase retention.
4.	Incentivize Auto-Payments: Encourage the use of auto-payment methods through perks or small discounts.
5.	Target High-Risk Segments: Segment customers based on tenure, payment method, and contract to proactively manage churn.

