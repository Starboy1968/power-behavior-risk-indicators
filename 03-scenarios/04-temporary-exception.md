# Scenario 4 · The "Temporary" Exception

> **Illustrative scenario.** Fictional organization and roles.

## Setup
To meet a holiday shipping deadline, a logistics company granted a temporary firewall exception allowing a carrier's tracking system to connect directly to an internal database. The exception has been renewed every quarter since, always with the same reason: "deadline; will remediate after peak." A related internal audit finding about the connection has had its due date moved several times, each time shortly before it would have shown as overdue. When asked, the network team lead says, "We've always done it this way and there's never been a problem."

## Indicators present
| Indicator | What was seen | Evidence grade |
|---|---|---|
| E2 Repeated deadline-driven exceptions | Same exception renewed each quarter, same rationale | Corroborated (exception log + change tickets) |
| E3 Findings re-dated | Audit issue due date changed repeatedly, no progress noted between changes | Corroborated (issue tracker history) |
| A3 Tradition as justification | "Always done it this way; never a problem" | Repeated pattern (interviews) |
| A4 Passive voice | Renewal entries: "exception extended" with no approver name | Corroborated (log review) |

## Risk created or hidden
- A standing direct connection from a third party into an internal database: third-party access risk that has quietly become permanent.
- Normalization of deviance: each renewal makes the next one easier.
- Re-dating keeps the issue out of overdue reporting, so leadership never sees it as aged.

## What the GRC analyst does
1. **Builds a timeline**: original exception, every renewal, every due-date change, who changed it and why.
2. **Checks compensating controls**: were they ever implemented and tested?
3. **Reframes the item**: this is no longer an exception; it is a standing risk that needs either formal acceptance at the right level or a funded remediation plan with a fixed end date.
4. **Reports original and current due dates together** so the age of the issue is visible.
5. **Asks the carrier relationship owner** whether the carrier's own security posture has been reviewed since the connection opened.

## Controls
- **Preventive:** exceptions expire automatically; each renewal requires approval one level higher and a new rationale; a cap on renewals before mandatory risk committee review.
- **Detective:** report of exceptions older than a set age; issue tracker report showing number of re-dates and original due dates.

## Framework anchors
COSO 2013 **Principle 16** (ongoing and separate evaluations) and **Principle 17** (deficiencies communicated in a timely manner); NIST CSF 2.0 **GV.SC-07** (supplier risk monitored over the relationship); NIST SP 800-39 risk monitoring. Real-world parallel: Diane Vaughan's work on the Challenger launch decision (real case, see [sources.md](../sources.md)). See [04-framework-mapping.md](../04-framework-mapping.md).
