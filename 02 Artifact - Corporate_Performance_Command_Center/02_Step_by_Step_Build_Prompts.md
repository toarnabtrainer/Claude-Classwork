# Corporate Performance Command Center
## Step-by-Step Build Prompts

Use these prompts in **one Claude Project conversation** and execute them in numerical order. Upload `01_Artifact_Blueprint_and_Quick_Start.md` and `03_Sample_Performance_Data.json` to Project Knowledge before beginning.

Do not paste every prompt at once. After each step, interact with the Artifact and confirm that the new feature works.

---

## Prompt 1 — Create the Artifact foundation

```text
Create a new interactive React Artifact titled “Corporate Performance Command Center.” First read the project-knowledge files “01_Artifact_Blueprint_and_Quick_Start.md” and “03_Sample_Performance_Data.json.” Treat the company and all values as fictional.

Build a polished first version of the dashboard as one self-contained Artifact. Embed the full JSON dataset directly in the Artifact so it does not depend on external files or network requests at runtime. Create a responsive corporate layout containing a header, reporting-period filter, region filter, business-unit filter, reset control, six executive KPI cards, a financial-performance section, a customer-and-operations section, a strategic-initiatives section, a risk section, and a management-insights section.

At this stage, make the filters functional and show meaningful initial content in every section. Use the exact aggregation rules and status logic in the blueprint. Use clear labels, accessible contrast, and text status badges. Prefer reliable chart components available in the Artifact environment, but use simple SVG or CSS visualisations if a chart library is unavailable. Do not make external calls. Keep the component code organised and understandable for a learner.

Create or update the Artifact directly rather than giving me a prose tutorial. After the Artifact is rendered, provide only a brief note listing the main sections created and any technical limitation that remains.
```

### Check before continuing

- The Artifact opens without an error.
- All three filters and the reset control work.
- Every dashboard section is visible.
- No value displays as undefined or `NaN`.

---

## Prompt 2 — Make KPI calculations reliable

```text
Update the existing Corporate Performance Command Center Artifact. Preserve all working layout and filters.

Audit and improve the six KPI calculations using the embedded sample data. Revenue and operating profit must be summed. Gross margin must be weighted by revenue. Customer retention must be weighted by active customers. On-time delivery must be weighted by orders. Employee productivity must be weighted by employee count. Calculate target values using the corresponding target fields and the same weighting logic.

For every KPI card, display the filtered actual value, target, absolute variance, appropriate percentage or percentage-point variance, status label, and direction indicator. Use each KPI’s tolerance definition from the JSON to classify it as On Track, Watch, or At Risk. Add a concise tooltip or help text explaining the metric and aggregation method. Add safe handling for zero denominators and empty filtered results.

Make each KPI card clickable. Clicking a card should open a compact detail panel showing the KPI definition, calculation method, selected filter context, latest available value, prior-period value, target, and a small trend visual. The panel must be closable by mouse and keyboard.

Modify the Artifact directly. Do not remove any working feature.
```

### Check before continuing

- KPI totals change when filters change.
- Weighted metrics do not use simple averages.
- Each card opens and closes a detail view.
- Status labels are understandable without colour.

---

## Prompt 3 — Improve financial visualisation

```text
Update the existing Corporate Performance Command Center Artifact and preserve all current functionality.

Strengthen the financial-performance section. Add a clear actual-versus-target revenue chart by reporting period and an actual-versus-target operating-profit chart by reporting period. Add a gross-margin trend visual with a target reference. Provide a control that switches the comparison view between region and business unit.

Every financial chart must respond to the current reporting-period, region, and business-unit filters. When one reporting period is selected, show a useful category comparison rather than a one-point time series. Include readable axes, units, legends, tooltips, and a short chart takeaway generated from the selected data. Avoid misleading truncated scales unless they are clearly marked.

Display monetary values in USD millions with sensible rounding. Preserve the KPI detail interaction and all other sections. Modify the Artifact directly rather than describing code.
```

### Check before continuing

- Actual and target series are clearly distinguishable.
- The comparison control works.
- Selecting one period still produces a useful visual.
- Monetary units and percentages are labelled correctly.

---

## Prompt 4 — Improve customer and operational analysis

