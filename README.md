# ICDFA GRC103 — Lab 3B: Advanced Cybersecurity Risk Quantification and Control Investment Analysis

**Prepared by:** Rosemary Gift Nelson
**Registration Number:** C11/26/CGRCE-17216
**Cohort:** 11 / Batch A
**Scenario:** SecureBank Financial — SecureMobile banking platform risk quantification
**Role assumed:** Lead GRC Analyst, SecureBank Financial
**Submission date:** 01 November 2026

## Scope

Quantifies three critical vulnerabilities on the SecureMobile banking platform (API Authentication Bypass, Database Injection, Session Hijacking), calculates Annualized Loss Expectancy (ALE = SLE × ARO) for each with full, visible worked calculations, and evaluates three candidate controls (Advanced API Security Gateway, Web Application Firewall, MFA Enhancement) by 3-year ROI, each control mapped to exactly one finding to avoid double-counting.

All assumptions (exploit probabilities treated as ARO; SLE basis per finding; the Database Injection full-breach modeling assumption; the 3-year evaluation period) are stated explicitly in the workbook's Assumptions sheet, per the brief's instruction to show all calculations and maintain proper documentation of risk decisions.

## Files in this repository

| File | Description |
|---|---|
| `GRC103_Lab3B_Risk_Quantification_Rosemary_Nelson_C11-26-CGRCE-17216.xlsx` | Calculation workbook — Executive Dashboard, Assumptions, Risk Calculations (step-by-step SLE/ARO/ALE per finding, live formulas), Risk Matrix + heat map, Control Analysis (cost-benefit/ROI/payback), Charts (7 required visualizations), Treatment Timeline (Gantt). 135 live formulas, 0 recalculation errors. |
| `GRC103_Lab3B_Executive_Briefing_Rosemary_Nelson_C11-26-CGRCE-17216.pptx` | 5-slide executive briefing deck — Title, Executive Dashboard, Financial Justification, Risk Treatment Plan, Residual Risk & Recommendation. |

## Key results

| Metric | Value |
|---|---|
| Current annual exposure (ALE, all 3 findings) | $35,000,000 |
| — API Authentication Bypass | $750,000 |
| — Database Injection Vulnerability | $31,250,000 |
| — Session Hijacking | $3,000,000 |
| Total investment (Year 1 + annual maintenance) | $700,000 initial + $105,000/yr |
| Residual ALE after all 3 controls | $8,037,500 |
| Risk reduction | $26,962,500 |
| Combined 3-year ROI | 7,869% |

Database Injection dominates current exposure and therefore the WAF's resulting ROI; this is a documented modeling consequence of the dataset's stated assumptions, not a calculation error (see workbook Assumptions #2–3).

## Deliverable mapping (per the brief)

1. **Calculate ALE for each vulnerability (SLE, ARO, ALE)** — Workbook, "Risk Calculations" sheet (step-by-step blocks per finding)
2. **Risk Matrix / heat map** — Workbook, "Risk Matrix" sheet
3. **Control cost-benefit / ROI analysis** — Workbook, "Control Analysis" sheet
4. **Risk treatment timeline** — Workbook, "Treatment Timeline" sheet (Gantt)
5. **Executive Briefing Package** — Briefing deck (.pptx)
