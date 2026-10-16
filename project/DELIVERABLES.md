# Required Deliverables

## D1 — Discovery, Decision & Requirements Pack
**Due:** Week 1  
**Location:** `docs/01-discovery/`

Required: decision statement; stakeholder map; as-is/to-be process; at least 8 prioritised functional/user requirements; non-functional requirements; assumptions/dependencies; acceptance criteria mapped to requirements.

**Acceptance:** every planned dashboard/analysis feature maps to an approved requirement.

## D2 — Data Governance & Source Control Pack
**Due:** Week 2  
**Location:** `docs/02-data-governance/`, `data/SOURCE_REGISTER.md`

Required: source inventory; frozen version; glossary; critical data elements; owner/steward assumptions; lineage; DQ rules; reuse notes; governance risks.

**Acceptance:** every headline KPI traces to governed source fields and definition.

## D3 — Reproducible Ingestion & Analytical Model
**Due:** Week 3  
**Location:** `src/`, `sql/`, `docs/03-data-model/`

Required: load process; raw preservation; schema/type checks; standardisation; keys/grain; curated table(s); rerun instructions; exceptions.

**Acceptance:** identical frozen input produces equivalent curated output on clean rerun.

## D4 — Data Quality, Reconciliation & Exceptions
**Due:** Week 3  
**Location:** `docs/04-data-quality/`, `tests/`

Required: row reconciliation; duplicate checks; missingness; accepted values/ranges; exception log; inclusion/exclusion rules.

**Acceptance:** every material record loss/exclusion is quantified and explained.

## D5 — KPI & Metric Catalogue
**Due:** Week 4  
**Location:** `docs/05-kpi-catalogue/`

Minimum metrics:
- complaints per 100,000 or published denominator;
- quarter-on-quarter change;
- year-on-year change where history allows;
- provider rank within service with caveat;
- distance from service median/benchmark;
- persistent above-benchmark quarters;
- largest deterioration/improvement;
- service-level median;
- data continuity flag;
- provider/service coverage count;

Each metric: purpose, definition, formula, grain, source, exclusions, owner, refresh expectation, limitation.

## D6 — Core Analytical Assessment I
**Due:** Week 5  
**Location:** `analysis/`, `docs/06-analysis/`

Required:
- provider/service benchmarking;
- trend persistence;
- quarterly deterioration/improvement;
- service-type comparison;

Each major finding must state comparison basis, materiality and limitation.

## D7 — Core Analytical Assessment II & Decision Framework
**Due:** Week 6  
**Location:** `docs/07-decision-framework/`

Required:
- root-cause priority segmentation;
- trend-break review;
- threshold sensitivity;
- provider/service continuity exceptions;
- explicit factors/thresholds;
- rationale;
- at least one sensitivity test;
- manual-review triggers;
- evidence insufficient for action.

## D8 — BI / Decision-Support Product
**Due:** Draft Week 6; final Week 7  
**Location:** `dashboard/`

Required: executive view; diagnostic drill-down; governed measures only; source/reporting period; definitions/quality notes; usable filters; accessibility/readability; reproducible build/access instructions.

**Acceptance:** at least five headline measures reconcile to curated data.

## D9 — Assurance & UAT
**Due:** Week 7  
**Location:** `docs/08-assurance-uat/`

Required: minimum 10 scenarios; calculation/filter/edge-case checks; reconciliation; defect log; requirement-to-test traceability; UAT feedback; acceptance status.

## D10 — Technical & Operational Handover
**Due:** Week 8  
**Location:** `docs/09-technical-handover/`

Required: setup; run/refresh; architecture/data flow; transformations; metric logic; tests; troubleshooting; limitations; maintenance/change guidance.

## D11 — Executive Briefing & Presentation
**Due:** Week 8  
**Location:** `deliverables/`

Maximum two-page briefing plus 15–20 minute presentation. Both state decision, evidence, recommendation/investigation, limitations and next steps.

## D12 — Contribution & Delivery Evidence
**Due:** Final submission  
**Location:** `CONTRIBUTIONS.md`

For each member: role, owned work packages, artefacts, linked issues/PRs/commits, review contribution and presentation contribution. Commit count alone is insufficient.
