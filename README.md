# CS4961 SBPD Power BI

Power BI model and report for the Santa Barbara Public Defender HR & EPR dashboards.

This repo keeps two main `.pbix` files:

- `SBPD_HR_EPR_Model.pbix`  
- `SBPD_HR_EPR_Report.pbix`  

---

## 1. Model vs Report

### `SBPD_HR_EPR_Model.pbix` (Semantic Model)

- Connects to current V3.0 Smartsheet data.
- Contains all **Power Query** steps, calculated columns, and core **DAX tables/measures**.  
- Tables of interest:
  - `Employees`  (wired to James's current **Employees V3.0** Smartsheet)
  - `Old Employees`  (backup/test employee + EPR data)
  - Dimension tables such as `Dim_Employee`, `Dim_EPRStage`, `Dim_JobClass`, `Dim_Date`.

In short: This file is where I edit current data connections, queries, DAX, and test visuals 

---

### `SBPD_HR_EPR_Report.pbix`  (Thin Report)

- Connects to James's old Employee Smartsheet data.

In short: This file is where I adjusted the dashboard to be ready for ealier demos (no longer needed).

---



