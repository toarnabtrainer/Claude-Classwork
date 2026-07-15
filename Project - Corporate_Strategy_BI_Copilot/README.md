# Corporate Strategy & Business Intelligence Copilot

A compact Claude Project for corporate strategy, business intelligence, decision support, executive reporting, and guided execution practice.

The package is deliberately limited to **one project-instructions file and four knowledge-base files** so it remains easy to understand and maintain.

---

<img width="1336" height="924" alt="image" src="https://github.com/user-attachments/assets/837e3f5d-14d7-49b6-8cc4-3d32cd27602d" />

---

## 1. Project Structure

```
Corporate_Strategy_BI_Copilot/
│
├── README.md
├── PROJECT_INSTRUCTIONS.md
│
└── PROJECT_KNOWLEDGE/
    ├── 01_Project_Guide_and_Business_Context.md
    ├── 02_Strategy_and_BI_Playbook.md
    ├── 03_Templates_and_Prompt_Library.md
    ├── 04_Practice_Cases_and_Demonstration.md
    └── 05_Category_Wise_Execution_Prompts.md
```

## 2. What Each File Does

| File | Purpose |
|---|---|
| `PROJECT_INSTRUCTIONS.md` | Defines Claude’s role, analytical workflow, evidence rules, output standards, and Practice Mode. Paste this into the project-instructions field. |
| `01_Project_Guide_and_Business_Context.md` | Explains how to use the project and provides a company-context profile, source register, and request brief. |
| `02_Strategy_and_BI_Playbook.md` | Supplies the core strategy, BI, market, financial, decision, risk, and execution methods. |
| `03_Templates_and_Prompt_Library.md` | Contains management-output templates, the compact core prompt library, practice prompts, and an evaluation rubric. |
| `04_Practice_Cases_and_Demonstration.md` | Contains four fictional cases, facilitator reference answers, and a demonstration script. |
| `05_Category_Wise_Execution_Prompts.md` | Contains 60 complete, placeholder-free prompts arranged in execution order across twelve categories. |

## 3. Setup in Claude

1. Create a new Claude Project.
2. **Title:** **Corporate Strategy & Business Intelligence Copilot**
3. **Description:**

```An AI-powered corporate strategy and business intelligence workspace for analyzing business challenges, KPIs, financial performance, markets, competitors, risks, and strategic options. It produces executive-ready insights, recommendations, decision memos, reports, and action plans while also supporting guided business-case practice and professional skill development.```

4. Open `PROJECT_INSTRUCTIONS.md`, copy its content, and paste it into the project-instructions field.
5. Upload the four Markdown files inside `PROJECT_KNOWLEDGE` to the project knowledge base.
6. Start a new project chat.
7. For real-company work, complete the Company Context Profile in `01_Project_Guide_and_Business_Context.md` or paste the relevant context into the chat.

Do not upload `PROJECT_INSTRUCTIONS.md` as a knowledge file unless you intentionally want a duplicate reference copy. Its primary location is the project-instructions field.

## 4. First Test

Use this prompt after setup:

```text
Summarise your role in this project, the analysis workflow you follow,
the management outputs you can create, and how you handle missing or uncertain evidence.
```

The response should demonstrate that Claude will:

- frame the business question;
- use evidence rather than inventing facts;
- distinguish facts, calculations, assumptions, and inferences;
- translate analysis into implications and actions;
- prioritise recommendations; and
- adapt the output to the audience.

## 5. Start with a Practice Case

Use a fictional case before introducing company information.

```text
Enter Practice Mode and use Case 1 from the project knowledge.
Present only the case information and assignment.
Do not reveal the facilitator reference answer until I submit my response.
```

After submitting your analysis:

```text
Evaluate my response using the six project criteria.
Score each from 1 to 5, explain strengths and gaps,
and give me one targeted revision task.
```

## 6. Start a Real Assignment

Use this compact request format:

```text
Objective: [Business question or decision]
Evidence: [Files, data, and known facts]
Scope: [Products, markets, segments, functions, and period]
Audience: [Intended reader]
Output: [Executive brief, KPI report, decision memo, etc.]
Constraints: [Budget, time, risk, policy, or confidentiality]

Separate verified facts, calculations, assumptions, inferences, and recommendations.
```

### Example

```text
Objective: Determine why Q2 operating profit fell and what management should do next.
Evidence: Attached Q1 and Q2 KPI report and campaign summary.
Scope: Domestic retail business, Q1–Q2.
Audience: CEO and CFO.
Output: One-page executive brief and 90-day action plan.
Constraints: Do not recommend stopping all online acquisition.
```

## 7. Main Capabilities

The project supports:

- strategic-position assessment;
- SWOT, PESTLE, and Five Forces analysis;
- growth-option comparison;
- KPI, variance, and root-cause analysis;
- revenue and profitability diagnostics;
- market and competitor assessment;
- business cases and scenarios;
- decision memos;
- executive briefs;
- risk registers;
- 30–60–90-day plans; and
- guided practice with scoring and feedback.

The project intentionally excludes a large library of specialised frameworks and department-specific files. Add new material only when it is repeatedly useful.

## 8. Recommended Demonstration Flow

Use one case from beginning to end.

1. **Diagnose:** Ask Claude to identify the three most important issues.
2. **Validate:** Ask for calculations, evidence, assumptions, and information gaps.
3. **Decide:** Ask Claude to compare options and recommend one.
4. **Communicate:** Convert the answer into an executive brief.
5. **Execute:** Create a 90-day plan with owners and KPIs.
6. **Challenge:** Ask the CFO and operations perspectives to test the recommendation.

Suggested demonstration prompt sequence:

```text
Analyse Case 1 and identify the three most important business issues.
```

```text
Show the evidence and calculation behind each issue. Label any hypothesis.
```

```text
Recommend three actions and explain why they should be prioritised.
```

```text
Convert the answer into a one-page executive brief for the CEO.
```

```text
Turn the recommendation into a 90-day plan, then challenge it from the CFO's perspective.
```

### For Prompt Library refer following files:
1. PROJECT_KNOWLEDGE/03_Templates_and_Prompt_Library.md
2. PROJECT_KNOWLEDGE/04_Practice_Cases_and_Demonstration.md
3. PROJECT_KNOWLEDGE/05_Category_Wise_Execution_Prompts.md (Main Prompt Library)

## 9. Adding Company Knowledge

Useful additions include:

- approved strategy and annual plan;
- current KPI definitions;
- budget and performance reports;
- product and customer-segment descriptions;
- market and competitor research;
- initiative status reports; and
- an example of the organisation’s preferred executive-report format.

Keep the knowledge base controlled:

- prefer approved and current sources;
- remove obsolete or duplicate versions;
- state the period, owner, and status of important documents;
- use consistent KPI definitions; and
- avoid unnecessary personal, restricted, or confidential data.

## 10. Responsible-Use Notes

The copilot supports analysis and communication; it does not replace accountable human review.

Verify material:

- financial calculations;
- legal, regulatory, tax, and accounting interpretations;
- investment assumptions;
- market estimates;
- confidential or personal information;
- external claims; and
- decisions requiring formal approval.

The fictional cases are for learning and demonstration only. They are not business benchmarks or recommendations for real organisations.

## 11. Lightweight Maintenance

Review the project when business priorities or source documents change.

Recommended routine:

- update the Company Context Profile;
- confirm KPI definitions;
- remove superseded files;
- retain only prompts and templates that are repeatedly useful;
- test the project with one packaged case after major instruction changes; and
- record material changes in the guide’s change log.

## 12. Version

**Version:** 1.0  
**Created:** July 2026  
**Package design:** One instruction file, four project-knowledge files, and this README.
