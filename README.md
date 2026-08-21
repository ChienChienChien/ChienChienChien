**English** | [繁體中文](README_ZH-TW.md)

# Kane Wang | Data & Business Analyst

> Specializing in data and business analysis across manufacturing, supply chain, and financial risk management

Specializes in turning operational challenges and decision needs into practical data and system solutions—aligning stakeholders on data definitions, business rules, and ownership, then using Python, SQL, Power BI, and Microsoft Power Platform to build governed, traceable data and decision platforms for sustained operational use.

Experience spans the full delivery lifecycle, from requirements discovery and process and data design through system integration, testing, deployment, production support, and continuous improvement. The focus is not simply on producing analysis, but on embedding it into day-to-day operations and decision-making.

Selected work includes a minimum-cost BOM platform and an inventory forecasting system supporting more than **50 raw materials** and approximately **NT$1 billion in monthly material spend**. It also includes an FX risk management system that captures exposures before accounting recognition, handles approximately **USD 100 million in internal FX transactions each month**, and has run reliably for more than four years.

## Core Capabilities

- **Business and Process Analysis:** Breaks down operational needs, current workflows, decision scenarios, business rules, and cross-functional responsibilities, then translates them into clear, actionable requirements for analytics and systems.
- **Data Analytics and Governance:** Uses Python and SQL to integrate data across systems, clean and transform datasets, define metrics, and implement analytical models. Establishes shared definitions, clear ownership for source data and ongoing maintenance, and version control so outputs remain reliable, traceable, and reproducible.
- **Digital Solution Delivery:** Connects enterprise systems, analytical models, and downstream applications through Power BI, Power Automate, Power Apps, Teams, and Flask APIs. Delivers production-ready automated workflows and proactive alerts, covering testing, deployment, exception handling, and ongoing support so analysis becomes part of everyday operations and decisions.
- **Domain Expertise:** Manufacturing operations, raw material supply chains, cost management, data quality, and foreign exchange risk management.

## Selected Projects

The projects below show how operational needs were translated into data foundations, business rules, integrated workflows, and decision-support tools across manufacturing, supply chain, data governance, and financial risk management. Each project page provides additional context, architecture, and implementation details.

### 1. [Minimum-Cost BOM Decision Platform](https://github.com/ChienChienChien/BOM_Management_Platform)

Brings together the data, rules, and operating workflows required to run a minimum-cost BOM model as a production decision platform, supporting both raw material planning and shop-floor execution.

- **Data Governance and Cross-Functional Alignment:** Brings together cross-functional inputs—including raw material constraints, composition data, pricing, and production plans—and establishes shared definitions, ownership, and validation procedures.
- **Model Deployment and System Integration:** Integrates the minimum-cost BOM model into existing workflows for raw material planning and real-time calculations initiated through MES, while preserving input versions and run results for traceability.
- **Decision Support and Performance Validation:** Uses Power BI to compare theoretical BOM recommendations with actual material consumption, creating a feedback loop for validation and continuous improvement. The platform covers more than **50 raw materials** and approximately **NT$1 billion in monthly material costs**.

> The minimum-cost BOM model itself, raw material price calculations, and cost management were handled by other team members. This case focuses on data governance, process design, system integration, and putting the model into production.

### 2. [Raw Material Inventory Forecasting and Alert System](https://github.com/ChienChienChien/Material_Forecasting_System)

Combines supply and demand data from multiple systems to project future inventory levels and flag shortage risks early enough for teams to act.

- **Supply Chain Data Integration:** Brings together inventory, purchase orders, inbound deliveries, production plans, and raw material requirements. Data from different systems and time intervals is standardized into a daily supply-and-demand view.
- **Business Metrics and Alert Design:** Defines inventory metrics and tiered alerts around actual inspection, release, and consumption conditions, showing when a shortage is expected, how severe it is, and what is driving it.
- **Workflow Automation and Decision Support:** Replaces roughly **three hours of manual preparation each week** with daily automated forecasts, Power BI dashboards, and proactive Teams alerts, supporting supply-and-demand planning for more than **50 raw materials**.

### 3. [Data Quality Monitoring Platform](https://github.com/ChienChienChien/Manufacturing_Data_Quality_Monitoring)

Adds a control layer before data reaches reports, analytical models, or operational decisions, allowing quality issues to be detected, communicated, and tracked proactively.

- **Data Quality Rule Design:** Defines executable checks for data timeliness, completeness, and basic structure based on downstream analytical needs.
- **Automated Monitoring Workflow:** Runs daily checks with Python and Great Expectations, connecting SQL Server, Power BI, Power Automate, and Teams in an end-to-end detection and notification workflow.
- **Analytics Governance and Traceability:** Stores validation summaries, rule-level results, and historical runs in one place, making it easier to diagnose issues, monitor quality trends, and extend the framework to additional data sources and analytical workflows.

### 4. [Automated FX Risk Transfer for Pre-Recognition Exposures](https://github.com/ChienChienChien/FX_Hedging_Automation)

Extends FX risk management upstream from the recognition of accounts receivable and payable to the point when a foreign-currency sale or purchase is committed. This allows exposures that arise before accounting recognition to be captured and transferred to central risk management through internal trades.

- **Financial Process and Trade Lifecycle Analysis:** Combines sales, purchasing, receivables and payables recognition, and exchange-rate data, translating business events into traceable FX positions and standardized internal trades.
- **Business Rule Automation and System Integration:** Implements rules for trade creation, amendment, reversal, and maturity, then feeds the resulting positions into position and risk management processes. Manual work is reserved for exceptions.
- **Operational Scale and Reliability:** Handles approximately **USD 100 million in internal FX trades each month** and has run reliably in production for more than four years. The system transfers risk internally; the risk management team independently decides whether, when, and how to hedge externally.

---

This portfolio contains de-identified descriptions of business context, analytical logic, data flows, and system architecture. It does not include proprietary source data, production parameters, credentials or connection details, complete internal rules, or unredacted code.
