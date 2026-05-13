# Cloud Infrastructure — Decision Support Site

A four-page, browser-resident decision-support tool for evaluating
cloud-migration readiness, total cost of ownership, and migration
sequencing for mid-sized Indian enterprises.

Built as the implementation artefact for the MCA project
*"Implementation of Cloud-Based Infrastructure in Business Operations."*

## Live site

After deployment to GitHub Pages, the site is reachable at:

```
https://<your-username>.github.io/<repo-name>/
```

## Pages

| File              | Purpose                                          |
| ----------------- | ------------------------------------------------ |
| `index.html`      | Project overview / landing page                  |
| `readiness.html`  | 16-question cloud-readiness assessment           |
| `calculator.html` | 5-year on-prem vs cloud TCO calculator           |
| `onepager.html`   | Executive A4-printable summary                   |

## Tech

- Plain HTML, CSS, and vanilla JavaScript (no build step)
- Chart.js loaded from jsDelivr CDN
- `localStorage` for client-side persistence

## Project artefacts

- `Cloud_Infrastructure_Project_Report.docx` — full MCA report (10 chapters)
- `Cloud_Infrastructure_Presentation.pptx` — viva slide deck
- `generate_report.py` — `python-docx` generator that builds the report
- `generate_pptx.py` — `python-pptx` generator that builds the slides

## Local preview

```bash
# Any one of the following:
open index.html                       # macOS
xdg-open index.html                   # Linux
python3 -m http.server 8000           # then visit http://localhost:8000/
```
