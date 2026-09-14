# EDL Monitoring Platform & Data Analytics

> **Project Recovery | Data Transformation | Data Engineering | Observability | Governance | Compliance | Power BI**

## Overview

A project recovery initiative focused on transforming a significantly delayed EDL monitoring project into an operational, higher-value data and analytics platform.

The initiative combined **data engineering, pipeline orchestration, automated monitoring and alerting, data quality, governance, security, analytics, incident management, and privacy/compliance monitoring** into a cohesive solution.

> **Recovery outcome:** Took over a project 3 months past its original delivery date with only a Functional Design Document delivered, diagnosed the underlying delivery challenges, rebuilt the delivery approach, and delivered an expanded solution within **5 months**.

---

## The Challenge

The project had been underway for 12 months but had produced only a Functional Design Document and was already **3 months beyond its original delivery target**.

Initial assessment identified significant:

* Resource and skillset gaps
* Delivery capability constraints
* Misalignment between scope and business value
* Data and integration complexities
* Pipeline monitoring and operationalization gaps
* Data quality and governance requirements
* Security and privacy considerations
* Need for automated operational response

The objective was not simply to complete the original scope, but to **recover the initiative while increasing the value delivered to the business**.

---

## Project Recovery Approach

I led the recovery through a structured approach:

**Diagnose → Stabilize → Align → Prioritize → Execute → Operationalize**

### 1. Diagnose

* Assessed the existing project state
* Identified resource and capability gaps
* Evaluated delivery dependencies and constraints
* Reviewed scope against business needs
* Identified risks to successful implementation

### 2. Stabilize

* Established a realistic recovery plan
* Addressed critical skillset and resource gaps
* Re-established delivery priorities
* Clarified ownership and accountability
* Increased visibility into risks, dependencies, and milestones

### 3. Realign

* Re-engaged business and technical stakeholders
* Validated requirements and expected outcomes
* Re-scoped the initiative around higher-value capabilities
* Balanced business value against time and resource constraints

---

## Solution Architecture

The recovered solution incorporated a **Medallion Architecture** to support scalable, governed data processing.

```text
Source Systems
      │
      ▼
┌──────────────┐
│    Bronze    │
│ Raw / Landing│
└──────┬───────┘
       │
       ▼
┌──────────────┐
│    Silver    │
│ Cleaned /    │
│ Transformed  │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│     Gold     │
│ Curated /    │
│ Business     │
│ Ready Data   │
└──────┬───────┘
       │
       ├──────────────► Data Quality
       │
       ├──────────────► Governance
       │
       ├──────────────► Security
       │
       └──────────────► Monitoring
                              │
                ┌─────────────┴─────────────┐
                │                           │
                ▼                           ▼
        Automated Alerts            Incident Management
                │                           │
                ▼                           ▼
         Email Notifications       Jira / ServiceNow
                │
                ▼
        ┌─────────────┐
        │   Power BI  │
        │  Dashboards │
        └─────────────┘
```

---

## Key Capabilities Delivered

### Data Engineering

* Medallion-architecture data pipeline
* Data ingestion and transformation
* Structured data processing
* Curated business-ready data

### Pipeline Orchestration & Observability

The solution introduced automated operational monitoring across the data pipeline lifecycle.

Capabilities included:

* Automated pipeline orchestration
* Pipeline refresh monitoring
* Pipeline health monitoring
* Monitoring of successful and failed refreshes
* Threshold-based monitoring
* Automated operational alerting

### Automated Email Alerting

Email notifications were implemented to provide timely visibility into pipeline execution.

Alerts were triggered for:

* Successful pipeline refreshes
* Failed pipeline refreshes
* Relevant pipeline health conditions
* Data quality or monitoring threshold breaches

This provided stakeholders and support teams with immediate visibility into pipeline status without requiring manual monitoring.

### Automated Incident Management

The monitoring framework was extended beyond notification into **automated incident creation**.

When defined data quality or monitoring thresholds were exceeded, the solution automatically initiated tickets in:

* **Jira**
* **ServiceNow**

This created a closed-loop operational process:

