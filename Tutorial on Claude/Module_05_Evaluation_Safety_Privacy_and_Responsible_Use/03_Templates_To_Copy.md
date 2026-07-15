# ✨ Evaluation and Safety Templates to Copy

## 1. Output Evaluation Template

```text
Evaluate this AI output.

Task:
[DESCRIBE TASK]

Output:
[PASTE OUTPUT]

Score 1–5 for:
1. Accuracy
2. Completeness
3. Format compliance
4. Tone
5. Safety
6. Source grounding

Return:
- Scores
- Issues found
- Suggested improvement
- Pass/fail decision
```

---

## 2. Hallucination Check Template

```text
Check this answer for unsupported claims.

Return:
1. Clearly supported claims
2. Claims that need verification
3. Possible hallucinations
4. Missing information
5. Safer revised answer
```

---

## 3. Privacy Review Template

```text
Review this content for sensitive data.

Return:
1. Sensitive data detected
2. Why it is sensitive
3. What to remove or anonymize
4. Safe rewritten version
```

---

## 4. Human Review Checklist

```text
Before using this output, check:
☑️ Is it factually accurate?
☑️ Is it supported by sources?
☑️ Does it include private data?
☑️ Could it harm someone if wrong?
☑️ Does it need expert review?
☑️ Are assumptions clearly marked?
```

---

## 5. Safe Connector Action Prompt

```text
Use the [CONNECTOR NAME] connector.

Before taking any action:
1. Show the exact action you plan to take.
2. Show the data you will use.
3. Ask for my confirmation.
4. Do not proceed without approval.
```
