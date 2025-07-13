# 🌍⚖️ AI Ethics – Week 7 Assignment 
**Theme: Designing Responsible and Fair AI Systems**

This assignment explores how AI systems can be developed responsibly and fairly. It combines theoretical foundations, case study evaluations, practical auditing, and ethical reflection to help learners build ethical awareness and technical competence in AI.

---

## Assignment Overview

This peer-group project involves four core components and one optional bonus task:

1. **Theoretical Understanding** – Definitions, distinctions, and frameworks related to AI ethics.
2. **Case Study Analysis** – Investigation of real-world ethical failures in AI.
3. **Practical Audit** – Bias detection using the COMPAS dataset and IBM’s AI Fairness 360 toolkit.
4. **Ethical Reflection** – A short reflection on ethical awareness in AI project work.
5. **Bonus Task** – A one-page healthcare AI policy proposal.

---

## Theoretical Questions (30%)

### Q1: Define algorithmic bias and provide two examples  
Algorithmic bias refers to systematic errors in AI systems that lead to unfair outcomes, often affecting marginalized groups.  
**Examples:**  
- A facial recognition model misidentifying people of color.
- A loan approval system denying women based on historical male-dominated data.

### Q2: Explain transparency vs explainability  
- **Transparency** refers to the openness of system design, including access to data and algorithms.  
- **Explainability** refers to the ability to interpret and understand why an AI system made a specific decision.  
**Importance:** Both promote accountability, trust, and regulatory compliance.

### Q3: How does GDPR impact AI development in the EU?  
GDPR mandates data protection and individual rights (e.g., right to explanation), forcing AI developers to design privacy-compliant, auditable systems. This impacts data handling, consent mechanisms, and model transparency.

---

### Ethics Principles Matching

Match the principles with their definitions:

| Principle       | Definition                                                             |
|----------------|-------------------------------------------------------------------------|
| A) Justice      | 4. Fair distribution of AI benefits and risks                          |
| B) Non-maleficence | 1. Ensuring AI does not harm individuals or society                |
| C) Autonomy     | 2. Respecting users’ right to control their data and decisions         |
| D) Sustainability | 3. Designing AI to be environmentally friendly                      |

---

## Case Study Analysis (40%)

### Case 1: Biased Hiring Tool  
**Scenario:** Amazon's AI hiring tool penalized female applicants.  
- **Bias Source:** Biased historical training data favoring male candidates.  
- **Proposed Fixes:**  
  1. Retrain using gender-balanced data  
  2. Implement fairness-aware algorithms  
  3. Conduct regular impact assessments  
- **Fairness Metrics:**  
  - Demographic parity  
  - Equal opportunity  
  - Disparate impact ratio

### Case 2: Facial Recognition in Policing  
**Scenario:** System misidentifies minority individuals at higher rates.  
- **Ethical Risks:**  
  - Wrongful arrests  
  - Discrimination  
  - Privacy invasion  
- **Policy Recommendations:**  
  - Mandatory bias audits before deployment  
  - Community oversight  
  - Ban on use in sensitive public surveillance areas

---

## Dataset Bias Audit (25%)

**Dataset:** COMPAS Recidivism Dataset  
**Tool:** IBM AI Fairness 360 (AIF360)

**Steps Performed:**  
- Loaded COMPAS dataset  
- Analyzed disparities between racial groups (e.g., false positive rates)  
- Visualized bias using bar graphs and confusion matrices  
- Measured fairness using statistical parity and equalized odds metrics

**Summary (300 Words):**  
Our audit revealed racial disparities in risk prediction: African American defendants were more likely to receive high-risk scores falsely. AIF360 tools confirmed significant differences in false positive rates. We recommend retraining models with debiased data, incorporating adversarial debiasing techniques, and enforcing transparency in scoring logic to ensure fair treatment across racial lines.

---

## Ethical Reflection (5%)

In a past project involving a chatbot for student advising, ethical principles were not prioritized. In future AI work, I will ensure transparency in data use, secure informed consent, and actively test models for biases related to gender, age, or location. I'll also consult ethical checklists and adopt open communication with end users to promote trust and accountability.

---

## Bonus: Healthcare AI Policy Proposal (10%)

**Title:** *Ethical Guidelines for AI Use in Healthcare*

**1. Patient Consent Protocols:**  
- Ensure all data is collected with informed, opt-in consent.  
- Allow patients to withdraw consent at any time.

**2. Bias Mitigation Strategies:**  
- Audit all models on gender, race, and socioeconomic bias.  
- Train on diverse datasets and validate using real-world demographic segments.

**3. Transparency Requirements:**  
- Publish model logic and risk assessment criteria.  
- Provide plain-language explanations of AI decisions to patients and clinicians
---
