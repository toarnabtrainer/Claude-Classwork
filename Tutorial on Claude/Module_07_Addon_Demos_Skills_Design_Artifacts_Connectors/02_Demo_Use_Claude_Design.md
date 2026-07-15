# 🎨 Demo 2 — How to Use Claude Design

## 1. What Learners Should Understand

Claude Design is used for visual and design-oriented creation.

Learners can use Design for:

```text
✅ Landing pages
✅ One-page brochures
✅ Prototype screens
✅ Presentation-style layouts
✅ Design systems
✅ Brand-aware visual concepts
```

---

## 2. Access Path

Open:

```text
Claude.ai ➜ Design
```

Availability may depend on account plan, rollout, and organization settings.

---

## 3. Resource to Use

Open:

```text
Resources/EcoServe_Addon_Demo_Resources.md
```

Use the section:

```text
Design Brief
```

---

## 4. Design Creation Steps

```text
1. Open Claude.ai
2. Click Design from the left sidebar
3. Create a new design project
4. Paste the EcoServe Design Brief
5. Use the Design Creation Prompt below
6. Review the visual output
7. Ask for revisions
8. Export if required
```

---

## 5. Design Creation Prompt

```text
Create a clean one-page landing page design for EcoServe.

Use this design direction:
- Professional sustainability brand
- Calm green and blue visual direction
- Clear hero section
- Plan overview
- Pickup workflow section
- Customer support note
- Call-to-action section

Audience:
Small and medium business operations teams.

Style:
Modern, clean, simple, trustworthy, and easy to scan.

Rules:
- Do not invent pricing.
- Do not make legal compliance guarantees.
- Do not claim environmental certification.
- Use placeholders where information is missing.
```

---

## 6. Design Revision Prompt

```text
Improve this design for:

1. Visual hierarchy
2. Spacing
3. Readability
4. CTA clarity
5. Mobile-friendly layout
6. Sustainability brand feel

Do not add unsupported claims or pricing.
```

---

## 7. Exporting Design Files

Learners should understand that export options can vary, but common options may include:

```text
✅ Download as ZIP
✅ Export as standalone HTML
✅ Export as PDF
✅ Export as PPTX
✅ Send to Canva
✅ Handoff to Claude Code or local coding agent
```

---

## 8. Run Exported HTML Locally

If exported as standalone HTML:

```text
1. Download the HTML file
2. Double-click it to open in a browser
```

If it does not display properly, run a local server.

### Windows PowerShell

```powershell
py -m http.server 8000
```

Open:

```text
http://localhost:8000
```

### macOS / Linux

```bash
python3 -m http.server 8000
```

Open:

```text
http://localhost:8000
```

---

## 9. Run ZIP Export Locally

After downloading a ZIP:

```text
1. Extract the ZIP
2. Open the folder
3. Check whether it has index.html or package.json
```

If it has `index.html`:

```text
Open index.html
```

or run:

```bash
python3 -m http.server 8000
```

If it has `package.json`:

```bash
npm install
npm run dev
```

Then open the local URL shown in the terminal.

---

## 10. Safety Notes

Learners should understand:

```text
🔴 Review downloaded code before running it.
🔴 Do not paste API keys into frontend code.
🔴 Do not use real sensitive data in design demos.
✅ Keep demo data fictional.
```
