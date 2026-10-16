# Data Guidance

## Approved Core Source

Use Ofcom's **Telecoms and Pay-TV complaints quarterly underlying CSV data**.

Official source:
https://www.ofcom.org.uk/telecoms-and-pay-tv-complaints

## Required Time Scope

This project should **not** rely on one quarter only.

Recommended core history:
- minimum: **4 consecutive quarters**;
- preferred: **8 quarters** where provider/service definitions remain comparable.

Use **Q1 2026** as the latest frozen reference quarter for the cohort, then add the preceding quarters needed to build the history.

## Why Multiple Quarters Are Required

The project must distinguish:
- persistent deterioration;
- persistent improvement;
- temporary spikes;
- service-specific issues.

A single quarter cannot support those conclusions.

## What to Put in `data/raw/`

Store one untouched CSV per quarter:

```text
data/raw/
├── ofcom-telecom-complaints-2024-q2.csv
├── ofcom-telecom-complaints-2024-q3.csv
├── ...
└── ofcom-telecom-complaints-2026-q1.csv
```

Use the exact quarters your team selects and record all filenames and URLs in `SOURCE_REGISTER.md`.

## Recommended Analytical Grain

**One row per provider × service × quarter**.

Preserve:
- provider;
- service type;
- quarter;
- published complaint rate;
- published denominator/unit;
- source version.

## Continuity Rules

Before combining quarters:
- standardise provider names cautiously;
- record provider entry/exit;
- record service/category changes;
- record methodology changes;
- do not combine broadband, mobile and pay-TV into one score without an approved method.

## File Size Guidance

The quarterly CSVs are small enough to keep directly in GitHub.

The key challenge is longitudinal comparability, not storage size.

## Optional Extension

After the core 4–8 quarter history works, teams may add older quarters if comparability remains defensible.
