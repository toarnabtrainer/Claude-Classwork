# Templates and Prompt Library

**Project:** Corporate Strategy & Business Intelligence Copilot  
**Version:** 1.0  
**Purpose:** Provide a concise set of management-output templates and reusable prompts for strategy, BI, decision support, execution, and practice.

---

## 1. How to Use This File

1. Select the output template that matches the assignment.
2. Copy a prompt from the relevant section.
3. Replace text in `[square brackets]`.
4. Attach or paste the relevant business information.
5. Specify the audience, time period, and required length.
6. Ask the copilot to label assumptions and information gaps.

A good request normally contains:

```text
Objective + Context + Evidence + Required analysis + Audience + Output + Constraints
```

### Universal prompt blueprint

```text
Act as the Corporate Strategy & Business Intelligence Copilot.

Objective: [State the business question or decision.]
Context: [Provide the relevant background.]
Evidence: [Identify attached files, data, and known facts.]
Scope: [Specify products, markets, functions, segments, and period.]
Required analysis: [Name the analysis or ask the copilot to select the minimum suitable method.]
Audience: [State the intended reader.]
Output: [Select a template and desired length.]
Constraints: [State budget, timing, risk, policy, or confidentiality constraints.]

Separate verified facts, calculations, assumptions, inferences, and recommendations.
Prioritise the most material findings and identify any evidence needed to validate the conclusion.
```

---

# Part I — Output Templates

## 2. Executive Brief

```markdown
# [Decision or Issue]

## Executive Summary
[Two to five sentences: conclusion, material evidence, implication, and recommendation.]

## Key Findings
1. [Finding supported by evidence]
2. [Finding supported by evidence]
3. [Finding supported by evidence]

## Business Implications
- [Effect on growth, margin, cash, customers, operations, or risk]

## Recommendation
[Clear recommended direction and rationale]

## Immediate Actions
| Priority | Action | Owner | Timing | Success measure |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |

## Risks, Assumptions, and Decisions Required
- **Risk:**
- **Assumption:**
- **Decision required:**
```

## 3. Strategic Assessment

```markdown
# Strategic Assessment: [Company, Business Unit, or Issue]

## Objective and Scope
[Question, business area, period, and exclusions]

## Current Position
[Concise performance and strategic context]

## Internal Assessment
### Strengths
- 
### Weaknesses
- 

## External Assessment
### Opportunities
- 
### Threats
- 

## Critical Strategic Issues
1. 
2. 
3. 

## Strategic Options
| Option | Value-creation logic | Required capabilities | Investment/time | Main risk |
|---|---|---|---|---|
| A | | | | |
| B | | | | |
| C | | | | |

## Recommended Direction
[Preferred option, rationale, and conditions for success]

## Execution Priorities
| Initiative | Owner | Milestone | KPI | Target | Risk |
|---|---|---|---|---|---|
| | | | | | |
```

## 4. KPI Performance Report

```markdown
# KPI Performance Report — [Period]

## Performance Summary
[Overall assessment in three to five sentences]

## KPI Scorecard
| KPI | Actual | Target/budget | Prior period | Variance | Trend | Status |
|---|---:|---:|---:|---:|---|---|
| | | | | | | |

## Material Insights
| Finding | Evidence | Probable driver | Business implication | Confidence |
|---|---|---|---|---|
| | | | | High/Medium/Low |

## Corrective Actions
| Priority | Action | Owner | Timing | Leading indicator | Outcome KPI |
|---|---|---|---|---|---|
| | | | | | |

## Data Limitations
- 
```

## 5. Competitor Comparison

```markdown
# Competitor Comparison — [Market or Category]

## Decision Context
[Why the comparison is needed]

## Comparison Matrix
| Dimension | Our company | Competitor A | Competitor B | Competitive implication |
|---|---|---|---|---|
| Target customer | | | | |
| Offering | | | | |
| Value proposition | | | | |
| Pricing position | | | | |
| Route to market | | | | |
| Strengths | | | | |
| Weaknesses | | | | |
| Recent moves | | | | |

## Main Advantages to Defend
1. 
2. 

## Main Vulnerabilities to Address
1. 
2. 

## Recommended Competitive Response
[Defend, differentiate, partner, selectively imitate, or avoid]

## Evidence Gaps
- 
```

## 6. Decision Memo

