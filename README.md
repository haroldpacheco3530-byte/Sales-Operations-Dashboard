# Operational BI Dashboard — From AppSheet CRM to Real-Time Decisions

**Data Analyst Portfolio Project**
Transforming scattered operational data into a live, decision-ready dashboard.

---

## 📌 Business Problem

The company managed sales and project operations through an AppSheet-based CRM. Although the data existed, answering simple business questions required manual filtering across multiple views and tools.

- **Reporting delays** — managers needed 5–10 minutes to retrieve weekly sales and project information.
- **Manual filtering** — every analysis required navigating multiple AppSheet views and filters.
- **Limited operational visibility** — sales, installations and project progress were hard to monitor in real time.
- **Reactive decisions** — without centralized KPIs, management relied on manual reporting instead of live insights.

**Business impact:** 5–10 minutes average time required just to answer an operational question.

---

## 🔄 Existing Workflow (Before)

```
Customer Call → Call Center Agent → AppSheet CRM → Manual Filters → Manual Reports
```

Data entered the CRM manually, was spread across multiple tables, and required managers to apply filters by hand every week just to compile a report. This process was time-consuming and prone to human error — manual reporting prevented managers from getting timely operational insight.

---

## 💡 Solution

I designed and implemented an automated Business Intelligence pipeline that connects AppSheet CRM data to real-time executive dashboards.

**Architecture overview:**

```
AppSheet CRM  →  REST API (data extraction)  →  Power Query (transformation)
             →  Google Sheets (centralized data model)  →  Looker Studio (dashboard)
```

1. **Automated data extraction** — data pulled automatically from AppSheet using its REST API with key authentication, removing manual exports entirely.
2. **Power Query transformation** — cleaned data types, removed nulls/duplicates, standardized categories, and converted US-format dates (MM/DD/YYYY) to regional format (DD/MM/YYYY).
3. **Data modeling** — merged multiple CRM tables (leads, clients, payments, projects) into a single analytical model.
4. **Dashboard delivery** — built interactive dashboards in Looker Studio, giving management real-time, filterable KPIs.

> A first prototype was built in Power BI using the AppSheet API and Power Query, then validated and replicated in Looker Studio to align with the company's Google Workspace environment.

---

## 📊 Executive Dashboard

**Questions the dashboard answers:**
- How much revenue was generated?
- Who are the top agents?
- Which services perform best?
- How many projects are completed?
- How are monthly trends evolving?

**Key features:** data filters by period, interactive controls per agent, executive KPIs, and automatic refresh from source data.

---

## 🛠️ My Contribution

- Connected the AppSheet REST API to automatically extract operational data.
- Built all Power Query transformations (cleaning, modeling, standardization).
- Designed the executive dashboards in Looker Studio.
- Delivered actionable insights that reduced reporting time and increased visibility for management.

---

## 📈 Business Impact

| Metric | Result |
|---|---|
| Time savings on reporting | **80%** reduction in time spent gathering/preparing reports |
| Real-time KPI visibility | **100%** of critical KPIs available live in one dashboard |
| Productivity boost | **+50%** — managers focus on analysis, not manual tasks |
| Manual reporting eliminated | **100%** per week |
| Data accuracy | Improved — consistent, trusted information for management |

**Before → After**

| Before | After |
|---|---|
| Information spread across multiple AppSheet views | Centralized information in one interactive dashboard |
| Manual data extraction and manipulation | Automated data pipeline, refreshed continuously |
| Reports created manually every week | Real-time dashboards with up-to-date data |
| Reactive decisions based on partial data | Proactive decisions based on complete insights |

---

## 🎓 Lessons Learned

- **Understand the business first** — deeply understanding the problem was key to designing a solution that truly adds value.
- **Data quality is everything** — cleaning and standardizing data had the biggest impact on dashboard reliability.
- **Automation saves time** — automating extraction and refresh eliminated repetitive work and reduced errors.
- **Iterate and improve** — continuous feedback helped refine the dashboard and deliver more value over time.

---

## 🧰 Tools & Skills

**Data Extraction:** REST API · JSON · API Key Authentication
**Data Transformation:** Power Query (M) · Data Cleaning · Standardization
**Data Modeling:** Google Sheets · Relational Modeling · Data Validation
**Data Visualization:** Looker Studio · Interactive Dashboards · KPI Design · Filters & Controls
**Core Skills:** Data Analysis · Problem Solving · ETL Processes · API Integration · Data Storytelling

---

## 📎 Full Case Study

A detailed visual walkthrough of this project (business problem, workflow, solution, and technical architecture) is available here: *[link to your Figma Present view]*
