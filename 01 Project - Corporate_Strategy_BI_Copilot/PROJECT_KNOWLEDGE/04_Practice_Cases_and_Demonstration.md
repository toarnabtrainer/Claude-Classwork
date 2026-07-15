# Practice Cases and Demonstration

**Project:** Corporate Strategy & Business Intelligence Copilot  
**Version:** 1.0  
**Purpose:** Provide four fictional business cases for analysis practice, assessment, and colleague demonstrations.

> All companies and figures in this file are fictional. Amounts are illustrative and should not be treated as market benchmarks.

---

## 1. How to Run a Case

Use this opening prompt:

```text
Enter Practice Mode and use Case [number] from the project knowledge.
Present only the case background, data, assignment, and constraints.
Do not reveal the facilitator reference answer until I submit my response.
```

After responding, use:

```text
Evaluate my response using the project's six criteria. Score each from 1 to 5,
explain strengths and gaps, and give me one targeted revision task before showing the model answer.
```

## 2. Common Evaluation Criteria

| Criterion | What good performance demonstrates |
|---|---|
| Problem framing | Defines the decision, scope, time horizon, and success measure |
| Analytical structure | Breaks the problem into distinct, logical components |
| Evidence and calculations | Uses the data accurately and labels assumptions or hypotheses |
| Commercial judgement | Connects findings to customers, economics, capabilities, timing, and risk |
| Recommendation quality | Gives a clear, prioritised, feasible, and measurable course of action |
| Executive communication | Leads with the conclusion and communicates concisely for management |

Maximum score: **30**.

---

# Case 1 — Retail Growth Without Profit

## 3. Business Background

**UrbanNest** is a fictional omnichannel retailer selling home furnishings, appliances, and home-electronics accessories. Management invested in aggressive online promotions during Q2 to accelerate growth. Revenue increased from Q1, but profitability deteriorated sharply.

The CEO wants to know whether Q2 represents a temporary investment in growth or a breakdown in unit economics.

## 4. Management Question

What caused the decline in operating profit, and what should management do during the next 90 days?

## 5. Performance Data

Amounts are in **USD millions**, except operational metrics.

| Metric | Q1 actual | Q2 target | Q2 actual |
|---|---:|---:|---:|
| Revenue | 12.00 | 13.20 | 12.60 |
| Transactions (000) | 300 | 320 | 315 |
| Average order value | $40.00 | $41.25 | $40.00 |
| Gross margin | 42.0% | 41.0% | 36.0% |
| Gross profit | 5.040 | 5.412 | 4.536 |
| Operating expenses | 4.200 | 4.350 | 4.700 |
| Operating profit | 0.840 | 1.062 | -0.164 |
| Average customer discount | 8.0% | 9.0% | 15.0% |
| Product return rate | 6.0% | 6.5% | 10.0% |
| Marketing spend | 0.800 | 0.850 | 1.200 |
| Online share of revenue | 35% | 40% | 48% |
| Inventory write-down | 0.100 | 0.100 | 0.400 |

## 6. Additional Facts

- Stores generated a 40% gross margin in Q2; the online channel generated 32%.
- Seventy percent of the increase in returns came from a newly promoted home-electronics range.
- Paid-social customer-acquisition cost increased 45% from Q1, while paid-social conversion declined 20%.
- The inventory write-down relates mainly to promotional products ordered before the campaign.
- Operating expenses include marketing spend and inventory write-downs.
- No evidence has yet been provided on customer lifetime value for the newly acquired Q2 customers.

## 7. Assignment

Prepare a concise executive brief that:

1. quantifies the principal causes of the operating-profit decline;
2. distinguishes confirmed findings from hypotheses;
3. recommends the three most important 90-day actions;
4. identifies KPIs and trigger points; and
5. states what further evidence management needs before resuming aggressive promotion.

## 8. Constraints

- The CEO does not want to stop all online growth.
- Existing customer orders must not be disrupted.
- Management can change discounts, assortment, marketing allocation, and return controls immediately.
- The brief should be no longer than 700 words.

## 9. Suggested Practice Prompt

```text
Analyse Case 1 using KPI variance, profitability-driver, and root-cause analysis.
Show the material calculations, then prepare an executive brief with three prioritised actions.
Label any cause not proven by the data as a hypothesis.
```

