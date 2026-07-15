# 🔶 EcoServe Add-on Demo Resources

This single resource file supports Design, Artifacts, and Connectors demonstrations.

---

# 1. Artifact Source Brief

## EcoServe Overview

EcoServe is a fictional sustainability operations platform for small and medium businesses.

EcoServe helps customers:

```text
- Submit waste pickup requests
- Track pickup status
- Record recycling activity
- Generate monthly sustainability summaries
```

## Plans

| Plan | Intended Customer | Main Features |
|---|---|---|
| Starter | Small office | Waste pickup requests, recycling log, monthly email summary |
| Team | Multi-location business | Location dashboard, user roles, pickup status, monthly summary |
| Pro | Operations-heavy business | Advanced reporting, exportable data, priority support |

Pricing is not provided.

## Pickup Process

Customers submit a pickup request by opening the Pickup tab, selecting a location, choosing a waste category, adding a preferred pickup window, and submitting the request.

## Support Escalation

Missing pickup status and vendor disputes should be routed to Vendor Operations.

Privacy requests should be routed to Privacy Desk.

EcoServe does not provide legal compliance advice, tax advice, certification guarantees, or vendor performance guarantees.

---

# 2. Design Brief

## Brand Direction

```text
Brand name: EcoServe
Brand personality: trustworthy, calm, practical, sustainability-focused
Visual style: clean, modern, simple, professional
Suggested colors: green, blue, white, soft neutral backgrounds
Audience: operations teams at small and medium businesses
```

## Landing Page Requirements

```text
- Hero section
- Problem statement
- How EcoServe works
- Plan overview
- Pickup request workflow
- Reporting summary
- CTA section
- Missing information placeholders
```

## Design Constraints

```text
- Do not invent pricing.
- Do not claim legal compliance guarantee.
- Do not claim environmental certification.
- Use placeholders where details are missing.
```

---

# 3. Mock Connector Data

Treat this as if it came from a connected company knowledge source.

## EcoServe Support Escalation Guide

```text
Missed pickup:
Route to Vendor Operations.
Ask for account name, location, pickup request ID, and callback email.

Privacy request:
Route to Privacy Desk.
Do not provide legal advice.

Vendor dispute:
Acknowledge the concern.
Avoid blame language.
Do not promise vendor action unless confirmed.
Route to Vendor Operations.
```

## EcoServe Plan Overview

```text
Starter: Small office, pickup requests, recycling log, monthly email summary.
Team: Multi-location dashboard, user roles, pickup status, monthly summary.
Pro: Advanced reporting, exportable data, priority support.
```

---

# 4. Remote MCP Custom Connector Blueprint

## Connector Name

```text
EcoServe Support Tools Connector
```

## Purpose

Allow Claude to access EcoServe support systems safely.

## Example Tools

```text
search_support_tickets
get_pickup_request_status
list_vendor_operations_escalations
```

## Example Read Tool

```json
{
  "name": "get_pickup_request_status",
  "description": "Check the status of a pickup request.",
  "input_schema": {
    "type": "object",
    "properties": {
      "pickup_request_id": {
        "type": "string",
        "description": "Pickup request ID"
      }
    },
    "required": ["pickup_request_id"]
  }
}
```

## Approval Rules

```text
- Read status: allowed after user request
- Create support ticket: ask for confirmation
- Close ticket: ask for confirmation
- Delete data: route to Privacy Desk and require approval
```

## Security Notes

```text
- Use least privilege.
- Do not expose private customer data unnecessarily.
- Log connector actions.
- Avoid running untrusted tools.
```
