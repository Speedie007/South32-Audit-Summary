# Summary Report Contextual Framework

## Purpose

This file is the working contextual framework for development of the South32 consolidated summary report.

The primary purpose of the final report is not merely to restate the findings contained in the completed source reports. It must provide clarity around those findings, explain how they should be interpreted, and present the overall picture in clear, professional English.

The report should help the reader understand:
- what the individual reports found;
- how the findings relate to one another;
- what the findings mean in practical and engineering terms;
- where findings are significant, recurring, isolated, uncertain, or potentially connected;
- what conclusions can reasonably be drawn from the available evidence;
- what should not be inferred where the evidence does not support a conclusion.

## Role of the Report Writer

ChatGPT will act as:
- expert technical report writer;
- English-language specialist;
- structure and coherence editor;
- synthesis assistant;
- interviewer for context discovery;
- custodian of the evolving report context.

The writing approach should prioritize:
- clarity;
- precision;
- professional tone;
- logical progression;
- consistency of terminology;
- clear separation between factual findings and interpretation;
- avoidance of ambiguity, overstatement, and unsupported conclusions.

## Context Discovery Method

The report framework will be developed through a structured question-and-answer interview with the user.

### Interview Context Preservation Procedure

The detailed historical interview record is stored under:

`SummaryReport/Notes/interview_question_answers_context/`

Each interview question must have its own context file containing:

1. the question as asked;
2. the user's answer as provided;
3. the contextual interpretation of that answer;
4. the contextual significance for the report framework.

Questions that have been asked but not yet answered are recorded with status **Pending answer**.

At the end of each interview round, the accepted conclusions from that round will be consolidated into a separate round-level context file. The round consolidation will reference the individual question files so that the high-level conclusions remain traceable to the original interview history.

The individual question files are the detailed historical record. The round consolidation files are the higher-level synthesized context. This framework file contains the current accepted report-development position.

The purpose of this layered structure is to minimize contextual drift and prevent important historical context, qualifications, or changes in interpretation from being lost.

### Interview Phase Structure

#### Phase 1 — Report Contextual Foundation

Questions **1–N** establish the complete background framework required before detailed technical interpretation begins.

This phase covers the proverbial **who, what, where, why, how**, together with:
- audit background and purpose;
- site and system context;
- intended audience;
- report objective;
- scope and exclusions;
- the three audited component sets;
- relationship between source reports;
- interpretation principles;
- level of technical detail;
- report tone and narrative style;
- recommendation philosophy;
- prioritisation expectations;
- treatment of uncertainty;
- evidence boundaries;
- desired reader outcome;
- any other foundational context required to prevent ambiguity later.

The phase remains open until the background is sufficiently established. It is not limited to a predefined number of questions.

When complete, Questions 1–N will be consolidated into a dedicated **Report Contextual Foundation — Background Context Consolidation** file. That consolidation becomes the authoritative background context for later technical interviews.

#### Phase 2 — Section-Specific Contextual Interpretation

Once the foundation is closed, separate contextual interview rounds will be conducted for:

1. **Main Shaft Head Sheaves**
2. **Cable Belt Sheaves**
3. **Product Spillage**

For each section, the interview will establish:
- what the contextual findings mean;
- how the source report should be interpreted;
- condition implications;
- defined remedial actions;
- remedial philosophy;
- sequencing and priority where relevant;
- dependencies and implementation logic;
- what the final summary report should emphasize;
- what detailed findings should remain in the source report rather than be repeated;
- how the section contributes to the holistic audit narrative.

#### Phase 3 — Holistic Remedial Integration

After all three section-specific rounds are complete, a final synthesis will establish:
- the overall remedial philosophy;
- how the three sections should be presented together;
- cross-cutting implications;
- sequencing across workstreams where relevant;
- dependencies and strategic considerations;
- the final report narrative;
- final conclusions and forward-action philosophy.

Questions should be asked in manageable groups, with conclusions recorded after each agreed section.

## Working Principles

### Evidence vs Interpretation

The report must distinguish clearly between:
- **Source Finding** — what the original report explicitly records.
- **Observed Pattern** — a relationship or recurrence that becomes apparent when reports are considered together.
- **Interpretation** — the reasoned meaning assigned to the available findings.
- **Inference** — a conclusion derived from evidence but not directly stated in a source report.
- **Recommendation** — an action proposed in response to findings or interpretation.
- **Unknown / Unresolved** — matters where the evidence is insufficient or contradictory.

Interpretation must not be presented as though it were a directly observed fact.

### English and Communication Standard