```markdown
# Decision Memo: [Decision]

**Decision owner:** [Role]  
**Decision date:** [Date]  
**Prepared for:** [Audience]

## Decision Required
[One sentence]

## Why Now
[Trigger, deadline, or consequence of delay]

## Material Facts and Assumptions
- **Fact:**
- **Calculated result:**
- **Assumption:**

## Options Considered
| Criterion | Weight | Option A | Option B | Option C |
|---|---:|---:|---:|---:|
| Strategic alignment | | | | |
| Financial attractiveness | | | | |
| Execution feasibility | | | | |
| Time to benefit | | | | |
| Risk | | | | |
| **Weighted total** | **100%** | | | |

## Recommendation
[Preferred option and rationale]

## Principal Risks and Mitigation
| Risk | Likelihood | Impact | Mitigation | Owner |
|---|---|---|---|---|
| | | | | |

## Approval and Next Steps
- [Decision or approval needed]
- [Immediate action]
```

## 7. Business Case

```markdown
# Business Case: [Initiative]

## Problem or Opportunity
[Baseline and consequence of inaction]

## Strategic Alignment
[Relevant objective or priority]

## Options
[Status quo and realistic alternatives]

## Financial Summary
| Item | Year 0 | Year 1 | Year 2 | Year 3 | Total |
|---|---:|---:|---:|---:|---:|
| Investment/cost | | | | | |
| Gross benefit | | | | | |
| Ongoing cost | | | | | |
| Net cash benefit | | | | | |

- **ROI:**
- **Payback period:**
- **NPV, if applicable:**

## Non-Financial Benefits
- 

## Delivery Requirements
- People:
- Technology:
- Process:
- Governance:

## Sensitivities and Risks
- 

## Recommendation
[Proceed / pilot / defer / reject, with rationale]
```

## 8. 30–60–90-Day Action Plan

```markdown
# 90-Day Action Plan — [Objective]

## Desired Outcome
[Measurable result by day 90]

## Days 1–30: Diagnose and Stabilise
| Action | Owner | Due | Deliverable/KPI | Dependency |
|---|---|---|---|---|
| | | | | |

## Days 31–60: Implement and Test
| Action | Owner | Due | Deliverable/KPI | Dependency |
|---|---|---|---|---|
| | | | | |

## Days 61–90: Scale and Govern
| Action | Owner | Due | Deliverable/KPI | Dependency |
|---|---|---|---|---|
| | | | | |

## Risks and Escalation Triggers
| Risk | Trigger | Mitigation | Escalation owner |
|---|---|---|---|
| | | | |

## Review Cadence
[Weekly, fortnightly, or monthly review and decision forum]
```

## 9. Compact Risk Register

```markdown
| ID | Risk event | Cause | Consequence | Likelihood (1–5) | Impact (1–5) | Score | Mitigation | Contingency | Owner | Indicator |
|---|---|---|---|---:|---:|---:|---|---|---|---|
| R1 | | | | | | | | | | |
```

---

# Part II — Execution Prompt Library

## 10. Strategy Prompts

### Prompt 1 — Strategic position

```text
Analyse [company/business unit] and identify its three most important strategic issues.
Use only the minimum suitable frameworks. For each issue, state the evidence, business implication,
and recommended response. End with the three management decisions that matter most.
Audience: [executive committee].
```

### Prompt 2 — Concise SWOT to actions

```text
Conduct an evidence-based SWOT analysis of [company/initiative].
Limit each quadrant to the four most material items and distinguish internal factors from external factors.
Convert the SWOT into five prioritised actions with owners, timing, and success measures.
```

### Prompt 3 — External-environment scan

```text
Assess the external environment affecting [business/market] over [time horizon].
Use PESTLE, but include only material factors. For each factor, state the direction of change,
likely timing, business exposure, opportunity or risk, and practical response.
```

### Prompt 4 — Industry attractiveness

```text
Evaluate the attractiveness of [industry/market] using Porter’s Five Forces.
Rate each force Low, Medium, or High, explain the evidence, and conclude on likely margin pressure,
barriers, defensible advantages, and whether entry or further investment is justified.
```

### Prompt 5 — Growth options

```text
Develop three genuinely different growth options for [company].
Compare them using strategic alignment, customer value, financial potential, capability requirements,
time to benefit, and risk. Recommend one option and state what evidence could change the decision.
```

### Prompt 6 — Strategy to execution

```text
Convert the attached strategy into an execution roadmap.
For each strategic objective, define initiatives, accountable owners, milestones, KPIs, targets,
dependencies, risks, and the next 90-day action. Flag objectives that are not measurable.
```

## 11. Business Intelligence Prompts

### Prompt 7 — KPI diagnostic

```text
Analyse the supplied KPI table for [period]. Compare actual performance with target and prior period.
Identify the five most material variances, probable drivers, business implications, and corrective actions.
Use percentage points for changes in rates and label unsupported drivers as hypotheses.
```

### Prompt 8 — Dashboard commentary

```text
Convert this dashboard into management commentary. Do not repeat every number.
Explain what changed, why it may have changed, why it matters, and what management should do.
Limit the output to [300] words and prioritise the three most important messages.
```

