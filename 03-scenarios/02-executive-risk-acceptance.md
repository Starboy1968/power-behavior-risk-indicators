# Scenario 2 · The Executive's Risk Acceptance

> **Illustrative scenario.** Fictional organization and roles.

## Setup
A distribution company's warehouse management system runs on an older server platform that cannot support the required multi-factor authentication for remote administration. Security recommends a compensating control and a replacement plan. The senior vice president of operations, who owns the system and whose annual objectives include peak-season uptime, asks for a 12-month risk acceptance. In the risk review meeting, the SVP speaks first: "This system has never been breached. We accept the risk. Leadership is aligned." The meeting moves on within minutes.

## Indicators present
| Indicator | What was seen | Evidence grade |
|---|---|---|
| E1 Risk owner accepts own risk | Same executive owns the system, benefits from no change, and signs the acceptance | Corroborated (acceptance form + objectives + DoA matrix) |
| A2 Pre-decided language | "Leadership is aligned" before discussion | Single observation, then repeated in a follow-up email |
| A3 Tradition as justification | "Never been breached" offered as the main rationale | Corroborated (minutes + email) |
| B1 HiPPO effect | Security architect began to describe exposure; discussion converged on SVP's view; no alternative recorded | Repeated pattern (this and two prior reviews) |
| A4 Passive voice | Final minutes: "The risk was accepted for 12 months." No approver named | Single document, verified |

## Risk created or hidden
- Remote administrative access without MFA on a system critical to fulfillment.
- Acceptance sits with someone who is not independent of the outcome.
- The acceptance rationale rests on absence of past incidents, not on current threat information.
- Minutes hide who accepted the risk and that a technical concern was raised.

## What the GRC analyst does
1. **Checks authority**: does policy let a system owner accept a risk of this severity alone, or does it need the CISO or a risk committee?
2. **Asks for the rationale in writing**, with the compensating control and a review date.
3. **Interviews the security architect separately** to capture the technical concern accurately.
4. **Requests a minutes correction** naming the approver and recording the concern raised.
5. **Frames the finding around the acceptance process**, not the SVP's judgment: "Acceptance was approved by the risk owner without the independent approval policy requires."
6. **Escalates** to the CISO (second line) if the acceptance stands without independent review.

## Controls
- **Preventive:** tiered acceptance authority (severity-based, with an independent co-approver above a threshold); mandatory compensating-control description; expiry date.
- **Detective:** quarterly report of active risk acceptances by owner and approver; flag any where they are the same person.
- **Meeting practice:** technical briefing before the decision discussion; senior attendees give their view last.

## Framework anchors
NIST CSF 2.0 **GV.RR-01** (leadership accountable, fosters risk-aware culture), **GV.RR-02** (roles and authorities enforced), **GV.RM-02** (risk appetite and tolerance statements); COSO ERM 2017 **Principle 1** (board risk oversight) and **Principle 7** (defines risk appetite); NIST SP 800-39 risk response and risk framing. See [04-framework-mapping.md](../04-framework-mapping.md).
