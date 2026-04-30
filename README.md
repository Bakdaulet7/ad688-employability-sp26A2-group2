<<<<<<< HEAD
# 📊 Salary Disparities Across Disciplines

> **Who benefits most from AI's rise?** A data-driven look at the AI salary premium across skills, experience levels, and US states.

**Authors:** Hasnat & Bakdaulet
**Source data:** Lightcast US job postings · May–Sep 2024 · n = 29,798

---

## 🎨 Design

- **Colors:** Navy (`#0f172a`) + Sky Blue (`#0ea5e9`) + Amber accents
- **Typography:** Syne (display) · DM Sans (body) · DM Mono (eyebrows/code)
- **Charts:** Chart.js with custom interactivity, hover tooltips, and animated load
- Responsive (mobile-first)

---

## 📁 Project Structure

```
ai-salary-website/
├── _quarto.yml             # site config: navbar, theme, output
├── styles.css              # custom CSS design system
├── index.qmd               # Findings page (3 interactive charts)
├── methodology.qmd         # Data, methods, limitations
├── about.qmd               # Project + author bios
├── .github/workflows/
│   └── deploy.yml          # auto-deploy on push to main
└── images/                 # favicon and any image assets
```

---

## 🚀 Deploying to GitHub Pages

### Option A — Auto-deploy (recommended)

1. Create a new repo on GitHub (e.g. `ai-salary-disparities`)
2. Push this folder to the `main` branch
3. Go to **Settings → Pages → Source → GitHub Actions**
4. Push any commit — it builds and deploys automatically ✅

### Option B — Manual render

1. Install Quarto: [quarto.org/docs/get-started](https://quarto.org/docs/get-started)
2. Run `quarto render` in this folder
3. Commit the generated `docs/` folder
4. Go to **Settings → Pages → Source → Deploy from branch → main / docs**

---

## 🛠️ Local Development

```bash
# Live preview with hot reload
quarto preview

# One-shot render to docs/
quarto render
```

---

## ✏️ Customization

| File              | What to change                                |
|-------------------|-----------------------------------------------|
| `_quarto.yml`     | Site title, navbar links, footer text         |
| `styles.css`      | Colors, typography, layout                    |
| `index.qmd`       | Findings page — chart data & explanations     |
| `methodology.qmd` | How the analysis was done                     |
| `about.qmd`       | Author bios, project background               |

To edit chart data, find the `<script>` block at the bottom of `index.qmd` —
each chart has its own data array (`skillData`, `expLabels/aiData/nonAiData`, `stateData`).

---

## 📜 License

Class project · Boston University · MS Applied Business Analytics · 2026
=======
# ad688-employability-sp26A2-group2
Final project Cloud Computing
>>>>>>> 95993378e46096e28bf4d3980643a9df81f17e84
