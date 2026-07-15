# 🔴 Category-Wise Execution Prompt Library

**Project:** Corporate Strategy & Business Intelligence Copilot  
**Version:** 1.1  
**Purpose:** Provide a complete, sequenced set of copy-and-paste prompts for project setup, business analysis, execution practice, quality review, colleague demonstrations, and interactive business Artifact creation.

> Every prompt in this file is complete and contains no text that must be replaced before use. Copy one prompt at a time into a Claude Project chat. Prompts that depend on company-specific evidence instruct Claude what to do when such evidence is not yet available.

---

## How to Use This Library

1. Run Prompts 1–5 once after setting up the Claude Project.
2. Select the relevant analytical category for a real assignment.
3. Run Prompts 41–45 for guided practice using the four fictional cases.
4. Run Prompts 46–50 before using an important output in a meeting or decision.
5. Run Prompts 51–55 in order for a concise colleague demonstration.
6. Run Prompts 56–60 for continued coaching, comparison, and skill development.
7. Run Prompts 61–65 to create interactive, visual business Artifacts in Claude.

The uploaded Project Instructions remain the controlling operating rules. The prompts below activate specific workflows; they do not replace those rules.

---

# ☑️ Categories (5 sample prompts for each category):
* 🔶 Category 1 — Project Setup and Business Context
* 🔶 Category 2 — Corporate Strategy Analysis
* 🔶 Category 3 — Business Intelligence and KPI Analysis
* 🔶 Category 4 — Market and Competitive Intelligence
* 🔶 Category 5 — Financial and Commercial Analysis
* 🔶 Category 6 — Decision Support, Risk, and Scenario Planning
* 🔶 Category 7 — Executive Communication and Management Reporting
* 🔶 Category 8 — Execution Planning and Performance Monitoring
* 🔶 Category 9 — Guided Practice Cases and Coaching
* 🔶 Category 10 — Quality Assurance and Decision Readiness
* 🔶 Category 11 — Five-Step Colleague Demonstration Sequence
* 🔶 Category 12 — Continued Coaching and Skill Development
* 🔶 Category 13 — Interactive Business Artifact Creation

---

# 🔴 Category 1 — Project Setup and Business Context

## 🔰 Prompt 1 — Confirm the project role and operating method

```text
Summarise your role as the Corporate Strategy & Business Intelligence Copilot. Explain the business problems you can address, the analysis workflow you follow, the management outputs you can create, how you distinguish facts from assumptions and inferences, and how you handle missing or conflicting evidence. Keep the response concise enough to use as a project-orientation note for a new user.
```

## 🔰 Prompt 2 — Audit the project knowledge base

```text
Review all files currently available in this project knowledge base. Create a concise knowledge-base audit showing each file, its purpose, the tasks it supports, and any overlap or inconsistency you detect. Confirm which document controls project behaviour, which documents provide methods and templates, and which document provides fictional practice cases. Do not invent missing files. End with the recommended order in which a new user should read or use the files.
```

## 🔰 Prompt 3 — Build the available business-context profile

```text
Review all company-specific information currently available in the project knowledge and this chat. Build a concise business-context profile covering the organisation, industry, customers, products or services, business model, revenue sources, geographic scope, competitors, strategic priorities, current challenges, key performance indicators, and reporting period. Separate verified information from assumptions and information gaps. If no company-specific material is available, state that clearly and provide a precise evidence-request list without inventing a company profile.
```

## 🔰 Prompt 4 — Create a source and evidence register

```text
Create a source and evidence register from all company-specific documents and data currently available in the project and this chat. For each source, record its title, period covered, subject, apparent status, main facts supported, limitations, conflicts with other sources, and suitability for decision-making. Give each source a confidence rating of high, medium, or low and explain the rating. If only the generic project files are available, state that no company-specific source register can yet be completed and list the first five documents that would be most valuable to add.
```

## 🔰 Prompt 5 — Frame the first management assignment

```text
Using the information currently available in this chat and project knowledge, define the most decision-relevant business assignment that can be completed now. State the management question, intended audience, scope, period, available evidence, constraints, required output, and success criteria. If the available information is insufficient for a real company assignment, frame a demonstration assignment using Case 1 — Retail Growth Without Profit from the project knowledge. Do not solve the assignment yet.
```

---

# 🔴 Category 2 — Corporate Strategy Analysis

## 🔰 Prompt 6 — Conduct a decision-oriented SWOT analysis

