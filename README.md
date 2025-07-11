# Project 2: User Engagement & Growth Strategy for Meituan AI Chatbot

![Project Banner](https://github.com/RainySheena/Meituan-User-Growth-Analysis/blob/main/meituan_logo.png)

---

### 1. Project Overview

This project focused on enhancing user engagement for Meituan's "Guangnian" AI Project. A key challenge was that many new users were not actively engaging with the chatbot after their initial contact. By developing in-depth user profiles to identify and understand these "non-engaging" users, I designed and implemented targeted optimization strategies.

My contributions spanned user behavior analysis, data engineering, and business intelligence. The initiative resulted in a **10% increase in the chat initiation rate for new users**.

---

### 2. Business Problem & Goal

* **Problem**: A significant portion of new users for the Guangnian AI chatbot were dropping off after their initial interaction. The business needed to understand the "why" behind this low activation and find data-driven ways to enrich the early user experience to boost retention.

* **Goal**: The primary objective was to increase the new user activation rate, measured specifically by the chat initiation rate. A secondary goal was to build a sustainable data infrastructure—including dashboards and foundational data tables—to empower the team to continuously monitor user engagement.

---

### 3. My Methodology & Process

My approach to solving this problem involved a multi-faceted data science workflow:

1.  **User Profiling & Analysis**: I began by developing user profiles to pinpoint the characteristics and behaviors of non-engaging users. This involved segmenting users based on their activity and using statistical analysis to uncover patterns that led to churn.

2.  **Data Engineering & Automation**: To support this analysis and future A/B tests, I designed and built denormalized wide tables using Spark. These tables consolidated user data for both offline analysis (Hive2Hive) and online service needs (Hive2MySQL). A key feature was the automation of user stratification, which significantly accelerated the team's experimentation lifecycle.

3.  **Dashboarding & Business Intelligence**: I built and maintained a suite of data dashboards using HiveSQL. These dashboards visualized Key Performance Indicators (KPIs) such as DAU, WAU, MAU, user retention, and chat activity, providing the product team with a real-time, comprehensive view of user engagement trends.

4.  **Strategy & Optimization**: Based on the insights from the user profiles, I implemented tailored optimizations designed to enrich the experience for these at-risk, non-engaging users.

---

### 4. Tech Stack

* **Big Data Technologies**: `Spark`, `HiveSQL`
* **Databases**: `MySQL`
* **Core Languages & Libraries**: `Python`, `SQL`

---

### 5. My Contribution

* **End-to-End User Analysis**: I independently conducted the user profiling initiative, from data analysis and segmentation to delivering actionable insights that informed product strategy.
* **Data Engineering for Analytics**: I designed and engineered the core data tables using Spark, which became a foundational asset for the team's A/B testing and broader analytical efforts.
* **Business Intelligence & Visualization**: I built the team's primary user engagement dashboards, empowering data-driven decision-making and providing clear visibility into product health.

---

### 6. Results & Impact

* **Key Result**: The targeted optimizations I implemented led directly to a **10% increase in the new user chat initiation rate**.
* **Business Impact**: This project not only directly improved a critical user activation metric but also provided the team with lasting data infrastructure (dashboards and analytics tables). This empowered the team to monitor user health more effectively and accelerate future experimentation cycles.
