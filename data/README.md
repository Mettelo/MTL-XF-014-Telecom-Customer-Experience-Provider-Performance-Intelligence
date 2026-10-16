# Data Guidance

## Approved Core Dataset

Use Ofcom's **Telecoms and Pay-TV complaints underlying quarterly CSV data**.

Official source:
https://www.ofcom.org.uk/telecoms-and-pay-tv-complaints

## Core Time Scope

This project should **not** be based on one quarter only.

Recommended core history:
- minimum: **4 consecutive quarters**;
- preferred: **8 quarters** where provider/service definitions remain comparable.

Use **Q1 2026** as the latest frozen reference quarter for the cohort, then add the preceding quarters needed to create the history.

## Why Multiple Quarters Are Required

The business problem requires distinguishing:
- persistent deterioration;
- persistent improvement;
- temporary spikes;
- service-specific issues.

A single-quarter file cannot support those conclusions.

## Raw Folder Strategy

Store one untouched CSV per quarter:

```text
data/raw/
├── ofcom-telecom-complaints-2024-q2.csv
├── ofcom-telecom-complaints-2024-q3.csv
├── ...
└── ofcom-telecom-complaints-2026-q1.csv
```

Use the exact quarters your team selects and document them in `SOURCE_REGISTER.md`.

## Provider/Service Continuity

Before combining quarters:
- standardise provider names cautiously;
- preserve service type;
- record provider entry/exit;
- record methodology changes;
- avoid comparing unlike service categories.

## Recommended Analytical Grain

**One row per provider × service × quarter**.

Do not collapse broadband, mobile and pay-TV into one overall provider score unless a documented method has been explicitly approved.

## Small Data Guidance

These quarterly CSVs are small enough to commit directly to GitHub.

The challenge is not storage size; it is building a clean longitudinal history and preserving comparability.

## Optional Extension

Teams may extend to older quarters after the core 4–8 quarter history is working, but they should not add years of history if provider/methodology changes make the comparison less reliable.