```text
Review all available company-specific evidence and conduct a concise SWOT analysis. Include only factors supported by the evidence or clearly labelled as inferences. Rank the items within each quadrant by materiality. Then convert the SWOT into five strategic actions: two actions that use strengths to capture opportunities, one action that corrects a critical weakness, one action that reduces a major threat, and one action that should be stopped or deferred. If no company-specific evidence is available, apply the analysis to Apex Components in Case 3 — Selecting an Export Market.
```

## 🔰 Prompt 7 — Assess the external environment and industry structure

```text
Assess the external environment and industry structure relevant to the company information currently available. Use PESTLE only for macro factors that could materially affect the decision, and use Porter’s Five Forces only for industry economics and competitive pressure. For every factor, explain the evidence, likely business impact, time horizon, and management response. Avoid generic lists. If no real-company evidence is available, perform the assessment for Apex Components and its proposed export expansion in Case 3.
```

## 🔰 Prompt 8 — Develop and compare growth options

```text
Develop three realistic growth options using the company information currently available. Include one lower-risk option, one balanced option, and one higher-growth option. Compare them using strategic fit, customer value, revenue potential, margin impact, investment requirement, implementation difficulty, time to benefit, capability requirements, and downside risk. Explain the evidence behind the assessment, recommend one option, and state the conditions that would make another option preferable. If no company-specific evidence exists, develop the options for CloudFlow in Case 2 — SaaS Growth Masked by Churn.
```

## 🔰 Prompt 9 — Identify strategic priorities and trade-offs

```text
Identify the five most important strategic priorities supported by the available evidence. For each priority, state the business problem, desired outcome, rationale, owner function, first milestone, success KPI, main dependency, and principal trade-off. Rank the priorities using business impact, urgency, feasibility, risk, and strategic alignment. Explicitly identify two activities that management should defer or stop to protect execution capacity. If no company-specific material is available, perform this exercise for UrbanNest in Case 1 — Retail Growth Without Profit.
```

## 🔰 Prompt 10 — Build a concise three-year strategy

```text
Create a concise three-year strategy using the company information currently available. Structure it around the strategic ambition, current position, three strategic objectives, major initiatives, capability requirements, financial or commercial logic, annual milestones, KPIs, principal risks, and review gates. Distinguish what can be decided now from what requires further validation. Keep the strategy practical and avoid unsupported market forecasts. If no real-company information is available, build the strategy for Apex Components after selecting the UAE as the initial export market in Case 3.
```

---

# 🔴 Category 3 — Business Intelligence and KPI Analysis

## 🔰 Prompt 11 — Perform a data-quality review before analysis

```text
Review all numerical tables, reports, and KPI definitions currently available in this chat and project knowledge before drawing conclusions. Check periods, currencies, units, formulas, totals, missing values, duplicates, outliers, inconsistent definitions, segment coverage, and possible double counting. Create a compact issue log with severity, likely impact on conclusions, and required validation. Then state which analyses are safe to perform immediately and which should be treated as provisional. If no company dataset is available, conduct the review on the data in Case 1 — Retail Growth Without Profit.
```

## 🔰 Prompt 12 — Create a management KPI scorecard

```text
Create a management KPI scorecard from the available business data. For each KPI, show the definition, current result, target or budget, prior-period result, absolute variance, percentage or percentage-point variance, trend, status, probable driver, business implication, owner function, and recommended action. Limit the scorecard to the ten KPIs most relevant to the management decision. If no real-company data is available, use the Case 2 — SaaS Growth Masked by Churn dataset and calculate all material recurring-revenue and customer-service metrics.
```

## 🔰 Prompt 13 — Analyse performance variances and trends

```text
Analyse the available performance data against both target and prior period. Quantify the largest favourable and adverse variances, identify whether each movement is driven by volume, price, mix, cost, quality, customer behaviour, capacity, or a one-off item, and explain the business implication. Separate confirmed drivers from hypotheses. End with three corrective actions, two monitoring indicators, and one decision that management should take now. If no real-company data is available, perform the analysis on Case 1 — Retail Growth Without Profit.
```

## 🔰 Prompt 14 — Build a profitability-driver bridge

```text
Build a clear bridge explaining the change in operating profit using the available financial and operational data. Reconcile the movement from the prior period or target through revenue, volume, price, discount, mix, gross margin, returns, marketing, operating expenses, write-downs, and other material factors. Show the calculation logic, avoid double counting, and state where the data does not permit exact attribution. Conclude with the three drivers management can influence most quickly. If no company-specific figures are available, use Case 1 — Retail Growth Without Profit.
```

## 🔰 Prompt 15 — Conduct root-cause and segment analysis

