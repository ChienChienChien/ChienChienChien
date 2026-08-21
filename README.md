**English** | [繁體中文](README_ZH-TW.md)

# Kane Wang | Data & Business Analyst

> Data and business analysis for manufacturing, supply chain, and financial risk management

Turns operational challenges and decision needs into practical data and system solutions by aligning stakeholders on data definitions, business rules, and ownership, then using Python, SQL, Power BI, and Microsoft Power Platform to build governed, traceable data platforms and decision-support systems for sustained operational use.

Experience spans the full delivery lifecycle, from requirements discovery and process and data design through system integration, testing, deployment, production support, and continuous improvement. The focus is not simply on producing analysis, but on embedding it into day-to-day operations and decision-making.

Selected work includes the Lowest-Cost BOM Data and Decision Platform and the Raw Material Inventory Forecasting and Stockout Alert System, which together support more than **50 raw materials representing approximately NT$1 billion in monthly material costs**. It also includes a pre-recognition FX exposure management solution that processes approximately **USD 100 million in internal FX transaction volume per month** and has operated reliably in production for more than four years.

## Core Capabilities

- **Business and Process Analysis:** Breaks down operational needs, current workflows, decision scenarios, business rules, and cross-functional responsibilities, then translates them into clear, actionable requirements for analytics and systems.
- **Data Analytics and Governance:** Uses Python and SQL to integrate data across systems, clean and transform datasets, define metrics, and implement analytical models. Establishes shared data definitions, sources, ownership, validation methods, and version controls so results remain reliable, traceable, and reproducible.
- **Digital Solution Delivery:** Integrates enterprise systems, analytical models, and downstream applications using Power BI, Power Automate, Power Apps, Teams, and Flask APIs. Delivers production-ready automated workflows and proactive alerts, covering testing, deployment, exception handling, and ongoing support so data and analysis become part of daily operations and decision-making.
- **Domain Expertise:** Manufacturing operations, raw material supply chains, cost management, data quality, and foreign exchange risk management.

## Selected Projects

The projects below show how operational needs were translated into shared data foundations, business rules, cross-system workflows, and decision-support tools across manufacturing, supply chain, data governance, and financial risk management. Each project page provides additional context, architecture, and implementation details.

### 1. [Lowest-Cost BOM Data and Decision Platform](https://github.com/ChienChienChien/BOM_Management_Platform/blob/main/README.md)

Brings together the cross-functional data, business rules, and usage workflows required by the lowest-cost BOM model in a governed, traceable operations platform that supports both raw material planning and real-time shop-floor production.

- **Data Governance and Cross-Functional Collaboration:** Standardizes the definitions, sources, ownership, and validation methods for raw material quantity limits, raw material composition, raw material prices, and production plans.
- **Model Deployment and System Integration:** Deploys the lowest-cost BOM model across weekly planning and real-time shop-floor production, while linking each run's input versions and BOM output through a unique run key for traceability.
- **Decision Support and Validation:** Uses Power BI to track changes in raw-material demand and compare theoretical BOMs with actual material usage, supporting validation and continuous improvement. The platform supports more than **50 raw materials representing approximately NT$1 billion in monthly material costs**.

> The core lowest-cost BOM model, raw material price calculations, and cost management were handled by other members of the team. This case focuses on data governance, process design, system integration, and model deployment.

### 2. [Raw Material Inventory Forecasting and Stockout Alert System](https://github.com/ChienChienChien/Material_Forecasting_System/blob/master/README.md)

Integrates data across systems to produce daily raw-material inventory forecasts, identify stockout risks early, and support timely response actions.

- **Supply Chain Data Integration:** Combines inventory, purchase orders, inbound receipts, production plans, and BOM data in a daily supply-and-demand forecast for the next three months.
- **Management Metrics and Tiered Alerts:** Uses Total Inventory and Available Inventory to distinguish recorded stock from material that has been released for production, and classifies risk based on expected stockout dates.
- **Daily Automated Monitoring and Decision Support:** Replaces approximately **three hours of manual data consolidation and inventory forecasting each week** with daily data refreshes, rolling forecasts, Power BI dashboards, and Teams alerts. The system covers more than **50 raw materials representing approximately NT$1 billion in monthly material costs**.

### 3. [Data Quality Monitoring Platform](https://github.com/ChienChienChien/Manufacturing_Data_Quality_Monitoring/blob/main/README.md)

Implements an automated monitoring and alerting framework that validates data freshness, completeness, and schema integrity before data moves from the data warehouse into downstream reports, analytical models, and decision-making workflows.

- **Data Quality Rule Design:** Defines executable checks for data freshness, completeness, and schema integrity based on downstream analytical requirements.
- **Automated Daily Validation and Alerts:** Runs daily checks with Python and Great Expectations, writes validation summaries and rule-level details to SQL Server, refreshes monitoring in Power BI, and sends anomaly notifications through Power Automate and Teams.
- **Centralized Monitoring and Traceability:** Stores validation summaries, rule-level details, and historical records centrally, making it easier to identify affected tables and failed rules, monitor data quality over time, and extend the framework to additional data sources and analytical workflows.

### 4. [Pre-Recognition FX Exposure Management via Automated Internal FX Transactions](https://github.com/ChienChienChien/FX_Hedging_Automation/blob/main/README.md)

Shifts the start of FX exposure management upstream—from A/R and A/P recognition to the confirmation of foreign-currency sales contracts and purchase commitments—so that pre-recognition exposures can be captured and centrally managed through standardized internal FX transactions.

- **Risk Management Rules and Exposure Lifecycle:** Defines risk ownership, exposure management periods, applicable currencies, and exchange-rate conventions, then converts them into consistent data rules and transaction logic for internal FX transfers.
- **Business-Event Detection and Downstream Integration:** Integrates sales, procurement, A/R and A/P recognition, exchange-rate, and existing-position data to detect exposure inception, amount adjustments, cancellations, and close-out upon accounting recognition. Generated transactions are posted to PAS and RMD, with manual intervention limited to exceptions.
- **Operational Scale and Risk Governance:** Processes approximately **USD 100 million in internal FX transaction volume per month** across sales and procurement and has operated reliably in production for more than four years. Any decision to hedge externally—including whether, when, and how—is made independently by the risk management function and remains outside the system's scope.

---

This portfolio contains de-identified descriptions of business context, analytical logic, data flows, and system architecture. It does not include proprietary source data, production parameters, credentials or connection details, complete internal rules, or unredacted code.