```text
Data Pipeline
     │
     ▼
Monitoring
     │
     ▼
Threshold Evaluation
     │
 ┌───┴────┐
 │        │
Pass    Breach
 │        │
 ▼        ▼
Continue  Alert
          │
          ▼
   Email Notification
          │
          ▼
   Automated Ticket
          │
      ┌───┴────┐
      ▼        ▼
    Jira   ServiceNow
```

This reduced dependence on manual detection and escalation and provided a more structured mechanism for responding to data and pipeline issues.

### Data Quality

* Embedded data quality checks
* Threshold-based monitoring
* Validation of critical data flows
* Automated escalation when defined thresholds were exceeded
* Improved confidence in downstream analytics

### Security & Governance

* Data security controls
* Access management
* Governance processes
* Controlled handling of sensitive data
* Monitoring aligned with applicable organizational requirements

### Analytics

* Power BI dashboards
* Business-facing monitoring and reporting
* Operational visibility
* Data-driven decision support

### Privacy & Compliance

The solution incorporated monitoring and reporting considerations for applicable privacy and regulatory requirements, including:

* PIPEDA
* SOX
* HIPAA
* Other applicable regulatory frameworks

---

## Operational Monitoring & Incident Management

A key aspect of the recovered solution was moving from **passive reporting to proactive operational monitoring**.

The platform provided visibility across the data lifecycle:

| Capability              | Outcome                                            |
| ----------------------- | -------------------------------------------------- |
| Pipeline monitoring     | Visibility into pipeline health                    |
| Refresh monitoring      | Identification of successful and failed executions |
| Email alerting          | Timely notification to stakeholders/support teams  |
| Data quality thresholds | Automated identification of quality issues         |
| Monitoring thresholds   | Detection of abnormal conditions                   |
| Jira integration        | Automated incident/ticket creation                 |
| ServiceNow integration  | Automated service-management escalation            |
| Power BI                | Business and operational visibility                |

The result was an operational model in which issues could be **detected, communicated, and routed for resolution automatically**.

---

## Project Management & Leadership

The recovery required management across:

* Scope
* Schedule
* Resources
* Budget constraints
* Stakeholders
* Risks and dependencies
* Technical delivery
* Business requirements
* Governance and compliance
* Operational readiness

A key focus was balancing **speed of recovery with long-term operational sustainability**, rather than simply delivering a minimum viable version of the original scope.

---

## Outcome

Within **5 months of taking over the initiative**, the project moved from a significantly delayed state with only an FDD completed to an expanded, operational data and analytics platform providing:

* Automated data pipelines
* Pipeline orchestration
* Pipeline health monitoring
* Successful/failed refresh notifications
* Automated email alerting
* Data quality threshold monitoring
* Automated Jira and ServiceNow ticket creation
* Security and governance controls
* Privacy/compliance monitoring
* Business-facing Power BI analytics
* A scalable foundation for future data capabilities

### Recovery Transformation

```text
12 Months of Prior Delivery
            │
            ▼
   FDD Only + 3 Months Late
            │
            ▼
      Project Recovery
            │
     ┌──────┴──────┐
     │             │
Resource Gaps   Scope Reset
     │             │
     └──────┬──────┘
            ▼
        5 Months
            │
            ▼
Expanded Operational
Data & Analytics Platform
            │
            ▼
   Automated Monitoring
            │
            ▼
 Automated Incident Management
       Jira / ServiceNow
```

---

## My Role

**Project Recovery & Transformation Project Manager**

Responsibilities included:

* Project recovery strategy
* Stakeholder management
* Scope management
* Schedule recovery
* Resource planning
* Risk and dependency management
* Budget management
* Delivery governance
* Business and technical alignment
* Data and analytics delivery oversight
* Operational readiness
* Compliance and governance coordination

---

## Technology & Capability Areas

`Project Recovery` `Data Engineering` `Medallion Architecture` `Data Pipelines` `Pipeline Orchestration` `Data Observability` `Monitoring` `Alerting` `Incident Management` `Jira` `ServiceNow` `Data Quality` `Data Governance` `Data Security` `Power BI` `Analytics` `Privacy` `PIPEDA` `SOX` `HIPAA` `Project Management` `Stakeholder Management`

---

## Note

This case study describes the project at a high level. Specific organizational, architectural, security, data-source, integration, workflow, and implementation details have been intentionally omitted or generalized to protect confidential information.
