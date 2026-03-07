# Flagship City Commons — Construction Dashboard

Interactive construction management dashboard for the Flagship City Commons project at 24–28 North Park Row, Erie, PA.

## Overview

A self-contained HTML dashboard with six views for tracking all aspects of the $24.15M mixed-use development:

- **Summary** — KPIs, milestones, active issues, and safety record
- **Management Detail** — Budget tracking, trade packages, change orders, and risk register
- **Field Activity** — Daily logs, weather, equipment, and inspection tracking
- **Contacts** — Project team directory with roles and contact info
- **Tenant Recruitment** — Leasing status for restaurant and residential spaces
- **Financial Forecast** — Month-by-month estimated vs. actual payment tracking with charts

## Tech Stack

- Single-file HTML — no build step, no server required
- [Chart.js 4.5.1](https://www.chartjs.org/) for data visualization
- [jsPDF 2.5.2](https://github.com/parallax/jsPDF) for PDF export
- Responsive design, works on desktop and mobile

## Deployment

Hosted on GitHub Pages. Any push to `main` automatically updates the live site.

## Updating

Edit `index.html` directly to update project data — KPIs, pay applications, milestones, field logs, forecast actuals, etc.

**To update financial forecast actuals:** Find the `FORECAST_DATA` array in the JavaScript section and replace `null` with the actual pay app amount as they come in.

## Maintained By

**Erie Downtown Development Corporation**
Corey Cook, Chief Operating Officer
