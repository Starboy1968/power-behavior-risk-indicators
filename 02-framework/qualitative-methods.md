# Qualitative Methods: How to Assess What Metrics Miss

Qualitative work is not "soft." Done well, it is systematic: you decide in advance what to look for, record it consistently, test it against other sources, and say plainly how strong the evidence is.

## 1. Structured observation

Observe governance meetings you already attend or are invited to (risk committees, change advisory boards, vendor reviews, project steering groups). Never record covertly; follow your organization's policy on meeting attendance and note-taking.

**What to note (behavior, not interpretation)**

| Record this | Not this |
|---|---|
| "Risk item 4 approved in under one minute; no questions asked." | "Nobody cared about item 4." |
| "Control owner began to describe the patch backlog; chair said 'let's take that offline.' Not revisited." | "The chair shut them down." |
| "Minutes draft says 'agreed'; two attendees raised timing concerns during discussion." | "The minutes are a cover-up." |
| "VP gave a view first; three subsequent speakers agreed; final rating matched VP's view." | "Everyone is scared of the VP." |

**What to watch for over several meetings**
- Speaking order, and whether early senior opinions predict outcomes
- Who is interrupted, redirected, or talked over, and on what topics
- How questions and challenges are received (answered, deflected, dismissed, joked away)
- Whether decisions are discussed or announced
- Tone shifts when risk topics come up (rushed, defensive, dismissive). Record what was said and done, not how someone "seemed."

**Nonverbal cues: use with care**
Silence, posture, or eye contact can prompt a follow-up question ("I noticed the team went quiet on item 3; is there anything we should know?"). They are never evidence on their own, because they vary across people, cultures, and neurotypes, and because reading individuals' body language invites unfair conclusions.

Template: [observation-note-template.md](../05-analyst-toolkit/observation-note-template.md)

## 2. Semi-structured interviews

A short list of planned open questions, with room to follow up.

- **Interview across levels and lines:** the decision-maker, the control owner, the person doing the work, and someone in a second-line role.
- **Ask about process, not people:** "Walk me through the last time a vendor exception was approved" works better than "Does your manager bully people?"
- **Ask for examples:** "Can you think of a time when...?" turns opinion into evidence you can check.
- **Neutral wording:** avoid leading questions ("Isn't it true that...").
- **Protect the source:** tell interviewees how notes will be used; report themes in aggregate; never attribute sensitive comments without consent.
- **Interview separately:** people in the same room converge, which is the very thing you are trying to observe.

Question bank: [interview-question-bank.md](../05-analyst-toolkit/interview-question-bank.md)

## 3. Document and minutes language review

Read the record for what it says, how it says it, and what it leaves out.

| Look for | Example | Why it matters |
|---|---|---|
| Minimizing words | "just", "only", "minor", "formality" | Control seen as an obstacle |
| Pre-decided framing | "already approved", "leadership decided", "need sign-off" | Risk process used to ratify |
| Passive voice | "was accepted", "it was decided" | Hides who owns the decision |
| Absence | No recorded concerns in a contentious meeting | Dissent edited out |
| Copy-forward text | Identical risk narrative for many cycles | Assessment is a ritual |
| Date sequence | Due diligence dated after contract | Decision made before review |
| Hedged commitments | "aim to", "where possible", "subject to resources" | No real commitment |

Tip: build a short glossary of the phrases you search for, and apply it the same way across all documents so your review is consistent and repeatable.

## 4. Triangulation

A finding needs at least **two independent sources** pointing the same way. Independent means the sources did not inform each other.

```
Observation (what you saw)  ─┐
Interview (what people say)  ─┼──►  Do they agree?  ──►  Finding strength
Documents (what the record shows) ─┘
```

- If sources **agree**, the pattern is corroborated.
- If they **conflict**, that is itself a finding (for example, minutes say consensus; interviews describe disagreement).
- If you only have one source, say so, and treat it as a lead.

## 5. Grade the evidence in words

| Grade | Meaning | What you can say |
|---|---|---|
| **Single observation** | Seen or heard once, one source | "We observed one instance of..." Use as a lead; do not report as a finding on its own. |
| **Repeated pattern** | Seen several times, one type of source | "Across four of five committee meetings observed, ..." Reportable as an observation; recommend review. |
| **Corroborated pattern** | Repeated and confirmed by an independent source | "Minutes, approval records, and interviews consistently show..." Reportable as a finding with a recommendation. |

Also note **limits**: how many meetings you observed, how many people you interviewed, what you could not access.

## 6. Writing a qualitative finding that holds up

Use **Condition → Criteria → Cause → Effect → Recommendation**, and keep it about the process.

**Weak (opinion):**
> The procurement lead bullies people into skipping due diligence.

**Strong (factual, defensible):**
> **Condition:** For 3 of 4 contracts with Supplier X sampled from the last 12 months, the security due diligence questionnaire was completed after contract signature. In two related email threads, the request was described as "just a formality" and "already decided by leadership." (Evidence: contract system dates, questionnaire timestamps, email extracts. Grade: corroborated pattern.)
> **Criteria:** Third-party policy requires due diligence before contract award; NIST CSF 2.0 GV.SC-06 expects due diligence before entering formal supplier relationships.
> **Cause:** The workflow lets a PO be raised before due diligence is complete; one person manages the supplier relationship, requests the contract, and approves the evaluation.
> **Effect:** Supplier risk is accepted by default, without review at the appropriate level.
> **Recommendation:** Add a workflow gate; assign independent evaluation; require a current conflict-of-interest declaration; add a secondary relationship owner.

Notice what the strong version does: it counts, it dates, it quotes the record (not people's tone), it names the control gap, and it never characterizes anyone's personality. (These numbers are part of an illustrative example, not real data.)

Template: [finding-write-up-template.md](../05-analyst-toolkit/finding-write-up-template.md)

## 7. Ethics, privacy, and fairness

- Observe only work settings and work records you are authorized to access.
- No covert recording, personal social media review, or monitoring outside your mandate.
- Protect interviewees; report sensitive themes in aggregate.
- Do not investigate possible misconduct or retaliation yourself. Route it to the right function.
- Share draft findings with management for factual accuracy before finalizing.
- Separate what you observed from what you infer, every time.
