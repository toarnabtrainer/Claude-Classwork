# ✨ Developer and Automation Templates to Copy

## 1. API System Prompt Template

```text
You are a [ROLE].

Rules:
- Follow the required output schema.
- Do not invent facts.
- If information is missing, return "unknown".
- Escalate risky cases.
- Keep responses concise.
```

---

## 2. API User Message Template

```text
Task:
[DESCRIBE TASK]

Input:
[PASTE INPUT]

Return JSON with:
{
  "summary": "",
  "category": "",
  "urgency": "",
  "suggested_reply": "",
  "escalation_required": true/false
}
```

---

## 3. Tool Schema Design Template

```json
{
  "name": "tool_name",
  "description": "What the tool does and when Claude should use it.",
  "input_schema": {
    "type": "object",
    "properties": {
      "id": {
        "type": "string",
        "description": "The ID to look up"
      }
    },
    "required": ["id"]
  }
}
```

---

## 4. Safe Tool Prompt

```text
Use tools only when needed.

Before any write action:
1. Show the planned action.
2. Ask for confirmation.
3. Do not proceed without approval.

Never guess tool results.
```

---

## 5. Claude Code Planning Prompt

```text
Inspect this codebase first.
Do not edit files yet.

Return:
1. Project purpose
2. Main folders
3. Entry point
4. Potential risks
5. Step-by-step plan
```

---

## 6. Claude Code Implementation Prompt

```text
Implement the approved plan.

Rules:
- Keep changes minimal.
- Do not change unrelated files.
- Add or update tests if relevant.
- Summarize the diff.
- Suggest a commit message.
```
