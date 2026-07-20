# Projects Department — Data Analytics with Claude and Microsoft Excel

This repository package is designed for client participants who have **Microsoft Excel** and access to the **client-approved Claude account**. It has no programming, Python, VBA, macro, add-in, command-line, or developer requirement.

## Repository contents

This package contains only three files and no folders:

1. `Projects_Claude_Excel_Assignment_Participant.xlsx` — the participant assignment workbook.
2. `Projects_Source_Data.zip` — all 11 original project source workbooks, retained unchanged and placed at the ZIP root.
3. `README.md` — this guide.

## Assignment objective

Prepare a project-management review covering:

- Erection DPR progress and daily activity.
- Drawing upload, release, revision, overdue, and workflow bottlenecks.
- Cement and reinforcement-steel readiness.
- An integrated exception register and one-page management summary.

Claude may assist with data interpretation, prompt refinement, formulas, exception logic, and management communication. Every material calculation and conclusion must be independently checked in Excel.

## How participants should work

1. Save a working copy of the Excel assignment workbook.
2. Open `01_Start_Here` and confirm the reporting date and thresholds.
3. Complete the actions in `05_Actions_Prompts` in sequence.
4. Copy the relevant prompt into the approved Claude account.
5. Verify Claude's calculations using the formula columns already provided in Excel.
6. Complete `07_Exceptions`.
7. Complete the management summary, validation checklist, and prompt log in `08_Summary_Validation`.
8. Present the ten highest-priority issues and the recommended actions.

The main working sheets are:

- `02_DPR_Data`
- `03_Drawing_Data`
- `04_Material_Data`
- `06_Analysis`

## Source-data originality

`Projects_Source_Data.zip` contains the uploaded project workbooks without changes to their bytes. The assignment workbook contains manageable working tables extracted from the DPR summary, drawing register, and material summary. Every working record includes a source-file and source-row or source-reference field.

The remaining source workbooks are retained for optional extension exercises and project-team validation.

## Important analysis safeguards

- Do not add quantities measured in **KM** to quantities measured in **Nos**.
- Do not add material quantities measured in **Bags** to quantities measured in **MT**.
- Treat a district-wide average as an unweighted management indicator, not as a physical-quantity total.
- Confirm whether the common drawing scheduled date is a valid baseline before presenting overdue days as contractual delay.
- Treat repeated drawing identifiers and high revisions as review items, not automatic errors.
- Do not present a relationship between progress, drawings, and materials as proven causation unless the project team confirms the dependency.

## Data security

This package contains company project information.

- Use a **private GitHub repository** only.
- Use the client-approved Claude environment only.
- Do not upload the files to public repositories, personal AI accounts, or unapproved file-sharing services.
- The facilitator may upload the three files through the GitHub web interface; participants do not need Git commands.

## Software requirement

Microsoft Excel and the approved Claude account are sufficient.
