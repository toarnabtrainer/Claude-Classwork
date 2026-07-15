# Claude Skill Creation and Testing Guide

**Purpose:** A learner-friendly, step-by-step guide for creating, uploading, enabling, testing, improving, and demonstrating a custom Claude Skill.

---

<img width="1491" height="1055" alt="image" src="https://github.com/user-attachments/assets/b548cdc1-a19f-429f-92d8-689385966b07" />

---

**Example used in this guide:** Executive Brief Writer

**Last verified:** 15 July 2026

> Claude’s interface can change over time. If a label differs slightly, look for the equivalent option under **Customize → Skills**.

---

## 1. What is a Claude Skill?

A Claude Skill is a folder containing instructions and, optionally, reference resources or executable files. Claude loads the Skill when the user’s task matches the Skill’s description.

A simple Skill does **not** require programming. It can contain only Markdown files.

A good Skill should:

- solve one specific, repeatable task;
- clearly explain when it should be used;
- define a reliable step-by-step workflow;
- specify the expected output;
- include examples or reference material when useful;
- remain inactive for unrelated tasks.

---

## 2. Minimum requirements

A custom Skill needs at least:

```text
skill-folder/
└── SKILL.md
```

A concise learner-friendly Skill can use this structure:

```text
executive-brief-writer/
├── SKILL.md
├── README.md
└── resources/
    ├── Executive_Brief_Template.md
    └── Sample_Business_Report_and_Test_Prompts.md
```

### File purposes

| File | Purpose | Required? |
|---|---|---:|
| `SKILL.md` | Defines the Skill, triggering conditions, workflow, and output rules | Yes |
| `README.md` | Explains installation, use, testing, and maintenance | No, but recommended |
| `resources/` | Stores templates, examples, checklists, and reference material | No |
| `scripts/` | Stores executable code for advanced Skills | No |

---

# Part A — Create the Skill Files

## Step 1 — Select one focused workflow

Choose a task that you perform repeatedly.

Good examples:

- convert business reports into executive briefs;
- evaluate a business case;
- analyse KPI performance;
- prepare a decision memo;
- convert meeting notes into actions.

Avoid combining many unrelated purposes in the same Skill.

### Example purpose

```text
Convert detailed business reports into concise, decision-focused executive briefs.
```

---

## Step 2 — Create the Skill folder

Create a folder with a short, clear name.

Recommended naming style:

```text
lowercase-words-separated-by-hyphens
```

Example:

```text
executive-brief-writer
```

Do not use passwords, confidential information, or personal data in the folder name.

---

## Step 3 — Create `SKILL.md`

Inside the Skill folder, create a file named exactly:

```text
SKILL.md
```

The file must begin with YAML frontmatter containing a `name` and `description`.

### Ready-to-copy example

```markdown
---
name: Executive Brief Writer
description: Convert detailed business reports into concise executive briefs with conclusions, evidence, implications, recommendations, risks, and decisions required.
---

# Executive Brief Writer

## Purpose

Use this Skill when the user asks Claude to convert detailed business information into a concise executive, board, performance, issue, strategy, or decision brief.

## Do Not Use This Skill For

- casual summaries with no management purpose;
- creative writing;
- general brainstorming;
- reports that require detailed legal, tax, audit, or investment advice;
- tasks unrelated to executive communication.

## Required Workflow

1. Identify the intended audience.
2. Identify the decision, issue, or management objective.
3. Review the available evidence.
4. Separate confirmed facts from assumptions and inferences.
5. Select only the information that changes the decision or action.
6. Lead with the conclusion.
7. Explain the most material findings and business implications.
8. Recommend clear, prioritised actions.
9. State the principal risks, assumptions, and decisions required.
10. Perform a final concision and evidence check.

## Required Output Structure

1. Title
2. Executive conclusion
3. Decision or issue
4. Material findings
5. Business implications
6. Recommended actions
7. Risks and assumptions
8. Decision required or next steps

## Writing Standards

- Use concise professional language.
- Do not invent facts or figures.
- Label assumptions and inferences.
- Quantify material variances when the source data permits.
- Avoid repeating background information.
- Keep the brief focused on management decisions and actions.

## Resources

When relevant, use:

- `resources/Executive_Brief_Template.md`
- `resources/Sample_Business_Report_and_Test_Prompts.md`
```

### Metadata checks

Before continuing, confirm:

- the `name` is clear and no longer than 64 characters;
- the `description` explains both what the Skill does and when it should be used;
- the description is no longer than 200 characters;
- the YAML block starts and ends with `---`;
- the Markdown instructions are specific and actionable.

---

