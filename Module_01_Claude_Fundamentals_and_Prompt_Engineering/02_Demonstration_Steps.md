# ✳️ Demonstration Steps — Claude Fundamentals and Prompting

## Demo Goal

Learners should understand how prompt quality changes Claude’s response quality.

---

## Part A — Weak Prompt Demo

Open Claude and type:

```text
Write about productivity.
```

Learners should observe:

```text
🔴 The answer may be generic.
🔴 It may not match a specific audience.
🔴 It may not produce a reusable output.
```

---

## Part B — Improved Prompt Demo

Now type:

```text
Act as a productivity coach for working professionals.

Create a practical 5-day productivity improvement plan.

Return:
1. Daily focus
2. Main activity
3. Time required
4. Expected benefit
5. Reflection question

Tone:
Simple, motivating, and practical.
```

Learners should observe:

```text
✅ The output is more structured.
✅ The audience is clear.
✅ The answer is easier to use.
```

---

## Part C — Add Constraints

Type:

```text
Revise the plan.

Constraints:
- Each activity must take less than 20 minutes.
- Avoid generic advice.
- Include one example for each day.
- Return the answer in a table.
```

Learners should understand that constraints improve usefulness.

---

## Part D — Ask for Self-Review

Type:

```text
Review your previous answer.

Check for:
1. Clarity
2. Practicality
3. Missing details
4. Repetition
5. Improvement opportunities

Then provide a better final version.
```

Learners should understand that Claude can help improve its own draft, but human review is still necessary.

---

## Part E — Practice Task

Use the resource file:

```text
Resources/Module_01_Practice_Resource.md
```

Ask Claude:

```text
Using the sample business scenario, create a better prompt for generating a training plan.
```

---

## ✅ Expected Result

At the end of this demo, learners should be able to explain:

```text
☑️ Why vague prompts produce vague outputs
☑️ Why role and context matter
☑️ Why output format matters
☑️ Why revision improves quality
```
