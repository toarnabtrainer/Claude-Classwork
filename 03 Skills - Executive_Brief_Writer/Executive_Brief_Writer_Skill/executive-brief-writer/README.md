# Executive Brief Writer Skill

## Overview

The **Executive Brief Writer** is a simple, Markdown-only Claude Skill for converting detailed business material into concise, decision-focused executive briefs.

It is designed for learners, managers, analysts, consultants, and project teams that need to communicate findings clearly to senior leadership.

No Python, JavaScript, executable script, external package, or API connection is required.

## What the Skill Can Do

The Skill can turn:

- business reports;
- KPI or performance analyses;
- meeting notes;
- project updates;
- market assessments;
- risk reviews;
- business cases;
- strategy documents;

into:

- one-page executive briefs;
- decision briefs;
- performance summaries;
- issue briefs;
- strategy briefs;
- recommendations with risks and next steps.

## Folder Structure

```text
executive-brief-writer/
│
├── SKILL.md
├── README.md
│
└── resources/
    ├── Executive_Brief_Template.md
    └── Sample_Business_Report_and_Test_Prompts.md
```

## File Guide

### `SKILL.md`

The required operating file. It defines when the Skill should activate, the evidence rules, drafting workflow, output structure, writing standards, and final quality check.

### `README.md`

This learner guide explains the Skill, installation process, testing sequence, and demonstration method.

### `resources/Executive_Brief_Template.md`

Contains reusable structures for decision, performance, issue, and strategy briefs, together with an input checklist and quality rubric.

### `resources/Sample_Business_Report_and_Test_Prompts.md`

Contains a complete fictional company report, ready-to-run demonstration prompts, a model brief, triggering tests, non-triggering tests, and an evaluation rubric.

## Install in Claude

1. Keep the folder name as `executive-brief-writer`.
2. Create a ZIP file containing the complete folder.
3. In Claude, open **Customize → Skills**.
4. Select the option to create or upload a custom Skill.
5. Upload the ZIP file.
6. Enable the Skill after it appears in the Skills list.

The ZIP should contain the `executive-brief-writer` folder as its top-level folder, rather than placing the individual files directly at the ZIP root.

## First Test

Use this request after enabling the Skill:

```text
Use the Executive Brief Writer Skill. Read the fictional HarborOne Services report in the Skill resources and prepare a one-page performance brief for the chief executive officer. Lead with the conclusion, quantify the most material variances, recommend three actions, and state the decision required.
```

## Simple Demonstration Sequence

### Step 1 — Explain the Skill

```text
Explain what the Executive Brief Writer Skill does, when it should be used, and the structure it follows. Keep the explanation under two hundred words.
```

### Step 2 — Create the Brief

```text
Use the Executive Brief Writer Skill and the HarborOne Services sample report. Prepare a one-page executive performance brief for the chief executive officer.
```

### Step 3 — Change the Audience

```text
Rewrite the same brief for the board. Give greater emphasis to strategic exposure, financial implications, risk, and the decision required.
```

### Step 4 — Review Quality

```text
Audit the brief using the Skill's quality checklist. Identify any unsupported claims, missing implications, vague actions, or unnecessary detail, and then produce the corrected final version.
```

## Expected Behaviour

The Skill should:

- lead with the conclusion;
- use only supplied evidence;
- distinguish facts from assumptions and inferences;
- quantify important variances;
- explain business implications;
- provide a specific recommendation;
- show risks, actions, and the decision required;
- remain concise and executive-ready.

The Skill should not:

- invent missing figures or company facts;
- repeat the entire source report;
- hide material risks;
- describe data without explaining why it matters;
- give a confident recommendation when the evidence is insufficient.

## Recommended Learning Approach

1. Run the first test without reading the model output.
2. Compare Claude's result with the model brief in the sample resource.
3. Ask Claude to explain the differences.
4. Change the audience or purpose and observe how the structure changes.
5. Test the Skill with one of your own non-confidential reports.

## Limitations

This Skill improves synthesis and executive communication. It does not replace the need to validate source data, complete missing analysis, or obtain qualified legal, accounting, tax, regulatory, or investment advice.

Do not upload confidential or personal information unless you are authorised to process it in Claude.
