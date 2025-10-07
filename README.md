# 📱 MobileImpact Donor Analytics – Data-Driven Engagement Strategy  

## 🌟 Highlights  
- Analysed donor behaviour across **traditional** and **in-app** channels using five integrated datasets.  
- Identified that **10% of in-app donors contribute 85.6% of revenue**, compared with 31.9% in traditional giving.  
- Revealed **lapsed and at-risk donor segments** using RFM segmentation and engagement metrics.  
- Mapped **channel efficiency**, showing email as the most cost-effective and social media best for re-engagement.  
- Delivered **AI-assisted, privacy-compliant strategies** for personalised outreach, predictive retention, and incentive design.  

---

## ℹ️ Overview  
This project was developed as part of **MIS784 – Marketing Analytics** at Deakin University.  
It focuses on analysing donor and engagement data for **MobileImpact**, a non-profit organisation that aligns with the UN Sustainable Development Goals (SDGs 1, 3, 4).  

The analysis combined five datasets covering **customers**, **traditional donations**, **in-app purchases**, and **campaign responses** to uncover insights into donor behaviour, churn risk, and channel effectiveness.  

The goal was to provide **evidence-based recommendations** to improve donor retention, optimise fundraising performance, and ensure responsible use of Generative AI in personalised engagement.  

---

## 📂 Project Structure  
📁 mobileimpact-donor-analytics
┣ 📄 MIS784_A3_Group60_Report.docx # Full business report with insights and recommendations
┣ 📄 MIS784_A3_Group60_Query.docx # SQL and analytical queries used for analysis
┗ 📄 README.md # This file

markdown
Copy code

---

## 🚀 How to Use  

### 1. Review the Queries  
Open `MIS784_A3_Group60_Query.docx` to explore the SQL and analytical queries used for segmentation, churn analysis, and channel performance.  

### 2. Read the Report  
`MIS784_A3_Group60_Report.docx` provides the complete analysis, findings, and strategic recommendations written for a non-technical audience.  

---

## 📈 Key Analytical Components  

### **Data Preparation & Integration**  
- Cleaned, merged, and validated five datasets from both traditional and mobile-app channels.  
- Flagged active memberships, handled missing values, and removed duplicates.  

### **Donor Behaviour Analysis**  
- Conducted **RFM segmentation** into five groups: *Cannot Lose*, *Active Fans*, *Promising Newbies*, *At Risk*, and *Other*.  
- Analysed donation patterns, payment preferences, and engagement frequency.  
- Compared demographic influences such as **age, income, and family size** on retention.  

### **Churn & Retention Modelling**  
- Identified churn predictors: RFM metrics for traditional donors, and campaign response for in-app contributors.  
- Found that **67% of traditional donors were inactive for 180+ days** and **half donated only once**.  

### **Revenue Optimisation**  
- Tracked monthly donation trends (Jan 2024 – Aug 2025), identifying **March 2024** as the peak revenue month.  
- Highlighted dependence on **high-value in-app whales** (top 10%) and seasonal variations in giving behaviour.  

### **Campaign Effectiveness**  
- Measured response, click-through, and engagement by **channel and RFM segment**.  
- Found **email** most cost-efficient, **social media** best for re-engaging *At Risk* donors, and **direct mail** most effective for onboarding.  

---

## 💡 Strategic Recommendations  

### **1. Personalised Outreach**  
- Reactivate one-time and younger donors using campaign updates that link to past causes.  
- Retain high-value app donors (*whales* and *dolphins*) through behaviour-based reminders.  
- Engage younger in-app donors with **game-themed messages** aligned to genres such as Adventure or MMORPG.  
- Use **Generative AI** for automated message generation while ensuring human oversight and data compliance.  

### **2. Predictive Retention for Traditional Donors**  
- Implement a **predictive RFM-scoring model** using logistic regression or gradient boosting.  
- Classify donors into alert tiers (Cannot Lose → Red Alert) and trigger tailored interventions.  
- Personalise retention strategies by demographics and contribution tier.  
- Integrate **AI-enhanced personalisation** within GDPR-compliant frameworks.  

### **3. Tiered Incentives & Early Activation**  
- Retain whales with exclusive bundles and recognition; motivate dolphins with progression rewards.  
- Engage minnows early using low-cost starter packs or micro-bonuses.  
- Trigger **first-purchase incentives** within two weeks of installation to build loyalty.  
- Use time-based streaks, loyalty badges, and genre-specific rewards to sustain engagement.  

---

## 🧩 Compliance & Ethics  
All recommendations align with **GDPR** and privacy-by-design principles:  
- **Federated learning** for model training without centralised data transfer.  
- **Differential privacy** applied to RFM and response metrics.  
- **Transparency and consent management** embedded in AI-assisted communications.  

---

## 🧰 Tools & Techniques  
- **Google BigQuery & SQL** – Data extraction and transformation.  
- **Looker Studio** – Visual analytics and campaign dashboards.  
- **Python (VADER, pandas)** – Supporting sentiment and pattern analysis.  
- **RFM Segmentation** – Recency, Frequency, Monetary scoring.  
- **Predictive Modelling** – Logistic regression, gradient boosting for churn risk.  
- **AI Integration** – Generative AI for scalable personalisation within ethical guidelines.  

---

## 👤 Authors  
- **Ba Huy Hoang Le** 
- **Jayseon Choi** 
- **Simran Thakur** 

📧 huyhoangle040502@gmail.com  
---

## 📜 Acknowledgement of AI Use  
Some content drafting, grammar editing, and structural improvements were supported by AI tools, with all final materials critically reviewed and edited by the authors to ensure accuracy, originality, and academic integrity.  
