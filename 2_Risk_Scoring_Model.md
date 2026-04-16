# Vendor Risk Scoring Model

This model assigns a risk rating to vendors based on their responses to the risk assessment questionnaire.

---

## Scoring Criteria

Each response is assigned a score:

- Yes = 1 (Control exists)
- Partial = 2 (Control partially exists)
- No = 3 (Control does not exist)

---

## Risk Categories & Weightage

| Category                     | Weight |
|----------------------------|--------|
| Information Security       | 30%    |
| Data Protection & Privacy  | 25%    |
| Incident Management        | 20%    |
| Business Continuity        | 15%    |
| Third-Party Dependencies   | 10%    |

---

## Risk Calculation

Total Risk Score =  
(Sum of responses × Category Weight)

---

## Risk Rating

| Score Range | Risk Level |
|------------|-----------|
| 1.0 – 1.5  | Low Risk  |
| 1.6 – 2.2  | Medium Risk |
| 2.3 – 3.0  | High Risk |

---

## Example

If a vendor scores high in:
- No encryption
- No incident response
- No risk assessment

👉 They will fall into **High Risk**

---

## Outcome

This scoring model helps:

- Standardize vendor evaluation  
- Prioritize high-risk vendors  
- Support onboarding decisions  
- Enable continuous monitoring  

---

## Business Value

This approach allows organizations to move from subjective assessment to **data-driven risk decisions**, improving governance and compliance.
