# Scenario 1 · The Favored Supplier

> **Illustrative scenario.** Fictional organization and roles.

## Setup
A mid-sized consumer goods manufacturer is renewing and expanding a contract with its long-time packaging supplier. The new scope gives the supplier access to the company's production scheduling portal. The procurement lead has managed this supplier for years and is the only internal contact. The lead also chairs the bid evaluation. The request reaches the vendor risk team on a Friday afternoon with a Monday start date.

## Indicators present
| Indicator | What was seen | Evidence grade |
|---|---|---|
| A1 Minimizing language | Email: "the security questionnaire is just a formality, they've been with us forever" | Repeated pattern (3 emails) |
| A2 Pre-decided language | "Leadership already decided, we just need your sign-off" | Corroborated (email + meeting notes) |
| D1 Single relationship owner | All supplier contact, pricing history, and performance notes sit with one person | Corroborated (email routing + interviews) |
| D4 Requester = evaluator | Procurement lead requested, scored, and recommended the award | Corroborated (bid sheet + workflow record) |
| E4 Due diligence after the decision | PO raised and portal access requested before questionnaire returned | Corroborated (system dates) |

## Risk created or hidden
- A supplier gains system access without a current security review (third-party cyber risk).
- Possible conflict of interest is untested; no current declaration on file.
- Pricing and performance are not independently benchmarked; concentration and key-person risk.
- The record will show an "approved" vendor, hiding that the review was bypassed.

## What the GRC analyst does
1. **Pauses access, not the relationship.** Asks that portal access wait until the questionnaire is returned, citing the policy gate. Offers a fast-track review rather than a refusal.
2. **Clarifies "leadership."** Asks which named role approved the award, and checks whether that role holds the authority under the delegation-of-authority matrix.
3. **Documents the sequence** (request, PO, access request, questionnaire dates) without commentary.
4. **Checks conflict-of-interest declarations** for everyone involved in the evaluation.
5. **Writes a process finding**: due diligence gate not enforced; segregation of duties missing in evaluation. No characterization of the procurement lead.
6. **Escalates proportionately**: to the third-party risk manager first; to procurement leadership if the gate is bypassed again.

## Controls
- **Preventive:** workflow gate so no PO or access is issued before due diligence completes (or a documented exception at the right level); independent bid evaluation; annual conflict-of-interest declarations.
- **Detective:** monthly report of POs raised before due diligence completion; periodic rotation or second owner for critical supplier relationships.

## Framework anchors
NIST CSF 2.0 **GV.SC-06** (due diligence before formal supplier relationships), **GV.SC-07** (supplier risks managed over the relationship); COSO 2013 **Principle 3** (authorities and responsibilities), **Principle 8** (fraud risk: incentives and pressures, opportunities, attitudes and rationalizations). See [04-framework-mapping.md](../04-framework-mapping.md).
