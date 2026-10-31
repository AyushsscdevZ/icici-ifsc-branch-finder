# ICICI IFSC Branch Finder

A single-file web tool that looks up ICICI Bank branch details from IFSC codes.
Paste IFSC codes or upload an Excel sheet, fetch branch addresses, and export the results.

## Features
- Bulk IFSC lookup (paste a list or upload `.xlsx`)
- Branch name, address, city, state and ICICI branch page link
- Export results to Excel
- No build step, no backend, no API keys

## Data sources
- Branch details: [Razorpay IFSC API](https://ifsc.razorpay.com/)
- Branch page links: [icici.bank.in](https://www.icici.bank.in/find-atm-branch)

## Run locally
Open `index.html` in a browser (needs internet for the CDN scripts and the IFSC API).

## Deploy with GitHub Pages
Repo **Settings → Pages → Deploy from a branch → `main` / root**.
The site will be live at `https://<your-username>.github.io/icici-ifsc-branch-finder/`.

## Disclaimer
Unofficial tool, not affiliated with ICICI Bank. Verify details on the bank's official site.
