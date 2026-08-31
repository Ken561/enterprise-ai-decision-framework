# Choosing an Enterprise AI Coding Assistant: A Decision Framework

> Leadership says "we need an AI coding assistant." The real question isn't which tool is coolest — it's which option provides the best balance of business value, adoption potential, security, governance, integration, and cost.

**Portfolio category:** DECISION — *the ability to evaluate competing options, make a recommendation, and defend the tradeoff.*

**Classification: Portfolio scenario.** This is a structured decision-making exercise built for this portfolio. It does not represent a decision made at JPMorganChase or any other employer, and the tools, scores, and outcome below are illustrative, not real vendor evaluations.

---

## The Problem

"We need an AI coding assistant" is a mandate, not a decision. Without a structured way to evaluate options, a decision like this tends to default to whichever tool is loudest in the market or whichever a senior engineer personally prefers — neither of which accounts for security exposure, governance fit, or whether the organization will actually adopt it once it's purchased.

## Why It Matters

An enterprise coding-assistant decision affects thousands of developers, touches source code and potentially proprietary systems, and is expensive and disruptive to reverse once rolled out. Getting the evaluation structure right matters as much as getting the final pick right.

## My Role

In this scenario, I act as the technical program/product leader responsible for running the decision process: defining criteria, building the scoring model, assessing risk, mapping stakeholders, and delivering a defensible executive recommendation — the same structure I use for real technology and AI tooling decisions in my program management work.

## Context

- Three candidate tools ("Tool A," "Tool B," "Tool C") under consideration.
- Competing priorities: engineering wants strong developer experience; security and risk want strict governance and data controls; finance wants predictable cost.
- No existing internal precedent for evaluating an AI coding tool at this scale.

## Approach

Defined evaluation criteria before looking at any specific tool, so the criteria wouldn't be reverse-engineered to justify a favorite. Built a weighted scoring model, ran each candidate against it, then layered a risk assessment and stakeholder map on top of the score — because the highest score and the right decision aren't automatically the same thing.

## Evaluation Criteria

Developer experience · Security · Enterprise integration · Governance · Cost · Adoption potential · Supportability · Implementation complexity

See [Evaluation Criteria](evaluation-criteria/criteria.md) and [Weighting](evaluation-criteria/weighting.md).

## Weighted Decision Matrix

| Criterion | Weight | Tool A | Tool B | Tool C |
|---|---|---|---|---|
| Developer experience | 25% | 4 | 5 | 3 |
| Security | 25% | 5 | 4 | 5 |
| Enterprise integration | 20% | 4 | 5 | 3 |
| Governance | 15% | 5 | 4 | 4 |
| Cost | 15% | 3 | 4 | 5 |
| **Weighted score** | **100%** | **4.35** | **4.45** | **3.85** |

*Portfolio demonstration data — not factual vendor ratings.* Full calculation logic in [Scoring Model](scoring-model/scoring-model.md).

## Decision

**Select Tool B.**

Tool B provides the strongest overall balance of developer experience and enterprise integration while remaining sufficiently strong across security, governance, and cost.

## Key Insight

The highest-scoring option and the safest option aren't always the same tool, and the job of the decision framework is to make that tension visible rather than let the weighted score quietly decide by default. Tool A scored higher on Security and Governance individually; Tool B still wins overall because those advantages weren't large enough to offset Tool B's clear lead on the criteria that determine whether developers actually use the tool day to day.

## Explicit Tradeoff

**We accept somewhat greater governance complexity in exchange for stronger adoption potential and enterprise integration.** A tool developers resist using delivers no value regardless of how well it scores on security or governance — but that tradeoff has to be named and accepted deliberately, with a mitigation plan, not ignored.

## Tradeoffs (Process-Level)

- **Speed vs. rigor:** A structured evaluation with a weighted scorecard, risk register, and stakeholder map takes longer than picking the loudest tool. Chosen deliberately, because reversing an enterprise-wide coding-assistant rollout is far more expensive than the extra weeks of evaluation.
- **Objectivity vs. usability:** A purely quantitative score is easy to defend but can hide judgment calls (like the Tool A vs. Tool B tension above). The decision memo makes that judgment explicit rather than hiding it behind the number.

## Outcome / Expected Outcome

**Expected outcome:** A phased rollout (pilot → controlled expansion → enterprise rollout → measurement) that validates the decision with real usage data before full-scale commitment, rather than betting the full enterprise deployment on the scoring model alone. See [Rollout Plan](rollout-plan/rollout.md).

## What I Would Do Next

- Re-run the scoring model after the pilot phase with real adoption and security data, not just vendor claims, and confirm the decision holds.
- Track the accepted governance tradeoff explicitly during rollout — the [Risk Register](risk-analysis/risk-register.md) is the place that tradeoff gets monitored, not forgotten.

## Artifacts

| Folder | Contents |
|---|---|
| [`problem-statement/`](problem-statement/) | The framing question and why it matters |
| [`evaluation-criteria/`](evaluation-criteria/) | Criteria definitions and weighting rationale |
| [`scoring-model/`](scoring-model/) | Scoring logic and the decision matrix (`.csv`) |
| [`risk-analysis/`](risk-analysis/) | Risk register across security, adoption, vendor, governance, cost |
| [`stakeholder-analysis/`](stakeholder-analysis/) | Stakeholder map and decision rights |
| [`decision-memo/`](decision-memo/) | One-page executive decision and decision log |
| [`rollout-plan/`](rollout-plan/) | Phased rollout plan |
| [`interview/`](interview/) | 30-second / 2-minute / 5-minute talking points |

## Skills Demonstrated

Structured decision-making · Weighted scoring models · Risk assessment · Stakeholder mapping · Executive communication · Governance-aware technology evaluation

---

## Source Notes

This entire repository is a **portfolio scenario** built to demonstrate a decision-making method. The evaluation criteria and process reflect how I approach real technology and AI tooling decisions in my program management work; the specific tools, scores, and final recommendation are fictional and created for this exercise. No real vendor, employer, or internal evaluation is represented here.
