# Corporate Performance Command Center

A learner-friendly package for building an interactive corporate dashboard as a Claude Artifact.

The finished artifact will help users review company performance, compare actual results with targets, explore trends by period, region, and business unit, inspect strategic initiatives and risks, and generate concise management insights.

---

<img width="1491" height="1055" alt="Artifact - Infographics" src="https://github.com/user-attachments/assets/af03c342-bb57-4286-9413-e51c7710f984" />

---

## Package contents

```text
Corporate_Performance_Command_Center/
├── README.md
├── 01_Artifact_Blueprint_and_Quick_Start.md
├── 02_Step_by_Step_Build_Prompts.md
└── 03_Sample_Performance_Data.json
```

| File | Purpose | Required? |
|---|---|---|
| `README.md` | Explains the package and recommended workflow. | Recommended |
| `01_Artifact_Blueprint_and_Quick_Start.md` | Defines what the artifact should contain and how it should behave. | Recommended |
| `02_Step_by_Step_Build_Prompts.md` | Provides the prompts to build, refine, test, and demonstrate the artifact. | Essential |
| `03_Sample_Performance_Data.json` | Supplies fictional data for the interactive dashboard. | Essential for this demonstration |

The final React or JSX artifact is **not included as a starting file**. Claude will create it while you execute the prompts. This allows you to learn the development process instead of beginning with a finished solution.

## Recommended Claude setup

1. Create or open a Claude Project named **Corporate Performance Command Center**.
2. Add `01_Artifact_Blueprint_and_Quick_Start.md` and `03_Sample_Performance_Data.json` to Project Knowledge.
3. Keep `02_Step_by_Step_Build_Prompts.md` open on your computer and paste its prompts into one Claude Project chat in numerical order.
4. Ask Claude to create an Artifact when you execute Prompt 1.
5. Test the Artifact after every major step before continuing.

Uploading the prompt file to Project Knowledge is optional. The safest learning workflow is to keep it outside Project Knowledge and paste one prompt at a time, because each pasted prompt becomes the active instruction.

## What the completed artifact should include

- Executive KPI cards with actual-versus-target status
- Period, region, and business-unit filters
- Revenue, profitability, customer, and operational charts
- Strategic-initiative progress tracking
- Risk prioritisation
- Automatically generated management insights
- KPI detail interaction and a simple executive demonstration mode
- Responsive, accessible corporate visual design

## Suggested build sequence

```text
Read the blueprint
        ↓
Upload the sample data
        ↓
Run Prompt 1 in a new Claude Project chat
        ↓
Run the remaining prompts in order
        ↓
Test filters, calculations, and interactions
        ↓
Run the final review and demonstration prompts
```

## Important operating rules

- Use the same Claude conversation for the complete build so Claude can update the existing Artifact.
- Do not paste all prompts at once. Complete and inspect one step before running the next.
- The dataset is fictional and safe for demonstrations. Do not present it as real company information.
- When replacing the sample data with real information, remove confidential or personally identifiable data unless your organisation has approved its use.
- If Claude rebuilds the Artifact instead of updating it, instruct it to modify the existing Artifact and preserve all working features.

## Completion checklist

The project is complete when:

- all filters update every relevant card, chart, table, and insight;
- displayed totals reconcile with the source data;
- no empty, undefined, `NaN`, or broken states appear;
- the layout works on desktop and smaller screens;
- KPI status colours are explained with text or icons, not colour alone;
- the executive summary identifies both strengths and concerns;
- the Artifact can be demonstrated clearly in five to seven minutes.

## Recommended first command

After uploading the blueprint and sample data, paste Prompt 1 from `02_Step_by_Step_Build_Prompts.md` into a new Claude Project chat.
