# Performance Infographics — Step-by-Step Design Prompts

**Project:** Performance Infographics  
**Design example:** NorthBridge Business Services Ltd. Q2 2026  
**Primary output:** Single-page landscape corporate performance infographic

---

## How to use these prompts

1. Make `01_Design_Blueprint_and_Style_Guide.md` and `02_Sample_Performance_Content_and_Data.md` available to Claude Design.
2. Use one design conversation for the full build.
3. Run the prompts below in sequence.
4. Review the design after every prompt.
5. Do not run the next prompt until the current stage is working.
6. Use the repair prompts only when the related problem occurs.

The prompts are complete and contain no fields that must be replaced.

---

# Build sequence

## Prompt 1 — Create the initial landscape infographic

```text
Create a new single-page landscape corporate performance infographic titled “Q2 2026 Corporate Performance” for the fictional company NorthBridge Business Services Ltd.

Use the exact facts and figures from 02_Sample_Performance_Content_and_Data.md and follow 01_Design_Blueprint_and_Style_Guide.md. Use a 16:9 landscape canvas suitable for presentation on a widescreen display.

Build the first complete version with these sections:
1. header with company, title, reporting period, subtitle, and fictional-data note;
2. six executive KPI cards for revenue, gross margin, operating profit, customer retention, Net Promoter Score, and on-time delivery;
3. revenue actual-versus-target trend for Q3 2025 through Q2 2026;
4. profitability trend showing gross margin and operating profit without combining incompatible scales misleadingly;
5. regional or business-unit performance comparison;
6. customer and operational performance summary;
7. strategic-initiative progress;
8. ranked enterprise risks;
9. three management priorities;
10. source note.

Use the headline: “Growth continued, but margin and retention require management action.”

Do not invent any data, logos, people, external facts, or unsupported causes. Keep the page professional, balanced, concise, and readable from presentation distance. Produce the visual design rather than a written description of what the design could contain.
```

### Check after Prompt 1

Confirm that:

- the complete page exists;
- all required sections are visible;
- the six KPI values are accurate;
- the design is landscape;
- the page is not dominated by decorative elements.

---

## Prompt 2 — Apply the corporate visual system

```text
Refine the current NorthBridge performance infographic using the corporate visual system in 01_Design_Blueprint_and_Style_Guide.md.

Use deep navy and executive blue for structure, teal as a secondary accent, green for positive status, amber for attention, red for material underperformance or high risk, off-white for the page background, and white for content panels.

Create a consistent grid, equal card heights, precise alignment, generous internal spacing, and clear section boundaries. Use one clean sans-serif type family with a strong hierarchy. Make the title and executive message prominent, KPI values easy to scan, section headings consistent, and source notes unobtrusive but readable.

Use simple, consistent business icons only where they improve scanning. Remove decorative imagery, gradients that reduce readability, excessive shadows, unnecessary borders, and visual clutter.

Preserve every correct figure and message. Do not change the content or add new data.
```

### Check after Prompt 2

Confirm that:

- visual hierarchy is clear;
- cards and panels align;
- status colours are consistent;
- the design still fits on one page.

---

## Prompt 3 — Strengthen the executive KPI strip

```text
Improve the executive KPI strip in the current NorthBridge infographic.

Use exactly these six KPI cards and values:
- Revenue: $48.6m, target $50.0m, 2.8% below target, 5.2% above Q1, status Attention.
- Gross margin: 34.8%, target 36.0%, 1.2 percentage points below target, 0.6 percentage points below Q1, status Below target.
- Operating profit: $6.4m, target $7.5m, 14.7% below target, 4.5% below Q1, status Below target.
- Customer retention: 91.2%, target 93.0%, 1.8 percentage points below target, 0.9 percentage points below Q1, status Attention.
- Net Promoter Score: 52, target 50, 2 points above target, 3 points above Q1, status Above target.
- On-time delivery: 94.1%, target 96.0%, 1.9 percentage points below target, 0.9 percentage points below Q1, status Attention.

Give every card the same structure:
1. KPI name;
2. large current value;
3. target comparison;
4. prior-quarter comparison;
5. status label;
6. one short interpretation.

Use green, amber, or red status cues together with text labels. Keep the cards concise and prevent the KPI strip from taking more than one fifth of the page height. Do not change any other section unless required to preserve alignment.
```

