# Rollout Plan

## Phase 1 — Pilot

- Deploy Tool B to a small, volunteer group of developers across 1–2 teams.
- Collect developer-experience feedback and baseline productivity signals.
- Begin the governance remediation plan required by the [Executive Decision](../decision-memo/executive-decision.md) in parallel, not after the pilot ends.

## Phase 2 — Controlled Expansion

- Expand to a broader set of teams representative of different engineering contexts (e.g., varying codebases, security sensitivity levels).
- Complete the independent security review identified in the [Risk Register](../risk-analysis/risk-register.md).
- Confirm the governance remediation plan is functioning as intended before proceeding further.

## Phase 3 — Enterprise Rollout

- Full deployment across engineering, gated on successful completion of Phases 1 and 2.
- Governance and security sign-off required before this phase begins — this is the point at which the accepted tradeoff on Governance must be demonstrated as adequately mitigated, not just planned for.

## Phase 4 — Measurement & Optimization

- Re-run the [Scoring Model](../scoring-model/scoring-model.md) using real usage, security, and adoption data instead of initial vendor evaluation inputs.
- Confirm the original decision holds; if not, this is the checkpoint where it gets revisited, per the [Decision Log](../decision-memo/decision-log.md)'s revisit trigger.

## Why Phase Gates, Not a Single Launch

Each phase gate exists specifically to catch the risks identified in the [Risk Register](../risk-analysis/risk-register.md) before they affect the whole organization — a single big-bang launch would mean discovering an adoption or governance problem only after it's already enterprise-wide.
