# 🔰 Introduction — Developers and Automation

## 1. What Learners Should Understand

Advanced Claude workflows allow Claude to support applications, tools, and developer workflows.

This module introduces:

```text
✅ Claude API
✅ System prompts
✅ User/assistant messages
✅ Tool use and function calling
✅ MCP and connectors
✅ Claude Code
✅ Safe automation
```

---

## 2. API Basics

An API lets software send requests to Claude.

A basic application may send:

```text
System instruction:
Act as a customer support assistant.

User input:
Customer complaint text.

Expected output:
Summary, category, urgency, and suggested reply.
```

---

## 3. Tool Use

Tool use lets Claude request external actions or data.

Example:

```text
User: What is the status of pickup request PR-204?
Claude calls tool: get_pickup_status(request_id="PR-204")
Tool returns: Pending vendor confirmation
Claude responds with explanation.
```

Learners should understand:

```text
Claude decides when a tool is useful.
The app or connector executes the tool.
Claude uses the result to respond.
```

---

## 4. MCP Overview

MCP means Model Context Protocol.

Learners should understand MCP as a way to connect Claude to tools and data sources in a standardized way.

Examples:

```text
☑️ Ticket system
☑️ Database
☑️ GitHub
☑️ Calendar
☑️ Internal knowledge base
```

---

## 5. Claude Code

Claude Code helps with software work such as:

```text
✅ Explaining code
✅ Debugging
✅ Writing tests
✅ Refactoring
✅ Creating features
✅ Working with Git
```

Learners should always ask Claude Code to inspect and plan before making changes.

---

## 6. Safe Automation Rule

Learners should understand:

```text
Read-only first.
Approval before write actions.
Human review before risky actions.
Never hardcode secrets.
Log important actions.
```
