**English** | [繁體中文](README_ZH-TW.md)

# Kane Wang | Data Analytics & Business Analysis

> Data analytics and business analysis across manufacturing, supply chain, and financial risk management

Transforms operational challenges and decision-making needs into clearly defined data definitions, business rules, and cross-functional accountabilities. Applies Python, SQL, Power BI, and Microsoft Power Platform to operationalize analytical logic as governed, traceable, and sustainable data and decision platforms.

Brings end-to-end project delivery experience—from requirements clarification and process and data design to system integration, testing, deployment, ongoing operations, maintenance, and continuous improvement. The work extends beyond producing analytical outputs to embedding analytics into day-to-day operations and decision-making.

Representative projects include minimum-cost BOM and inventory decision platforms supporting more than **50 raw materials and approximately NT$1 billion in monthly raw material costs**, as well as a pre-recognition FX risk management system that processes approximately **USD 100 million in internal FX transaction volume per month** and has operated reliably for more than four years.

## Core Capabilities

- **Business and Process Analysis:** Analyze operational needs, current-state processes, decision scenarios, business rules, and cross-functional accountabilities, translating them into actionable system and analytical requirements.
- **Data Analytics and Governance:** Use Python and SQL to integrate data across systems, perform data cleansing and transformation, calculate metrics, and implement analytical models. Establish consistent data definitions, sources, ownership, and version controls to ensure reliable, traceable, and reproducible results.
- **Digital Solution Delivery:** Integrate enterprise systems, analytical models, and downstream platforms using Power BI, Power Automate, Power Apps, Teams, and Flask APIs. Build sustainable automated workflows and proactive alerting mechanisms, and manage testing, deployment, incident handling, and ongoing maintenance so that data and analytics support daily operations and decision-making.
- **Domain Expertise:** Manufacturing operations, raw material supply chains, cost management, data quality, and foreign exchange risk management.

## Selected Projects

These projects span manufacturing, supply chain, data governance, and financial risk management. Together, they demonstrate how operational needs can be translated into process analysis, data integration, rule design, system implementation, and decision support. Follow each link for the business context, system architecture, and implementation details.

### 1. [Lowest-Cost BOM Data and Decision Platform](https://github.com/ChienChienChien/BOM_Management_Platform)

Integrates the data, rules, and operating workflows required by a lowest-cost BOM model into a sustainable decision platform, enabling model outputs to support raw material planning and shop-floor production.

- **Data Governance and Cross-Functional Collaboration:** Integrates cross-functional data—including raw material constraints,raw material composition,raw material price, and production plans—and establishes consistent definitions, ownership, and validation workflows.
- **Model Operationalization and System Integration:** Embeds the lowest-cost BOM model into existing operational processes to support both raw material planning and real-time calculations for MES, while retaining input versions and execution results for traceability.
- **Decision Support and Outcome Validation:** Uses Power BI to compare theoretical BOM results with actual material consumption, creating a validation and continuous-improvement mechanism. The platform supports more than **50 raw materials** and approximately **NT$1 billion in monthly raw material costs**.

> The core minimum-cost BOM model, raw material price calculations, and cost management were owned by other team members. This case focuses on data governance, process design, system integration, and model operationalization.

### 2. [Raw Material Inventory Forecasting and Alert System](https://github.com/ChienChienChien/Material_Forecasting_System)

Integrates supply and demand data distributed across multiple systems to forecast future inventory and provide risk alerts, helping stakeholders identify potential shortages early and take action.

- **Supply Chain Data Integration:** Connects inventory, purchasing, goods receipt, production planning, and raw material requirement data, transforming sources with different structures and time granularities into a consistent daily supply-and-demand view.
- **Business Metrics and Alert Design:** Defines inventory metrics and tiered alert logic based on actual inspection, release, and consumption conditions, highlighting projected shortage dates, risk levels, and underlying causes.
- **Workflow Automation and Decision Support:** Replaces approximately **three hours of weekly manual data preparation** with daily automated forecasts, Power BI visualizations, and proactive Teams alerts, supporting supply-and-demand management for more than **50 raw materials**.

### 3. [Data Quality Monitoring Platform](https://github.com/ChienChienChien/Manufacturing_Data_Quality_Monitoring)

Creates a quality control layer before data enters reports, analytical models, and operational decisions, enabling the system to proactively detect, notify, and track data issues.

- **Data Quality Rule Design:** Defines validation rules for data timeliness, completeness, and basic structure based on downstream analytical requirements, making quality standards systematically executable.
- **Automated Monitoring Workflow:** Runs daily checks with Python and Great Expectations, integrating SQL Server, Power BI, Power Automate, and Teams into an end-to-end detection and notification workflow.
- **Analytics Governance and Traceability:** Centralizes validation summaries, rule-level details, and historical results to accelerate issue diagnosis, track quality trends, and support expansion to additional data sources and analytical workflows.

### 4. [Pre-Recognition FX Exposure Transfer System](https://github.com/ChienChienChien/FX_Hedging_Automation)

Moves the point of FX risk management forward from accounts receivable and payable recognition to the initiation of foreign-currency transactions, allowing pre-recognition exposures to be captured and centrally managed through internal transactions.

- **Financial Process and Transaction Lifecycle Analysis:** Integrates sales, procurement, accounting recognition, and exchange-rate data, translating business events into traceable FX exposures and internal transaction workflows.
- **Systematized Complex Rules and Cross-System Integration:** Establishes mechanisms for transaction creation, amendment, reversal, and maturity processing, while synchronizing results with position and risk management processes so that manual intervention is limited to exceptions.
- **Operational Scale and System Reliability:** Processes approximately **USD 100 million in internal FX transaction volume per month** and has operated reliably in production for more than four years. The system manages internal risk transfers; decisions on whether, when, and how to execute external hedging remain independently owned by the risk management function.

---

This portfolio presents only de-identified business contexts, analytical logic, data flows, and system architectures. It excludes proprietary company data, actual parameters, connection details, complete internal rules, and unredacted source code.
