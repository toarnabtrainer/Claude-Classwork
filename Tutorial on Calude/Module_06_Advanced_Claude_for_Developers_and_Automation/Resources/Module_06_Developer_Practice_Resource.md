# 🔶 Module 6 Practice Resource — EcoServe Automation Design

## Scenario

EcoServe wants a technical assistant that helps support agents classify tickets and check pickup request status.

---

## Sample Customer Tickets

| Ticket ID | Message |
|---|---|
| T-1001 | My pickup request PR-204 has not updated for two days. |
| T-1002 | I want to know if EcoServe guarantees environmental compliance. |
| T-1003 | Please delete my personal information from your system. |
| T-1004 | The vendor missed my scheduled pickup again. |

---

## Desired Ticket Classification Output

```json
{
  "ticket_id": "T-1001",
  "summary": "Customer reports pickup status has not updated.",
  "category": "pickup_status",
  "urgency": "medium",
  "owner_team": "Vendor Operations",
  "missing_information": ["account name", "location", "pickup request ID", "callback email"],
  "suggested_reply": "...",
  "escalation_required": true
}
```

---

## Example Tool: get_pickup_request_status

Purpose:

```text
Check the current status of an EcoServe pickup request.
```

Input:

```json
{
  "pickup_request_id": "PR-204"
}
```

Example output:

```json
{
  "pickup_request_id": "PR-204",
  "status": "Pending vendor confirmation",
  "last_updated": "2026-05-20T10:30:00",
  "owner_team": "Vendor Operations"
}
```

---

## Safety Rules

```text
☑️ Do not guess pickup status.
☑️ Do not create or close tickets without approval.
☑️ Privacy deletion requests go to Privacy Desk.
☑️ Legal or compliance questions should not receive legal advice.
☑️ All write actions require confirmation.
```

---

## Practice Task

Learners should design:

```text
1. System prompt
2. User message template
3. JSON output schema
4. Tool schema
5. MCP workflow
6. Claude Code safety checklist
```
