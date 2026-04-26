# Project Viewer

## Vision
A hierarchical mind-map style data visualization that lets users drill down through the organization structure by clicking boxes. Each level expands to reveal its children with relevant performance stats.

## Hierarchy Flow
```
Organization (all)
    └── Office (SFL, CFL, ATL, etc.)
        └── Pod (SFL-ALR, SFL-GAB, etc.)
            └── Team (if applicable)
                └── Individual Rep
```

## Data Sources
- **Hierarchy:** `employees` table — `hierarchyOffice`, `hierarchyPod`, `hierarchyTeam`, `hierarchyRegion`, `hierarchyDirectorate`
- **Performance:** `rep_logs` table — signed, CV, green rate, drops
- **Leads:** `leads` table — lead submissions

## Stats per Box
- YTD (year to date)
- MTD (month to date)  
- Today

## Open Questions
1. Animation style for expansion (radial, slide, expand below)?
2. Closing behavior (toggle, click elsewhere, explicit close)?
3. Which metrics to display per box?
4. Visual theme preference?

## Status
**Planning phase** — discussing requirements with Jon

---
*Created: 2026-04-25*