```text
Identify the most important performance problem in the available evidence and analyse it by customer segment, product, channel, geography, cohort, or process stage wherever the data allows. Separate symptoms, confirmed facts, probable drivers, and untested hypotheses. Use a concise root-cause tree and identify the next analysis or experiment needed to validate each major hypothesis. If no company-specific evidence is available, investigate the mid-market churn problem in Case 2 — SaaS Growth Masked by Churn.
```

---

# 🔴 Category 4 — Market and Competitive Intelligence

## 🔰 Prompt 16 — Assess market attractiveness

```text
Assess the attractiveness of the market represented in the available company materials. Cover customer need, addressable demand, growth, profitability, competitive intensity, barriers to entry, regulation, channel structure, required capabilities, concentration risk, and strategic fit. Label every conclusion as verified fact, calculated result, assumption, or inference. Conclude with one of four decisions: enter, pilot, monitor, or do not enter. If no real-company market evidence is available, compare Germany, the UAE, and Vietnam using Case 3 — Selecting an Export Market.
```

## 🔰 Prompt 17 — Create a competitor comparison matrix

```text
Create a competitor comparison matrix using all reliable competitor information currently available. Compare target customers, offering, value proposition, pricing position, route to market, service model, geographic coverage, strengths, weaknesses, capabilities, recent moves, and threat level. Identify two advantages to defend, two vulnerabilities to correct, and one competitor move that should trigger management action. If no company-specific competitor information is available, create an illustrative comparison for Apex Components against a large global supplier, a specialist regional supplier, and a low-cost local supplier, clearly labelling all illustrative assumptions.
```

## 🔰 Prompt 18 — Develop actionable customer segments

```text
Develop an actionable customer-segmentation model from the available evidence. Use needs, economics, behaviour, growth potential, retention, cost to serve, and strategic importance rather than demographics alone. Define no more than five segments. For each segment, state its business value, primary need, current performance, risk, recommended proposition, route to market, service model, and KPI. If no real-company customer data is available, segment CloudFlow’s customers using the small-business, mid-market, and enterprise information in Case 2 and add only evidence-supported subsegments.
```

## 🔰 Prompt 19 — Prepare a market-entry decision

```text
Prepare a market-entry decision using a weighted decision matrix and staged-entry logic. Define the criteria and weights, score each market, explain every score, compare direct entry with distributor-led and hybrid entry modes, recommend one market and entry mode, and identify validation milestones, investment gates, partner safeguards, and exit conditions. Do not allow the matrix score to replace judgement. If no company-specific market-entry decision is available, complete the assessment for Apex Components using Case 3 — Selecting an Export Market.
```

## 🔰 Prompt 20 — Design a competitive-intelligence monitoring plan

```text
Design a practical competitive-intelligence monitoring plan for the business context currently available. Specify the ten signals management should monitor, the source for each signal, review frequency, responsible owner, warning threshold, and management response. Cover pricing, product changes, partnerships, customer wins or losses, hiring, capacity, regulation, channel behaviour, service quality, and financial stress where relevant. If no company-specific context is available, create the monitoring plan for Apex Components during its first 18 months in the UAE.
```

---

# 🔴 Category 5 — Financial and Commercial Analysis

## 🔰 Prompt 21 — Review financial performance

```text
Review all available financial information and prepare a concise performance assessment covering revenue, gross profit, gross margin, operating expenses, operating profit, cash implications, budget variance, prior-period variance, and major one-off items. Quantify the material movements and connect them to operational or commercial drivers. Distinguish revenue growth from profitable growth. If no real-company financial information is available, analyse Case 1 — Retail Growth Without Profit and explain why higher revenue did not create higher profit.
```

## 🔰 Prompt 22 — Analyse unit economics and customer economics

```text
Analyse the unit economics and customer economics supported by the available data. Examine price, discount, variable cost, contribution margin, acquisition cost, activation, retention, repeat purchase, expansion, return rate, service cost, and payback where available. Identify which metrics are confirmed, which cannot yet be calculated, and which data would close the gaps. If no real-company data is available, compare UrbanNest’s online and store economics in Case 1 and CloudFlow’s acquisition-versus-retention economics in Case 2.
```

## 🔰 Prompt 23 — Prepare a full business case

```text
Prepare a management-ready business case for the most material investment decision supported by the available evidence. Include the problem or opportunity, status quo, realistic alternatives, strategic alignment, initial and ongoing costs, quantified benefits, cash-flow logic, ROI, payback, NPV where possible, non-financial benefits, implementation requirements, risks, sensitivities, and recommendation. Use only supported values and label illustrative assumptions. If no company-specific investment decision is available, complete the business case for NorthStar Logistics in Case 4 — Automation, Outsourcing, or Incremental Improvement.
```

