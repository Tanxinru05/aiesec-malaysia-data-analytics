# AIESEC Malaysia — Entity Performance Data & Analytics

![Python](https://img.shields.io/badge/Python-3.10-3776AB?logo=python&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-Automation-4285F4?logo=google&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-Dashboards-FF6384?logo=chartdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

End-to-end data infrastructure built for **AIESEC in Malaysia's** national Organization Development function — automating performance reporting, visualizing results across all local entities, and upskilling the wider organization in data literacy.

> **Role:** Entity Performance Data Analyst & Data Specialist — Organization Development *(Sep 2025 – Present)*

---

## Overview

AIESEC in Malaysia operates through **11 local entities (Local Committees)**, each reporting performance across multiple programme and functional pillars. Before this work, performance tracking relied on manual spreadsheet consolidation, which was slow, error-prone, and hard to scale.

This repository brings together the three systems I built to solve that, moving the entity from manual reporting to a **repeatable, automated, insight-driven analytics workflow**:

| # | Project | What it does |
|---|---------|--------------|
| 1 | **LC Report Generator** | Ingests raw performance and finance workbooks and auto-generates standardized, per-entity reports with AI-assisted insights and PDF export. |
| 2 | **Performance Dashboards** | Interactive dashboards for exploring current and historical performance across all 11 entities and multiple seasons. |
| 3 | **Data Academy Portal** | An AI-agent-powered learning platform and structured curriculum that builds data literacy across the organization. |

### Impact at a glance
- ⚙️ **Automated data pipelines** using Google Apps Script and APIs, cutting manual reporting effort and turnaround time.
- 📊 Delivered dashboards and reports serving **50+ stakeholders across 11 entities**, enabling data-driven decisions at both local and national level.
- 🗓️ Produced **quarterly performance reports** and enhanced entity performance tracking with strategic insights for leadership.
- 🎓 Built a **data learning academy** to scale data capability across the organization rather than concentrating it in one role.

---

## Repository structure

```
aiesec-malaysia-data-analytics/
├── README.md
├── lc-report-generator/         # Automated report + insight generation
│   ├── README.md
│   ├── src/
│   └── sample_output/
├── performance-dashboards/      # Interactive visualization suite
│   ├── README.md
│   ├── historical-dashboard/
│   └── quarterly-dashboard/
└── data-academy-portal/         # Data literacy platform + curriculum
    ├── README.md
    ├── app/
    └── curriculum/
```

---

## 1. LC Report Generator

An automated reporting engine that takes raw performance and finance workbooks (e.g. the OD Model and quarterly finance sheets) and produces clean, standardized reports for each Local Committee — removing repetitive manual consolidation.

**Key features**
- Parses multi-sheet Excel workbooks and generates **per-entity, per-metric breakdowns** automatically.
- Produces **executive-style report views** across programme and functional pillars (e.g. XDI, MDI, HDI / oGV, GvA inputs).
- **AI-assisted insight generation** that turns raw numbers into written performance commentary for leadership.
- Multiple visual themes and **one-click PDF export** for distribution.

**Tech:** Claude · Prompting ·  LLM API for insight generation

---

## 2. Performance Dashboards

A suite of interactive dashboards that let national leadership and local teams explore performance without touching a spreadsheet.

**Historical performance dashboard**
- Multi-tab interface enabling **multi-entity and multi-season comparison** across exchange programmes and sales metrics spanning several years of data.
- Built for fast, self-serve exploration of trends and benchmarking between entities.

**Quarterly performance dashboard**
- Visualizes current-quarter performance across all **11 entities** and across the XDI / MDI / HDI pillars.
- Surfaces KPI cards, comparative charts, and standings at a glance.

**Tech:** Google Data Studio, Google Sheets

---

## 3. Data Academy Portal

A platform designed to raise the data capability of the whole organization, so performance analytics doesn't depend on a single specialist.

**Key features**
- **AI-agent-powered learning experience** that helps members build practical data skills and get answers in context.
- A **structured data-competency curriculum** progressing from data literacy → dashboard interpretation → data strategy.
- Centralizes knowledge sharing and reporting best practice across all entities.

**Tech:** Promting · LLM API / AI agent framework · web front-end

---

## Tech stack summary

| Category | Tools |
|----------|-------|
| Automation & pipelines | Google Apps Script, APIs, Python |
| Data processing | Python, Excel/CSV processing, ETL |
| Visualization | Google Data Studio, dashboard design |
| AI / insight generation | LLM APIs, prompt engineering, AI agents (Claude) |
| Delivery | PDF export, web deployment |

---

## About

Built and maintained by **Tan Xin Ru** as part of AIESEC in Malaysia's Organization Development function.

📫 [LinkedIn](https://www.linkedin.com/in/your-linkedin) · ✉️ tanxinru05@gmail.com

> *Data in this repository has been anonymized / uses sample values where necessary to protect organizational confidentiality.*
