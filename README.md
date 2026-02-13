# CS4961-62 – SBPD Power BI (PBIP)

This repo contains the **Power BI Project (PBIP)** version of the SBPD dashboard so multiple teammates can work on it with Git.

## ✅ What to open (Power BI Desktop)
Open this file in Power BI Desktop:

- **SBPD_PowerBI_Model.pbip**

> Do **NOT** open the `.Report` or `.SemanticModel` folders directly — those are project folders Power BI uses internally.

## Repo structure (PBIP)
- `SBPD_PowerBI_Model.pbip`  
  Entry file you open in Power BI Desktop
- `SBPD_PowerBI_Model.Report/`  
  Report pages, visuals, layout
- `SBPD_PowerBI_Model.SemanticModel/`  
  Model: tables, relationships, DAX measures, etc.
- `.gitignore`  
  Prevents unnecessary local/cache files from being committed

## How to collaborate (recommended workflow)
1. **Pull** latest changes before you start (GitHub Desktop → Pull origin)
2. Make your edits in Power BI Desktop (after opening `SBPD_PowerBI_Model.pbip`)
3. **Save** in Power BI Desktop
4. Commit + Push in GitHub Desktop with a clear message  
   Example: `Add Personnel Matters KPIs` or `Fix Closed Matters measure`

## Notes
- If two people edit the **same report page** (layout/visuals) at the same time, merges can be messy.
  - Try to “claim” pages (such as: one person edits Seperation page, another edits Vacancies Recruitments page).
- Data refresh depends on the data source each person has access to (Smartsheet/API credentials, etc.).