## 🔰 Prompt 24 — Perform scenario and sensitivity analysis

```text
Create downside, base, and upside scenarios for the main decision in the available evidence. For each scenario, state the changed assumptions, financial and operational outcome, risk exposure, early-warning indicators, and management response. Then conduct a sensitivity analysis identifying the three variables most likely to change the recommendation and estimate the decision threshold for each. If no real-company decision is available, perform this analysis for the three options in Case 4 — Automation, Outsourcing, or Incremental Improvement.
```

## 🔰 Prompt 25 — Review pricing and revenue opportunities

```text
Review the available evidence for pricing and revenue improvement opportunities. Assess customer value, discounting, price realisation, product and channel mix, willingness to pay, competitor position, cost to serve, contribution margin, cross-sell, upsell, retention, and potential customer harm. Recommend no more than five actions, rank them by impact and execution risk, and define a controlled test and success metric for each. If no company-specific evidence is available, design the recommendations for UrbanNest using the pricing, discount, margin, channel, and return information in Case 1.
```

---

# 🔴 Category 6 — Decision Support, Risk, and Scenario Planning

## 🔰 Prompt 26 — Compare options with a weighted decision matrix

```text
Identify the most important unresolved decision in the available business evidence and compare at least three realistic options using a weighted decision matrix. Define the criteria before scoring, explain the weights, support each score with evidence, test the result under a downside scenario, and state what would change the preferred option. Include the option to maintain the current approach where relevant. If no real-company decision is available, compare the three alternatives in Case 4 — Automation, Outsourcing, or Incremental Improvement.
```

## 🔰 Prompt 27 — Prepare a concise decision memo

```text
Prepare a concise decision memo for the most material decision currently supported by the project evidence. Include the decision required, why it is required now, material facts and calculations, assumptions, options considered, evaluation criteria, recommendation, principal risks, mitigation, approvals required, and immediate next steps. Lead with the recommendation and keep operational detail only when it changes the decision. If no company-specific decision exists, write the memo for Apex Components using Case 3 — Selecting an Export Market.
```

## 🔰 Prompt 28 — Create an executive risk register

```text
Create a compact executive risk register for the strategy or initiative currently under consideration. For each risk, state the event, cause, consequence, likelihood, impact, current controls, mitigation, contingency, early-warning indicator, owner function, and review frequency. Separate current issues from future risks and highlight the three risks requiring executive attention. If no company-specific initiative is available, create the register for NorthStar Logistics if it proceeds with warehouse automation in Case 4.
```

## 🔰 Prompt 29 — Run a pre-mortem and downside stress test

```text
Assume the recommended strategy has failed eighteen months after approval. Conduct a pre-mortem identifying the ten most plausible causes of failure across customers, economics, capabilities, technology, operations, people, partners, regulation, governance, and execution. Rank them by likelihood and impact, identify preventable warning signs, and recommend safeguards. Then explain whether the recommendation should remain unchanged, be staged, or be rejected. If no real-company recommendation is available, stress-test the UAE market-entry recommendation in Case 3.
```

## 🔰 Prompt 30 — Challenge the recommendation and define decision triggers

```text
Act as a constructive review panel consisting of a CEO, CFO, customer leader, operations leader, and risk leader. Challenge the most recent recommendation in this chat. Identify unsupported assumptions, weak calculations, customer consequences, capability constraints, cash exposure, execution risks, and unintended effects. Then provide a strengthened recommendation with explicit decision triggers, stop conditions, review dates, and evidence required before further commitment.
```

---

# 🔴 Category 7 — Executive Communication and Management Reporting

## 🔰 Prompt 31 — Produce a one-page executive brief

```text
Convert the most recent analysis in this chat into a one-page executive brief for the chief executive officer. Lead with the conclusion, decision, and why it matters. Include only the five most material findings, business implications, recommended direction, three immediate actions, principal risks, key assumptions, and decisions required. Remove background and analytical detail that does not change the recommendation. Clearly label any unverified inference.
```

## 🔰 Prompt 32 — Prepare a board-level decision paper

```text
Convert the most recent analysis into a concise board-level decision paper. Emphasise strategic significance, financial exposure, material customer or operational consequences, major risks, governance, alternatives considered, management recommendation, decision requested, and conditions of approval. Include a short appendix containing only the calculations required to understand the recommendation. Avoid routine operational detail unless it affects risk or value.
```

