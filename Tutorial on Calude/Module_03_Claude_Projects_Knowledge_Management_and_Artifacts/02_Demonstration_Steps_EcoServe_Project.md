# ✳️ Demonstration Steps — EcoServe Project and Artifact Demo

## Demo Goal

Learners should understand how to create a Claude Project, use Project Knowledge, test performance, and create a reliable Artifact.

---

# Part A — Create the Claude Project

## Step 1: Open Projects

```text
Claude.ai ➜ Projects
```

## Step 2: Create a New Project

Use:

```text
Project Name:
EcoServe Support Project

Project Description:
A customer support knowledge assistant for EcoServe, a fictional sustainability operations platform.
```

Learners should understand that this creates a dedicated workspace.

---

# Part B — Add Project Instructions

## Step 1: Open Project Instructions

Inside the Project, find the Project Instructions area.

## Step 2: Copy Instructions

Copy the full content from:

```text
03_Project_Instructions_To_Copy.txt
```

Paste it into Claude Project Instructions.

Learners should understand that these instructions control Claude’s role, tone, source rules, and escalation behavior.

---

# Part C — Upload Project Knowledge

Upload only this file:

```text
Resources/EcoServe_Project_Knowledge_Base.md
```

Do not upload:

```text
❌ README.md
❌ MCQ file
❌ Demonstration steps
❌ Project instructions file
```

Learners should understand that Project Knowledge should contain business source information, not teaching instructions.

---

# Part D — Test Project Understanding

Use this prompt inside the EcoServe Project chat:

```text
Using only the uploaded project knowledge, summarize what this EcoServe Project is about.

Return:
1. Project purpose
2. Target users
3. Available knowledge categories
4. Tasks you can help with
5. Information that appears to be missing
```

Expected behavior:

```text
✅ Claude summarizes EcoServe from uploaded knowledge.
✅ Claude identifies available knowledge.
✅ Claude avoids inventing unsupported details.
```

---

# Part E — Test Grounded Answering

Use this prompt:

```text
Use only uploaded project knowledge.

What are the EcoServe plans, who are they intended for, and what are their main features?

Return the answer in a table and include the source used.
```

Expected behavior:

```text
✅ Claude gives Starter, Team, and Pro plans.
✅ Claude uses the resource file as the source.
```

---

# Part F — Test Support Workflow

Use this prompt:

```text
Use only uploaded project knowledge.

A customer says:
"My pickup request status has not updated for two days. I need help."

Return:
1. Summary of the issue
2. Answer based on project knowledge
3. Recommended next action
4. Source used
5. Escalation required? Yes/No
```

Expected behavior:

```text
✅ Claude asks for account name, location, pickup request ID, and callback email.
✅ Claude routes missing pickup status to Vendor Operations.
```

---

# Part G — Test Missing Information

Use this prompt:

```text
Use only uploaded project knowledge.

What is EcoServe's exact pricing for Starter, Team, and Pro plans?

If pricing is not available in project knowledge, do not guess.
```

Expected behavior:

```text
✅ Claude says pricing is not found in project knowledge.
❌ Claude should not invent pricing.
```

---

# Part H — Create an Artifact the Reliable Way

## Important Classroom Rule

```text
✅ New Artifact ➜ Use Artifacts tab ➜ New Artifact
✳️ Improve Artifact ➜ Continue in the same Artifact workflow
```

## Steps

1. Open Claude.ai.
2. Click:

```text
Artifacts
```

3. Click:

```text
New Artifact
```

4. Upload or paste:

```text
Resources/EcoServe_Project_Knowledge_Base.md
```

5. Use this prompt:

```text
Create a reusable customer-facing FAQ Artifact for EcoServe.

Audience:
EcoServe customers and support agents.

Purpose:
Help users understand EcoServe plans, pickup requests, reporting, escalation, and unsupported areas.

Use only the uploaded or pasted source content.

Include:
1. Clear title
2. Getting started section
3. Plan comparison table
4. Pickup request steps
5. Pickup status explanation
6. Reporting overview
7. Escalation guidance
8. Unsupported areas
9. Missing information section
10. Quality checklist

Rules:
- Do not invent pricing.
- Do not provide legal compliance advice.
- Do not promise vendor actions unless confirmed.
- Do not claim EcoServe guarantees certification or regulatory compliance.
- Mark missing information clearly.
```

Expected behavior:

```text
✅ Artifact is created through New Artifact.
✅ Output is structured and reusable.
✅ Missing information is clearly marked.
```

---

# Part I — Revise the Artifact

Continue in the same Artifact workflow and use:

```text
Review this FAQ Artifact for:

1. Accuracy against source content
2. Customer friendliness
3. Reusability
4. Missing information
5. Unsupported claims
6. Clarity of escalation guidance

Then revise it without adding unsupported facts.

At the end, include:
- What changed
- What information is still missing
- Final quality checklist
```

Learners should understand that revision is part of Artifact creation.

---

# Part J — Deleting an Artifact

Learners should understand:

```text
To remove an Artifact created from a chat, delete the entire associated chat from chat history.
```

Important caution:

```text
🔴 If an Artifact was published or shared, use the visible Unpublish or Unshare option where available before assuming the shared version is no longer accessible.
```

---

# Part K — Final Learner Submission

Learners should submit:

```text
1. Project name
2. Project purpose
3. Project instructions used
4. Knowledge file uploaded
5. Three grounded answers
6. One missing-information test
7. Artifact creation prompt
8. Artifact revision prompt
9. Final Artifact summary
10. One improvement idea
```
