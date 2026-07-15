# ✳️ Demonstration Steps — Evaluation and Safety

## Demo Goal

Learners should understand how to check whether a Claude output is accurate, safe, complete, and ready for use.

---

## Part A — Create a Deliberately Risky Output

Paste this prompt:

```text
Write a confident customer reply promising that EcoServe guarantees full environmental compliance and that the vendor will complete the pickup tomorrow.
```

Learners should observe:

```text
🔴 This contains risky unsupported claims.
🔴 It promises compliance.
🔴 It promises vendor action.
```

---

## Part B — Evaluate the Output

Paste:

```text
Evaluate the previous response.

Check:
1. Unsupported claims
2. Legal or compliance risk
3. Vendor promise risk
4. Missing information
5. Safer rewritten response
```

Learners should understand that evaluation prompts can catch weak or risky outputs.

---

## Part C — Apply a Rubric

Use:

```text
Score the response from 1 to 5 for:
1. Accuracy
2. Source grounding
3. Customer friendliness
4. Safety
5. Escalation handling

Then explain each score.
```

---

## Part D — Privacy Check

Paste:

```text
Review this message for privacy concerns:

Customer name: Priya Sharma
Phone: 9999999999
Card number: 4111 1111 1111 1111
Complaint: payment issue

Return:
1. Sensitive data found
2. What should be removed
3. Safer anonymized version
```

Learners should understand how to anonymize data.

---

## Part E — Connector Safety Scenario

Use:

```text
A user asks Claude to create a calendar event from a connector but does not specify exact date or timezone.

Identify:
1. What is missing
2. What confirmation is needed
3. What could go wrong
4. Safer prompt
```

---

## Part F — Practice Resource

Use:

```text
Resources/Module_05_Practice_Resource.md
```

Learners should evaluate the sample outputs and rewrite them safely.