### Check after Prompt 3

Verify all six values and the use of percentage points.

---

## Prompt 4 — Improve the financial-performance story

```text
Refine the financial-performance section of the current NorthBridge infographic.

Create a clear revenue actual-versus-target visual for:
- Q3 2025: actual $43.7m, target $44.0m.
- Q4 2025: actual $45.5m, target $46.0m.
- Q1 2026: actual $46.2m, target $47.0m.
- Q2 2026: actual $48.6m, target $50.0m.

Also show the profitability trend:
- gross margin: 36.1%, 35.9%, 35.4%, 34.8%;
- operating profit: $6.5m, $6.8m, $6.7m, $6.4m.

Use two aligned mini charts or another honest layout that does not place percentage and dollar scales on one ambiguous axis. Directly label important endpoints. Keep gridlines light and use consistent quarter labels.

Add one concise conclusion beside the charts:
“Revenue increased in every quarter, while gross margin declined for four consecutive quarters and operating profit fell during the last two quarters.”

Do not add forecasts or change any source value.
```

### Check after Prompt 4

Confirm that:

- all four quarters appear;
- actual and target are distinguishable;
- different units are not presented misleadingly;
- the conclusion matches the data.

---

## Prompt 5 — Improve regional, customer, and operational performance

```text
Refine the regional, customer, and operational sections in the current NorthBridge infographic.

For regional performance, show:
- North: $18.4m actual, $18.0m target, 102.2% attainment, 36.2% gross margin, On track.
- South: $16.1m actual, $17.0m target, 94.7% attainment, 33.4% gross margin, Attention.
- West: $14.1m actual, $15.0m target, 94.0% attainment, 34.7% gross margin, Attention.

For customer and operations, prioritise these measures:
- new customers: 640 versus target 700;
- customer retention: 91.2% versus target 93.0%;
- Net Promoter Score: 52 versus target 50;
- support cases resolved within service level: 86.0% versus target 90.0%;
- on-time delivery: 94.1% versus target 96.0%;
- average process-cycle time: 4.8 days versus target 4.5 days;
- first-time-right rate: 92.6% versus target 94.0%;
- employee productivity: $182,000 revenue per FTE versus target $180,000.

Use a compact visual comparison rather than a dense spreadsheet. Highlight that North is the only region above revenue target, customer advocacy improved, and service execution weakened.

Do not repeat information already clearly visible in the KPI strip. Preserve space for initiatives, risks, and actions.
```

### Check after Prompt 5

Confirm that:

- North, South, and West are easy to compare;
- customer and operational measures remain readable;
- the page is not overcrowded.

---

## Prompt 6 — Clarify strategic initiatives, risks, and priorities

```text
Improve the execution and risk area of the current NorthBridge infographic.

Show these four initiatives with progress bars, status labels, and concise next milestones:
- Customer Portal Upgrade: 78%, On track, complete enterprise pilot in August 2026.
- Cost Efficiency Programme: 62%, Attention, validate $1.2m annualised savings in September 2026.
- Regional Expansion: 45%, Delayed, appoint two channel partners in September 2026.
- Data Quality Improvement: 84%, On track, complete customer-master remediation in August 2026.

Rank these enterprise risks:
1. Margin compression — High.
2. Key-account churn — High.
3. Service reliability — Medium-high.
4. Regional expansion delay — Medium.
5. Data inconsistency — Medium.

Display these three management priorities prominently:
1. Restore margin discipline.
2. Protect high-value customer retention.
3. Improve delivery reliability and operational quality.

Use text labels with colour status cues. Avoid large risk matrices if they make the page harder to scan. Preserve every source value and do not introduce additional initiatives or risks.
```