## Step 4 — Add optional resources

Create a `resources` folder only when extra material improves the Skill.

Useful resources include:

- an output template;
- an example input;
- an example output;
- a terminology guide;
- a quality checklist;
- test prompts.

Reference every important resource from `SKILL.md`. This helps Claude understand when it should open and use the file.

### Example

```text
executive-brief-writer/
├── SKILL.md
└── resources/
    └── Executive_Brief_Template.md
```

For a simple Skill, Markdown files are sufficient. Programming files are optional and should be added only when they provide a genuine benefit.

---

## Step 5 — Review the Skill before packaging

Check the following:

- `SKILL.md` exists;
- the Skill has one clear purpose;
- the description is specific;
- all referenced files exist;
- file paths in `SKILL.md` are correct;
- no resource contradicts the main instructions;
- there are no confidential credentials or secrets;
- example data is fictional or authorised for use;
- instructions say what Claude must do, not merely what the topic is.

---

## Step 6 — Create the ZIP package

Create a ZIP file containing the complete Skill folder.

### Correct structure

```text
Executive_Brief_Writer_Skill.zip
└── executive-brief-writer/
    ├── SKILL.md
    ├── README.md
    └── resources/
        ├── Executive_Brief_Template.md
        └── Sample_Business_Report_and_Test_Prompts.md
```

### Incorrect structure

```text
Executive_Brief_Writer_Skill.zip
├── SKILL.md
├── README.md
└── resources/
```

The files should not be placed directly in the ZIP root. The Skill folder should be the top-level item inside the ZIP.

---

# Part B — Upload and Enable the Skill in Claude

## Step 7 — Confirm that Skills are available

### Free, Pro, or Max account

Check:

```text
Settings
→ Capabilities
→ Code execution and file creation
→ Enable
```

Skills require Claude’s code-execution environment to be enabled, even when the Skill itself contains only Markdown files.

### Team or Enterprise account

Your organization owner may need to enable Skills and code execution under:

```text
Organization settings
→ Skills
```

If **Skills** is missing or greyed out, contact the organization owner.

---

## Step 8 — Open the Skills page

In Claude, use this click path:

```text
Claude
→ Customize
→ Skills
```

---

## Step 9 — Start the upload

On the Skills page:

```text
Click +
→ Click + Create skill
→ Select Upload a skill
```

---

## Step 10 — Select the ZIP file

Choose the ZIP package from your device.

Example:

```text
Executive_Brief_Writer_Skill.zip
```

Do not extract the ZIP before uploading.

---

## Step 11 — Complete the upload

After choosing the ZIP:

1. Click **Open**, **Choose**, or the equivalent browser button.
2. Allow Claude to validate the package.
3. Confirm that the Skill appears in the Skills list.
4. Open the Skill and review its name and description.
5. Turn the Skill toggle **ON**.

A Skill that is uploaded but disabled will not be available to Claude.

---

# Part C — Test the Skill Explicitly

Testing should confirm both of these behaviours:

1. Claude uses the Skill when it is relevant.
2. Claude does not use the Skill when it is irrelevant.

Run the tests below in a new Claude chat after enabling the Skill.

---

## Test 1 — Visibility and enablement test

### Action

Go to:

```text
Customize
→ Skills
```

### Pass condition

- The Skill appears in the list.
- Its name and description are correct.
- Its toggle is ON.

### Fail action

If it is absent or disabled, re-upload it or turn it on before continuing.

---

## Test 2 — Explicit invocation test

Use the Skill’s exact name in the prompt.

### Test prompt

```text
Use the Executive Brief Writer Skill. Read the fictional HarborOne Services report in the Skill resources and prepare a one-page performance brief for the chief executive officer. Lead with the conclusion, quantify the most material variances, recommend three actions, and state the decision required.
```

### Pass condition

The response should:

- follow the Skill’s required structure;
- lead with the conclusion;
- use evidence from the sample report;
- distinguish facts from assumptions;
- recommend clear actions;
- state a decision required or next steps.

### Fail indicators

- Claude says it cannot find the Skill resources;
- the response is a generic summary;
- the response ignores the required structure;
- unsupported facts or figures are invented.

---

## Test 3 — Natural-language trigger test

Do not name the Skill. Ask for the task naturally.

### Test prompt

```text
Convert the detailed quarterly business report into a concise one-page executive brief for the CEO. Lead with the conclusion, identify the most material performance issues, recommend three actions, and state the decision required.
```

### Pass condition

Claude applies the same method and output structure even though the Skill was not named explicitly.

### Fail action

If the Skill does not activate reliably, improve the `description` in `SKILL.md` so it more precisely states the relevant tasks and situations.

