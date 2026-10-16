# AdminOps Toolkit — 500-script starter release

## Contents
- `index.html`: responsive static website with 500 searchable scripts, categories, view/copy/download controls.
- `catalog.json`: structured catalog for all 500 scripts.
- `scripts/`: 500 individual `.ps1` files.
- `README.md`: deployment and safety notes.

## Test locally
Open `index.html` in a modern browser. The script catalog is embedded in the page, so the site works without a server or build process.

## Deploy on GitHub Pages
1. Extract the ZIP.
2. Upload/replace `index.html`, `catalog.json`, `README.md`, and the complete `scripts` folder in your GitHub repository.
3. Commit changes to the `main` branch.
4. In Settings → Pages, configure deployment from branch `main`, folder `/ (root)`.
5. Visit the URL GitHub Pages provides.

This package was generated locally; it has not been pushed to your GitHub account.

## Safety
Scripts are starter templates, not production-certified. Review each script and test in a lab before deployment. Some require elevation, modules, or a managed Windows device. Read-only queries are preferred. Review any script marked Medium risk before running it. Never store credentials in scripts or publish employer-owned code or confidential environment details.

## Revenue readiness
The static site does not yet process payments, authenticate customers, or gate premium downloads. Validate demand and add hosted checkout, access control, terms, privacy, refunds, and support contact before selling access.
