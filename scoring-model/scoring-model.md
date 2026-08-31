# Scoring Model

**Portfolio demonstration data — not factual vendor ratings.**

## Method

Each tool is scored 1–5 on each criterion, multiplied by the criterion's weight, and summed to produce a weighted score out of 5.

## Weighted Decision Matrix

| Criterion | Weight | Tool A | Tool B | Tool C |
|---|---|---|---|---|
| Developer experience | 25% | 4 | 5 | 3 |
| Security | 25% | 5 | 4 | 5 |
| Enterprise integration | 20% | 4 | 5 | 3 |
| Governance | 15% | 5 | 4 | 4 |
| Cost | 15% | 3 | 4 | 5 |
| **Weighted score** | **100%** | **4.35** | **4.45** | **3.85** |

## Calculation Logic (Tool B)

```
Developer experience: 5 × 0.25 = 1.25
Security:             4 × 0.25 = 1.00
Enterprise integration: 5 × 0.20 = 1.00
Governance:           4 × 0.15 = 0.60
Cost:                 4 × 0.15 = 0.60
-----------------------------------------
Weighted score:                = 4.45
```

Machine-readable version: [decision-matrix.csv](decision-matrix.csv)

## Reading the Result

Tool B wins by a narrow margin (4.45 vs. 4.35 for Tool A) — narrow enough that the score alone shouldn't be the entire justification. That's why the [Risk Register](../risk-analysis/risk-register.md) and [Executive Decision Memo](../decision-memo/executive-decision.md) go further than the number, examining what the gap actually means in practice: Tool A's security and governance edge versus Tool B's developer experience and integration edge.

## Why Not Just Pick the Highest Score

A model this simple can't capture everything — for instance, it doesn't weight how *close* two options are, or whether a single low score (like Tool C's governance-relevant security score of 5 undercut by weak developer experience) represents a dealbreaker rather than an average-able input. The score is a structured starting point for judgment, not a replacement for it.