### Prompt 9 — Root-cause analysis

```text
Investigate why [metric/outcome] moved from [expected result] to [actual result] in [period].
Decompose the metric into measurable drivers, locate the affected segments, test alternative hypotheses,
and distinguish confirmed causes from issues requiring validation. Recommend the next diagnostic steps.
```

### Prompt 10 — Revenue bridge

```text
Explain the change in revenue between [period A] and [period B].
Separate volume, price, mix, acquisition, retention, and timing effects where the data permits.
Show calculation logic, reconcile to the reported total, and identify the two most actionable drivers.
```

### Prompt 11 — Profitability analysis

```text
Analyse the change in profitability using revenue, gross margin, operating expenses, product/customer mix,
and one-off items. Quantify the largest drivers and distinguish revenue growth from profitable growth.
Recommend three actions to improve profit without creating unacceptable customer or operational risk.
```

### Prompt 12 — Data-quality review

```text
Review the supplied dataset or report before analysing it.
Check periods, units, currencies, definitions, missing values, duplicates, outliers, totals, and segment coverage.
Create a short issue log showing severity, likely effect on conclusions, and proposed validation.
Then state which analyses remain safe to perform.
```

## 12. Market and Competitor Prompts

### Prompt 13 — Market assessment

```text
Assess [market] for [company/product]. Cover customer need, segments, size, growth, demand drivers,
competition, economics, barriers, required capabilities, and risks. Separate verified market evidence
from assumptions. Conclude with enter, pilot, monitor, or do not enter.
```

### Prompt 14 — Competitor profile

```text
Create a concise profile of [competitor] using the supplied sources.
Cover target customers, offering, value proposition, pricing position, route to market, strengths,
weaknesses, recent strategic moves, and threat level. Label each major statement as fact or inference.
```

### Prompt 15 — Competitive comparison

```text
Compare [our company] with [competitors] using a consistent matrix.
Identify two advantages to defend, two vulnerabilities to address, and one competitor move to monitor.
Recommend a response based on customer value and economic impact, not feature count alone.
```

### Prompt 16 — Market-entry decision

```text
Evaluate entry into [market/geography]. Compare at least three entry modes, including a low-commitment option.
Assess strategic fit, market attractiveness, unit economics, investment, regulatory or operational complexity,
time to revenue, and risk. Recommend an entry mode and staged validation plan.
```

## 13. Financial and Commercial Prompts

### Prompt 17 — Financial performance review

```text
Review the attached financial summary for [period]. Analyse revenue, gross margin, operating expenses,
operating profit, cash implications, and budget variance. Quantify the largest changes and prepare an
executive summary with three management actions.
```

### Prompt 18 — Business case

```text
Prepare a business case for [initiative]. Include the status quo, alternatives, strategic alignment,
costs, benefits, cash flows, ROI, payback, key non-financial benefits, delivery requirements, and risks.
Use only supplied assumptions; clearly label illustrative values. Recommend proceed, pilot, defer, or reject.
```

### Prompt 19 — Scenario analysis

```text
Create base, upside, and downside scenarios for [plan/investment].
For each scenario, state the assumptions that change, expected financial or operational result,
early warning indicators, and management response. Identify the variable most likely to change the decision.
```

### Prompt 20 — Pricing review

```text
Assess the current pricing approach for [product/service]. Consider customer value, willingness to pay,
competitor position, discounting, cost-to-serve, contribution margin, and segment differences.
Recommend pricing actions and safeguards, including how results should be tested and measured.
```

## 14. Decision and Executive Communication Prompts

### Prompt 21 — Decision memo

```text
Prepare a decision memo for [decision]. Define the decision, why it is required now, material facts,
assumptions, options, evaluation criteria, recommendation, risks, mitigation, and approvals needed.
Keep it suitable for [audience] and no longer than [length].
```

### Prompt 22 — Executive brief

```text
Convert the attached analysis into a one-page executive brief for [audience].
Lead with the conclusion and decision. Include only material evidence, implications, recommendation,
risks, and immediate actions. Remove analytical detail that does not affect the decision.
```

### Prompt 23 — Board-level rewrite

```text
Rewrite this report for a board-level audience. Emphasise strategic significance, financial exposure,
material risk, governance, decisions required, and management accountability. Avoid operational detail
unless it changes the risk or recommendation.
```

### Prompt 24 — Challenge the recommendation

```text
Act as a constructive review panel consisting of a CEO, CFO, customer leader, and operations leader.
Challenge the attached recommendation. Identify unsupported assumptions, financial weaknesses,
customer consequences, delivery constraints, and unintended effects. Then propose improvements.
```

