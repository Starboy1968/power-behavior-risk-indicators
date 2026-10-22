# Reading the Room: Qualitative Power and Behavior Indicators in GRC

**A practical framework for spotting how power, incentives, and group behavior shape risk decisions, and for turning what you observe into findings that hold up.**

Risk registers and dashboards record what people agree to write down. They rarely show *who* decided, *who* stayed quiet, or *why* a red risk keeps reporting green. This project gives a GRC or third-party risk analyst a structured, evidence-based way to read those signals: the language around risk, how meetings run, how dissent is treated, who people actually go to, and how documents drift from reality. It covers qualitative methods (observation, interviews, minutes review, triangulation), a catalog of observable indicators, six illustrative scenarios (two in supply chain / third-party risk), mapping to COSO and NIST, and a ready-to-use analyst toolkit.

> All scenarios are fictional and labeled illustrative. Real cases are cited briefly, labeled as real, and linked to primary or reputable sources in [sources.md](sources.md).

## Why this matters to GRC

- **Controls fail through people before they fail on paper.** COSO treats management override as an inherent limit of any internal control system, and its control environment principles are about integrity, oversight, authority, and accountability: behavior, not tooling.
- **Metrics miss what nobody is willing to report.** A dashboard can stay green while the people closest to the work are worried. Qualitative evidence fills that gap.
- **Third-party risk is relationship risk.** Due diligence can be bypassed by whoever owns the supplier relationship. NIST CSF 2.0 (GV.SC-06) expects due diligence *before* the relationship starts, not after someone influential has already chosen.

## The indicator framework at a glance

| Lens | What you look for (examples) | Where you find it |
|---|---|---|
| **Language** | "Just a formality", "leadership already decided", "we've always done it this way", passive voice that hides who owns the decision | Minutes, emails, risk acceptance rationale, interviews |
| **Meeting dynamics** | Who speaks first, who gets interrupted or talked over, decisions made before the meeting | Structured observation over several meetings |
| **Dissent** | Concerns raised once then never again; dissent missing from minutes; people who raised issues later sidelined | Minutes vs. attendee recollection, interviews |
| **Informal power** | Gatekeepers, sponsors, one person who "owns" a vendor; real decision path differs from the org chart | Interviews, approval trails, email routing |
| **Decision trail** | Risk owner signs their own acceptance; exceptions renewed again and again; audit dates quietly moved | Exception logs, acceptance forms, issue trackers |
| **Reporting** | Watermelon status (green outside, red inside); updates that never change; bad news arriving late and all at once | Status reports vs. ground-level evidence |

Full catalog: **22 indicators**, each with what it may signal, how to evidence it, and a proportionate response: [02-framework/indicator-catalog.md](02-framework/indicator-catalog.md)

## Scenario teaser (illustrative)

> A procurement lead has used the same packaging supplier for years. A new contract is "urgent," the security questionnaire is described as "just a formality," and the lead tells the vendor risk team that "leadership already decided." Approval is requested on a Friday with a Monday start date. No single item proves anything. Together, and repeated across three emails and a meeting, they form a pattern worth evidencing.
> 
> What the analyst does next: [03-scenarios/01-favored-supplier.md](03-scenarios/01-favored-supplier.md)

## How the analysis works

1. **Observe** with structured notes (behavior, not interpretation).
2. **Ask** with semi-structured interviews (open, neutral questions).
3. **Read** documents and minutes for language and gaps.
4. **Triangulate** across at least two independent sources.
5. **Grade** evidence in words: *single observation*, *repeated pattern*, *corroborated pattern*.
6. **Write** the finding about the process and its effect on risk, never about personality.

Method guide: [02-framework/qualitative-methods.md](02-framework/qualitative-methods.md)

## Skills demonstrated

- Control environment and risk culture assessment (COSO 2013, COSO ERM 2017)
- Governance analysis against NIST CSF 2.0 Govern (GV.RR, GV.RM, GV.OV, GV.SC) and NIST SP 800-39 risk framing
- Third-party and supply chain risk: due diligence bypass, key-person and relationship concentration
- Qualitative methods: structured observation, interviewing, document review, triangulation
- Writing defensible, fair findings and escalating sensitive issues safely
- Recognizing judgment distortions (anchoring, optimism, groupthink, normalization of deviance, HiPPO, availability)

## Repo map

| Path | What it is |
|---|---|
| [01-project-brief.md](01-project-brief.md) | Objective, scope, questions answered |
| [02-framework/indicator-catalog.md](02-framework/indicator-catalog.md) | 22 observable indicators in six lenses |
| [02-framework/qualitative-methods.md](02-framework/qualitative-methods.md) | Observation, interviews, document review, triangulation, evidence grading, writing findings |
| [02-framework/judgment-distortions.md](02-framework/judgment-distortions.md) | How bias distorts risk judgment, and specific debiasing controls |
| [02-framework/influence-map.md](02-framework/influence-map.md) | Formal authority vs. informal influence (mermaid diagram) |
| [03-scenarios/](03-scenarios/) | Six illustrative case scenarios |
| [04-framework-mapping.md](04-framework-mapping.md) | COSO 2013, COSO ERM 2017, NIST CSF 2.0, NIST SP 800-39, IIA Three Lines |
| [05-analyst-toolkit/](05-analyst-toolkit/) | Interview bank, risk-culture checklist, observation template, finding template, escalation guide |
| [sources.md](sources.md) | Framework sources and briefly summarized real cases |

## Related projects

- [AI Supply Chain Risk Assessment](https://github.com/Starboy1968/ai-supply-chain-risk-assessment): scored risk assessment of AI in the supply chain, with controls, KRIs, and vendor due diligence.
- [AI-Assisted Risk Analysis](https://github.com/Starboy1968/ai-assisted-risk-analysis): using AI tools to support, not replace, analyst judgment.

This project is the qualitative complement to those: the numbers tell you *what* the risk is; reading the room tells you whether the numbers can be trusted.

---

**Author:** [Rashon Alsberry, supply chain and third-party risk analyst](https://starboy1968.github.io) · CompTIA Security+
