# Interview Talking Points — Enterprise AI Decision Framework

## 30-Second Version

"Leadership said 'we need an AI coding assistant' — that's a direction, not a decision. I built a weighted evaluation framework across developer experience, security, integration, governance, and cost, scored three candidate tools against it, and picked the option with the strongest overall balance — even though a competitor scored higher on security and governance individually. I named that tradeoff explicitly instead of hiding it behind the final number."

## 2-Minute Version

**Problem →** An ambiguous mandate with no structured way to evaluate options, which usually means the loudest tool or a senior engineer's personal favorite wins by default.

**Evidence →** Defined evaluation criteria before looking at any specific tool, so criteria wouldn't be reverse-engineered to justify a favorite. Built a weighted scoring model with input synthesized from every stakeholder group — engineering, security, risk, finance.

**Decision →** The two top options were close (4.45 vs. 4.35). Rather than treat the number as the whole answer, I looked at *why* they were close: the winning tool led on developer experience and integration — the factors most predictive of real adoption — while the other candidate led on security and governance.

**Implementation →** Made the tradeoff explicit in the decision memo instead of letting the score quietly resolve it, and built a phased rollout (pilot → controlled expansion → enterprise rollout → measurement) so the decision gets validated with real data before full commitment.

**Result →** A decision that's defensible twelve months later, because the reasoning — including what was deliberately given up — is documented, not just the outcome.

## 5-Minute Version

Add to the 2-minute version:

- **Stakeholders:** Executives (final approval), engineering (input + pilot sign-off), security and risk/legal (veto rights on unresolved findings), procurement (contract terms), and developers (no formal vote, but adoption depends entirely on their buy-in).
- **Constraints:** No existing internal precedent for evaluating an AI coding tool at enterprise scale; competing stakeholder priorities that would each weight the criteria differently if left alone.
- **Alternatives considered:** The stronger-security, stronger-governance option (rejected as the top pick specifically because a tool developers resist using delivers no value regardless of governance strength); the lowest-cost option (rejected — weakest developer experience and integration, the two most adoption-predictive criteria).
- **Tradeoffs:** Accepted somewhat greater governance complexity in exchange for stronger developer experience and integration — tracked explicitly in the risk register with a named mitigation and owner, not left implicit.
- **Risks managed:** A governance remediation plan is a required gate before full enterprise rollout, not an afterthought; each rollout phase gates on results from the previous one so problems surface at pilot scale, not enterprise scale.
- **Metrics:** The scoring model gets re-run with real usage and security data at the measurement phase, to confirm — or revisit — the original decision.
- **Lessons / next steps:** A close score between two options is itself useful information — it means the qualitative judgment about *why* they're close matters as much as the number, and that judgment belongs in the decision memo, not buried in a spreadsheet.

## Likely Interviewer Questions & Strong Answers

**"How do you avoid a scoring model just producing whatever answer you already wanted?"**
Define the criteria and weights before evaluating any specific tool, and get the weights from a synthesis of stakeholder input, not from the person running the process. Here, developer experience and security are weighted equally at the top by design — a deliberate signal, not a coincidence of the math.

**"The two top scores were close. How do you know you made the right call?"**
I don't treat "close" as noise — I treat it as a sign the decision needs judgment, not just arithmetic. The memo says explicitly why the second-place option's security and governance edge didn't outweigh the winner's adoption and integration edge, so the reasoning is visible and challengeable, not hidden behind a single number.

**"What if the pilot shows the decision was wrong?"**
That's exactly what the phased rollout and the decision log's revisit trigger are for. The decision was made with named assumptions — if pilot data contradicts one of them, the framework calls for revisiting the decision at that gate, not defending the original call for its own sake.
