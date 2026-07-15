# Project Guide and Business Context

**Project:** Corporate Strategy & Business Intelligence Copilot  
**Version:** 1.0  
**Purpose:** Provide a compact operating guide, reusable company-context record, and request brief for strategy, BI, and management-reporting work.

---

## 1. What This Project Does

The copilot helps users turn business information into:

- strategic assessments;
- KPI and performance insights;
- competitor and market analysis;
- decision support;
- executive-ready reports;
- implementation plans; and
- guided business-analysis practice.

It is designed for practical corporate work and demonstrations. It is not intended to replace accountable executives, qualified advisers, audited financial models, or approved company systems of record.

## 2. Project Components

| Component | Purpose |
|---|---|
| `PROJECT_INSTRUCTIONS.md` | Defines the copilot’s role, workflow, quality rules, and response behaviour. |
| `01_Project_Guide_and_Business_Context.md` | Explains usage and stores the company and assignment context. |
| `02_Strategy_and_BI_Playbook.md` | Provides the core strategy, BI, financial, market, and decision methods. |
| `03_Templates_and_Prompt_Library.md` | Supplies reusable output templates and execution prompts. |
| `04_Practice_Cases_and_Demonstration.md` | Provides fictional cases, answer keys, and a colleague demonstration flow. |

## 3. Three Ways to Use the Copilot

### Mode A — Analyse

Give the copilot a business question and relevant information.

**Example**

```text
Analyse our quarterly results. Identify the three most material performance issues,
their probable drivers, and the management actions required.
Audience: Executive committee.
Output: One-page executive brief.
```

### Mode B — Produce

Ask the copilot to create a defined management output.

**Example**

```text
Convert the attached analysis into a decision memo comparing the three expansion options.
Use strategic fit, financial attractiveness, execution difficulty, and risk as criteria.
```

### Mode C — Practise

Ask the copilot to act as a mentor or assessor.

**Example**

```text
Enter Practice Mode. Give me an intermediate KPI-performance case.
Do not reveal the answer until I submit my analysis. Then score me using the project rubric.
```

## 4. Quick-Start Setup

1. Create a Claude Project named **Corporate Strategy & Business Intelligence Copilot**.
2. Paste the content of `PROJECT_INSTRUCTIONS.md` into the project-instructions field.
3. Upload the four files in the `PROJECT_KNOWLEDGE` folder to the project knowledge base.
4. Complete the Company Context Profile below when working with a real organisation.
5. Start a new chat and use either the Request Brief or a prompt from `03_Templates_and_Prompt_Library.md`.

For a demonstration, no company data is required. Use one of the fictional cases in `04_Practice_Cases_and_Demonstration.md`.

---

# Part I — Company Context Profile

Complete only the fields relevant to the assignment. Replace the placeholders rather than creating multiple competing versions of the company profile.

## 5. Organisation Overview

| Field | Company information |
|---|---|
| Company name | `[Enter name]` |
| Industry and sub-industry | `[Enter industry]` |
| Headquarters and key markets | `[Enter locations]` |
| Ownership or listing status | `[Private / public / subsidiary / other]` |
| Approximate size | `[Revenue, employees, sites, or customers]` |
| Reporting currency | `[Currency]` |
| Financial year | `[Start and end dates]` |
| Primary planning horizon | `[For example: 12 months / 3 years]` |

## 6. Business Model

| Field | Company information |
|---|---|
| Main products or services | `[List the principal offerings]` |
| Target customers | `[Segments and buyer types]` |
| Customer need addressed | `[Core problem or value proposition]` |
| Revenue model | `[Subscription / transaction / licence / project / other]` |
| Main revenue sources | `[Products, services, regions, channels]` |
| Main cost drivers | `[Labour, materials, acquisition, logistics, technology, etc.]` |
| Key channels | `[Direct sales, distributors, digital, partners, retail, etc.]` |
| Critical capabilities | `[Brand, technology, distribution, expertise, data, scale, etc.]` |

## 7. Strategic Context

| Field | Company information |
|---|---|
| Vision or long-term ambition | `[Enter statement]` |
| Current strategic priorities | `[List three to five]` |
| Most important business challenges | `[List three to five]` |
| Major growth opportunities | `[List known opportunities]` |
| Major threats or constraints | `[List known threats]` |
| Current transformation programmes | `[List relevant initiatives]` |
| Important non-negotiables | `[Legal, financial, brand, ethical, or operational constraints]` |

## 8. Market and Competitive Context

| Field | Company information |
|---|---|
| Market definition | `[What market is being considered?]` |
| Customer segments | `[List segments]` |
| Named competitors | `[List competitors]` |
| Main substitutes | `[List alternatives used by customers]` |
| Perceived competitive strengths | `[Enter strengths]` |
| Perceived competitive weaknesses | `[Enter weaknesses]` |
| Relevant external trends | `[Economic, technological, regulatory, social, etc.]` |

## 9. Performance and KPI Context

Use company-approved definitions whenever possible.

| KPI | Definition or formula | Current target | Frequency | Owner | Source |
|---|---|---:|---|---|---|
| Revenue | `[Definition]` | `[Target]` | `[Monthly]` | `[Owner]` | `[System/report]` |
| Gross margin | `[Definition]` | `[Target]` | `[Monthly]` | `[Owner]` | `[System/report]` |
| Operating profit | `[Definition]` | `[Target]` | `[Monthly]` | `[Owner]` | `[System/report]` |
| Customer retention | `[Definition]` | `[Target]` | `[Monthly/quarterly]` | `[Owner]` | `[System/report]` |
| Additional KPI | `[Definition]` | `[Target]` | `[Frequency]` | `[Owner]` | `[System/report]` |