The final report should:
- use concise, technically accurate English;
- avoid unnecessary jargon where plain language is clearer;
- retain necessary engineering terminology;
- explain technical significance where a non-specialist reader may otherwise misinterpret a finding;
- avoid repetitive wording;
- use consistent terminology across all sections;
- make causal statements only where evidence supports causation;
- use qualified language where only correlation, possibility, or indication is supported.

### Context Preservation

All material conclusions reached during the interview should be incorporated into this file as the framework evolves.

This document is a working context record rather than the final report itself.

## Current Status

Framework initialized: **2026-09-24**

Current confirmed direction:
- the deliverable will be a summary report;
- the report will synthesize findings from the completed reports;
- its primary purpose is to provide clarity regarding the findings and their interpretation;
- report development will proceed through a structured interview with the user;
- ChatGPT will act as expert report writer and English-language specialist during the process.

## Interview Record

### Section A — Report Purpose and Audit Context

Status: **In progress**

#### Accepted Context — Audit Background

An audit was conducted by **Inspection & Specification Services cc (ISS)** at **South32 Wessels Mine**.

The audit comprised two principal workstreams:

1. **Sheave operational-condition assessment**
   - Assessment of the current operational condition of sheaves forming part of the conveyor transport system.
   - Assessment of sheaves forming part of the main shaft lift system.
   - The individual completed reports provide the detailed findings for the specific inspected sections and equipment groups.

2. **Conveyor product-spillage investigation**
   - Investigation of product spillage escaping from the conveyor transport system.
   - The conveyor system transports product from the underground sections through to the surface processing and material-handling sections.
   - The spillage investigation was intended to identify the causes or contributing causes of the spillage problem.
   - The dedicated spillage report records the detailed findings and was structured to identify areas that should receive earlier attention in the remediation process.

The completed audit reports are retained in the repository under `CompletedReports/`.

#### Accepted Context — Purpose of the Summary Report

The summary report is **not intended to reproduce or condense the detailed findings from each completed report**. Those reports already serve as the dedicated technical records for the different inspected sections.

The summary report should instead provide a **holistic overview and interpretation** of the audit findings.

Its purpose is to:
- bring the separate inspection reports into one coherent overall picture;
- explain what the combined findings indicate when considered together;
- provide clarity on how the detailed findings should be interpreted;
- identify important relationships, common themes, or broader implications across the inspected systems;
- retain enough technical context for the interpretation to be credible without duplicating the detailed evidence already contained in the source reports;
- direct readers back to the individual reports where detailed section-specific evidence is required.

For the spillage workstream specifically, the summary report should also clarify the broader meaning of the findings and the logic behind the areas identified for earlier remedial attention. It should not merely repeat the detailed spillage findings or reproduce the original report section by section.

#### Working Interpretation Principle

The final report should function as an **interpretive bridge between the detailed technical reports and the reader's overall understanding of the audit**.

The detailed reports answer primarily:

> What was found at each inspected section?

The summary report should answer primarily:

> What do these findings mean when viewed collectively, and how should they be understood in the context of the overall audit?

### Section B — Intended Audience and Required Decision Context

Status: **Accepted baseline**

#### Accepted Context — Intended Audience

The summary report is intended for a mixed South32 audience comprising:

- mine management;
- engineering management;
- maintenance management;
- operational personnel;
- procurement and project personnel who may be required to act on the recommendations or resulting remedial work.

Because the audience spans technical, operational, managerial, and implementation roles, the report should be written as a **high-level technical narrative** rather than as a highly detailed engineering inspection report.

The report should remain technically credible and sufficiently specific to support engineering and maintenance interpretation, while being clear enough for management and non-specialist stakeholders to understand the overall significance of the findings.

#### Accepted Context — Communication Approach

The report should read as a coherent technical story explaining:

- what was inspected;
- what the inspections collectively indicate;
- what the findings mean at system level;
- the remedial philosophy that follows from those findings;
- where a logical order or sequence of remedial actions can be identified;
- the implications of the findings if they are left unattended;
- how the remedial philosophies differ between the principal audit areas;
- how detailed technical findings in the source reports support the higher-level conclusions.

The intention is not to provide a detailed maintenance work instruction, nor to repeat all individual inspection observations. The report should establish a clear **management-and-engineering understanding of the condition, implications, and remediation logic**.

#### Accepted Context — Principal Report Sections

The audit and the summary report should be understood as comprising **three distinct technical component sets**:

1. **Main Shaft Head Sheaves**
   - These form a separate audited component set associated with the main shaft lift system.
   - They should not be grouped into the cable belt sheave system.
   - The summary report should provide a high-level interpretation of their condition, significance, and remedial philosophy while referring readers to the dedicated source report for detailed findings.

