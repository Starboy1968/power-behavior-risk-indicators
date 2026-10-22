# 04 · Framework Mapping: Qualitative Analysis in COSO, NIST, and IIA Terms

Every principle number and identifier below was checked against the source document or a reputable reproduction of it (links in [sources.md](sources.md)). Where a framework is cited for a concept rather than a numbered item, it is referenced at the component or section level only.

The point of this page: these frameworks already expect organizations to manage **culture, authority, accountability, and override**. Those are mostly assessed qualitatively. This project shows *how*.

## COSO Internal Control: Integrated Framework (2013)

**Component: Control Environment (Principles 1 to 5).** This is where power and behavior live.

| Principle | What it says (short) | Qualitative evidence an analyst can gather | Indicators |
|---|---|---|---|
| **1** | Commitment to integrity and ethical values. Point of focus: *sets the tone at the top* | Do leaders' actions match stated values? How are deviations handled? Language used about controls | A1, A2, C3 |
| **2** | Board independence from management; oversight of internal control. Its points of focus include oversight of risks from fraud and *management override* | Does the oversight body ask probing questions, or approve what arrives? Is dissent recorded? | B3, B4, C1 |
| **3** | Structures, reporting lines, authorities, responsibilities (including segregation of duties and outsourced service providers) | Formal vs. observed decision path; who can approve what; supplier relationship ownership | D1, D2, D4 |
| **4** | Attract, develop, retain competent individuals. Point of focus: *plans and prepares for succession* | Key-person dependence; single relationship owners | D1 |
| **5** | Accountability for internal control responsibilities. Points of focus: performance measures, incentives, and rewards; *considers excessive pressures* | Incentives tied to dates over quality; who benefits from risk acceptance; named owners on decisions | A4, E1, F1 |

**Other COSO 2013 principles used in this project**

| Principle | Component | Use here |
|---|---|---|
| **8** | Risk Assessment: considers the potential for fraud (points of focus: incentives and pressures, opportunities, attitudes and rationalizations) | Conflict of interest, favored supplier, pressure-driven reporting |
| **13** | Information & Communication: relevant, quality information | Watermelon reporting; static assessments |
| **14** | Information & Communication: internal communication. Point of focus: *provides separate communication lines* (for example whistleblower channels) | Off-record concerns; fear of escalation |
| **16** | Monitoring: ongoing and separate evaluations | Long-running exceptions; committee effectiveness reviews |
| **17** | Monitoring: deficiencies communicated in a timely manner | Re-dated findings |

**Management override.** COSO treats management override as an *inherent limitation* of internal control, not a principle: overruling prescribed policies for illegitimate purposes. It is distinct from *management intervention*, which is a legitimate, overt, documented departure for unusual situations. This distinction is the core test in Scenarios 1, 2, and 4: was the departure disclosed and authorized, or not?

## COSO Enterprise Risk Management: Integrating with Strategy and Performance (2017)

**Component: Governance and Culture (Principles 1 to 5).**

| Principle | Title | Qualitative angle |
|---|---|---|
| **1** | Exercises Board Risk Oversight | Does oversight challenge management, or ratify? |
| **2** | Establishes Operating Structures | Do structures match how decisions actually flow? |
| **3** | Defines Desired Culture | Are desired risk behaviors defined, and do observed behaviors match? |
| **4** | Demonstrates Commitment to Core Values | Tone in meetings; how messengers of bad news are treated |
| **5** | Attracts, Develops, and Retains Capable Individuals | Key-person risk; whether expertise is heard |

Also used: **Principle 7, Defines Risk Appetite** (Strategy and Objective-Setting), relevant when appetite is effectively set by whoever has the most authority in the room; **Principle 20, Reports on Risk, Culture, and Performance** (Information, Communication, and Reporting), relevant to watermelon reporting.

## NIST Cybersecurity Framework (CSF) 2.0: Govern (GV) function

| ID | Outcome (abridged from CSF 2.0) | Qualitative angle |
|---|---|---|
| **GV.RR-01** | Leadership is responsible and accountable for cybersecurity risk and fosters a culture that is risk-aware, ethical, and continually improving | Observable leadership behavior around risk decisions |
| **GV.RR-02** | Roles, responsibilities, and authorities are established, communicated, understood, and enforced | Formal vs. observed authority; self-approval |
| **GV.RM-02** | Risk appetite and risk tolerance statements are established, communicated, and maintained | Is appetite applied as written, or overridden in the room? |
| **GV.RM-05** | Lines of communication across the organization are established for cybersecurity risks, including risks from suppliers and other third parties | Do concerns travel up, or stop with a gatekeeper? |
| **GV.OV-01** | Risk management strategy outcomes are reviewed to inform and adjust strategy and direction | Do oversight forums actually adjust anything? |
| **GV.OV-03** | Risk management performance is evaluated and reviewed for adjustments needed | Reconciling reported vs. actual status |
| **GV.SC-02** | Cybersecurity roles and responsibilities for suppliers, customers, and partners are established, communicated, and coordinated | Single relationship owners |
| **GV.SC-04** | Suppliers are known and prioritized by criticality | Critical suppliers managed informally |
| **GV.SC-06** | Planning and due diligence are performed before entering formal supplier relationships | Due diligence done after the decision |
| **GV.SC-07** | Supplier risks are understood, recorded, prioritized, assessed, responded to, and monitored over the relationship | Standing exceptions; filtered supplier information |

## NIST SP 800-39: Managing Information Security Risk

| Reference | What it covers | Qualitative angle |
|---|---|---|
| **Section 2.7, Organizational Culture** | Culture shapes how organizations respond to uncertainty and "informs and even, to perhaps a large degree, defines" the risk management strategy; a strategy inconsistent with culture is likely to be hard to implement | Assess culture directly; it predicts whether controls will operate as written |
| **Section 2.8.4, Culture and Risk Tolerance** | Relationship between culture and the organization's risk tolerance | Stated tolerance vs. tolerance shown in actual decisions |
| **Section 2.3.2, risk executive (function)** | Organization-wide function coordinating risk strategy and oversight | Is there an independent place for power-related concerns to go? |
| **Section 3.1, Framing Risk** (Tasks 1-1 to 1-4: assumptions, constraints, risk tolerance, priorities and trade-offs) | Making the risk frame explicit | Surface unstated assumptions such as "never been breached" or "leadership already decided" |
| **Section 3.4, Monitoring Risk** | Ongoing monitoring | Exceptions and findings that never close |

## IIA Three Lines Model (2020)

The model has six principles. The ones most relevant here:

| Principle | Relevance |
|---|---|
| **Principle 2, Governing body roles** | Oversight that is informed and willing to challenge |
| **Principle 3, Management and first and second line roles** | Second line provides expertise, support, monitoring, and **challenge** to first line, which is where power-related findings usually start |
| **Principle 5, Third line independence** | Internal audit's accountability to the governing body, unfettered access, and freedom from bias or interference: the escalation route when management is the issue |

## How this mapping is used in a finding

Each finding cites the **criteria** it is measured against. For example: "Risk acceptance was approved by the system owner without independent approval (criteria: internal acceptance policy; NIST CSF 2.0 GV.RR-02; COSO 2013 Principle 3)." The framework reference strengthens the finding, but the internal policy is always the primary criterion.