<details>
<summary><strong>Facilitator reference answer — open only after completing the case</strong></summary>

### Core conclusion

Q2 was not simply a planned short-term investment in growth. Revenue increased **5.0%** from Q1 but remained **4.5% below target**, while operating profit declined by approximately **$1.004 million** from a $0.840 million profit to a $0.164 million loss. The deterioration was primarily caused by weaker unit economics and increased operating expenditure.

### Material calculations

- Revenue change from Q1: `(12.60 − 12.00) / 12.00 = 5.0%`.
- Revenue variance to target: `(12.60 − 13.20) / 13.20 = -4.5%`.
- Gross margin declined **6.0 percentage points** from Q1 and **5.0 points** below target.
- Gross profit declined by **$0.504 million** from Q1 despite higher revenue.
- Operating expenses increased by **$0.500 million** from Q1.
- Operating-profit change: `-0.164 − 0.840 = -$1.004 million`.
- Compared with target, operating profit was approximately **$1.226 million lower**.

### Confirmed drivers

1. **Discount and channel mix pressure:** average discounts rose to 15%, and online revenue—at a 32% margin—grew to 48% of the mix.
2. **Returns and assortment quality:** returns rose four points, concentrated in the promoted electronics range.
3. **Higher operating expenditure:** marketing increased by $0.400 million and inventory write-downs increased by $0.300 million versus Q1. These explain much of the cost increase, although the expense categories should be reconciled to avoid double counting.

### Hypotheses requiring validation

- Newly acquired paid-social customers may have weak lifetime value.
- Product-description, quality, fulfilment damage, or customer mismatch may be contributing to electronics returns.
- Online promotions may be cannibalising higher-margin store demand.

### Recommended 90-day actions

1. **Restore promotional discipline:** introduce SKU- and channel-level contribution-margin floors, discount approval thresholds, and weekly promotion profitability reviews.
2. **Correct the electronics return problem:** pause the weakest SKUs from paid promotion, analyse return reasons, work with suppliers, and improve product information and fulfilment controls.
3. **Reallocate marketing by contribution:** reduce spend on high-CAC/low-conversion audiences and fund channels and cohorts that meet payback and repeat-purchase thresholds.

### Suggested KPIs and triggers

- Online gross margin: recover from 32% to at least 36% within 90 days.
- Return rate: reduce from 10% to below 7.5%; escalate if any priority SKU remains above 12%.
- Paid-social CAC and first-order contribution margin.
- 30- and 60-day repeat purchase and predicted payback by acquisition cohort.
- Inventory write-down and aged stock.

### Evidence needed

Cohort-level customer value, SKU-level contribution, detailed return reasons, store-to-online cannibalisation, promotion incrementality, and a reconciliation of operating-expense drivers.

</details>

---

# Case 2 — SaaS Growth Masked by Churn

## 10. Business Background

**CloudFlow** is a fictional B2B workflow-software company. Q2 new sales exceeded target, but recurring-revenue growth was much weaker than expected. The sales team considers the quarter successful; the customer-success team warns that onboarding and support capacity have deteriorated.

## 11. Management Question

Is CloudFlow’s growth engine healthy, and what should management prioritise before the next sales push?

## 12. Recurring-Revenue Data

Amounts are in **USD millions of annual recurring revenue (ARR)**.

| Metric | Q1 actual | Q2 target | Q2 actual |
|---|---:|---:|---:|
| Starting ARR | 8.50 | 9.60 | 9.60 |
| New ARR | 1.10 | 1.20 | 1.40 |
| Expansion ARR | 0.50 | 0.70 | 0.60 |
| Contraction ARR | 0.10 | 0.10 | 0.20 |
| Churned ARR | 0.40 | 0.50 | 1.50 |
| Ending ARR | 9.60 | 10.90 | 9.90 |
| Net revenue retention | 100.0% | 101.0% | 88.5% |

`Ending ARR = Starting ARR + New ARR + Expansion − Contraction − Churn`

## 13. Customer and Service Metrics

