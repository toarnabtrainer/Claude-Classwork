# ✳️ Demonstration Steps — API, Tools, MCP, and Claude Code

## Demo Goal

Learners should understand how advanced Claude workflows are designed, even before writing full production code.

---

## Part A — API Prompt Design

Use this design prompt in Claude:

```text
Design a Claude API workflow for customer complaint classification.

Input:
Customer message

Output:
1. Summary
2. Sentiment
3. Category
4. Urgency
5. Suggested reply
6. Escalation required? Yes/No

Include:
- System prompt
- User message template
- JSON output schema
- Test cases
```

Learners should understand that API work starts with clear input and output design.

---

## Part B — Tool Design

Use:

```text
Design a tool called get_pickup_request_status.

The tool should help a support assistant check the status of an EcoServe pickup request.

Return:
1. Tool name
2. Description
3. Input schema
4. Example tool result
5. Safety rule
```

Learners should understand that tools need clear names, inputs, outputs, and safety rules.

---

## Part C — Tool-Use Loop Explanation

Ask Claude:

```text
Explain the tool-use loop using this example:

User asks for pickup status.
Claude requests get_pickup_request_status.
The application executes the tool.
The tool returns status.
Claude gives final answer.

Return this as a numbered workflow.
```

---

## Part D — MCP Concept Demo

Use:

```text
Explain MCP to a beginner using the EcoServe support system.

Show how Claude could connect to:
1. Ticket database
2. Vendor operations system
3. Knowledge base
4. Calendar

Include read-only tools and write-action approval rules.
```

---

## Part E — Claude Code Safe Workflow

In a sample code project, learners should use this style of prompt:

```text
Inspect this project first.
Do not modify files yet.

Return:
1. What the project does
2. Main files and folders
3. Likely entry point
4. Risks
5. Suggested plan for adding a small feature
```

Then:

```text
Now implement only the approved small change.
Run or describe relevant tests.
Summarize changed files.
```

---

## Part F — Practice Resource

Review:

```text
Resources/Module_06_Developer_Practice_Resource.md
```

Learners should create:

```text
☑️ API prompt
☑️ Tool schema
☑️ MCP workflow design
☑️ Claude Code safety checklist
```
