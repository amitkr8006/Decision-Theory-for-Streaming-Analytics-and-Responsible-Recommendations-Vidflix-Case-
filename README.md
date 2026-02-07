# Decision Theory for Streaming Analytics and Responsible Recommendations (Vidflix Case)

## Overview
This project applies decision theory and AI/analytics governance to a streaming platform case (Vidflix). It evaluates whether Vidflix should partner with a third-party recommendation vendor (FilMine), designs practical agreement conditions to manage risk, and demonstrates how expanded datasets and association rules can improve analytics, recommendations, and marketing.

## Part 1 — Partner Decision: Vidflix × FilMine
### Decision Challenge
FilMine claims it already knows the “right variables” and will not disclose the algorithm. The project evaluates the benefits of outsourcing versus the risks of low transparency, bias, and regulatory exposure.

### Key Risks (Bias Types)
- Selection bias: training data may not represent all user groups/markets.
- Stability bias: model may not adapt to fast-changing content trends.
- Confirmation bias: over-favouring assumed “safe hits” can reduce discovery.
- Emergent bias: societal preferences shift over time; old patterns can drift.
- Interpretation bias: lack of explainability can mislead business decisions.

### Governance Conditions Proposed
A “middle ground” approach is recommended: FilMine can keep the algorithm confidential, but must prove performance and fairness through:
- Accuracy testing on Vidflix data across markets
- Bias testing and documented remediation
- Explainability for stakeholders
- Clear compliance and data-handling commitments
- Continuous monitoring, regular retraining, and review cadence

A decision-tree framework is included to guide the final go/no-go decision based on compliance, accuracy, bias checks, and update commitments.

## Part 2 — Enhancing Vidflix Analytics with Richer Data
This section designs and critiques a GenAI prompt about using additional data beyond watch history:
- Demographics, behavioural patterns, and external trend signals
Improvements focus on:
- Platform performance: filtering noisy trends, combining trends with user taste, and localising by region
- Marketing optimisation: seasonal targeting with opt-in controls and real-time behaviour awareness

## Part 3 — Association Rule Insight
The project interprets an association rule linking viewership between key titles and converts it into:
- Cross-recommendation and curated collections to increase engagement
- Targeting strategies to surface “missing” relevant titles to the right audiences
- Content acquisition guidance based on shared audience drivers

## Outcome
A complete decision-focused analysis that connects AI governance (bias + transparency + compliance) with practical streaming growth levers (data strategy, recommendations, marketing, and content planning).