| Metric | Q1 actual | Q2 target | Q2 actual |
|---|---:|---:|---:|
| Logo retention | 94% | 95% | 87% |
| Median time to first value | 12 days | 10 days | 21 days |
| Support first-response time | 3 hours | 2 hours | 9 hours |
| Weekly active licensed seats | 72% | 75% | 55% |
| Net Promoter Score | 42 | 45 | 24 |

## 14. Churn by Segment in Q2

| Segment | Starting ARR | Churned ARR | ARR churn rate | Share of churned ARR |
|---|---:|---:|---:|---:|
| Small business | 2.00 | 0.18 | 9.0% | 12% |
| Mid-market | 4.00 | 1.12 | 28.0% | 75% |
| Enterprise | 3.60 | 0.20 | 5.6% | 13% |
| **Total** | **9.60** | **1.50** | **15.6%** | **100%** |

## 15. Additional Facts

- Sixty-eight percent of churned mid-market accounts had onboarding periods longer than 20 days.
- A major product release increased implementation complexity during Q2.
- The support backlog peaked at three times normal volume.
- Sales incentives reward new bookings but contain no retention or implementation-quality component.
- Some mid-market customers purchased more licences than they activated.
- No controlled analysis has established that slow onboarding alone caused churn.

## 16. Assignment

Prepare a management recommendation that:

1. reconciles the ARR movement;
2. identifies where churn is concentrated;
3. distinguishes symptoms, probable drivers, and confirmed facts;
4. proposes a 90-day retention and onboarding response; and
5. recommends changes to growth governance and KPIs.

## 17. Constraints

- The company cannot pause all new sales.
- The product-release roadmap cannot be reversed.
- Additional temporary implementation capacity can be funded.
- Management expects a decision on sales incentives before the next quarter.

## 18. Suggested Practice Prompt

```text
Analyse Case 2 as a recurring-revenue and customer-retention problem.
Reconcile ARR, calculate the material variances, identify the priority segment,
and recommend a 90-day response with leading and lagging indicators.
```

<details>
<summary><strong>Facilitator reference answer — open only after completing the case</strong></summary>

### Core conclusion

New ARR exceeded target by $0.20 million, but churned ARR was three times target and erased the acquisition gain. Ending ARR was **$1.00 million below target**, and Q2 net revenue retention fell to **88.5%**. The growth engine is unhealthy because acquisition is compensating for severe mid-market retention failure.

### Reconciliation

`9.60 + 1.40 + 0.60 − 0.20 − 1.50 = 9.90` ending ARR.

Target ending ARR was $10.90 million, so the shortfall was $1.00 million. The largest gap versus target was churn: **$1.00 million worse than target**. Expansion was $0.10 million below target and contraction was $0.10 million worse.

### Concentration

Mid-market customers generated **75% of churned ARR** and experienced a 28% ARR churn rate. This segment should receive immediate attention rather than applying equal action to all customers.

### Confirmed facts

- Onboarding, support, product usage, NPS, logo retention, and NRR all deteriorated.
- Churn is concentrated in mid-market accounts.
- Most churned mid-market accounts had onboarding longer than 20 days.

### Hypotheses

- Slow onboarding and low activation contributed to churn.
- Overselling licence quantities reduced perceived value.
- The product release created implementation complexity beyond current capacity.

These are plausible but require account-level validation and structured churn interviews.

### 90-day response

1. **Retention recovery team:** assign executive owners to at-risk mid-market accounts; complete recovery plans for high-value customers within 14 days.
2. **Onboarding stabilisation:** add temporary implementation capacity, standardise implementation paths, and gate complex configurations. Target median time to value below 14 days.
3. **Value and incentive governance:** track activated seats and 90-day retention by salesperson and cohort; introduce a quality component to incentives while avoiding retroactive penalties.

### KPIs

Leading: onboarding backlog, time to first value, implementation milestone completion, activated-seat ratio, support response time, product adoption, high-risk account count.

Lagging: gross and net revenue retention, logo retention, expansion ARR, churned ARR, NPS, and customer lifetime value.

### Decision triggers

- Escalate if any strategic account misses two implementation milestones.
- Restrict complex mid-market sales if onboarding capacity exceeds a defined utilisation threshold.
- Reassess incentive design after one quarter of cohort data.

</details>

---

# Case 3 — Selecting an Export Market

## 19. Business Background