```text
Update the existing Corporate Performance Command Center Artifact while preserving all working features.

Enhance the customer-and-operations section with three responsive visuals: customer-retention trend, on-time-delivery trend, and employee-productivity trend. Each visual must include its target and update with all dashboard filters.

Add a compact performance matrix that compares every visible region and business unit for the selected period context. Show revenue attainment, retention, on-time delivery, and productivity with values and On Track, Watch, or At Risk labels. Allow the user to sort the matrix by any displayed metric. When all periods are selected, use the latest period for the matrix and state that rule visibly.

Add one concise operational takeaway beneath the visuals. It should identify the strongest combination and the combination needing the most attention based on the filtered context. Modify the Artifact directly and keep it usable on smaller screens.
```

### Check before continuing

- All operational charts update with filters.
- The matrix sorts correctly.
- Latest-period behaviour is clearly explained.
- The takeaway changes with context.

---

## Prompt 5 — Add strategy execution and risk prioritisation

```text
Update the existing Corporate Performance Command Center Artifact and preserve all existing features.

Improve the strategic-initiatives section. Show each initiative as a compact card or table row with name, owner, status, completion percentage, target period, KPI, current result, target result, expected impact, and next action. Add filters for initiative status and owner. Sort At Risk initiatives first, then Watch, then On Track. Include an accessible progress bar and a button that expands or collapses the detailed information.

Improve the risk section. Calculate risk score as likelihood multiplied by impact, sort risks from highest to lowest score, and display category, description, likelihood, impact, score, status, owner, mitigation, and review period. Add a simple likelihood-versus-impact matrix that places each risk in the correct cell. Selecting a risk in the list should highlight it in the matrix and show its mitigation.

Strategic initiatives and risks should remain visible regardless of performance filters because they are enterprise-level items. State this rule in the interface. Modify the Artifact directly.
```

### Check before continuing

- Initiatives are sorted by urgency.
- Status and owner filters work.
- Risk scores are correct.
- Selecting a risk connects the list, matrix, and mitigation detail.

---

## Prompt 6 — Generate contextual management insights

```text
Update the existing Corporate Performance Command Center Artifact without removing any feature.

Create a management-insights engine based only on the embedded data and the current filters. The insight panel must update immediately when reporting period, region, or business unit changes.

Generate exactly two positive findings, two concerns, three prioritised management actions, and one data or interpretation caveat. Every statement must include the relevant metric or variance that supports it. Do not invent causes that are not present in the data. When offering a possible explanation, label it clearly as an inference. Prioritise actions according to business impact and urgency.

Add an “Executive Summary” button that opens a readable summary panel containing the selected context, headline performance, key strengths, concerns, actions, and top enterprise risk. Add a “Copy Summary” control that copies a plain-text version and gives visible success or failure feedback. Ensure the summary remains concise enough for a management meeting.

Modify the Artifact directly and preserve all calculations and interactions.
```

### Check before continuing

- Insights change when filters change.
- Each insight is supported by a number.
- The summary opens, closes, and copies correctly.
- Possible causes are labelled as inference rather than fact.

---

## Prompt 7 — Add guided demonstration mode

```text
Update the existing Corporate Performance Command Center Artifact and preserve all working functionality.

Add an optional guided demonstration mode for a learner presenting the dashboard to colleagues. Provide a clearly labelled “Start Guided Tour” button. The tour should contain six short steps: dashboard purpose, filter controls, executive KPI cards, financial performance, customer and operations performance, and strategy plus risk priorities.

Each step should highlight or visually emphasise the relevant section, provide a two-sentence explanation, and offer Previous, Next, Exit, and Restart controls. The tour must not block normal dashboard use after exit. Include a final tour message that summarises the fictional company story using the latest period across all regions and business units.

Make the tour keyboard accessible and ensure it works on a smaller screen. Modify the Artifact directly rather than returning instructions.
```

### Check before continuing

- All six tour steps appear in order.
- Previous, Next, Exit, and Restart work.
- The highlighted section matches the tour explanation.
- Normal use resumes after exiting.

---

## Prompt 8 — Apply final visual and responsive polish

```text
Refine the existing Corporate Performance Command Center Artifact into a polished executive dashboard while preserving every working calculation and interaction.

Use a restrained corporate visual system with a light neutral background, strong hierarchy, consistent spacing, rounded but professional cards, readable typography, and restrained status accents. Improve alignment, chart sizing, hover and focus states, empty states, loading-free transitions, and the visual distinction between actual, target, positive, warning, and risk information.

Make the desktop layout efficient without becoming crowded. Make the tablet and mobile layouts stack logically, keep controls usable, avoid horizontal page overflow, and allow wide tables to scroll inside their own containers. Do not use colour as the only status signal. Add a small legend for status meanings and chart conventions.

Review every visible label for plain business language. Remove decorative elements that do not improve comprehension. Modify the Artifact directly.
```

### Check before continuing

- The dashboard looks coherent rather than crowded.
- Mobile layout has no page-level horizontal overflow.
- Focus states are visible.
- Status meaning is clear without colour.

---

## Prompt 9 — Perform calculation, interaction, and accessibility testing

```text
Perform a complete quality review of the existing Corporate Performance Command Center Artifact and fix all issues you find. Do not remove features merely to make the review pass.

Verify the embedded data is complete and that all calculations follow the blueprint. Test all combinations of reporting period, region, and business unit, including selections with a single record and selections with no matching record. Confirm every KPI, chart, matrix, takeaway, and management insight updates from the same filtered dataset. Check prior-period comparisons, weighted averages, target calculations, risk scores, sorting, reset behaviour, modal or drawer close behaviour, copy feedback, and guided-tour controls.

Fix undefined values, NaN values, division-by-zero errors, duplicate keys, unstable sorting, misleading rounding, stale insights, clipped content, inaccessible controls, missing labels, keyboard traps, insufficient focus visibility, and small-screen overflow. Add a friendly empty state that explains how to reset filters whenever no records match.

After applying fixes, add a compact “Data Notes” panel in the Artifact that states the data is fictional, explains the major aggregation rules, and identifies the latest reporting period. Modify the Artifact directly. Then provide a brief test summary listing what was checked and any limitation that genuinely remains.
```

### Check before continuing

- There are no broken states.
- All controls are reachable with a keyboard.
- Data Notes are visible.
- Claude reports no unresolved issue unless it is genuine.

---

## Prompt 10 — Final executive review and completion

```text
Conduct a final executive-readiness review of the Corporate Performance Command Center Artifact. Preserve the finished dashboard and make only changes that improve accuracy, clarity, usability, or presentation.

Confirm that a first-time executive can understand within one minute: current performance, target gaps, strongest area, weakest area, key strategic initiative, highest risk, and three recommended actions. Ensure the latest-period all-company view provides a coherent management story. Check that every number shown can be traced to the embedded dataset and that no unsupported causal claim appears.

Add a subtle “Demo Reset” control that returns the dashboard to the latest reporting period with all regions and all business units selected, closes open panels, clears initiative and risk selections, and exits the guided tour. Add a small footer showing the fictional company name, latest period, and the statement “Demonstration data — not for business decisions.”

Modify the Artifact directly. When complete, provide a concise five-minute demonstration script in the chat covering the exact sequence a learner should follow when presenting the Artifact to colleagues. Do not place the script inside the Artifact.
```

---

# Optional repair prompts

Use these only when the described problem occurs.

## Repair A — Claude created a new Artifact instead of updating the existing one

```text
Return to the existing Corporate Performance Command Center Artifact and apply the requested change there. Preserve its current data, filters, calculations, charts, initiative tracking, risk analysis, management insights, guided tour, and responsive design. Do not create a second Artifact and do not replace working features with placeholders.
```

## Repair B — A chart library fails

```text
Repair the Corporate Performance Command Center Artifact without changing its business logic. Replace only the failing chart implementation with dependable inline SVG or CSS-based visuals. Preserve tooltips or accessible value labels, target references, responsive sizing, filtered data behaviour, and the existing visual hierarchy. Do not remove the charted information.
```

## Repair C — Filters produce inconsistent numbers

```text
Audit the Corporate Performance Command Center Artifact so every KPI, chart, table, takeaway, and management insight uses one shared filtered-record collection. Remove any stale or separately filtered calculations. Reapply the blueprint aggregation rules, verify weighted averages and targets, and add safe empty-state handling. Preserve the visible interface while correcting the data flow.
```

## Repair D — The Artifact becomes visually crowded

```text
Simplify the Corporate Performance Command Center Artifact without removing business capability. Reduce repeated labels, group related controls, use collapsible detail areas, improve spacing, shorten explanatory text, and keep only one primary visual for each management question. Preserve all data, filters, calculations, accessibility, and drill-down interactions.
```

# Recommended execution discipline

- Run Prompts 1–10 in the same conversation.
- Interact with the Artifact after every prompt.
- Use a repair prompt only when needed.
- Do not request new optional features until Prompt 10 is complete.