## 15. Execution Prompts

### Prompt 25 — 90-day plan

```text
Turn the recommendation into a 30–60–90-day plan.
Specify actions, accountable owners, due dates, milestones, leading indicators, outcome KPIs,
dependencies, risks, and escalation triggers. Limit the plan to the actions essential for the outcome.
```

### Prompt 26 — Initiative prioritisation

```text
Prioritise the proposed initiatives using business impact, urgency, strategic alignment, effort,
cost, dependency, and risk. Show the criteria and weights, rank the initiatives, and explain why the
top three should begin now. Identify items to defer or stop.
```

### Prompt 27 — Risk register

```text
Create a compact risk register for [strategy/project]. For each risk, state event, cause, consequence,
likelihood, impact, mitigation, contingency, early-warning indicator, owner, and review date.
Separate current issues from future risks and highlight the three requiring executive attention.
```

### Prompt 28 — Operating review

```text
Prepare an operating-review agenda and briefing for [initiative/business unit].
Cover KPI status, progress since the last review, material variances, decisions required, risks,
dependencies, and next-period commitments. Focus the meeting on decisions rather than status narration.
```

---

# Part III — Practice and Evaluation Prompts

## 16. Guided Case Practice

### Prompt 29 — Generate a case

```text
Enter Practice Mode. Create a fictional [beginner/intermediate/advanced] case about [strategy/BI/market/finance].
Provide the business background, management question, relevant data, constraints, and expected deliverable.
Do not reveal the answer until I submit my analysis.
```

### Prompt 30 — Use a packaged case

```text
Enter Practice Mode and use Case [1/2/3/4] from `04_Practice_Cases_and_Demonstration.md`.
Present only the case information and assignment. Ask me for my analysis and do not reveal the reference answer.
```

### Prompt 31 — Evaluate my response

```text
Evaluate my response using six criteria: problem framing, analytical structure, evidence and calculations,
commercial judgement, recommendation quality, and executive communication. Score each from 1 to 5.
Explain what I did well, what I missed, and the single most important improvement. Do not rewrite everything yet.
```

### Prompt 32 — Socratic coaching

```text
Coach me without giving the answer. Ask one question at a time that helps me test my assumptions,
quantify the issue, consider alternatives, and improve my recommendation. Stop after each question for my reply.
```

### Prompt 33 — Revision round

```text
Based on your assessment, give me one targeted revision task.
After I submit the revision, rescore only the affected criteria and explain whether the answer is now management-ready.
```

### Prompt 34 — Model answer and comparison

```text
Now provide a concise model answer to the case. Compare it with my response in a table showing:
shared conclusions, missed insights, stronger evidence, recommendation differences, and communication improvements.
End with three principles I should apply to the next case.
```

## 17. Practice Evaluation Rubric

| Criterion | 1 — Weak | 3 — Competent | 5 — Excellent |
|---|---|---|---|
| Problem framing | Misstates or ignores the decision | Defines the main question and scope | Frames the decision, trade-offs, constraints, and success measure precisely |
| Analytical structure | Unstructured observations | Uses a logical sequence | Uses a concise, mutually distinct structure that connects drivers to outcomes |
| Evidence and calculations | Unsupported claims or errors | Uses most evidence correctly | Reconciles figures, shows material logic, and labels uncertainty accurately |
| Commercial judgement | Limited business relevance | Recognises main implications | Balances growth, economics, customers, capabilities, timing, and risk |
| Recommendation quality | Generic or unprioritised | Clear and broadly feasible | Decisive, evidence-led, prioritised, executable, and resilient to downside |
| Executive communication | Long, unclear, or data-heavy | Understandable and organised | Conclusion-led, concise, decision-focused, and audience-appropriate |

### Overall interpretation

- **6–12:** Reframe and rebuild the analysis.
- **13–18:** Developing; major gaps remain.
- **19–24:** Competent; refine evidence and prioritisation.
- **25–27:** Strong and management-ready with minor edits.
- **28–30:** Excellent; clear, rigorous, and decision-ready.

Scores support learning; they are not a substitute for business accountability or specialist review.

---

# Part IV — Fast Demonstration Prompts

## 18. Five-Prompt Demonstration Sequence

Use one fictional case throughout.

```text
1. Analyse this case and identify the three most important business issues.
```

```text
2. Show the calculation and evidence behind each issue. Label any hypothesis.
```

```text
3. Compare three response options and recommend one.
```

```text
4. Convert the answer into a one-page executive brief for the CEO.
```

```text
5. Turn the recommendation into a 90-day action plan, then challenge it from the CFO's perspective.
```

This sequence demonstrates diagnosis, evidence discipline, decision support, executive communication, execution planning, and critical review without requiring additional files.