**Apex Components** is a fictional manufacturer of industrial sensor modules. It has strong engineering capability and established sales in India and selected Southeast Asian markets. Management can fund entry into only one new export market during the next 18 months.

The three shortlisted markets are **Germany, the United Arab Emirates (UAE), and Vietnam**.

## 20. Management Question

Which market and entry mode should Apex select, and how should it control the initial risk?

## 21. Market Data

| Factor | Germany | UAE | Vietnam |
|---|---:|---:|---:|
| Estimated addressable market in 2026 | $420m | $160m | $230m |
| Expected five-year annual market growth | 4% | 8% | 11% |
| Expected gross margin for Apex | 32% | 38% | 35% |
| Realistic three-year Apex revenue | $12m | $9m | $11m |
| Initial entry investment | $4.5m | $1.8m | $3.2m |
| Expected time to first revenue | 14 months | 6 months | 10 months |
| Top-five-customer share of market | 28% | 52% | 38% |
| Regulatory complexity (1 low–5 high) | 4 | 2 | 3 |
| Competitive intensity (1 low–5 high) | 5 | 3 | 4 |
| Local channel availability (1 weak–5 strong) | 3 | 5 | 3 |
| Strategic fit with current offer (1–5) | 4 | 4 | 3 |
| Current execution capability (1–5) | 3 | 4 | 2 |
| Political/currency risk (1 low–5 high) | 2 | 2 | 4 |

## 22. Entry Modes Under Consideration

| Mode | Investment | Control | Speed | Main consideration |
|---|---|---|---|---|
| Direct local subsidiary | High | High | Slow | Builds capability but creates fixed cost and compliance burden |
| Exclusive distributor | Low | Low–medium | Fast | Rapid access but creates partner concentration and weaker customer insight |
| Non-exclusive distributor plus direct key accounts | Medium | Medium–high | Medium | Balances access and learning but requires channel governance |

## 23. Additional Facts

- Apex has one experienced distributor relationship in the UAE, but no signed agreement.
- German customers require extensive certification and a strong local technical-service presence.
- Vietnam offers attractive growth, but Apex currently lacks local language, service, and regulatory capability.
- Apex’s board places high value on early cash generation and learning before committing more capital.
- Management has proposed the following decision weights: strategic fit 25%, market attractiveness 25%, economics 20%, ease and speed of execution 15%, and risk/resilience 15%.

## 24. Assignment

Prepare a decision memo that:

1. scores and compares the three markets using the stated criteria;
2. explains the evidence and judgement behind the scores;
3. recommends a market and entry mode;
4. defines a staged 18-month market-entry plan; and
5. specifies decision gates and exit conditions.

## 25. Constraints

- Initial investment cannot exceed $5 million.
- Apex must preserve technical quality and brand reputation.
- The recommendation should not rely on market size alone.
- Any distributor arrangement must protect customer data and service standards.

## 26. Suggested Practice Prompt

```text
Analyse Case 3 using a weighted decision matrix and staged market-entry logic.
Explain each score rather than treating the matrix as an automatic decision.
Recommend the market, entry mode, validation milestones, and exit conditions.
```

<details>
<summary><strong>Facilitator reference answer — open only after completing the case</strong></summary>

### Illustrative scoring

Scores below use 1 as weak and 5 as strong. Risk is scored for resilience, so a higher score is better.

| Criterion | Weight | Germany | UAE | Vietnam |
|---|---:|---:|---:|---:|
| Strategic fit | 25% | 4 | 4 | 3 |
| Market attractiveness | 25% | 4 | 3 | 4 |
| Economics | 20% | 3 | 5 | 4 |
| Ease and speed | 15% | 2 | 5 | 2 |
| Risk and resilience | 15% | 4 | 4 | 2 |
| **Weighted score** | **100%** | **3.50** | **4.10** | **3.15** |

The exact scores are judgement-based; a strong answer may use different scores if the evidence is explained consistently.

### Recommendation

Enter the **UAE** through a **non-exclusive distributor plus direct management of key accounts**. The UAE is not the largest or fastest-growing market, but it offers the best combination of margin, speed, capital efficiency, current capability, and manageable risk. This is aligned with the board’s preference for early learning and cash generation.

### Main risks