## 🔰 Prompt 33 — Create a quarterly business review

```text
Prepare a quarterly business review from all available performance evidence. Include the quarter at a glance, KPI scorecard, performance versus target and prior period, major drivers, customer and market developments, strategic initiative status, financial outlook, risks, decisions required, and priorities for the next quarter. Lead each section with the management implication rather than repeating data. If no real-company performance data exists, create the review for CloudFlow using Case 2 — SaaS Growth Masked by Churn.
```

## 🔰 Prompt 34 — Develop an executive presentation outline

```text
Create a ten-slide executive presentation outline from the most recent analysis. For each slide, provide a conclusion-led title, the single message the slide must communicate, the evidence or visual required, and the decision or action it supports. Use this sequence: context, performance, diagnosis, strategic implication, options, recommendation, economics, risks, execution plan, and decision required. Do not add decorative slides or repeat the same message.
```

## 🔰 Prompt 35 — Draft a management communication

```text
Draft a concise management email communicating the most recent decision or recommendation to the responsible leadership team. Include the decision, rationale, expected outcome, immediate actions, accountable functions, first deadline, measures of success, main risk, and escalation route. Use professional language, avoid unnecessary detail, and make clear which points are final decisions and which remain subject to validation.
```

---

# 🔴 Category 8 — Execution Planning and Performance Monitoring

## 🔰 Prompt 36 — Build a 30–60–90-day action plan

```text
Turn the most recent recommendation into a 30–60–90-day action plan. Limit the plan to the actions essential for the intended outcome. For each action, specify the accountable function, timing, milestone, leading indicator, outcome KPI, dependency, risk, and escalation trigger. Identify one activity that must stop or be deferred to protect execution capacity. End with the decisions required during the first seven days.
```

## 🔰 Prompt 37 — Create a strategic initiative charter

```text
Create a strategic initiative charter for the highest-priority recommendation in the most recent analysis. Include the business problem, objective, scope, exclusions, sponsor, accountable owner, workstreams, deliverables, milestones, budget logic, KPIs, benefits, dependencies, risks, governance cadence, decision rights, and completion criteria. Keep the charter concise enough to use in a project kickoff meeting.
```

## 🔰 Prompt 38 — Design an execution scorecard

```text
Design an execution scorecard for the most recent strategy or initiative. Include no more than twelve measures divided among financial outcomes, customer outcomes, operational performance, capability development, and risk. For each measure, define the formula, source, frequency, owner, baseline, target, warning threshold, and management response. Distinguish leading indicators from lagging outcomes and avoid vanity metrics.
```

## 🔰 Prompt 39 — Prepare an operating-review agenda and briefing

```text
Prepare a sixty-minute operating-review agenda and pre-read for the most recent initiative. Focus the meeting on decisions and exceptions rather than status narration. Include KPI status, milestone progress, unresolved variances, risks, dependencies, benefits realised, decisions required, owners, and commitments for the next review. Allocate time to each agenda item and identify which information should be circulated before the meeting.
```

## 🔰 Prompt 40 — Review benefits realisation and corrective action

```text
Review the expected and realised benefits of the most recent initiative using all evidence currently available. Compare baseline, target, current result, timing, investment, and risk. Identify benefits that are achieved, delayed, at risk, or unsupported by measurement. Recommend corrective actions, changes to ownership or governance, and any decision to continue, redesign, pause, or stop the initiative. If no live initiative data is available, demonstrate the method for NorthStar Logistics after choosing warehouse automation in Case 4.
```

---

# 🔴 Category 9 — Guided Practice Cases and Coaching

## 🔰 Prompt 41 — Practice Case 1: Retail profitability

```text
Enter Practice Mode and use Case 1 — Retail Growth Without Profit from 04_Practice_Cases_and_Demonstration.md. Present only the business background, management question, data, additional facts, assignment, and constraints. Do not reveal the facilitator reference answer, calculations, or recommendations. Ask me to submit a concise executive brief with quantified drivers, three 90-day actions, KPIs, trigger points, and evidence gaps. After presenting the case, stop and wait for my response.
```

## 🔰 Prompt 42 — Practice Case 2: SaaS churn

```text
Enter Practice Mode and use Case 2 — SaaS Growth Masked by Churn from 04_Practice_Cases_and_Demonstration.md. Present only the case information and assignment. Do not reveal the facilitator reference answer. Ask me to reconcile annual recurring revenue, identify the priority segment, distinguish facts from hypotheses, and recommend a 90-day retention and onboarding response with leading and lagging indicators. After presenting the case, stop and wait for my response.
```

