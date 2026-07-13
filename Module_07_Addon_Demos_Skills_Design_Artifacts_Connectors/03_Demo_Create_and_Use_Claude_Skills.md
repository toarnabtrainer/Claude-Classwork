# 🧩 Demo 3 — How to Create and Use Claude Skills

## 1. What Learners Should Understand

Skills are reusable instruction packages that teach Claude how to perform a repeatable task.

Examples:

```text
✅ Customer response style
✅ Brand guideline enforcement
✅ Report formatting
✅ Data analysis workflow
✅ Document generation method
```

---

## 2. Skill Resource to Use

Use this ZIP file:

```text
Resources/EcoServe_Customer_Response_Skill.zip
```

Learners should upload the ZIP file, not the Markdown resource file.

---

## 3. Skill Creation Path

Use:

```text
Claude.ai ➜ Customize ➜ Skills ➜ + ➜ Create skill ➜ Upload a skill
```

Then upload:

```text
EcoServe_Customer_Response_Skill.zip
```

Learners should understand that a custom Skill normally contains a folder with a `Skill.md` file.

---

## 4. What the EcoServe Skill Does

The EcoServe Skill teaches Claude to respond to customer messages using:

```text
✅ Calm tone
✅ Customer-friendly language
✅ Internal issue summary
✅ Missing information request
✅ Escalation decision
✅ No unsupported promises
```

---

## 5. Where to Test the Skill

After uploading the Skill, do not type the test prompt inside the Skill tab.

Use:

```text
New Chat
```

Learners should understand:

```text
Skill tab = create/manage Skills
Chat window = use Skills
```

---

## 6. First Test Prompt

Open a new chat and type:

```text
Use the EcoServe customer response style to reply to this customer:

"My pickup request status has not updated for two days. I need help."

Return:
1. Internal issue summary
2. Customer-ready reply
3. Missing information to request
4. Escalation required? Yes/No
```

---

## 7. Stronger Test Prompt

If the Skill does not appear to trigger, use:

```text
Use the EcoServe Customer Response Skill.

Reply to this customer:

"My pickup request status has not updated for two days. I need help."

Return:
1. Internal issue summary
2. Customer-ready reply
3. Missing information to request
4. Escalation required? Yes/No
```

---

## 8. Signs the Skill Is Working

```text
✅ Response is structured
✅ Tone is calm and professional
✅ Missing information is requested
✅ Escalation logic is applied
✅ No pricing, legal, or vendor promises are invented
```

---

## 9. Signs the Skill Is Not Triggering

```text
❌ Generic response
❌ No structure
❌ No escalation decision
❌ No missing information request
❌ Tone does not match the Skill
```

---

## 10. Skill Troubleshooting

| Problem | Suggested Fix |
|---|---|
| Skill does not trigger | Mention the Skill name directly |
| Upload fails | Confirm ZIP contains the skill folder and Skill.md |
| Output is generic | Improve the Skill description |
| Skill has risky scripts | Inspect before enabling |
| Wrong behavior | Revise Skill.md and upload again |

---

## 11. Safety Notes

Learners should understand:

```text
🔴 Do not include passwords or API keys in Skills.
🔴 Review scripts before enabling Skills.
✅ Keep Skills focused on one repeatable workflow.
✅ Use examples inside Skill.md when helpful.
```
