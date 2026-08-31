# Risk Register

**Portfolio demonstration data.**

| Risk | Category | Likelihood | Impact | Mitigation | Owner |
|---|---|---|---|---|---|
| Developers resist adoption despite good developer-experience score | Adoption | Medium | High | Pilot with a volunteer team first; build champion network before full rollout | Program Office |
| Governance gap identified post-launch (Tool B scored lower than Tool A on Governance) | Governance | Medium | High | Require a governance remediation plan from the vendor before full rollout, tracked as a rollout gate | Risk / Compliance |
| Vendor dependency — pricing or roadmap changes after enterprise commitment | Vendor | Medium | Medium | Negotiate contract terms with defined price protection and an exit clause before scaling past pilot | Procurement |
| Security exposure through code/data handling at scale | Security | Low | High | Independent security review before controlled expansion phase, not just at initial evaluation | Security |
| Implementation complexity delays rollout timeline | Implementation | Medium | Medium | Phase rollout (see [Rollout Plan](../rollout-plan/rollout.md)) so delays affect a pilot group, not the full enterprise | Program Office |
| Cost scales faster than expected as usage grows | Cost | Low | Medium | Set a usage-based cost review checkpoint at the end of the controlled-expansion phase | Finance |

## Why the Governance Gap Is the Risk to Watch Most Closely

The scoring model shows Tool B scoring lower than Tool A on Governance (4 vs. 5) — the exact tradeoff named in the [Executive Decision](../decision-memo/executive-decision.md). Because this is a known, accepted tradeoff rather than a surprise, it gets an explicit mitigation and a named owner here instead of being rediscovered as a problem after rollout.

## Review Cadence

This register is reviewed at every rollout-plan gate (pilot → controlled expansion → enterprise rollout), not just at the point of initial decision — a risk accepted at the pilot stage should be re-examined once real usage data exists.
