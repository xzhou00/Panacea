# Mia’s Design Exercise

A product design exercise exploring financial clarity for early-career doctors.

## Start here

Open **index.html** for Mia’s approach and a visual overview of the three iterations.

- **Approach** (`index.html`): problem framing, user needs, constraints, priorities and the evolution from V1 to V3.
- **Iterations** (`process.html`): the detailed design story, including the original A/B sketches and broader dashboard.
- **Refined Prototype** (`refined.html`): the final single-page prototype, with a return link to Mia’s approach.
- **Earlier work**: `v1.html` contains the original static sketches; `v2.html` preserves the expanded interactive dashboard.

## Run locally

This is a static HTML, CSS and JavaScript project. No dependencies or build step are required.

Open `index.html` directly, or serve this folder:

```sh
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Publish with GitHub Pages

1. Create or open your GitHub repository.
2. Upload **the contents of this folder** into the repository root. `index.html` should be at the top level, not inside an extra folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose your default branch (usually `main`) and **/(root)**, then Save.
6. When GitHub finishes deploying, copy the published URL shown in Pages and share it with reviewers.

GitHub Pages setup reference: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Prototype behavior

- Fictional accounts show debt balances, upcoming payments and relevant product options.
- Living-expense estimates and debt/account changes update the monthly overview.
- Income upload starts with file selection or a device-camera input. Amount review happens in a separate second step.
- CSV files matching `assets/sample-income.csv` can populate pay details. PDF/photo amounts require manual entry in this concept.
- Camera capture depends on device and browser support; desktop browsers may show a file picker.
- Reminders and edits are stored only in the visitor’s browser. No bank connection, OCR service, notifications or payments are sent.

## Assets and attribution

Brand assets and typefaces reference Panacea Financial’s public website for this interview exercise. Source details are in `assets/brand-sources.txt`. All dashboard account information is fictional. The project is exploratory design work, not an official banking service.

The package contains no Sites credentials, hosting account configuration or Git history.
