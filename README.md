# Brightcart-Online-Retail-Analysis | Website Traffic & Performance Analysis
E-commerce analytics project using Excel and Tableau to uncover website traffic patterns, user engagement, customer behaviour, and conversion trends, driving data-informed marketing and performance improvements.

---

## Dashboard Preview

### Dashboard 1: Cockpit – User Engagement Overview

![image alt](https://github.com/ALLIANCEMARIE/Brightcart-Online-Retail-Analysis/blob/e5f5a56ef095dbedf7314748284cae4c5ab731f6/Image(Brightcart%20Dashboard)/Brightcart%20Dashboard%201%20(Cockpit).png)

This dashboard provides an overview of website performance, including new and returning users, average session duration, unique page views, device distribution, monthly traffic trends, traffic sources, and geographical user distribution.

### Dashboard 2: Top Performers – Traffic & Engagement Patterns

![image alt](https://github.com/ALLIANCEMARIE/Brightcart-Online-Retail-Analysis/blob/aeb09f42b1218b30cf73c39e3ab257f84b3f6494/Image(Brightcart%20Dashboard)/Brightcart%20Dashboard%202%20(Top%20Performers).png)

This dashboard explores page performance and traffic distribution across different days and hours, helping identify high- and low-engagement periods.

---

## 1. Business Problem

BrightCart Online Retail, an e-commerce business specializing in consumer electronics, home goods, and lifestyle products, faces challenges understanding how customers interact with its website.

Limited visibility into peak traffic periods, traffic source effectiveness, customer behaviour, and conversion patterns makes it difficult to optimize marketing campaigns and allocate resources efficiently.

**The central business question:**

How can BrightCart leverage website traffic and customer engagement data to optimize marketing activities, improve conversions, and enhance overall website performance?

## 2. Project Objectives

The analysis aims to:

- Identify peak and low-traffic periods to improve marketing scheduling.
- Evaluate traffic sources and their contribution to website engagement.
- Examine the relationship between traffic patterns and conversions.
- Understand user behaviour across devices and geographical locations.
- Identify high-performing website pages and engagement opportunities.
- Develop actionable recommendations to improve marketing effectiveness and website performance.

## 3. Dataset Overview

The project uses an Excel dataset containing two related tables:

| Dataset | Records | Description |
|---|---:|---|
| User Session Data | 1,079 | User information, timestamps, traffic sources, devices, locations, and user types. |
| Engagement Data | 1,079 | Session duration, page views, unique page views, conversion indicators, and page URLs. |

**Data relationship:** Both tables share `SessionID`, which serves as the common identifier for connecting session information with engagement metrics.

**Key variables include:**
- SessionID and UserID
- Timestamp
- Traffic Source
- Device Type
- Country and State
- User Type and User Gender
- Average Session Duration
- Page Views and Unique Page Views
- Conversion Flag
- Page URL

## 4. Tools & Technologies

- **Microsoft Excel:** Dataset inspection and preparation.
- **Tableau:** Data visualization, dashboard development, and interactive analysis.

## 5. Analytical Approach

The project followed a structured analytical workflow:

1. **Data Collection:** Worked with website session and engagement datasets.
2. **Data Preparation:** Prepared and organized the data for analysis.
3. **Data Integration:** Connected the session and engagement tables using SessionID.
4. **Exploratory Analysis:** Examined traffic sources, user types, devices, geographical distribution, page performance, and engagement timing.
5. **Data Visualization:** Developed interactive Tableau dashboards to communicate findings.
6. **Insights & Recommendations:** Translated analytical observations into business-oriented recommendations.

## 6. Key Findings

The analysis highlighted several important patterns:

**1. Device Usage**
- Users predominantly access the platform through desktops and mobile phones, with a significantly lower usage on tablets

**2. Monthly Trend**
- We notice a decline in user engagement during the last quarter of the year, specifically in October, November, and December, for both 2023 and 2024. This trend could be attributed to various factors, including holidays, vacations, serious competition during that particular season or end-of-year routines.

**3. Traffic Sources**
- Organic Search and Direct Traffic emerged as the leading sources of user engagement in the project analysis.
- Referral and Social Media also contributed to website traffic.

**4. Page Performance**
- The `/order-confirmation` page recorded the highest unique page views, users, and conversions in the reported analysis, although its performance declined in 2024.

**5. Traffic Timing**
- Sundays and Mondays showed strong page-view activity.
- Wednesday at 7 AM recorded the highest reported average page views (12).
- Friday at 4 AM and Saturday at 3 PM recorded some of the lowest engagement levels (2 average page views each).

**6. Geographical Distribution**
- Canada led in users and conversions in 2022 and 2023.
- The UK emerged as the leading country in 2024, with Scotland identified as its top-performing state.

## 7. Business Recommendations

Based on the findings, the following actions are recommended:

- **Device Optimization:** Prioritize mobile and desktop user experiences while identifying opportunities to improve tablet engagement.
- **Monthly Trend:** To address the decline in user engagement during the last quarter, updating landing pages, publishing timely guides, and maximizing campaigns during this period
- **Marketing Strategy:** Strengthen organic search performance through keyword research, SEO improvements, and website optimization.
- **Traffic Scheduling:** Align promotional campaigns and website updates with observed high-engagement periods.
- **Customer Experience:** Review high-performing landing and confirmation pages, gather user feedback, and conduct A/B testing to identify improvement opportunities.
- **Geographical Strategy:** Investigate changes in geographical engagement and adapt marketing strategies to evolving regional user behaviour.
- **Resource Allocation:** Focus marketing resources on channels and periods that demonstrate stronger engagement and conversion performance.

## 8. Limitations & Opportunities for Further Analysis

Although the dashboards provide useful insights, further analysis could strengthen the business recommendations.

Potential areas for improvement include:

- Investigating the reasons behind declining engagement and geographical shifts.
- Examining conversion rates across individual traffic sources and time periods.
- Incorporating marketing expenditure to calculate actual channel ROI.
- Exploring customer retention and repeat-purchase behaviour.
- Conducting A/B testing to evaluate the effectiveness of proposed website improvements.

The available dataset does not include marketing expenditure or detailed customer purchase values, limiting the ability to establish actual campaign ROI and revenue impact.

## 9. Project Deliverables

| Deliverable | File |
|---|---|
| Excel Dataset | `brightcart_web_traffic_dataset.xlsx` |
| Tableau Workbook | `brightcart_online_retail_dashboard.twbx` |
| Dashboard Screenshots | Available in the `images/` folder |

---

## Conclusion

This project demonstrates how website traffic and customer engagement data can support more informed marketing and operational decisions.

By examining traffic sources, user behaviour, device preferences, geographical distribution, page performance, and engagement timing, businesses can identify opportunities to improve customer experience, optimize marketing activities, and strengthen website performance.

**The ultimate goal is not simply to attract more visitors, but to understand their behaviour and turn website engagement into meaningful business outcomes.**


