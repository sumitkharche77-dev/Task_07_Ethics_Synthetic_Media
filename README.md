# Task 07 — The Ethics of Synthetic Representation

## Project Description

This project is the ethics follow-on to Task 6, where I built a synthetic
two-person interview (host + analyst) delivering real, verified findings
from a Netflix viewership dataset, using three different synthesis
approaches (ElevenLabs, Bark, and D-ID). This task takes that artifact and
process log as its starting material and reasons outward from it — first
through systematic ethical analysis, then into a concrete governance
document.

The task has two required phases, both in this repository:

- **`ETHICAL_ANALYSIS.md`** (Phase A) — returns to the Task 6 artifact with
  fresh eyes, reasons through five axes (truth, consent, context, scale,
  and an added fifth axis — format authority) using specific, invented
  scenarios grounded in what I actually built and tested, and surveys the
  mitigation landscape (disclosure, provenance, detection, legal/regulatory
  context, platform policy, professional norms) against what my own Task 6
  testing actually showed.
- **`POLICY.md`** (Phase B) — a synthetic-media governance policy written
  for a local/regional newsroom, addressing permitted uses, prohibited
  uses, consent workflow, disclosure standards, provenance requirements,
  review and approval, incident response, refusal conditions, and an
  honest limitations section on where the policy would fail.

## Why a Newsroom

I chose a local/regional newsroom as the organizational context because it
connects directly to what I built in Task 6: a host/analyst interview
format is a journalism convention, and a newsroom's core asset — audience
trust that a real, accountable person is speaking — is exactly the thing
the Format Authority axis in my analysis identifies as most exposed by
this technology. Writing the policy for a setting where refusal is
genuinely costly (a newsroom under deadline pressure, competing on speed)
felt like a more honest test of the policy than a setting where saying no
costs nothing.

## Repository Contents

```
Task_07_Ethics_Synthetic_Media/
├── README.md              # this file
├── ETHICAL_ANALYSIS.md    # Phase A — ethical analysis and mitigation survey
└── POLICY.md              # Phase B — governance policy + limitations section
```

## Relationship to Task 6

This task's Phase A analysis is grounded in, and repeatedly references, my
Task 6 artifact, process log, evaluation, and detection results. That work
is not reproduced here — see the Task 6 repository:

**https://github.com/sumitkharche77-dev/Task_06_Deep_Fake**

No new synthetic media artifacts were produced for this task. This is a
written-reasoning and governance task only, per the assignment's
constraint.

## Reflection: What Surprised Me

Two things stood out while working through this. First, how much of the
Phase A reasoning came from re-reading my own *process log* rather than
listening to the artifact again — the engineering notes about loudness
imbalance, watermark survival, and Bark's non-determinism turned out to be
the actual evidence base for the ethical claims, not just production
trivia. Second, how much harder it was to write a policy that refuses
something than to write one that permits everything with disclosure — the
easy version of Phase B would have been a document that never said no.
Writing Section 8 (Refusal) and being specific about the four unconditional
prohibitions in Section 2 took noticeably more thought than the sections
describing what's allowed, which itself feels like a finding: permissive
governance is the path of least resistance, and a credible policy has to
actively resist that pull.
