# Weighting Rationale

## Weights Used

| Criterion | Weight |
|---|---|
| Developer experience | 25% |
| Security | 25% |
| Enterprise integration | 20% |
| Governance | 15% |
| Cost | 15% |

*Supportability and implementation complexity are tracked as qualitative decision inputs (see [Risk Register](../risk-analysis/risk-register.md)) rather than weighted numerically, since they primarily affect risk and timeline rather than the core value proposition.*

## Why Developer Experience and Security Are Weighted Equally, at the Top

This is a deliberate signal, not an accident of arithmetic: a tool that scores well on security but that developers won't use delivers no value, and a tool developers love but that creates unmanaged security exposure isn't a responsible choice either. Weighting these two criteria equally, and highest, forces the scoring model to treat them as equally disqualifying rather than letting a strong score in one silently outweigh a weak score in the other.

## Why Cost Is Weighted Lowest of the Numerically Scored Criteria

At enterprise scale, the cost difference between credible vendor options is usually smaller than the cost of choosing a tool with weak security or low adoption. Cost still matters — it's part of the model — but it shouldn't be allowed to dominate a decision this consequential.

## How Weights Were Set

Weights reflect a synthesis of the stakeholder priorities identified in the [Stakeholder Map](../stakeholder-analysis/stakeholder-map.md), not a single group's preference. Where stakeholders disagreed on relative importance, the weighting favors the criteria with the largest downside if under-weighted (security, adoption) over the criteria with the largest upside if over-weighted (cost).