## 🔰 Prompt 43 — Practice Case 3: Export market selection

```text
Enter Practice Mode and use Case 3 — Selecting an Export Market from 04_Practice_Cases_and_Demonstration.md. Present only the case background, market data, entry modes, facts, assignment, and constraints. Do not reveal the facilitator scoring or recommendation. Ask me to prepare a weighted market comparison, recommend a market and entry mode, and define an eighteen-month staged plan with decision gates and exit conditions. After presenting the case, stop and wait for my response.
```

## 🔰 Prompt 44 — Practice Case 4: Investment decision

```text
Enter Practice Mode and use Case 4 — Automation, Outsourcing, or Incremental Improvement from 04_Practice_Cases_and_Demonstration.md. Present only the case background, option data, demand scenarios, additional facts, assignment, and constraints. Do not reveal the facilitator calculations or recommendation. Ask me to calculate ROI, payback, and three-year NPV, compare financial and non-financial trade-offs, recommend one primary approach, and define safeguards and decision triggers. After presenting the case, stop and wait for my response.
```

## 🔰 Prompt 45 — Evaluate and coach my practice response

```text
Evaluate my most recent practice response using six criteria: problem framing, analytical structure, evidence and calculations, commercial judgement, recommendation quality, and executive communication. Score each criterion from one to five and justify every score. Identify what I did well, the three most material gaps, and the single improvement that would have the greatest impact. Give me one targeted revision task and do not show the full model answer until I submit the revision.
```

---

# 🔴 Category 10 — Quality Assurance and Decision Readiness

## 🔰 Prompt 46 — Audit evidence and source integrity

```text
Audit the most recent analysis for evidence integrity. Check every material factual claim, calculation, assumption, inference, and recommendation against the information available in this project and chat. Identify unsupported claims, stale or conflicting sources, hidden assumptions, missing evidence, and statements that overstate certainty. Present the issues in order of decision risk and provide exact corrections. Do not rewrite the full report yet.
```

## 🔰 Prompt 47 — Verify calculations and KPI logic

```text
Independently verify every material calculation in the most recent analysis. Recalculate totals, growth rates, variances, margins, retention measures, ROI, payback, NPV, weighted scores, and percentage-point changes where applicable. Check units, periods, signs, rounding, formula consistency, and double counting. Show any discrepancy, explain its effect on the conclusion, and provide the corrected figure and formula.
```

## 🔰 Prompt 48 — Test recommendation feasibility

```text
Test the feasibility of the most recent recommendation across funding, people, capabilities, systems, timing, customer impact, partner dependence, operational continuity, governance, and risk. Identify the critical path, capacity constraints, hidden dependencies, and points of no return. State whether the recommendation is executable as written, executable with conditions, or not currently executable. Provide the minimum changes required to make it credible.
```

## 🔰 Prompt 49 — Conduct a final decision-readiness review

```text
Review the most recent output as if it will be presented to an executive decision meeting today. Assess whether the business question is answered, evidence is sufficient, calculations are correct, alternatives are fairly compared, risks are visible, the recommendation is clear, ownership is assigned, success measures are defined, and the requested decision is explicit. Produce a decision-readiness score out of one hundred, explain the deductions, and list the final edits required before circulation.
```

## 🔰 Prompt 50 — Produce the final management-ready version

```text
Using the completed analysis and the findings from the evidence, calculation, feasibility, and decision-readiness reviews, produce the final management-ready version. Lead with the conclusion and requested decision. Include only material findings, calculations, implications, recommendation, risks, assumptions, owners, timing, success measures, and immediate next steps. Correct all identified errors and remove repetition, unsupported certainty, excessive detail, and generic language.
```

---

# 🔴 Category 11 — Five-Step Colleague Demonstration Sequence

Run Prompts 51–55 in order in one Claude Project chat.

## 🔰 Prompt 51 — Start the demonstration

```text
This is a colleague demonstration of the Corporate Strategy & Business Intelligence Copilot. Briefly explain your role, the evidence-to-action workflow you will follow, and the outputs you will produce. Then introduce Case 1 — Retail Growth Without Profit in no more than two hundred words. Do not analyse it yet.
```

## 🔰 Prompt 52 — Demonstrate diagnosis and calculations

```text
Now analyse Case 1 — Retail Growth Without Profit. Quantify the change in revenue, gross profit, operating expenses, operating profit, discounting, returns, channel mix, marketing spend, and inventory write-downs. Separate confirmed drivers from hypotheses and identify the three issues that matter most to management. Show only the calculations needed to understand the conclusion.
```

