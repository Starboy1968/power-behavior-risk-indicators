# Indicator Catalog: 22 Observable Power and Behavior Indicators

Each indicator is something an analyst can **see, hear, or read** in normal GRC work: meetings, minutes, emails, approval records, interviews. None of them proves wrongdoing alone. Each tells you where to look harder.

**How to read each entry**
- **You observe:** the concrete signal
- **May signal:** the underlying risk (a hypothesis, not a conclusion)
- **Evidence it by:** how to confirm or rule it out
- **Proportionate response:** start here; escalate only if evidence strengthens (see [escalation guide](../05-analyst-toolkit/escalation-decision-guide.md))

**Evidence strength** (used throughout, defined in [qualitative-methods.md](qualitative-methods.md#5-grade-the-evidence-in-words)):
`Single observation` → `Repeated pattern` → `Corroborated pattern` (repeated *and* confirmed by an independent source)

---

## Lens A · Language around risk

### A1. Minimizing language
- **You observe:** "It's just a formality." "Only a questionnaire." "Low risk, trust me." Used to describe a control, review, or due diligence step.
- **May signal:** The control is seen as an obstacle; it may be done superficially or skipped.
- **Evidence it by:** Collect the phrases with date and context. Check whether the step was actually completed, and how thoroughly (time spent, sections left blank, evidence attached).
- **Proportionate response:** Ask neutrally what the step is meant to catch. If completion quality is poor, raise it as a control-operation finding, not a comment on the speaker.

### A2. Pre-decided language
- **You observe:** "Leadership already decided." "This is happening either way." "We just need risk to sign off."
- **May signal:** The risk process is being used to ratify, not inform, a decision. Risk appetite is set by whoever spoke first, not by policy.
- **Evidence it by:** Compare the decision date (emails, purchase orders, project kick-off) with the risk review date. Ask who "leadership" is and whether that person holds the authority to accept this risk.
- **Proportionate response:** Clarify who the accountable decision-maker is and ask for the decision in writing at that level. Document the sequence.

### A3. Tradition as justification
- **You observe:** "We've always done it this way." "We've never had a problem." "That vendor has been fine for ten years."
- **May signal:** Normalization of deviance: a known gap has become accepted because nothing bad has happened yet. Availability bias in reverse (no recent incident, so no risk).
- **Evidence it by:** Ask when the practice was last reviewed against current policy. Look for near-misses, workarounds, or prior findings that were closed without change.
- **Proportionate response:** Request a fresh review against current requirements; frame it as routine re-validation.

### A4. Passive voice that hides ownership
- **You observe:** "The risk was accepted." "It was decided to proceed." "The exception was granted." No name, no role.
- **May signal:** Accountability gap. Nobody wants their name on the decision, or nobody actually made one.
- **Evidence it by:** Trace each passive statement to a named approver in the system of record. Note how many cannot be traced.
- **Proportionate response:** Require a named role and date for every acceptance and exception. Report untraceable decisions as a documentation control gap.

---

## Lens B · Meeting dynamics

### B1. Most senior voice first, then convergence (HiPPO effect)
- **You observe:** The highest-ranking person gives a view early; discussion then narrows to agreement with that view. Initial positions held by others quietly change.
- **May signal:** Ratings and decisions reflect authority, not analysis. Groupthink risk.
- **Evidence it by:** Structured observation across several meetings: note speaking order and whether early senior opinions predict outcomes. Compare pre-meeting written inputs (if any) with final ratings.
- **Proportionate response:** Recommend independent input before discussion and having senior attendees speak last. See [judgment-distortions.md](judgment-distortions.md).

### B2. The same people repeatedly interrupted or talked over
- **You observe:** A particular role (often a control owner, engineer, or junior analyst) is cut off, redirected ("let's take that offline"), or talked over, meeting after meeting.
- **May signal:** Risk information from the people closest to the work is not reaching decision-makers.
- **Evidence it by:** Observation notes that record *what was being said* when the interruption happened and *whether the point was ever picked up again*. Follow up privately with the person in a neutral interview.
- **Proportionate response:** Make sure the point gets captured in writing (an action item or a parking-lot log with an owner). Recommend facilitation changes rather than naming individuals.

### B3. The real decision happens outside the meeting
- **You observe:** Agenda items are "for noting." Decisions are announced, not discussed. Attendees say "that was settled last week."
- **May signal:** The governance forum is a formality; real authority sits with a smaller, undocumented group.
- **Evidence it by:** Compare meeting minutes with prior emails or calendar invites. Ask attendees where the decision was actually made.
- **Proportionate response:** Recommend that decisions within the forum's charter are tabled for discussion before they are final, with the record showing who decided.

### B4. Rubber-stamp approvals
- **You observe:** Risk items approved in seconds; no questions; large batches approved together; the same approver approves everything.
- **May signal:** The approval control exists on paper but provides no real review.
- **Evidence it by:** Approval timestamps, number of items per session, rejection or return rate over time (a rate near zero over a long period is a prompt to ask, not proof).
- **Proportionate response:** Sample approvals and test whether the approver can explain the basis. Recommend a review standard (what the approver must check).

---

## Lens C · How dissent is received

### C1. Dissent missing from minutes
- **You observe:** Minutes say "agreed" or "consensus," but attendees recall disagreement or a concern that was raised.
- **May signal:** The record is being cleaned. Future reviewers will believe the decision was uncontested.
- **Evidence it by:** Compare minutes against attendee recollections (separately interviewed), chat logs, or slide comments.
- **Proportionate response:** Recommend minutes record material concerns and how they were resolved. Raise the specific instance factually.

### C2. Concern raised once, never again
- **You observe:** Someone raises an issue in one meeting or email thread, then goes quiet on it, even though the issue was not resolved.
- **May signal:** Chilling effect. The person learned that raising it was costly or pointless.
- **Evidence it by:** Track the concern: was it logged, assigned, answered? Ask the person, privately and openly, what happened to it.
- **Proportionate response:** Get the concern into a tracked system with an owner. Protect the source.

### C3. Consequences for the messenger
- **You observe:** People who raised issues are later reassigned, excluded from meetings, or described as "difficult" or "not a team player."
- **May signal:** Fear of escalation; retaliation risk; future issues will go unreported.
- **Evidence it by:** Handle with care. Look for a pattern over time and across more than one person. Do not investigate employment matters yourself.
- **Proportionate response:** This is a potential retaliation matter. Route it through the appropriate channel (ethics, HR, legal, or internal audit) per the [escalation guide](../05-analyst-toolkit/escalation-decision-guide.md). Do not confront anyone.

### C4. Concerns only shared off the record
- **You observe:** "Don't quote me." "I'll tell you, but not in writing." Formal reporting channels are rarely used.
- **May signal:** Low psychological safety; formal channels are not trusted.
- **Evidence it by:** Number of off-record comments across interviews; usage data for the ethics or issue-reporting channel (low usage is a prompt, not proof).
- **Proportionate response:** Report the theme in aggregate (no attribution). Recommend reinforcing non-retaliation and channel independence.

---

## Lens D · Informal power and networks

### D1. One person owns a critical vendor relationship
- **You observe:** All communication with a key supplier goes through one person. Others "don't have the contact." Contract history lives in that person's inbox.
- **May signal:** Key-person risk, information gatekeeping, possible conflict of interest, and no independent view of supplier performance.
- **Evidence it by:** Map who interacts with the supplier (email domains, meeting invites, contract file access). Check whether performance reviews are done by anyone else.
- **Proportionate response:** Recommend a secondary relationship owner, centralized contract records, and periodic independent performance review.

### D2. The real approval path differs from the org chart
- **You observe:** People say "check with X first," and X has no formal role in that decision. Formal approvers wait for X's view.
- **May signal:** Informal authority that is not accountable. Decisions can be steered without a record.
- **Evidence it by:** Interview question: "Who do you go to when you need this approved fast?" Compare answers across several people with the formal RACI or delegation of authority.
- **Proportionate response:** Either formalize X's role (with accountability) or remove the informal step. Document the gap neutrally. See [influence-map.md](influence-map.md).

### D3. The untouchable sponsor
- **You observe:** A project or vendor is described as "the CEO's project" or "protected." Findings against it are softened or delayed.
- **May signal:** Authority overriding risk appetite; findings suppressed upstream.
- **Evidence it by:** Compare draft vs. final wording of findings; compare remediation timelines with similar issues elsewhere.
- **Proportionate response:** Apply the same standard as for any other item and document the comparison. If findings are being altered, escalate via an independent line (see escalation guide).

### D4. Requester, evaluator, and approver are the same person or circle
- **You observe:** The person who wants the vendor also scored the bids and approved the contract, or the approver reports to the requester.
- **May signal:** Segregation-of-duties failure; conflict of interest.
- **Evidence it by:** Approval workflow records, bid evaluation sheets, reporting lines, conflict-of-interest declarations (present, missing, or stale).
- **Proportionate response:** Recommend independent evaluation and approval, and a current conflict-of-interest declaration. Report as a design gap.

---

## Lens E · The decision trail

### E1. The risk owner accepts their own risk
- **You observe:** The executive who owns the system, project, or vendor also signs its risk acceptance, often with a target or bonus tied to delivery.
- **May signal:** Self-review; risk accepted above appetite with no independent challenge.
- **Evidence it by:** Risk acceptance forms vs. delegation-of-authority matrix; who benefits from acceptance.
- **Proportionate response:** Recommend that acceptances above a defined threshold require a second, independent approver and a review date.

### E2. Repeated deadline-driven exceptions
- **You observe:** The same exception renewed again and again, each time "temporary," each time because of a deadline.
- **May signal:** Normalization of deviance. The exception has become the real process.
- **Evidence it by:** Exception log history: count of renewals, stated reasons, whether the reason changed, whether compensating controls were ever verified.
- **Proportionate response:** Treat a long-running exception as a standing risk requiring formal acceptance at the right level, or a remediation plan with a fixed end.

### E3. Findings repeatedly re-dated
- **You observe:** Audit or issue due dates move again and again with thin rationale ("resource constraints"), often just before they would go overdue.
- **May signal:** Overdue reporting is being avoided; the issue is not actually being worked.
- **Evidence it by:** Issue tracker audit history: original date, each change, who changed it, stated reason, evidence of progress between changes.
- **Proportionate response:** Report both original and current dates. Recommend that re-dating beyond a set limit requires approval by someone independent of the issue owner.

### E4. Due diligence done after the decision
- **You observe:** Supplier questionnaire completed after contract signature, or after the vendor already has system access.
- **May signal:** Due diligence is a paperwork step, not a decision input. Third-party risk is accepted by default.
- **Evidence it by:** Compare dates: contract signature, purchase order, access provisioning, due diligence completion.
- **Proportionate response:** Report the sequence. Recommend a hard gate (no PO or access until due diligence is complete, or a documented exception at the right level).

---

## Lens F · Reporting

### F1. Watermelon reporting (green outside, red inside)
- **You observe:** Status reports or KRIs are green, while people doing the work describe delays, workarounds, or worry.
- **May signal:** Reporting carries a personal cost, so it is filtered on the way up. Leadership sees a better picture than reality.
- **Evidence it by:** Compare reported status with ground-level evidence: ticket backlogs, test results, interview themes, defect logs. Note who edits the status before it goes up.
- **Proportionate response:** Present the two views side by side with sources. Recommend status definitions that are evidence-based, and a channel for the delivery team's own view.

### F2. Assessments that never change, and bad news that arrives all at once
- **You observe:** Risk descriptions and ratings copied forward unchanged for many cycles, then a sudden jump when the problem can no longer be hidden.
- **May signal:** The assessment is a ritual, not an analysis; problems are surfaced only when unavoidable.
- **Evidence it by:** Version history of the risk register; compare with known changes in the environment (new systems, incidents, supplier changes).
- **Proportionate response:** Recommend a required "what changed since last time?" field and periodic independent challenge of static entries.

---

## Caution on interpreting indicators

- **Context first.** A blunt speaker may simply be blunt. An urgent exception may be legitimate. COSO distinguishes legitimate, disclosed *management intervention* from *management override* for illegitimate purposes.
- **Patterns over time.** Do not draw conclusions from a single meeting or a single gesture.
- **No body-language verdicts.** Nonverbal cues (crossed arms, silence, eye contact) vary across individuals, cultures, and neurotypes. Use them only as prompts to ask a neutral question, never as evidence on their own.
- **Fairness.** Describe what happened and its effect on risk. Give management a chance to respond before a finding is final.
