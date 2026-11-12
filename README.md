# pharmacovigilance-causality-assessment
Evaluate the relationship between a drug and an adverse reaction using standard causality assessment methods (WHO-UMC and Naranjo Algorithm).
# Pharmacovigilance: Drug Reaction Causality Assessment

## 📌 Project Overview
This project evaluates the causal relationship between a suspected drug exposure and an observed adverse drug reaction (ADR) using standard pharmacovigilance causality assessment methods (the **WHO-UMC Causality Assessment System** and the **Naranjo Algorithm**).

* **Reference Tutorial:** [Causality Assessment - VigiServe Academy](http://www.youtube.com/watch?v=6gH4AWnwTDI)

---

## 🧬 Factors Associated with Causality
1. **Drug-Related Factors:** Labeledness (known to cause the reaction), predisposing factors, and concomitant medications.
2. **Event-Related Factors:** Nature and specificity of the adverse event.
3. **Patient-Related Factors:** Pharmacogenomics, medical history, and past history of allergies (e.g., cross-reactivity between penicillins and cephalosporins).
4. **Clinical Factors:**
   * **Temporal Relationship:** Time elapsed between drug administration and onset of the adverse event.
   * **Dechallenge:** Response of the adverse event after stopping or reducing the dose of the suspected drug.
   * **Rechallenge:** Response when the suspected drug is restarted or the dose is increased again.
   * **Response to Corrective Treatment:** Resolution of the symptom upon administering treatment (e.g., antihistamines for an allergic rash).

---

## 📊 Standard Causality Assessment Scales

### 1. Naranjo Algorithm Scoring Scale
| Total Score | Causality Classification |
| :--- | :--- |
| **≥ 9** | **Definite** |
| **5 to 8** | **Probable** |
| **1 to 4** | **Possible** |
| **≤ 0** | **Doubtful** |

### 2. WHO-UMC Causality Categories
* **Certain:** Plausible time relationship to drug intake, cannot be explained by disease or other drugs, plausible response to withdrawal (dechallenge), and satisfactory rechallenge.
* **Probable / Likely:** Reasonable time relationship to drug intake, unlikely to be attributed to concurrent disease or other drugs, and clinically reasonable response on withdrawal (rechallenge not required).
* **Possible:** Reasonable time relationship to drug intake, could also be explained by disease or other drugs, or information on drug withdrawal is lacking/unclear.
* **Unlikely:** Improbable time relationship and other drugs/underlying disease provide plausible explanations.
* **Conditional / Unclassified:** More data is needed for proper assessment.
* **Unassessable / Unclassifiable:** Insufficient or contradictory information that cannot be supplemented or verified.

---

## 🧪 Case Study Evaluations

### Case Study 1: Workspace Graphic Case (Amoxicillin Skin Rash)
* **Patient:** 45-year-old Female
* **Suspected Drug:** Amoxicillin
* **Adverse Reaction:** Skin Rash
* **Onset:** 3 days after starting medication
* **Outcome / Dechallenge:** Recovered after stopping the drug (Positive Dechallenge)
* **WHO-UMC Classification:** **Probable** *(or **Certain** if a positive rechallenge is confirmed)*
  * **Justification:** Clear temporal relationship (onset 3 days after administration), known pharmacological profile of penicillin-class antibiotics causing cutaneous hypersensitivity, and clinical recovery upon discontinuation (dechallenge).

---

### Case Study 2: Video Tutorial Case (Raj – Amoxicillin Generalized Itchy Rash)
* **Case Summary:** 
  * **June 1:** Started on Amoxicillin 500 mg TID for a throat infection.
  * **June 2:** Developed itchy rashes over the body (Positive Temporal Relationship).
  * **June 3–4:** Dose reduced to 250 mg TID; rash disappeared the next day (Positive Dechallenge).
  * **June 5–6:** Dose increased back to 500 mg due to infection intensity; generalized itchy rashes reappeared on June 6 (Positive Rechallenge).

#### Naranjo Algorithm Breakdown:
| # | Assessment Question | Answer | Score |
| :--- | :--- | :---: | :---: |
| 1 | Are there previous conclusive reports on this reaction? | Yes | +1 |
| 2 | Did the adverse event appear after the suspected drug was administered? | Yes | +2 |
| 3 | Did the adverse reaction improve when the drug was discontinued/reduced? | Yes | +1 |
| 4 | Did the adverse event reappear when the drug was re-administered? | Yes | +2 |
| 5 | Are there alternative causes that could on their own have caused the reaction? | No | +2 (or +1/0) |
| 6 | Did the reaction reappear when a placebo was given? | Do not know | 0 |
| 7 | Was the drug detected in blood/fluids in concentrations known to be toxic? | Do not know | 0 |
| 8 | Was the reaction more severe when the dose was increased or less severe when decreased? | Yes | +1 |
| 9 | Did the patient have a similar reaction to the same or similar drugs in any previous exposure? | Do not know | 0 |
| 10 | Was the adverse event confirmed by any objective evidence? | Do not know | 0 |
| **Total** | **Naranjo Total Score** | | **7 to 9** |

* **Final Classification:** **Probable to Definite (Naranjo)** / **Certain (WHO-UMC)** due to documented positive dechallenge and positive rechallenge.
* 