## 🔰 Prompt 53 — Demonstrate option comparison and recommendation

```text
Develop three realistic 90-day response options for UrbanNest: continue aggressive promotion, stop broad promotion and restore economics, or run a controlled channel-and-product reset. Compare the options using revenue protection, margin recovery, customer impact, speed, operational feasibility, learning value, and risk. Recommend one option and state what evidence would cause management to change the decision.
```

## 🔰 Prompt 54 — Demonstrate executive communication

```text
Convert the UrbanNest analysis into a one-page executive brief for the chief executive officer. Include the conclusion, five material findings, business implications, recommended direction, three immediate actions, KPIs, trigger points, risks, assumptions, and evidence required before aggressive promotion resumes. Use concise professional language and do not repeat the full analysis.
```

## 🔰 Prompt 55 — Demonstrate execution planning and critical review

```text
Turn the UrbanNest recommendation into a 30–60–90-day action plan with accountable functions, milestones, leading indicators, outcome KPIs, dependencies, and escalation triggers. Then challenge the plan from the chief financial officer’s perspective, identify the two greatest weaknesses, and revise the plan to address them. End with the exact decisions required from management this week.
```

---

# 🔴 Category 12 — Continued Coaching and Skill Development

## 🔰 Prompt 56 — Generate a fresh advanced practice case

```text
Enter Practice Mode and create a new fictional corporate case at advanced difficulty. The case must combine strategy, business intelligence, financial analysis, risk, and execution. Provide a realistic company background, management decision, internally consistent quantitative data, qualitative evidence, constraints, conflicting stakeholder views, and a clearly defined deliverable. Include enough information for calculations but also include uncertainty that requires assumptions and judgement. Do not reveal the solution, scoring guide, or recommended answer. Stop after presenting the case and wait for my response.
```

## 🔰 Prompt 57 — Coach me using one question at a time

```text
Coach me on my most recent practice response without giving me the solution. Ask one focused question at a time that helps me improve the problem definition, calculations, evidence use, alternative explanations, commercial judgement, risk assessment, and feasibility of the recommendation. After each question, stop and wait for my reply. Continue until the most material weakness has been corrected or I explicitly request the model answer.
```

## 🔰 Prompt 58 — Assign a targeted revision and rescore it

```text
Review the evaluation of my most recent practice response and assign one targeted revision that addresses the highest-impact weakness. State the exact section or reasoning step to revise, the standard the revised work must meet, and the evidence or calculation that should be used. After I submit the revision, rescore only the affected evaluation criteria, explain the change in score, and state whether the response is now management-ready. Do not provide the full model answer before I attempt the revision.
```

## 🔰 Prompt 59 — Provide the model answer and compare it with mine

```text
Provide a concise model answer to the most recent practice case using the project playbook and any facilitator reference answer available in the project knowledge. Then compare the model answer with my final response in a table covering problem framing, calculations, evidence, missed insights, trade-offs, recommendation, risk treatment, execution planning, and executive communication. End with three transferable principles I should apply to the next case and one specific habit I should stop.
```

## 🔰 Prompt 60 — Create a four-week execution-practice plan

```text
Create a four-week practice plan for improving my corporate strategy and business intelligence execution skills using only the resources in this Claude Project. Design three sessions per week, with each session requiring no more than forty-five minutes. Balance strategy, KPI analysis, market assessment, financial reasoning, decision memos, executive briefs, and implementation planning. For every session, specify the prompt to run, expected deliverable, evaluation method, and progression standard. Include a final demonstration assignment that can be presented to colleagues.
```


---


# 🔴 Category 13 — Interactive Business Artifact Creation

## 🔰 Prompt 61 — Create an executive performance dashboard Artifact

```text
Create a functional Claude Artifact titled “Executive Performance Command Center” using all reliable company-specific KPI, financial, customer, and operational data currently available in this project and chat. If no company-specific dataset is available, use Case 1 — Retail Growth Without Profit as a clearly labelled fictional demonstration. Build a responsive single-page dashboard with an executive summary, five to eight KPI cards, actual-versus-target comparisons where targets exist, performance trends, profitability drivers, customer or channel indicators, management priorities, and a risk panel. Add only filters supported by the data, and ensure every filter updates all relevant cards, charts, tables, and insights. Use clear business labels, visible units, status text in addition to colour, concise tooltips, accessible contrast, and professional corporate styling. Do not invent figures, unsupported targets, or unsupported causal explanations. Distinguish confirmed observations from analytical inferences in the insight panel. Create the working Artifact directly rather than returning a dashboard description or presentation outline.
```

