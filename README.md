# Project Management Dashboard

An interactive Power BI dashboard tracking a portfolio of 99 projects across departments, statuses, and completion phases.

## Data

Single project-tracking table with columns for Project Name, Department, Project Manager, Project Type, Region, Complexity, Phase, Start/End Date, Status, and aggregated Project Cost / Project Benefit / Completion% measures.

## Features

- **KPI cards** by project type: Process Improvement ($222.23M), Income Generation ($237.93M), Cost Reduction ($194.57M), Working Capital ($219.25M)
- **Total Project Pipeline** donut chart breaking down all 99 projects by status (Completed, Cancelled, In-Progress, On-Hold)
- **Completion Rate per Phase**: horizontal bar chart across 5 project phases (Explore → Measure), ranging 83.4%–91.8%
- **Gauge visuals** for Overall Completion (89.2%) and In-Progress Completion (81.5%)
- **Conditional status icons** in the project summary table (on-track / at-risk / cancelled indicators) driven by completion thresholds
- **Cross-filtering** by Status and Year (2021–2025) across all visuals
- **Project Benefit per Year** trend bar chart, 2021–2025
- Portfolio totals: $411.5M total project cost against $874.0M total project benefit

## Tools
Power BI (interactive filtering, conditional formatting, gauge/KPI visuals)

## File
`Project Management Dashboard.pbix` — open in Power BI Desktop, or upload to [app.powerbi.com](https://app.powerbi.com) to view in browser.
