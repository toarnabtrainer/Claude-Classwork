# ✳️ Demonstration Steps — Document and Image Analysis

## Demo Goal

Learners should understand how to ask Claude for structured, careful analysis of uploaded or pasted documents.

---

## Part A — Upload or Paste the Practice Resource

Use:

```text
Resources/Module_04_Practice_Resource.md
```

Learners can either upload the file or paste its contents into Claude.

---

## Part B — Basic Summary

Use this prompt:

```text
Analyze the uploaded document.

Return:
1. Executive summary
2. Key facts
3. Important numbers or dates
4. Risks or concerns
5. Missing information
6. Recommended next steps

Separate facts from assumptions.
```

Expected behavior:

```text
✅ Claude summarizes the document.
✅ Risks are identified.
✅ Missing information is not invented.
```

---

## Part C — Extract Table

Use:

```text
Extract all important structured information from this document.

Return a table with:
- Topic
- Detail
- Source section
- Importance
- Action needed
```

Learners should understand that tables make analysis easier to review.

---

## Part D — Risk Review

Use:

```text
Review this document as a careful business analyst.

Identify:
1. Operational risks
2. Financial risks
3. Timeline risks
4. Missing information
5. Items needing human review

Do not provide legal advice.
```

---

## Part E — Chart or Visual Analysis Simulation

Use the data in the resource file and ask:

```text
Analyze the defect trend table.

Return:
1. Visible trend
2. Highest-risk month
3. Possible interpretation
4. What cannot be concluded from this data alone
5. Recommended next analysis
```

Learners should understand that Claude should not infer beyond the data.

---

## Part F — Final Action Plan

Use:

```text
Convert your findings into an action plan.

Return:
1. Action
2. Owner role
3. Priority
4. Deadline suggestion
5. Evidence from document
```

---

## ✅ Expected Final Skill

Learners should be able to use Claude for careful document analysis without blindly trusting unsupported conclusions.
