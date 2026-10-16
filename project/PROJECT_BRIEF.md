# Project Brief

## Engagement Details

| Field | Detail |
|---|---|
| Project ID | MTL-XF-014 |
| Project Title | Telecom Customer Experience & Provider Performance Intelligence |
| Client | Confidential UK Telecom Strategy & Customer Experience Directorate |
| Sector | Telecommunications / Customer Experience |
| Duration | 8 weeks |
| Recommended Team Size | 6–8 |
| Primary Sponsor | Customer Experience Director |
| Senior Stakeholders | Head of Broadband, Mobile Product Lead, Customer Operations Lead, Churn & Retention Lead, Regulatory Affairs Lead, Data Governance Lead, Customer Insight Lead |
| Primary Dataset | Ofcom Telecoms and Pay-TV Complaints — quarterly underlying data |

## 1. Client Situation
Customer-experience teams discuss broadband, mobile and pay-TV complaints in separate operational forums. Leadership lacks a consistent evidence base that distinguishes provider scale, service type and persistent complaint deterioration, making intervention priorities unclear.

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