- customer concentration;
- dependence on a distributor;
- loss of customer insight;
- service-quality inconsistency; and
- a smaller long-term market ceiling than Germany.

### Staged plan

**Months 0–3:** validate ten priority accounts, complete partner due diligence, define certification needs, negotiate non-exclusivity, data ownership, service levels, and termination rights.

**Months 4–9:** launch a limited product set, train the partner, assign an Apex technical lead, and pursue two direct strategic accounts.

**Months 10–18:** expand only if unit economics, customer satisfaction, repeat orders, and partner pipeline meet gates.

### Suggested gates

- signed pipeline of at least $2.0 million before full launch;
- gross margin at or above 35%;
- no unresolved critical service incident beyond agreed SLA;
- at least three repeat-order customers by month 12;
- customer data accessible to Apex; and
- partner-generated pipeline not concentrated in one account.

### Exit or redesign conditions

Exit or change the partner if margins remain below 30%, service failures threaten the brand, customer-data access is denied, or qualified pipeline remains below the launch threshold after two review cycles.

Germany may become the next market after Apex builds local-service capability. Vietnam should be monitored and revisited with a capable partner or acquired local capability.

</details>

---

# Case 4 — Automation, Outsourcing, or Incremental Improvement

## 27. Business Background

**NorthStar Logistics** is a fictional e-commerce fulfilment company operating a warehouse at 92% utilisation. Order errors and peak-period delays are rising. Management is considering three approaches for the next three years.

All monetary figures are in **USD millions**. Annual net benefits begin at the end of Year 1. Use a **10% discount rate**.

## 28. Options

| Factor | Option A: Automate | Option B: Outsource overflow | Option C: Improve current process |
|---|---:|---:|---:|
| Initial investment | 2.40 | 0.30 | 0.10 |
| Annual labour/operating savings | 1.00 | 0.55 | 0.20 |
| Annual incremental contribution from added capacity | 0.35 | 0.20 | 0.05 |
| Annual maintenance/vendor/ongoing cost | 0.20 | 0.25 | 0.10 |
| **Annual net benefit** | **1.15** | **0.50** | **0.15** |
| Implementation time | 12 months | 3 months | 2 months |
| Capacity increase | 35% | 20% | 8% |
| Operational control | High | Low | High |
| Execution risk | Medium | Medium–high | Low |

## 29. Demand Scenarios

| Scenario | Probability | Annual order-volume growth | Implication |
|---|---:|---:|---|
| Downside | 20% | -3% | Existing capacity pressure reduces |
| Base | 55% | 8% | Overflow becomes material within 12 months |
| Upside | 25% | 18% | Option B reaches its practical capacity limit during Year 3 |

## 30. Additional Facts

- Current order-error rate is 3.2%; the target is below 1.5%.
- A major customer has warned that another peak-season service failure could trigger contract review.
- Option A is expected to reduce errors to 1.0% after stabilisation.
- Option B’s vendor currently reports a 1.8% error rate; NorthStar would have limited process control.
- Option C is expected to reduce errors to approximately 2.4%, which remains above target.
- Under Option B, vendor fees may rise by 20% after 18 months unless a fixed-price clause is negotiated.
- Option A has a six-month exit cost if implementation fails; Option B can be terminated on six months’ notice.
- Management values speed, financial return, service reliability, and strategic control.

## 31. Assignment

Prepare a business case and decision memo that:

1. calculates simple ROI, payback period, and three-year NPV for each option;
2. compares financial and non-financial trade-offs;
3. considers the three demand scenarios;
4. recommends one primary approach for the next three years; and
5. defines safeguards and decision triggers.

## 32. Constraints

- Available investment capital is $2.5 million.
- Service reliability cannot be allowed to deteriorate during implementation.
- Management prefers a reversible commitment when financial returns are similar.
- Calculations may ignore tax and residual value for this exercise.

## 33. Suggested Practice Prompt

```text
Analyse Case 4 as an investment and operating-model decision.
Calculate payback, simple three-year ROI, and NPV at 10%.
Then compare speed, capacity, control, service reliability, reversibility, and scenario exposure.
Recommend one primary option and define safeguards.
```

<details>
<summary><strong>Facilitator reference answer — open only after completing the case</strong></summary>

