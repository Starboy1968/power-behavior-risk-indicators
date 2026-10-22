# Scenario 3 · Green Dashboard, Red Project

> **Illustrative scenario.** Fictional organization and roles.

## Setup
A retailer is migrating supplier onboarding to a new cloud platform. The program director's bonus is tied to go-live by quarter-end. For five straight months the steering committee report shows green on schedule, security, and data migration. In the program's own stand-ups, the integration team talks about failed data loads and an unresolved access-control design issue. When the integration lead raised the access issue at a steering meeting two months ago, the director replied "let's take that offline." It has not come up since.

## Indicators present
| Indicator | What was seen | Evidence grade |
|---|---|---|
| F1 Watermelon reporting | Steering report green; team tracker shows open critical defects | Corroborated (report vs. defect tracker vs. interviews) |
| F2 Assessment never changes | Risk narrative identical for five reports | Corroborated (version history) |
| B2 Interrupted voice | Integration lead redirected when raising access issue | Single observation in minutes; corroborated by two interviews |
| C2 Concern raised once, never again | Access issue absent from all later reports and minutes | Corroborated (document review + interview) |

## Risk created or hidden
- Go-live with an access-control design flaw and incomplete supplier data.
- Incentive-driven optimism: the person reporting status benefits from green.
- Leadership is making go-live decisions on a picture that does not match the ground truth.

## What the GRC analyst does
1. **Compares sources side by side**: steering report, defect tracker, and test results for the same dates.
2. **Interviews the delivery team separately**, using process questions ("What would have to be true for this to be green?").
3. **Runs a pre-mortem** with the team: "It's launch week and this failed. Why?"
4. **Presents both views to the steering committee factually**, with sources, and recommends evidence-based status definitions.
5. **Logs the access issue formally** with an owner and target date so it cannot drop off again.

## Controls
- **Preventive:** status definitions tied to evidence (for example, green requires passed security test); independent second-line view on major programs; incentives that include quality and risk measures, not only date.
- **Detective:** periodic reconciliation of reported status against tracker data; anonymous pulse check of delivery-team confidence.

## Framework anchors
COSO 2013 **Principle 5** (accountability, including pressures and incentives) and **Principle 13** (relevant, quality information); COSO ERM 2017 **Principle 20** (reports on risk, culture, and performance); NIST CSF 2.0 **GV.OV-03** (risk management performance evaluated). See [04-framework-mapping.md](../04-framework-mapping.md).