2. **Cable Belt Sheaves**
   - The relevant sheaves should be considered collectively as operating components within the broader cable belt transport system.
   - Although individual source reports address specific sheave locations or groups, the summary report should interpret their significance as parts of one operating system where appropriate.
   - The report should explain the overall condition philosophy, implications, and remedial approach for the cable belt sheave system rather than treating each source report as an isolated summary chapter.

3. **Product Spillage**
   - This section should address the product-spillage problem as a system-level issue along the conveyor transport route.
   - The report should explain the interpretation of the findings, the remedial philosophy, and where appropriate the logical priority or sequence in which areas should be addressed.
   - The purpose is to clarify how the identified problem areas relate to one another and how corrective actions should be understood in the broader spillage-control strategy.

#### Reader Outcome

After reading the report, the intended reader should have a clear understanding of:

- the overall condition identified by the audit;
- the significance of the findings;
- the difference between the two principal technical problem areas;
- the philosophy behind the recommended remedial actions;
- the broad order in which corrective actions may need to be considered;
- which detailed source reports should be consulted when section-specific evidence or technical detail is required.

### Section C — Three-Part Audit Structure and Interrelationships

Status: **In progress**

#### Accepted Context — Three Audited Component Sets

The audit comprised three technically distinct areas:

1. **Main Shaft Head Sheaves** — main shaft lift system.
2. **Cable Belt Sheaves** — sheaves operating within the cable belt conveyor transport system.
3. **Product Spillage** — investigation of product escaping from the conveyor transport system from underground sections through to surface handling and processing areas.

These three areas should remain distinguishable in the summary report, while still being brought together under one overall audit narrative.

#### Accepted Context — Independence of the Three Audit Areas

The three areas are separate technical concerns:

- The **Main Shaft Head Sheave** assessment is a standalone periodic condition assessment focused on sheave groove profile condition and forms part of the mine's required periodic safety inspection regime.
- The **Cable Belt Sheave** assessment is a separate condition-assessment category comprising three independently inspected sheave sections: Main Drive Sheaves, Angle Station Sheaves, and Upper Gantry Guide Sheaves. These may be interpreted collectively because they form part of the supporting sheave infrastructure of the cable belt system.
- The **Product Spillage** investigation is a separate operational/system investigation into loss or escape of material from the conveyor transport system.

There is **no intended causal or interpretive relationship between the Cable Belt Sheave condition findings and the Product Spillage findings**. They should remain separate concerns unless explicit source evidence later establishes a relationship.

This separation is important to prevent the final summary report from creating unsupported technical connections merely because the cable belt sheaves and spillage both relate to the broader conveyor transport environment.


### Accepted Context — Audit Trigger and Commissioning Qualification

The contextual reasons for the three audit areas were **not directly communicated to ISS as formal commissioning reasons**. They were understood from site conditions and discussions with personnel during the audit.

Accordingly:

- **Main Shaft Head Sheaves:** contextual drivers were scheduled/periodic inspection and regulatory/safety requirements.
- **Cable Belt Sheaves:** contextual drivers were deterioration/failure concern and a desire for an independent condition assessment.
- **Product Spillage:** contextual drivers were a known operational problem, recurring spillage or production-loss concerns, independent assessment, and possible preparation for maintenance or capital work.

These points are background context, not verified formal appointment statements.

The final report must distinguish between:
- documented scope or instruction;
- observed site context;
- information obtained through discussion;
- interpretation derived from those circumstances.

Unverified contextual drivers should be expressed with qualified language and must not be attributed to South32 as formal commissioning intent unless supported by documentary evidence.


### Accepted Context — ISS Deliverables and Scope Boundaries

ISS's scope differed by audited area:

- **Main Shaft Head Sheaves:** inspect and record condition, and advise whether the equipment could remain in service.
- **Cable Belt Sheaves:** inspect and record condition; diagnose probable causes; assess severity/risk; recommend remedial actions; define repair methodology at a conceptual/advisory level; advise on continued serviceability; and provide an independent technical opinion.
- **Product Spillage:** inspect and record condition/circumstances; diagnose probable causes; recommend remedial actions; define remediation methodology at a conceptual/advisory level; and provide an independent technical opinion.

Across all three areas, ISS was not expected to provide detailed engineering design, final repair drawings, issued-for-construction documentation, or implementation supervision.

Any technical drawings included in the source reports were conceptual aids used to support explanation of findings or recommendations. They were not to scale and were not intended to function as final technical specifications, fabrication drawings, construction drawings, or implementation-ready design documents.

The final summary report must preserve the distinction between **technical advisory/remedial concepts** and **detailed engineered solutions**.


### Accepted Context — Report Authority and Recommendation Tone

The summary report should be positioned as a combination of:

- a **professional technical recommendation** describing what ISS believes should be done based on the audit findings; and
- an **advisory interpretation** that South32 can use to support its own engineering, maintenance, operational, and project decisions.

It should not read as a binding directive, detailed work instruction, or implementation order.

Where source reports use strong action language such as `replace`, `repair`, `monitor`, or `attend urgently`, the summary report should generally translate those detailed actions into a broader **management-level remediation philosophy**.

Direct technical action wording may be retained selectively where it materially supports or clarifies the management-level interpretation, but it should not be the primary language mode.

The final report should emphasize the **reasoning, priority, implications, and strategic intent behind the remedial actions** rather than simply repeating section-specific instructions.


### Accepted Context — Summary Report Exclusions and Synthesis Boundaries

The summary report should avoid:

- repeating detailed findings already contained in the source reports, except where concise reference is necessary;
- reproducing long technical tables, detailed measurements, or granular inspection records;
- becoming a maintenance work instruction;
- becoming a detailed engineering design document;
- assigning formal risk ratings unless already established;
- creating artificial links between the three audited areas;
- assigning blame or responsibility to individuals or departments;
- making commercial, contractual, or legal conclusions;
- promising that remedial actions will fully eliminate a problem;
- presenting conceptual drawings as final design solutions.

Where detailed technical evidence is required, the report should refer back to the appropriate source report.

#### Remedial Philosophy — Prove Before Scaling

Where applicable, recommended remedial concepts should generally be understood as:

1. applied to a defined location, section, or subset;
2. verified against the intended outcome;
3. confirmed as effective;
4. then scaled to other relevant areas or components where justified.

The report should avoid implying universal effectiveness before a remedial concept has been demonstrated.

#### Evidence-Based Holistic Synthesis

The detailed reports remain the evidentiary foundation, but the summary report may derive higher-level conclusions from the combined context of multiple reports.

A system-level trend or implication may be valid even where it is not explicitly stated in a single detailed report, provided that:

- it is supported by the combined evidence;
- the reasoning is traceable;
- it does not contradict source findings;
- it is clearly presented as holistic interpretation rather than a direct source finding.

This is particularly relevant to the three Cable Belt Sheave reports, where individually granular findings may collectively reveal a broader trend across the cable belt sheave ecosystem.


### Accepted Context — Uncertainty and Professional Judgement

Where evidence does not support absolute certainty, the report should use qualified wording such as:

- `indicates`;
- `suggests`;
- `is consistent with`;
- `is likely associated with`.

Where appropriate, the report should also identify the need for further inspection, measurement, testing, or engineering verification.

The strength of the wording should therefore match the strength of the available evidence, avoiding overstatement while still allowing reasoned professional interpretation.


### Accepted Context — Priority and Remedial Sequencing

Priority and sequencing should be expressed through qualitative engineering and operational reasoning rather than rigid numerical scoring.

Relevant considerations include:

- serviceability or operational risk;
- impact on production or availability;
- whether an intervention addresses a root cause or only a symptom;
- ease of proving a remedial concept on a limited section or subset first;
- dependencies between remedial actions;
- whether one action should precede another to avoid wasted effort or ineffective sequencing.

Unless a numerical ranking already exists in the source material and is appropriate to retain, the summary report should use broader priority language such as:

- **immediate**;
- **early attention**;
- **planned intervention**;
- **monitor**;
- **verify first**.

The report should explain the reasoning behind sequencing rather than merely assigning priority labels.


### Accepted Context — Reader Familiarity and Source Report Referencing

The summary report should assume that readers have access to the detailed reports and may either:

- already be familiar with them; or
- not have read them in full.

The summary therefore does not need to reproduce detailed technical content, but it must contain enough contextual explanation for the high-level interpretation to remain understandable.

References to detailed source reports should generally be used only where necessary so the narrative remains clean.

Where reference is useful:
- use a light reference where general direction to the source report is sufficient;
- use an explicit report and section reference where a specific technical detail, qualification, or traceability point requires clarification.

The preferred approach is **minimal but traceable** rather than citation-heavy repetition.


### Accepted Context — Writing Style and Narrative Flow

The default narrative flow for the summary report is:

1. **What was inspected**
2. **What the collective findings indicate**
3. **What that means operationally/technically**
4. **What remedial philosophy follows from that**
5. **What should happen first, next, or be verified before scaling**
6. **What the broader implications are going forward**

This is the baseline narrative sequence rather than a rigid template and may be adjusted where a section requires a different order for clarity.

The writing style should be:

- formal and professional;
- plain English where possible;
- technically precise without being overly academic;
- primarily prose-led;
- supported by selective tables or figures only where they genuinely improve understanding.

The report should therefore read as a coherent technical story rather than a compressed inspection schedule or data-heavy technical appendix.