## 🔰 Prompt 62 — Create a strategic scenario simulator Artifact

```text
Create a functional Claude Artifact titled “Strategic Scenario Navigator” for the most material investment or strategic decision supported by the evidence currently available in this project and chat. If no real-company decision is available, use Case 4 — Automation, Outsourcing, or Incremental Improvement. Provide controls for selecting an option and adjusting the key assumptions that materially affect the decision, including demand, implementation cost, annual savings or benefit, operating cost, timing, and discount rate where relevant. Recalculate and display ROI, payback period, three-year NPV, annual net benefit, downside exposure, and the preferred option whenever an input changes. Include base, upside, and downside comparisons, a sensitivity view, assumptions and formula notes, decision triggers, a reset control, and a concise recommendation panel that explains why the preferred option changes. Keep all calculations internally consistent and label fictional or illustrative data clearly. Create the interactive Artifact directly and do not substitute a static memo or spreadsheet-style table.
```

## 🔰 Prompt 63 — Create a market-entry and competitor explorer Artifact

```text
Create a functional Claude Artifact titled “Market Entry and Competitive Intelligence Explorer” using all reliable market and competitor evidence currently available in this project and chat. If no company-specific market evidence is available, use Case 3 — Selecting an Export Market and compare Germany, the UAE, and Vietnam. Build an interactive weighted decision matrix with criteria for market demand, growth, profitability, competitive intensity, entry barriers, regulation, capability fit, investment, time to benefit, and risk. Allow users to adjust criterion weights, validate that the total equals one hundred percent, and update market rankings immediately. Include a ranked comparison chart, market profile cards, entry-mode comparison, key competitor positioning, principal risks, validation milestones, exit conditions, and a recommendation panel that explains the decisive factors. Clearly separate source facts, calculations, and illustrative assumptions. Use accessible visuals and create the working Artifact directly rather than producing a written market-entry report.
```

## 🔰 Prompt 64 — Create a profitability-driver and pricing simulator Artifact

```text
Create a functional Claude Artifact titled “Profitability Driver and Pricing Lab” using the financial and commercial evidence currently available in this project and chat. If no company-specific data is available, use Case 1 — Retail Growth Without Profit. Show the baseline revenue, gross profit, gross margin, operating expenses, operating profit, discount rate, return rate, marketing spend, channel mix, and inventory write-downs supported by the case or source data. Add interactive controls for price realisation, sales volume, discounting, product or channel mix, return rate, cost of goods sold, marketing spend, and other material operating costs. Recalculate revenue, gross profit, gross margin, operating profit, and profit change as each assumption moves. Include a baseline-versus-scenario view, a profitability-driver bridge, break-even guidance, warning thresholds, a reset control, and a management-action panel. Prevent impossible values, show formulas and units clearly, and do not imply that a simulated outcome is a forecast. Create the working Artifact directly rather than returning only calculations or recommendations.
```

## 🔰 Prompt 65 — Create a strategy execution and risk control-tower Artifact

```text
Create a functional Claude Artifact titled “Strategy Execution and Risk Control Tower” using the most recent strategy, recommendation, initiative charter, action plan, scorecard, and risk information available in this project and chat. If no live company initiative is available, use the recommended UAE market-entry plan for Apex Components from Case 3 as a fictional demonstration. Build an interactive view containing strategic objectives, initiatives, accountable functions, milestones, progress, leading indicators, outcome KPIs, dependencies, benefits, risks, decision gates, and immediate actions. Add filters for owner, status, priority, and time horizon; ensure all summary metrics and views update with the filters. Include an initiative portfolio, milestone timeline, KPI status table, risk heat map with text labels, overdue-action alerts, decisions-required panel, and concise executive commentary. Use local interactive state for demonstration, preserve data consistency, avoid decorative controls, and clearly label fictional information. Create the working Artifact directly rather than producing a static project plan or report.
```

---

# Recommended Everyday Starting Prompts

For most real assignments, begin with one of these:

- Prompt 3 for business context.
- Prompt 13 for performance analysis.
- Prompt 19 for market entry.
- Prompt 23 for an investment business case.
- Prompt 27 for a decision memo.
- Prompt 31 for an executive brief.
- Prompt 36 for an action plan.
- Prompt 41 for guided practice.
- Prompt 49 before an executive meeting.
- Prompt 61 for an executive performance dashboard Artifact.

---

# Responsible Use

These prompts support analysis and learning; they do not replace accountable management judgement or qualified legal, tax, accounting, audit, regulatory, or investment advice. Verify critical source data, calculations, and decisions before external or high-stakes use.
