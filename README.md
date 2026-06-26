# Cloud Infrastructure — Decision Support Site

A four-page, browser-resident decision-support tool for evaluating
cloud-migration readiness, total cost of ownership, and migration
sequencing for mid-sized Indian enterprises.

Built as the implementation artefact for the MCA project
*"Implementation of Cloud-Based Infrastructure in Business Operations."*

## Live site

The deployed site is reachable at:

**https://git-maddy.github.io/cloud-infra-in-business-operations/**

| Page              | Direct link                                                                                  |
| ----------------- | -------------------------------------------------------------------------------------------- |
| Project Overview  | https://git-maddy.github.io/cloud-infra-in-business-operations/index.html                    |
| Readiness         | https://git-maddy.github.io/cloud-infra-in-business-operations/readiness.html                |
| Cost Calculator   | https://git-maddy.github.io/cloud-infra-in-business-operations/calculator.html               |
| Executive 1-Pager | https://git-maddy.github.io/cloud-infra-in-business-operations/onepager.html                 |

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

## Local preview

```bash
# Any one of the following:
open index.html                       # macOS
xdg-open index.html                   # Linux
python3 -m http.server 8000           # then visit http://localhost:8000/
```