---

## Test 4 — Alternative-phrasing trigger test

Test whether the Skill works across different wording.

### Test prompt

```text
Prepare a board-ready decision brief from the available business report. Focus on strategic significance, financial implications, principal risks, management recommendation, and the approval requested.
```

### Pass condition

Claude recognises that a board-ready decision brief is within the Skill’s intended scope and adapts the format to the audience.

---

## Test 5 — Negative trigger test

Use a prompt that should not require the Skill.

### Test prompt

```text
Suggest ten friendly names for an employee wellness club.
```

### Pass condition

Claude answers normally without forcing the executive-brief structure onto the task.

### Fail action

If the Skill activates for unrelated requests, narrow the description and strengthen the `Do Not Use This Skill For` section.

---

## Test 6 — Incomplete-input test

Check whether Claude handles missing evidence responsibly.

### Test prompt

```text
Create an executive brief from this information: Revenue declined during the quarter.
```

### Pass condition

Claude should not invent figures or causes. It should either:

- produce a clearly limited brief using only the supplied fact; or
- state the information needed for a decision-ready brief.

### Fail indicators

- invented percentages;
- invented causes;
- invented competitors, dates, or management decisions;
- a confident recommendation unsupported by the input.

---

## Test 7 — Audience-adaptation test

Run these two prompts separately.

### CEO version

```text
Use the Executive Brief Writer Skill to prepare a one-page brief for the CEO. Emphasise the conclusion, immediate business implications, corrective actions, and the decision required this week.
```

### Board version

```text
Use the Executive Brief Writer Skill to prepare a one-page brief for the board. Emphasise strategic exposure, financial implications, governance, principal risks, alternatives considered, and approval conditions.
```

### Pass condition

The two outputs should differ appropriately in emphasis while following the same evidence and quality standards.

---

## Test 8 — Resource-loading test

Ask Claude to use a named resource from the Skill.

### Test prompt

```text
Use the Executive Brief Template included in the Executive Brief Writer Skill and prepare a performance brief from the fictional sample report. Follow every required section in the template.
```

### Pass condition

Claude uses the correct template and the sample report rather than inventing a new structure or dataset.

### Fail action

Confirm that:

- the resource file is inside the ZIP;
- the path is correct;
- the resource is explicitly referenced in `SKILL.md`;
- the file was included in the latest uploaded version.

---

## Test 9 — Repeatability test

Run the same explicit test prompt in two separate new chats.

### Pass condition

The wording may vary, but both outputs should consistently contain:

- the conclusion;
- material findings;
- business implications;
- recommended actions;
- risks or assumptions;
- the decision required or next steps.

### Fail action

Make the required output structure more explicit in `SKILL.md`.

---

## Test 10 — Disable-control test

1. Go to **Customize → Skills**.
2. Turn the Skill toggle OFF.
3. Open a new chat.
4. repeat the natural-language trigger prompt.

### Pass condition

Claude should no longer use the custom Skill’s specialised instructions.

5. Return to **Customize → Skills** and turn the Skill ON again.

This test confirms that the account-level toggle is controlling availability.

---

# Part D — Record the Test Results

Use this table after testing:

| Test | Expected result | Result | Pass/Fail | Required change |
|---|---|---|---|---|
| Visibility and enablement | Skill appears and is enabled |  |  |  |
| Explicit invocation | Correct workflow and output |  |  |  |
| Natural-language trigger | Activates without naming Skill |  |  |  |
| Alternative wording | Recognises related task |  |  |  |
| Negative trigger | Does not activate unnecessarily |  |  |  |
| Incomplete input | Does not invent evidence |  |  |  |
| Audience adaptation | Adjusts emphasis appropriately |  |  |  |
| Resource loading | Uses correct resource files |  |  |  |
| Repeatability | Produces consistent structure |  |  |  |
| Disable control | Stops applying when disabled |  |  |  |

## Recommended acceptance standard

Treat the Skill as ready for demonstration when:

- all critical tests pass;
- explicit invocation works reliably;
- at least two natural-language phrasings trigger it;
- at least two unrelated prompts do not trigger it;
- it does not invent missing evidence;
- the output follows the required structure;
- resource files are loaded correctly;
- repeated runs are acceptably consistent.

---

# Part E — Improve and Re-test the Skill

## If the Skill does not activate

Check:

1. The Skill is enabled.
2. The description clearly says what it does and when to use it.
3. The user request matches that description.
4. The instructions are clear and focused.
5. The ZIP contains the latest version of the files.

Improve the description by adding specific task terms such as:

```text
executive brief, board brief, performance brief, decision brief,
management summary, strategic issue brief
```

Do not make the description so broad that the Skill activates for unrelated writing tasks.

---

## If the Skill activates too often

- Narrow the description.
- Add a stronger `Do Not Use` section.
- State the intended audience and output types.
- Separate unrelated workflows into different Skills.

---

## If the output is inconsistent

- Make the workflow numbered and mandatory.
- Define a fixed output structure.
- Add a quality checklist.
- Include one strong example.
- State which sections may be omitted and under what conditions.

---

## If Claude ignores a resource file

- Refer to the resource explicitly in `SKILL.md`.
- Explain when the resource should be opened.
- Verify the path and filename.
- Repackage and upload the latest folder.

---

## How to update the Skill

Use either method available in your Claude interface:

### Method 1 — Edit, repackage, and re-upload

1. Edit `SKILL.md` or a resource file.
2. Save the changes.
3. Create a new ZIP package.
4. Upload the revised package through **Customize → Skills**.
5. Enable the revised Skill.
6. Repeat the complete test set.

### Method 2 — Edit with Claude, when available

1. Open the Skill’s files in Claude.
2. Highlight the text to change.
3. Select **Edit with Claude**.
4. Describe the required revision.
5. Review the updated files.
6. Re-run the relevant tests.

Test after every material change rather than waiting until the Skill becomes large.

---

# Part F — Common Problems

## Skills section is missing

Check:

```text
Settings
→ Capabilities
→ Code execution and file creation
```

For Team or Enterprise accounts, ask the organization owner to check:

```text
Organization settings
→ Skills
```

---

## ZIP upload fails

Common causes:

- missing `SKILL.md`;
- files placed directly in the ZIP root;
- folder name and Skill identity do not align;
- invalid characters in the name or description;
- broken YAML frontmatter;
- referenced files are missing;
- the ZIP contains an unnecessary nested wrapper folder;
- the file exceeds the applicable upload limit.

---

## Skill is visible but not used

Check:

- the toggle is ON;
- the description states when the Skill should be used;
- the prompt is relevant to the Skill;
- the instructions are not vague;
- the Skill is tested first with an explicit invocation.

---

## Skill is greyed out

Code execution may be disabled for the account or organization. Enable it or contact the organization owner.

---

# Part G — Security and Responsible Use

Before enabling a Skill:

- review every included file;
- install only Skills from trusted sources;
- do not store API keys, passwords, or access tokens in Skill files;
- avoid placing confidential corporate data in demonstration resources;
- review scripts carefully before enabling a Skill that contains executable code;
- verify important business, financial, legal, regulatory, and investment outputs before use;
- test the Skill privately before sharing it with colleagues or provisioning it organization-wide.

---

# Quick Creation Checklist

```text
[ ] Select one repeatable workflow
[ ] Create a clearly named Skill folder
[ ] Create SKILL.md
[ ] Add valid YAML name and description
[ ] Write the mandatory workflow
[ ] Define the output structure
[ ] Add only useful resources
[ ] Verify all file references
[ ] Remove secrets and confidential data
[ ] ZIP the complete folder
[ ] Open Customize → Skills
[ ] Click + → + Create skill → Upload a skill
[ ] Upload the ZIP
[ ] Enable the Skill
[ ] Run explicit trigger tests
[ ] Run natural-language trigger tests
[ ] Run negative tests
[ ] Run incomplete-input tests
[ ] Check resource loading
[ ] Record results
[ ] Revise and re-test
```

---

# One-Minute Demonstration Sequence

Use this sequence when presenting the Skill to colleagues:

1. Open **Customize → Skills** and show that the Skill is enabled.
2. Show the Skill’s name and description.
3. Run one explicit invocation prompt.
4. Show how the output follows the defined structure.
5. Run one natural-language prompt without naming the Skill.
6. Run one unrelated prompt to show that the Skill does not over-trigger.
7. Explain how the Skill can be revised and re-tested.

---

# Official References

- [What are Skills? — Claude Help Center](https://support.claude.com/en/articles/12512176-what-are-skills)
- [How to create custom Skills — Claude Help Center](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)
- [Use Skills in Claude — Claude Help Center](https://support.claude.com/en/articles/12512180-use-skills-in-claude)
- [Provision and manage Skills for your organization — Claude Help Center](https://support.claude.com/en/articles/13119606-provision-and-manage-skills-for-your-organization)

---

## Final principle

A successful Skill is not the one with the most files. It is the one that activates for the right task, follows a clear workflow, produces a consistent output, uses evidence responsibly, and remains inactive when it is not relevant.