### Financial calculations

The three-year annuity factor at 10% is approximately **2.4869**.

| Option | Payback | Simple three-year ROI | Three-year NPV |
|---|---:|---:|---:|
| A: Automate | `2.40 / 1.15 = 2.09 years` | `(3 × 1.15 − 2.40) / 2.40 = 43.8%` | `-2.40 + 1.15 × 2.4869 = $0.460m` |
| B: Outsource | `0.30 / 0.50 = 0.60 years` | `(3 × 0.50 − 0.30) / 0.30 = 400.0%` | `-0.30 + 0.50 × 2.4869 = $0.943m` |
| C: Improve | `0.10 / 0.15 = 0.67 years` | `(3 × 0.15 − 0.10) / 0.10 = 350.0%` | `-0.10 + 0.15 × 2.4869 = $0.273m` |

Simple ROI makes low-investment options appear exceptionally high, so the decision must also consider absolute NPV, capacity, service, and strategic value.

### Trade-offs

- **Option A** provides the strongest capacity and error performance, but is slow, less reversible, and consumes nearly all available capital.
- **Option B** has the highest three-year NPV and fastest meaningful capacity relief, but creates vendor, price, and service-control risk. It may be insufficient in the upside scenario.
- **Option C** is fast and low risk but does not meet the service target or provide enough capacity in the base scenario.

### Illustrative recommendation

Select **Option B as the primary three-year approach**, subject to strong contractual safeguards, while using Option C’s no-regret process improvements internally. This combination provides rapid capacity relief, the best three-year NPV, and reversibility. Treat Option A as a gated future investment rather than committing immediately.

A well-supported recommendation for Option A can also be valid if the learner places greater weight on service control and the upside scenario. The answer must explain why the extra capital and implementation risk are justified.

### Safeguards for Option B

- fixed or capped pricing for three years;
- service-level agreement below 1.5% errors with credits and termination rights;
- data access and audit rights;
- peak-capacity reservation;
- business-continuity plan;
- six-month exit assistance; and
- an internal owner for vendor performance.

### Decision triggers for automation

Begin an automation feasibility gate if:

- sustained demand growth exceeds 12%;
- outsourced volume approaches 80% of contracted capacity;
- vendor error performance exceeds 1.5% for two months;
- fee escalation erodes Option B’s NPV advantage; or
- a strategic customer requires tighter process control.

### Immediate actions

Run Option C’s process improvements during vendor mobilisation, protect peak-season service, and reassess Option A after six to nine months of verified demand and vendor data.

</details>

---

# Demonstration Guide

## 34. Recommended 12-Minute Demonstration

Use **Case 1** for a performance-focused audience or **Case 3** for a strategy-focused audience.

### Minute 1 — Establish the copilot’s role

```text
Explain your role, your evidence rules, and the types of management outputs you can produce.
```

### Minutes 2–5 — Diagnose

```text
Analyse Case [1 or 3]. Lead with the conclusion, show the material evidence,
and identify any assumptions or information gaps.
```

### Minutes 6–7 — Support a decision

```text
Compare the available options and make one clear recommendation.
Explain what would cause you to change it.
```

### Minutes 8–9 — Adapt for an executive

```text
Convert the answer into a one-page executive brief.
Remove detail that does not affect the decision.
```

### Minutes 10–11 — Plan execution

```text
Create a 90-day action plan with owners, milestones, KPIs, risks, and escalation triggers.
```

### Minute 12 — Demonstrate critical review

```text
Challenge the recommendation from the CFO and operations perspectives.
Identify the weakest assumption and the next evidence management should collect.
```

## 35. Optional Interactive Demonstration

Ask a colleague to provide a recommendation before revealing the reference answer:

```text
Do not solve the case yet. Ask my colleague for a two-minute recommendation,
then score it using the project rubric and provide one improvement question.
```

## 36. Facilitator Notes

- Use the reference answers as examples, not as the only acceptable solutions.
- Reward transparent assumptions and sensible trade-offs.
- Penalise fabricated evidence, unprioritised lists, and unexplained scores.
- Encourage users to connect actions to measures and owners.
- Keep the demonstration on one case so the workflow remains easy to understand.
- Do not use confidential company data unless its use is approved.
