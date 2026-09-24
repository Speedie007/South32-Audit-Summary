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


## Interview Context Preservation Procedure

For structured report-discovery interviews, use the following standard procedure:

1. Store individual question records under the applicable numbered interview-round folder beneath:
   `SummaryReport/Notes/interview_question_answers_context/`

   Completed foundation context is stored in:
   `SummaryReport/Notes/interview_question_answers_context/1. Report Contextual Foundation/`
2. Create one Markdown context file per interview question.
3. Each question file must contain:
   - the question exactly as asked;
   - the user's answer as provided;
   - the contextual interpretation of that answer;
   - the contextual significance for the developing report.
4. If a question has been asked but not yet answered, create the file with status **Pending answer** rather than omitting it.
5. Preserve historical answers. Later refinements should be added as refinements or superseding context, not by erasing the original response.
6. At the end of each interview round, create a consolidated round context file summarizing the accepted conclusions from that round.
7. Each round consolidation should reference the individual question context files used to derive its conclusions.
8. Use the consolidated round context as the higher-level working context while retaining the individual files as the audit trail for contextual history.
9. Reflect accepted conclusions into `SummaryReport/Notes/SummaryReportContextualFramework.md` and, where appropriate, the higher-level `SummaryReport/SummaryReportContext.md`.

The purpose of this procedure is to reduce contextual drift, preserve nuance, and maintain traceability from final report interpretation back to the original interview response.


## Interview Phase Governance

The interview is conducted in staged phases:

1. **Report Contextual Foundation — Questions 1–N**
   - Establish the complete background context: who, what, where, why, how, scope, audience, purpose, interpretation rules, and report expectations.
   - Keep this phase open until sufficient context exists to safely begin technical interpretation.
   - The foundation round closed at Question 16.
   - Its historical Q1–Q16 records are stored in `SummaryReport/Notes/interview_question_answers_context/1. Report Contextual Foundation/`.
   - Its authoritative consolidation is `SummaryReport/Notes/Report Contextual Foundation - Background Context Consolidation.md`.
   - Use the consolidation as the primary background context, but when any wording or intent is ambiguous, consult the original Q1–Q16 files instead of inferring or fabricating context.

2. **Section-Specific Contextual Interpretation**
   - Conduct separate interview rounds for:
     - Main Shaft Head Sheaves;
     - Cable Belt Sheaves;
     - Product Spillage.
   - For each section establish contextual findings, interpretation, implications, remedial actions, remedial philosophy, sequencing, and how the final report should communicate the section.

3. **Holistic Remedial Integration**
   - Consolidate the three section contexts into the overall remedial strategy and final report narrative.

Do not move into section-specific finding interpretation until the Report Contextual Foundation has been formally closed and consolidated.


## Section-Specific Interview Folder Convention

Each new section-specific interview round must begin by creating a numbered folder beneath:

`SummaryReport/Notes/interview_question_answers_context/`

Current convention:

- `1. Report Contextual Foundation/` — completed foundation Q1–Q16 history.
- `2. Main Shaft Head Sheaves Contextual Interpretation/` — completed section-specific Q1–Q3 history.
- `3. Cable Belt Sheaves Contextual Interpretation/` — completed section-specific Q1–Q10 history.
- `4. Product Spillage Contextual Interpretation/` — completed Product Spillage Q1–Q14 history.

For every section-specific round:
1. create the round folder before asking the first question;
2. create one context file per question;
3. preserve exact user answers;
4. record contextual interpretation and significance;
5. consolidate the round into a dedicated context file in `SummaryReport/Notes/` when complete;
6. reference the original question files from the consolidation;
7. if later context is ambiguous, fall back to the original question files rather than infer missing intent.


### Main Shaft Head Sheaves Consolidation

The completed Main Shaft Head Sheaves section-specific context is consolidated in:

`SummaryReport/Notes/Main Shaft Head Sheaves - Contextual Interpretation Consolidation.md`

Use this consolidation as the primary context for that section. If ambiguity remains, fall back to the original Q1–Q3 files under:

`SummaryReport/Notes/interview_question_answers_context/2. Main Shaft Head Sheaves Contextual Interpretation/`

Do not infer or fabricate additional remedial complexity beyond the accepted context.


### Cable Belt Sheaves Consolidation

The completed Cable Belt Sheaves section-specific context is consolidated in:

`SummaryReport/Notes/Cable Belt Sheaves - Contextual Interpretation Consolidation.md`

Use this consolidation as the primary context for the Cable Belt section. If ambiguity remains, fall back to the original Q1–Q10 files under:

`SummaryReport/Notes/interview_question_answers_context/3. Cable Belt Sheaves Contextual Interpretation/`

Preserve the accepted distinctions between Angle Station, Main Drive and Upper Gantry. Do not merge their causal mechanisms or elevate detailed source-report classifications and implementation actions into the summary unless they add material management value.


### Product Spillage Consolidation

The completed Product Spillage section-specific interview history is stored under:

`SummaryReport/Notes/interview_question_answers_context/4. Product Spillage Contextual Interpretation/`

Primary issued source:

`CompletedReports/South32_Spillage_Audit_Report_July2026_S32WPPSR_01_FinalV1.5.pdf`

Supporting historical/context source:

`Speedie007/Spillage-Report`, particularly `Context/`, `Report-Working/` and `Report-Working/SpillageReport/`.

The Product Spillage round is closed and consolidated in:

`SummaryReport/Notes/Product Spillage - Contextual Interpretation Consolidation.md`

Use the consolidation as the primary Product Spillage context and the original overview/Q1–Q14 files as the historical fallback source.

An integrated working draft is maintained at:

`SummaryReport/South32 Audit Summary Report - Working Draft V2.md`

Do not expand the summary into a reproduction of the detailed spillage report, its formal action register, supplier list or fabrication-level design.


### Working Draft Version Control

Active draft:

`SummaryReport/South32 Audit Summary Report - Working Draft V2.md`

Historical reference:

`SummaryReport/South32 Audit Summary Report - Working Draft.md`

Do not overwrite the V1 reference when refining V2 unless the user explicitly requests it.
