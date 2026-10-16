# Project Brief

## 1. Business Problem

Customer-experience teams across broadband, mobile and pay-TV often review provider complaints separately. Leadership can see quarterly league tables, but this does not automatically show whether a provider is experiencing a persistent deterioration, a one-quarter spike, a service-specific problem or a wider customer-experience issue.

This makes it difficult to decide where to direct root-cause analysis, retention activity or service-improvement effort. A provider may look weak in one service and strong in another, while short-term movement may be mistaken for a sustained trend.

The business problem is therefore to turn quarterly Ofcom complaint data into a longitudinal provider/service intelligence product that distinguishes persistent issues from temporary noise.

## What the Team Needs to Do

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

## Practical Use Case

The finished product should support a Customer Experience Director reviewing quarterly performance. They should be able to identify a broadband provider whose complaint rate has remained above the service benchmark for several quarters, distinguish that from a temporary spike, and drill into the service trend before deciding whether a root-cause investigation is justified.

The product is intended to focus investigation. It is not a complete measure of customer satisfaction, network reliability or churn.

## 2. Business Decision
> **Which provider/service combinations warrant the earliest root-cause investigation or customer-experience intervention, and what evidence should be monitored before resources are redirected?**

Charts without a defensible decision framework do not satisfy the commission.

## 3. Agreed Objectives
1. Create a consistent quarterly provider/service history from Ofcom complaint-rate releases.
2. Define governed provider, service and reporting-period reference data.
3. Identify persistent deterioration and meaningful provider/service variation rather than single-quarter noise.
4. Develop a transparent intervention-prioritisation framework tied to customer-experience questions.
5. Build an executive and diagnostic BI product that retains Ofcom metric definitions and caveats.

## 4. Key Business Questions
1. Which provider/service complaint rates are materially above the relevant comparison group?
2. Which deteriorations persist across multiple quarters?
3. Where are short-term spikes inconsistent with the longer trend?
4. How do broadband, mobile and pay-TV complaint patterns differ?
5. Which publication or provider changes affect comparability over time?
6. What evidence should trigger root-cause investigation rather than immediate commercial action?

## 5. Cross-Functional Roles
| Role | Minimum expected output |
|---|---|
| Business Analyst | Map customer-experience decisions, requirements, users and intervention criteria. |
| Data Governance Analyst | Govern provider/service master data, metric definitions, period comparability and lineage. |
| Data Engineer | Build quarterly ingestion/history and validation pipeline. |
| Customer Insight/Data Analyst | Own benchmarking, persistence and trend-break analysis. |
| BI Developer | Build provider/service performance dashboard and drill-down. |
| Product Analyst | Translate findings into testable service/product hypotheses. |
| Assurance Analyst | Own reconciliation, threshold challenge and UAT. |

## 6. Minimum Delivery Standard
- traceable requirements and acceptance criteria;
- governed definitions, ownership, lineage and data-quality rules;
- preserved raw source and reproducible transformations;
- explicit reconciliation and exception handling;
- domain-specific analytical outputs;
- transparent prioritisation/intervention logic;
- governed stakeholder-facing BI;
- assurance/UAT evidence;
- reproducible handover and visible collaboration.

## 7. Constraints
- Ofcom complaints are complaints received by Ofcom, not all complaints made to providers.
- Complaint rates do not directly measure churn, network reliability or overall satisfaction.
- Provider entry/exit and publication methodology changes may affect longitudinal comparison.
- Different services must not be combined into one score without justification.
- Priority flags are investigation signals, not definitive quality ratings.

## 8. Agreed Success Criteria
- Complaint rates are stored and displayed with the exact published unit/denominator.
- At least four quarters are used where available to distinguish persistence from a one-quarter spike.
- Provider/service changes affecting comparability are recorded in a continuity log.
- At least five dashboard values reconcile to Ofcom source data for selected provider/period combinations.
- No overall provider score combines unrelated services without an explicit approved weighting method.
- Priority flags require documented persistence/materiality rules.

## 9. Out of Scope
Core delivery does not require confidential customer-level data, paid production infrastructure, automated operational decisions or unsupported causal inference.

## 10. Reproducibility Definition
A reviewer should be able to clone the team repository, obtain the documented approved source data, run the workflow and reproduce the curated analytical outputs and validation evidence without undocumented manual changes.
