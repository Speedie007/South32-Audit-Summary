# AGENTS.md

## Purpose

This repository is the working repository for compiling the South32 audit summary report and retaining the completed source reports used during that process.

This file provides repository-wide working instructions for ChatGPT, Codex, and other agents operating in this repository.

## Repository Baseline

```text
South32-Audit-Summary/
├── AGENTS.md
├── README.md
├── CompletedReports/
│   ├── ISS_IRS32-Wessels-180726 - Cable Belt Main Drive SheavesV1.4- Final.pdf
│   ├── ISS_IRS32-Wessels-200726 - Cable Belt Angle Station SheavesV1.1-Final.pdf
│   ├── South32-IRS32-Wessels-160726 Main Shaft Head Sheaves- Final.pdf
│   ├── South32_IRS32-Wessels-180726_1-Upper Gantry Guide Sheaves - Final.pdf
│   └── South32_Spillage_Audit_Report_July2026_S32WPPSR_01_FinalV1.5.pdf
└── SummaryReport/
    ├── SummaryReportContext.md
    └── Notes/
        └── PlaceHolder.txt
```

## Directory Responsibilities

### `CompletedReports/`

Contains completed/final reports that form part of the reference and source material for the summary-report exercise.

Treat files in this directory as source records. Do not modify, overwrite, rename, or delete completed reports unless explicitly instructed by the user.

### `SummaryReport/`

Primary working area for the new consolidated summary report.

- `SummaryReportContext.md` is the authoritative evolving context file for the summary-report scope, findings, decisions, structure, terminology, source mapping, and report-generation notes.
- `Notes/` is for supporting notes, extracted observations, working material, questionnaires, intermediate text, and other report-development inputs.

Additional folders may be introduced later for images, videos/link indexes, tables, drafts, templates, or generated deliverables when required.

## Working Rules

1. Read this file and `SummaryReport/SummaryReportContext.md` before performing substantial report work.
2. Preserve source evidence. Completed reports are references, not working copies.
3. Record material report-development decisions and agreed interpretations in `SummaryReport/SummaryReportContext.md` so later sessions can resume without relying on chat history.
4. Distinguish clearly between:
   - facts/evidence from source material;
   - engineering interpretation;
   - recommendations;
   - unresolved questions or assumptions.
5. Do not invent missing technical facts, measurements, inspection results, dates, or conclusions.
6. When source material conflicts, record the conflict rather than silently choosing one version.
7. Keep repository paths stable where practical so report references remain usable.
8. Generated final or issued reports should not overwrite source reports in `CompletedReports/`.
9. Before deleting or replacing substantive material, verify that the information is preserved elsewhere or that deletion was explicitly requested.
10. Use clear versioning for generated report artifacts until a final naming convention is established.

## Current Status

Repository baseline established on 2026-09-24.

At baseline:
- five completed PDF reports are available in `CompletedReports/`;
- the summary-report working area exists;
- `SummaryReportContext.md` has been initialized;
- `SummaryReport/Notes/` currently contains only a placeholder file.

This file should remain high-level. Detailed report-specific context belongs in `SummaryReport/SummaryReportContext.md`.