### Check after Prompt 6

Confirm that initiative progress, status, risks, and actions are distinct.

---

## Prompt 7 — Improve the executive storytelling

```text
Review the complete NorthBridge infographic as an executive communication rather than as a collection of charts.

Reorganise the page only where necessary so that the reading sequence is:
1. headline conclusion;
2. six executive KPIs;
3. financial trend and profitability implication;
4. regional, customer, and operational evidence;
5. strategic execution and risks;
6. three management priorities;
7. closing takeaway and source note.

Use concise callouts:
- “Revenue grew 5.2% quarter on quarter but remained 2.8% below target.”
- “Gross margin fell to 34.8%, and operating profit declined to $6.4m.”
- “Customer advocacy improved, while retention and service execution weakened.”
- “Two initiatives are on track, one requires attention, and regional expansion is delayed.”

End with:
“Protect growth by restoring margin, stabilising key-account retention, and improving delivery discipline.”

Remove repeated wording, background explanation, decorative labels, and any detail that does not change the management message. Keep all source values unchanged.
```

### Check after Prompt 7

A reader should understand the story within approximately one minute.

---

## Prompt 8 — Improve readability and accessibility

```text
Conduct a readability and accessibility refinement of the current NorthBridge performance infographic.

Ensure:
- strong contrast between text and background;
- readable type at presentation size;
- a logical left-to-right and top-to-bottom reading order;
- direct chart labels where practical;
- status words in addition to green, amber, and red;
- consistent numerical formats;
- adequate white space;
- clear separation between percentages, percentage points, currency, counts, days, and scores;
- no text overlapping charts, icons, panels, or footers;
- no critical information communicated by colour alone.

Reduce any paragraph to no more than three short lines. Replace dense tables with concise comparisons where possible. Do not simplify away material figures or management actions.
```

### Check after Prompt 8

View the design at normal presentation size and confirm that every major label is readable.

---

## Prompt 9 — Audit every figure and claim

```text
Audit the current NorthBridge infographic against 02_Sample_Performance_Content_and_Data.md before making any final design changes.

Check every:
- KPI value;
- target;
- prior-quarter comparison;
- percentage variance;
- percentage-point variance;
- quarter label;
- regional value;
- customer and operational measure;
- initiative progress percentage;
- initiative status;
- risk severity;
- management action;
- source note.

Correct every mismatch. Remove any value, cause, forecast, logo, or factual claim that does not appear in the source file. Ensure the design says “Fictional training data” and includes this footer:

“Source: Fictional NorthBridge Business Services Ltd. Q2 2026 training dataset. Created for learning and demonstration only.”

After correcting the design, provide a brief audit summary listing the number of items checked and any corrections made.
```

### Check after Prompt 9

Do not finalise the design until the audit reports no unresolved data mismatch.

---

## Prompt 10 — Finalise the presentation-ready landscape version

```text
Finalise the NorthBridge Q2 2026 performance infographic as a polished single-page landscape design for an executive meeting and colleague demonstration.

Preserve all verified data and approved messages. Make final adjustments to alignment, spacing, chart labelling, panel balance, typography, icon consistency, and visual rhythm. Ensure the title, headline conclusion, KPI strip, financial story, customer and operational evidence, strategic initiatives, enterprise risks, management priorities, closing takeaway, and source note are all present.

The finished design must:
- use a 16:9 landscape layout;
- be understandable within one minute;
- remain readable when projected;
- use no more than three primary charts;
- show six executive KPI cards;
- show status through both colour and text;
- contain no placeholder text;
- contain no unsupported figure or claim;
- contain no decorative visual that competes with the management message.

Do not add new sections. Produce the final visual design and a concise completion note stating that layout, readability, and data accuracy have been reviewed.
```

---

# Optional adaptation and demonstration prompts

## Prompt 11 — Create a portrait adaptation

```text
Create a separate portrait adaptation of the completed NorthBridge Q2 2026 performance infographic.

Do not simply shrink the landscape version. Reflow the content for a portrait page using this sequence:
1. title and executive message;
2. six KPI cards arranged in two columns;
3. revenue and profitability trends;
4. regional comparison;
5. customer and operational performance;
6. strategic initiatives;
7. enterprise risks;
8. three management priorities;
9. closing takeaway and fictional-data source note.

Preserve all verified values and the same corporate visual language. Simplify supporting text where necessary, but do not remove the primary management conclusions. Ensure the portrait version remains readable as a digital one-pager.
```

## Prompt 12 — Prepare the colleague demonstration explanation

```text
Using the completed NorthBridge performance infographic, prepare a concise five-minute colleague demonstration script.

Explain:
1. the business objective of the infographic;
2. how the source data was converted into a visual hierarchy;
3. why the six executive KPIs were selected;
4. why the chosen charts support the performance story;
5. how status colours and labels are used;
6. what the three management priorities are;
7. how the numerical audit protects accuracy;
8. how the same approach could be reused with approved real-company data.

Keep the script practical and suitable for a learner presenting Claude Design to colleagues. Do not add facts that are not present in the project files.
```

---

# Repair prompts

Use these only when the stated issue occurs.

## Repair A — The page is overcrowded

```text
The current NorthBridge infographic is overcrowded. Reduce visual density without removing the six executive KPIs, the primary financial story, the three management priorities, the initiative status, or the top risks.

Remove repeated explanations, combine secondary measures into compact groups, shorten labels, increase white space, and limit the page to three primary charts. Preserve every material figure and the established reading order. Do not reduce font sizes below a comfortable presentation level.
```

## Repair B — Figures do not match the source

```text
The current NorthBridge infographic contains one or more figures that do not match 02_Sample_Performance_Content_and_Data.md.

Perform a complete source-to-design reconciliation. Correct all KPI, target, trend, regional, customer, operational, initiative, and risk values. Remove unsupported numbers. Use percentage points for differences between percentages and percentage for relative change. Preserve the visual layout where possible.
```

## Repair C — The visual hierarchy is weak

```text
The current NorthBridge infographic does not communicate the executive story clearly enough.

Strengthen the hierarchy so the reader sees, in order:
1. growth continued but margin and retention require action;
2. the six KPI outcomes;
3. the financial evidence;
4. customer and operational weaknesses;
5. initiatives and risks;
6. the three management priorities.

Increase prominence through position, scale, weight, and spacing rather than adding more colour or decorative elements. Preserve all accurate content.
```

## Repair D — The design looks decorative rather than corporate

```text
Restyle the current NorthBridge infographic as a restrained executive corporate communication.

Remove decorative illustrations, unnecessary gradients, excessive shadows, playful icons, oversized shapes, and ornamental backgrounds. Use the navy, blue, teal, green, amber, red, white, and off-white palette from the style guide. Apply a consistent grid, clean typography, simple business icons, concise chart styling, and disciplined spacing. Preserve all verified content.
```

## Repair E — Text is too small

```text
Improve the readability of the current NorthBridge infographic without enlarging the canvas.

Increase body, chart-label, and source-note readability by reducing repeated text, shortening labels, simplifying secondary details, and improving panel allocation. Preserve the title, headline, six KPI cards, three primary charts, initiative status, top risks, management priorities, and source note. Do not solve the problem by shrinking other important text.
```

---

# Final self-review prompt

```text
Review the completed NorthBridge performance infographic against the acceptance criteria in 01_Design_Blueprint_and_Style_Guide.md.

Score the design from 1 to 5 for:
- management-message clarity;
- numerical accuracy;
- information hierarchy;
- chart suitability;
- readability;
- visual consistency;
- accessibility;
- actionability;
- presentation readiness.

For every score below 5, state one specific correction and apply it. Then provide the final scores and confirm whether the design is ready for a colleague demonstration.
```
