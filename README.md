# Personalised Engagement Strategies for Sustainable Fundraising: A Data-Driven Approach

## 1. Executive Summary
MobileImpact faces a critical financial risk characterized by an 86.5% revenue concentration among its top 10% of donors. This project addresses the urgent need for donor diversification and churn prevention by moving away from generic marketing toward a segmented, behavior-based engagement strategy. By integrating disparate datasets via SQL (BigQuery), this solution identifies high-value "At Risk" segments and provides a framework to stabilize funding for Sustainable Development Goal (SDG) initiatives. This work transitioned the organization from reactive fundraising to proactive, data-backed donor lifecycle management.

## 2. Business Problem
**The Decision:** The organization repeatedly made the decision to apply uniform marketing outreach across its entire donor base, regardless of individual engagement history or platform preference.

**The Failure:** Current logic was flawed because it relied heavily on high-value "whale" donors without a retention framework for "minnow" or app-based supporters. The organization lacked a clear understanding of the distinct behavioral drivers between traditional donors and mobile app users.

**The Impact:** With 86.5% of total revenue tied to a tiny fraction of the donor base, the loss of even a few key contributors poses an threat to SDG-aligned projects. Generic outreach resulted in a 12% drop in campaign engagement among previously active mobile users.

## 3. Methodology
* **Data Integration:** Utilized **SQL (BigQuery)** to join five distinct tables: Customer, Donation, In-app, Campaign, and Response.
* **Exploratory Data Analysis:** Conducted a comprehensive audit of donor behavior patterns, payment method performance, and seasonal donation trends.
* **RFM Segmentation:** Developed a Recency, Frequency, and Monetary framework to categorize the donor base into actionable segments: Cannot Lose, At Risk, and Promising Newbies.
* **Churn Analysis:** Evaluated the relationship between campaign response rates, click-through metrics, and demographic influences to identify early warning signals of supporter fatigue.

## 4. Demonstration of Skills and Capabilities
* **Advanced SQL Querying:** Executed complex joins and aggregations in BigQuery to deduplicate campaign responses and calculate accurate ROI per donor segment.
* **Behavioral Segmentation:** Proved that traditional donors and mobile app users require different engagement models, as mobile users show higher frequency but lower individual monetary value compared to traditional contributors.
* **Data Integrity and Cleaning:** Identified and managed outlier behavior in the top 5% of contributors to ensure that "whale" data did not skew the strategic recommendations for the broader donor base.
* **Marketing Analytics:** Calculated Campaign Cost per Engaged Person across different campaign types to determine which channels (e.g., social media vs. direct email) yielded the highest retention for specific age demographics.

## 5. Results & Business Recommendations
* **Revenue Preservation:** Identified that "At Risk" donors previously averaged $271 per person. Reactivating just 10% of this segment would significantly diversify the revenue stream away from the 86.5% concentration.
* **Tiered Incentive Strategy:** Recommended a shift toward "behavior-based reminders" for in-app donors, focusing on game genres and device performance metrics that show higher engagement.
* **Channel Optimization:** Based on the data, outreach should prioritize personalized campaign updates for one-time donors to convert them into recurring supporters, specifically targeting younger demographics through optimized mobile channels.
* **Direct Impact:** Implementing the proposed segmented outreach is estimated to improve the click-through rate for "Promising Newbies" by aligning campaign types with their documented payment preferences.

## 6. Next Steps
* **Generative AI Integration:** Utilize GenAI to create personalized, high-scale content for different RFM segments to reduce manual marketing overhead.
* **Predictive RFM:** Move from descriptive segmentation to predictive modeling to forecast donor churn 30 days before the last engagement.
* **Privacy-Preserving Personalization:** Implement frameworks to ensure donor data remains secure while increasing the granularity of personalized outreach.

## 7. Context and Credits
* **Client:** MobileImpact (Non-profit organization). Client's name was anonymised due to confidentiality clause. 
* **Program:** MIS784: Marketing Analytics.
* **Team:** Ba Huy Hoang Le (224309594), Jayseon Choi, Simran Thakur.
* **AI Disclosure:** Generative AI tools were used for refining content and code snippets within the original report.
