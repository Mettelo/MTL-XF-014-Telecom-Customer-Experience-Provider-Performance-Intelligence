# Business Context

## Business Problem

Customer-experience teams across broadband, mobile and pay-TV often review provider complaints separately. Leadership can see quarterly league tables, but this does not automatically show whether a provider is experiencing a persistent deterioration, a one-quarter spike, a service-specific problem or a wider customer-experience issue.

This makes it difficult to decide where to direct root-cause analysis, retention activity or service-improvement effort. A provider may look weak in one service and strong in another, while short-term movement may be mistaken for a sustained trend.

The business problem is therefore to turn quarterly Ofcom complaint data into a longitudinal provider/service intelligence product that distinguishes persistent issues from temporary noise.

## Required Delivery Response

The team is expected to build a quarterly customer-experience performance solution.

The work should include:
- defining the root-cause investigation and intervention decisions;
- creating consistent provider/service reference data;
- preserving the exact published complaint-rate units and denominators;
- building a multi-quarter history;
- logging provider, service or publication changes that affect comparability;
- identifying persistent deterioration and improvement;
- distinguishing one-quarter spikes from sustained trends;
- comparing provider performance only within appropriate service groups;
- developing transparent investigation-priority rules;
- building executive and diagnostic BI;
- reconciling selected provider/quarter values to the source;
- completing UAT and handover.

## How the Client Will Use the Output

The finished product should support a Customer Experience Director reviewing quarterly performance. They should be able to identify a broadband provider whose complaint rate has remained above the service benchmark for several quarters, distinguish that from a temporary spike, and drill into the service trend before deciding whether a root-cause investigation is justified.

The product is intended to focus investigation. It is not a complete measure of customer satisfaction, network reliability or churn.

## Simulated Client
**Confidential UK Telecom Strategy & Customer Experience Directorate**

## Current Problem
Customer-experience teams discuss broadband, mobile and pay-TV complaints in separate operational forums. Leadership lacks a consistent evidence base that distinguishes provider scale, service type and persistent complaint deterioration, making intervention priorities unclear.

## Decision Owner
**Customer Experience Director**

## Senior Stakeholders
Head of Broadband, Mobile Product Lead, Customer Operations Lead, Churn & Retention Lead, Regulatory Affairs Lead, Data Governance Lead, Customer Insight Lead

## Decision
**Which provider/service combinations warrant the earliest root-cause investigation or customer-experience intervention, and what evidence should be monitored before resources are redirected?**

## Role Responsibilities
| Role | Required contribution |
|---|---|
| Business Analyst | Map customer-experience decisions, requirements, users and intervention criteria. |
| Data Governance Analyst | Govern provider/service master data, metric definitions, period comparability and lineage. |
| Data Engineer | Build quarterly ingestion/history and validation pipeline. |
| Customer Insight/Data Analyst | Own benchmarking, persistence and trend-break analysis. |
| BI Developer | Build provider/service performance dashboard and drill-down. |
| Product Analyst | Translate findings into testable service/product hypotheses. |
| Assurance Analyst | Own reconciliation, threshold challenge and UAT. |

## Evidence Chain
**Requirement → governed definition → transformation → quality control → metric/analysis → decision insight → recommendation → UAT**

Major recommendations must be traceable through this chain.