## 10. Decision and Governance Context

| Field | Company information |
|---|---|
| Primary decision makers | `[Roles or governance body]` |
| Common management audiences | `[Board, executive committee, functional leaders, etc.]` |
| Decision thresholds | `[Investment, risk, or approval limits if relevant]` |
| Preferred report style | `[Brief / detailed / board format / other]` |
| Confidentiality classification | `[Public / internal / confidential / restricted]` |
| Required reviewers | `[Finance, legal, risk, data owner, etc.]` |

## 11. Source Register

Record the most important files so the copilot can distinguish approved sources from working material.

| Source name | Period/version | Owner | Status | Intended use | Notes |
|---|---|---|---|---|---|
| `[Annual plan]` | `[FY2026]` | `[Strategy]` | `[Approved]` | `[Targets and priorities]` | `[Notes]` |
| `[KPI report]` | `[Q2 2026]` | `[Finance]` | `[Approved]` | `[Performance analysis]` | `[Notes]` |
| `[Market study]` | `[Date]` | `[Marketing]` | `[Draft/approved]` | `[Market assumptions]` | `[Notes]` |

When two sources conflict, identify the conflict and ask the owner or decision maker which source governs.

---

# Part II — Request Brief

Use this short brief for assignments where accuracy, scope, or audience matters.

## 12. Standard Request Brief

```text
ASSIGNMENT TITLE:

BUSINESS OBJECTIVE OR DECISION:
What question must be answered or what decision must be supported?

BACKGROUND:
What has happened and why is the assignment needed now?

SCOPE:
Which business units, products, regions, customers, or periods are included?

AVAILABLE INFORMATION:
List the files, tables, assumptions, and known facts.

REQUIRED ANALYSIS:
For example: KPI variance, SWOT, competitor comparison, scenarios, or option evaluation.

TARGET AUDIENCE:
For example: CEO, executive committee, finance team, or project team.

REQUIRED OUTPUT:
For example: executive brief, decision memo, report, table, or 90-day action plan.

CONSTRAINTS:
Budget, deadline, risk tolerance, policy, capacity, confidentiality, or other limits.

DEADLINE OR DECISION DATE:

SUCCESS CRITERIA:
What would make the answer useful and actionable?
```

## 13. Minimal Request Format

For faster work, provide only:

```text
Objective:
Evidence or data:
Audience:
Output:
Constraints:
```

If the user supplies none of these, the copilot should infer the most reasonable format, state material assumptions, and proceed.

---

# Part III — Information Handling

## 14. Recommended File Types

Useful project inputs include:

- approved strategy documents;
- annual plans and budgets;
- KPI reports and dashboard exports;
- financial summaries;
- customer and sales analyses;
- market and competitor research;
- initiative status reports;
- operating policies; and
- examples of preferred management reports.

Avoid uploading duplicate, obsolete, or unexplained files. A smaller set of current, authoritative sources usually produces clearer results.

## 15. Preparing Data for Analysis

Before asking for BI analysis:

- identify the reporting period;
- include units and currency;
- define important KPIs;
- distinguish actual, budget, forecast, and prior-period figures;
- retain segment labels;
- include totals where possible;
- explain known anomalies; and
- remove personal or restricted data that is not necessary for the task.

## 16. Confidentiality and Review

Use only information you are authorised to process. Do not use the copilot as the final authority for:

- audited financial statements;
- legal or regulatory interpretation;
- tax advice;
- investment approval;
- employee decisions involving sensitive personal data; or
- public disclosure.

Material outputs should be reviewed by the accountable business owner and relevant specialist functions.

---

# Part IV — Suggested Demonstration

## 17. Ten-Minute Colleague Demonstration

### Step 1 — Introduce the role

```text
Summarise your role in this project, the assignments you support,
and the rules you follow when evidence is incomplete.
```

### Step 2 — Analyse a case

Use Case 1 or Case 2 from `04_Practice_Cases_and_Demonstration.md`.

```text
Analyse the case using the project playbook. Identify the main performance issue,
its probable drivers, and the three most important management actions.
```

### Step 3 — Change the audience

```text
Convert the analysis into a one-page executive brief for the CEO.
Lead with the decision and do not repeat all of the raw data.
```

### Step 4 — Create an execution plan

```text
Turn the recommendation into a 90-day plan with owners, milestones, KPIs, and risks.
```

### Step 5 — Show Practice Mode

```text
Now act as my mentor. Ask me to defend the recommendation.
Score my answer using the six project criteria and tell me the most important improvement.
```

## 18. Demonstration Tips

- Use one case from start to finish rather than showing many unrelated features.
- Compare the initial analysis with the executive version to demonstrate audience adaptation.
- Ask the copilot to identify assumptions; this demonstrates responsible use.
- End with an action plan or decision memo so the business value is visible.
- Keep live demonstrations fictional unless confidential data is approved for use.

---

# Part V — Maintenance

## 19. Lightweight Governance

Use the following simple maintenance routine:

- review the Company Context Profile when strategy or leadership priorities change;
- remove superseded business files;
- confirm KPI definitions before each major reporting cycle;
- add only prompts or templates that are repeatedly useful;
- retain one approved version of each core document; and
- update the version number and change log below after material edits.

## 20. Change Log

| Version | Date | Change | Owner |
|---|---|---|---|
| 1.0 | July 2026 | Initial concise project package | Project owner |
