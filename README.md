# AtliQo 5G KPI Analysis – Tableau Dashboard

## 📌 Project Overview
AtliQo, a leading telecom provider in India, launched 5G services in May 2022. Contrary to expectations, the company faced a decline in active users and revenue growth. This Tableau project analyzes key performance indicators (KPIs) from periods before and after the 5G launch to uncover trends and areas for optimization.

## 📊 Key Dashboards
- **Revenue Analysis**: Regional revenue trends, before vs after 5G launch, and forecast insights.
- **Metric Analysis**: Trends in ARPU, TAU, active/inactive users, and unsubscribe patterns.
- **City Analysis**: City-level performance and market share comparisons.
- **Plan Analysis**: Revenue breakdown by recharge plans and timeframes.

## 🧠 Insights & Conclusion
1. **Revenue vs Active Users**: Post-5G, plan revenue increased but active users declined.
2. **Retention Focus**: Modified offers in underperforming cities can improve user engagement.
3. **Market Share Dynamics**: AtliQo’s share dropped—strategy revision is key.

## 🧩 Dataset Modeling

The dataset modeling process involved integrating **four key tables** using **inner joins** on the `city_code` column. This allowed for a cohesive and analyzable dataset combining plan, city, and time-based information.

### 🔗 Data Connectivity Diagram:
![Dataset Modeling]("Data Modeling.jpg")

The visual diagram above illustrates the join structure:
