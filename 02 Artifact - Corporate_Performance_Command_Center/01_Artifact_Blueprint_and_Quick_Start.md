# Corporate Performance Command Center
## Artifact Blueprint and Quick Start

## 1. Purpose

The **Corporate Performance Command Center** is an interactive executive dashboard that converts fictional corporate performance data into clear visual analysis and management actions.

It is designed to help a learner understand how an AI-built Artifact can combine:

- business data;
- interactive filters;
- KPI scorecards;
- charts and progress views;
- strategic initiatives and risks;
- concise executive insights.

## 2. Intended users

- Executives and business leaders
- Strategy and business-intelligence teams
- Finance and operations managers
- Analysts and consultants
- Learners demonstrating Claude Artifacts to colleagues

## 3. Core management questions

The Artifact should help answer:

1. Are revenue and profit meeting target?
2. Which regions and business units are performing well or poorly?
3. Are customer retention and service delivery improving?
4. Which strategic initiatives need attention?
5. Which risks require management action?
6. What are the three most important conclusions for leadership?

## 4. Dashboard structure

### A. Header and controls

Include:

- Artifact title
- Fictional company name
- Latest reporting period
- Period filter
- Region filter
- Business-unit filter
- Reset-filters control
- Button to open an executive summary or guided demonstration

### B. Executive KPI scorecard

Display six KPI cards:

1. Revenue
2. Gross margin
3. Operating profit
4. Customer retention
5. On-time delivery
6. Employee productivity

Each card should show:

- current filtered result;
- target;
- variance;
- status label;
- small trend indicator;
- concise explanation or tooltip.

### C. Financial performance

Include:

- Revenue actual versus target by reporting period
- Operating profit actual versus target by reporting period
- Gross-margin trend
- Region or business-unit comparison

### D. Customer and operations performance

Include:

- Customer-retention trend
- On-time-delivery trend
- Employee-productivity trend
- A comparison table or heatmap by region and business unit

### E. Strategy execution

Show each strategic initiative with:

- name;
- owner;
- status;
- completion percentage;
- target period;
- KPI;
- expected business impact;
- next management action.

### F. Risk and priority panel

For each risk, show:

- category;
- likelihood;
- impact;
- risk score;
- status;
- owner;
- mitigation action.

Sort the highest-scoring risks first.

### G. Management-insight panel

Generate a concise summary containing:

- two positive findings;
- two areas of concern;
- three recommended management actions;
- one important data or interpretation caveat.

The insight text must update when filters change.

## 5. Required interactions

The user should be able to:

- filter by one period or view all periods;
- filter by region;
- filter by business unit;
- reset all filters;
- click a KPI card to see a detailed explanation and relevant trend;
- hover over or focus on charts to view values;
- switch between selected financial and operational views;
- open and close the executive summary;
- move through a short guided demonstration.

## 6. Data and calculation rules

Use `03_Sample_Performance_Data.json` as the source.

Apply these aggregation rules:

- Revenue and operating profit: sum the selected records.
- Gross margin: revenue-weighted average.
- Customer retention: active-customer-weighted average.
- On-time delivery: order-weighted average.
- Employee productivity: employee-count-weighted average.
- Targets: aggregate using the equivalent target fields and weights.
- Variance: actual minus target; show both absolute and percentage variance where meaningful.
- Risk score: likelihood multiplied by impact.

Never average percentages without the supplied business weight.

## 7. Status logic

Use the KPI definitions in the JSON data. For metrics where higher is better:

- **On Track:** actual meets or exceeds target.
- **Watch:** actual is below target but within the metric's amber tolerance.
- **At Risk:** actual is below the amber range.

Use text labels and icons in addition to visual colour.

Strategic-initiative and risk statuses come directly from the data unless a prompt explicitly asks for derived status logic.

## 8. Visual direction

Use a clean corporate interface with:

- a light neutral background;
- strong typographic hierarchy;
- restrained accent colours;
- generous spacing;
- compact but readable cards;
- consistent status badges;
- responsive layout;
- no decorative clutter.

Do not rely on colour alone. Use labels, icons, and accessible contrast.

## 9. Technical boundaries

- Build the Artifact as a self-contained interactive React interface.
- Do not make external network calls.
- Embed the fictional data in the Artifact during generation.
- Prefer dependable chart components available in the Artifact environment.
- Provide a graceful fallback when a chart library is unavailable.
- Keep the code understandable enough for a learner to review.
- Preserve working features when applying later prompts.

## 10. What is intentionally excluded

To keep the project manageable, the first version does not require:

- user authentication;
- database connections;
- live APIs;
- editable financial forecasts;
- PDF export;
- multiple company profiles;
- complex role permissions;
- machine-learning predictions.

These may be added only after the core dashboard works correctly.

## 11. Build workflow

1. Upload this blueprint and the JSON data to Claude Project Knowledge.
2. Open `02_Step_by_Step_Build_Prompts.md` locally.
3. Start a new chat in the same Claude Project.
4. Run the prompts in order.
5. Inspect and test after each prompt.
6. Do not advance until the current stage works.
7. Use the final prompts to validate and demonstrate the Artifact.

## 12. Acceptance criteria

The Artifact is ready when:

- all six KPI cards calculate correctly;
- every filter updates all relevant visuals;
- chart values match the filtered records;
- initiative and risk panels are sortable and understandable;
- management insights change with the selected context;
- no broken or empty states appear;
- keyboard and mobile use remain practical;
- a colleague can understand the business story without reading the source data.
