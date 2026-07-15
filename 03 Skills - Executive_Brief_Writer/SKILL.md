---
name: executive-brief-writer
description: Turn reports, notes, and analyses into concise decision-focused executive briefs. Use for one-page leadership summaries with findings, recommendations, risks, and next steps.
---

# Executive Brief Writer

## Purpose

Create concise, evidence-based executive briefs for senior managers, leadership teams, and decision-makers. Convert detailed source material into a clear management message without inventing facts or repeating unnecessary background.

## Use This Skill When

Use this skill when the user asks to:

- turn a report, analysis, dashboard, meeting note, or business case into an executive brief;
- prepare a one-page leadership summary;
- present a recommendation and decision required;
- summarise performance, risks, or a business issue for senior management;
- rewrite detailed material for an executive audience.

Do not use this skill as a substitute for the underlying analysis. When the source material does not support a reliable conclusion, state the evidence gap and provide a provisional brief rather than inventing an answer.

## Required Inputs

Use the information available in the conversation and attached files. Identify, where possible:

1. the management audience;
2. the business issue or decision;
3. the reporting period;
4. the most material facts and calculations;
5. the available options;
6. the recommended action;
7. the principal risks and assumptions;
8. the immediate next steps.

If any item is missing, continue with the available evidence and label the gap clearly. Ask a question only when the missing information prevents a useful brief.

## Working Method

Follow this sequence:

1. **Define the purpose.** Identify what the reader must understand, decide, approve, or do.
2. **Review the evidence.** Extract only the facts, calculations, assumptions, and findings that materially affect the decision.
3. **Find the main message.** State the conclusion in one or two sentences before drafting the rest of the brief.
4. **Prioritise.** Keep only the most important findings, implications, risks, and actions.
5. **Draft.** Use the appropriate structure from `resources/Executive_Brief_Template.md`.
6. **Challenge.** Check whether the recommendation is supported, feasible, and clear about trade-offs.
7. **Edit.** Remove repetition, background detail, vague language, and unsupported certainty.
8. **Verify.** Complete the quality checklist before presenting the final brief.

## Evidence Rules

Distinguish clearly between:

- **Verified fact:** directly supported by the supplied source material.
- **Calculated result:** derived from supplied figures; show the logic when material.
- **User-provided assumption:** accepted for the purpose of the brief.
- **Analytical inference:** a reasonable interpretation that still requires validation.
- **Recommendation:** a proposed management action based on the evidence.

Never create missing company facts, dates, figures, quotations, or commitments. When sources conflict, describe the conflict and avoid selecting one version without justification.

## Default Output Structure

Unless the user requests another format, use:

1. **Title and reporting period**
2. **Decision or purpose**
3. **Executive summary**
4. **Key findings**
5. **Business implications**
6. **Recommendation**
7. **Principal risks and assumptions**
8. **Immediate next steps**
9. **Decision required**

Keep the standard brief to approximately 400–650 words. Use a table only when it improves comparison or decision clarity.

## Writing Standards

- Lead with the conclusion, not the history.
- Use clear corporate language and short paragraphs.
- Quantify material findings where evidence permits.
- Explain why each finding matters to the business.
- Prefer specific actions, owners, timing, and success measures.
- Limit the brief to the five most material findings unless the user requests more.
- Avoid jargon, filler, promotional language, and repeated data.
- Do not present hypotheses as confirmed causes.
- Make the requested management decision explicit.

## Brief Modes

Choose the mode that best matches the request:

### Decision Brief

Use when leadership must approve, reject, defer, revise, or select an option. Emphasise alternatives, recommendation, economics, risks, and approval conditions.

### Performance Brief

Use when summarising KPI, financial, customer, or operational performance. Emphasise target variance, trend, drivers, implications, and corrective actions.

### Issue Brief

Use when explaining a problem, incident, or emerging risk. Emphasise severity, evidence, likely causes, exposure, containment, and escalation.

### Strategy Brief

Use when summarising a strategy, market assessment, or growth proposal. Emphasise strategic rationale, choices, capabilities, trade-offs, milestones, and decision gates.

## Final Quality Check

Before presenting the brief, confirm that:

- the purpose or decision is clear in the opening section;
- the conclusion is supported by the supplied evidence;
- important figures, periods, and units are consistent;
- facts, assumptions, and inferences are distinguishable;
- the recommendation is specific and executable;
- risks and trade-offs are visible;
- actions include owners or accountable functions where possible;
- the brief contains no invented information;
- unnecessary detail and repetition have been removed;
- a senior reader can understand the required decision quickly.

## Supporting Resources

- Use `resources/Executive_Brief_Template.md` for the reusable structures and quality checklist.
- Use `resources/Sample_Business_Report_and_Test_Prompts.md` for a complete fictional demonstration, trigger tests, and a model output.
