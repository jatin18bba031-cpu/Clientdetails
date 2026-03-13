# Client Tracker NCR - Excel Dashboard

An interactive Excel dashboard for tracking and analyzing client incidents across NCR (Noida & Gurugram) facilities. Everything is in a single Excel file — no external tools needed.

## How to Use

Open `Client Tracker - NCR.xlsm` in Microsoft Excel. The workbook has 4 sheets:

### 1. Dashboard (Main View)
- **Filter Dropdowns**: City, Site/Facility, Month, Status, Category — select a value and all KPIs, charts, and summary tables update automatically
- **KPI Cards**: Total Incidents, Open, Closed, In Progress, Business Impact
- **Bar Charts**: Incidents by Category, Monthly Trend, Site/Facility breakdown, Aging Bucket distribution, Sub-Category breakdown
- **Pie Charts**: Status distribution (Open/Closed/In Progress), City-wise split (Gurugram/Noida), Business Impact (Yes/No)
- **Data Table**: First 100 incident rows shown directly on the dashboard

### 2. Dashboard Formula (Reference)
- All COUNTIFS-based summary calculations that power the dashboard charts
- Organized by: Category, Status, City, Business Impact, Month, Facility, Bucket, Sub-Category

### 3. Incidents
- 355 incident records with 22 columns (City, Facility, Date, Month, Status, Category, etc.)
- Use Excel AutoFilter (Ctrl+Shift+L) for detailed row-level filtering

### 4. Client MOM
- 95 client records with on-going issues, appreciation, and sales expansion details

## Filtering

Select any value from the dropdowns on the Dashboard sheet (e.g., City → "Gurugram") and all charts and KPI values recalculate to show only matching data. Select "All" to see everything.