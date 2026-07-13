# 🔗 Demo 4 — How to Create and Use Claude Connectors

## 1. What Learners Should Understand

Connectors allow Claude to access external apps, services, data, or tools.

Examples may include:

```text
✅ Google Drive
✅ Gmail
✅ Google Calendar
✅ Microsoft 365
✅ Notion
✅ GitHub
✅ Custom connectors using remote MCP
```

Availability depends on account plan, organization settings, and permissions.

---

## 2. Basic Connector Setup Path

Use:

```text
Claude.ai ➜ Customize ➜ Connectors
```

Then:

```text
1. Browse available connectors
2. Select a connector
3. Connect or authenticate
4. Grant required permissions
5. Enable the connector in the active chat if needed
```

---

## 3. Enable Connector in Current Chat

Learners should understand that connecting a service may not be enough.

In the active chat:

```text
Click + ➜ Connectors ➜ Turn ON the required connector
```

---

## 4. Google Calendar Demo Prompt

Use exact date and timezone.

```text
Use the Google Calendar connector.

Create an event on my primary Google Calendar.

Event details:
- Title: Study planner
- Date: [exact date]
- Time: 3:00 PM to 3:30 PM
- Time zone: [your time zone]
- Location: Office meeting room
- Description: Urgent issue
- Attendees: None
- Google Meet link: Not required

Before creating it, show the final event details and ask for confirmation if approval is needed.
```

Learners should understand that connector actions may require explicit approval.

---

## 5. Google Calendar Troubleshooting

If event creation does not work:

```text
1. Stop the current generation.
2. Start a new chat.
3. Enable Google Calendar in + ➜ Connectors.
4. Use exact date, time, and timezone.
5. Wait for approval or confirmation card.
6. Confirm the action if prompted.
7. Check Google Calendar manually.
8. Reconnect the connector if authentication is stuck.
```

Possible causes:

```text
🔴 Connector connected but not enabled in the current chat
🔴 Missing exact date or timezone
🔴 Approval card not clicked
🔴 Organization blocks write actions
🔴 Authentication token expired
🔴 Temporary service delay
```

---

## 6. Mock Connector Demo

If live connectors are unavailable, use the mock connector section in:

```text
Resources/EcoServe_Addon_Demo_Resources.md
```

Prompt:

```text
Treat the mock connector data below as if it came from a connected company knowledge source.

Using only that mock connector data, answer:
What should support do if a customer reports a missed pickup?
```

Learners should understand the idea of connected data without needing live permissions.

---

## 7. Custom Connector / Remote MCP Concept

Learners should understand that custom connectors can use remote MCP servers to expose tools and data.

Example custom connector:

```text
EcoServe Support Tools Connector
```

Possible tools:

```text
search_support_tickets
get_pickup_request_status
list_vendor_operations_escalations
```

These tools would let Claude search tickets or check pickup status, subject to permissions and approval rules.

---

## 8. Custom Connector Blueprint Prompt

Use the custom connector section in the resource file and ask:

```text
Explain how the EcoServe Support Tools Connector would work.

Return:
1. Connector purpose
2. Tools exposed
3. Read permissions
4. Write permissions
5. Approval rules
6. Security risks
7. Safe demo plan
```

---

## 9. Connector Safety Rules

Learners should understand:

```text
✅ Connect only trusted services.
✅ Use least-privilege permissions.
✅ Confirm actions before writing data.
✅ Use exact dates and details for calendar actions.
✅ Review organization restrictions.
❌ Do not connect personal accounts unnecessarily.
❌ Do not expose private data during demos.
```
