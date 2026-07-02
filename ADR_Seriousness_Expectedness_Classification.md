# ADR Classification: Seriousness & Expectedness

*(Based on ICH E2A pharmacovigilance definitions)*

---

## A. Reference Definitions

**Seriousness** — An adverse reaction is classified as **Serious** if it meets any one of the following criteria:
- Results in death
- Is life-threatening
- Requires or prolongs inpatient hospitalization
- Results in persistent or significant disability/incapacity
- Is a congenital anomaly/birth defect
- Is otherwise medically important (may jeopardize the patient or require intervention to prevent one of the above)

If none of these apply, the reaction is classified as **Non-Serious**.

**Expectedness** — An adverse reaction is classified as:
- **Expected**: the nature, severity, and specificity of the reaction is consistent with the information in the drug's reference safety information (package insert / product label)
- **Unexpected**: the reaction is not listed, or differs in nature/severity/specificity from what is described in the reference safety information

---

## B. Case-wise Classification

| Case | Drug | Adverse Reaction | Seriousness | Rationale | Expectedness | Rationale |
|---|---|---|---|---|---|---|
| 01 | Amoxicillin | Skin rash, itching | **Non-Serious** | Does not meet any seriousness criterion — mild, self-limiting, no hospitalization | **Expected** | Well-documented, commonly listed ADR for Amoxicillin/penicillins |
| 02 | Ibuprofen | Gastrointestinal bleeding requiring hospitalization | **Serious** | Meets the "requires hospitalization" criterion | **Expected** | GI bleeding is a well-known, labeled risk of NSAIDs |
| 03 | Metformin | Lactic acidosis | **Serious** | Life-threatening / medically important condition | **Unexpected** | Presentation was outside the typical expected pattern/severity for this patient population, warranting closer signal evaluation |
| 04 | Atorvastatin | Elevated liver enzymes (mild) | **Non-Serious** | Mild, asymptomatic lab finding — no hospitalization or disability | **Expected** | Transaminase elevation is a recognized, labeled ADR of statins |
| 05 | Levofloxacin | Tendon rupture | **Serious** | Results in significant/persistent disability — medically important | **Unexpected** | Severity/specificity of presentation was not consistent with routine expected profile, flagging it for further review |

---

## C. Summary

| Metric | Count |
|---|---|
| **Serious cases** | 3 (Case 02, 03, 05) |
| **Non-Serious cases** | 2 (Case 01, 04) |
| **Expected cases** | 3 (Case 01, 02, 04) |
| **Unexpected cases** | 2 (Case 03, 05) |

---

## D. Clinical/Regulatory Impact

- **Serious + Unexpected** reactions (Case 03 – Lactic acidosis with Metformin, Case 05 – Tendon rupture with Levofloxacin) carry the **highest reporting priority**. Under most pharmacovigilance regulations (e.g., CDSCO, US FDA FAERS, EU EudraVigilance), these typically require **expedited reporting** (often within 15 calendar days of the reporter becoming aware).
- **Serious + Expected** (Case 02 – GI bleed with Ibuprofen) still requires reporting per standard serious-ADR timelines, but does not trigger the same signal-detection urgency since it's a known risk.
- **Non-Serious + Expected** cases (Case 01, Case 04) are generally captured in routine/periodic safety reporting (e.g., Periodic Safety Update Reports) rather than expedited individual case reports.

---

## E. Reporter Details

| Field | Details |
|---|---|
| **Reported by** | *(fill in your name/designation)* |
| **Date of assessment** | *(fill in)* |
| **Signature** | *(fill in)* |
