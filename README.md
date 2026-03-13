# Client Tracker NCR - Dashboard

An interactive dashboard for tracking and analyzing client incidents across NCR (Noida & Gurugram) facilities.

## Features

- **KPI Cards**: Total Incidents, Open, Closed, In Progress, Business Impact, Unique Sites
- **Interactive Filters**: City, Site/Facility, Month, Category, Status, Client — all charts and tables update dynamically
- **Bar Charts**: Incidents by Category, Month trend, Site/Facility, Aging Buckets, Sub-Category breakdown
- **Pie Charts**: Status distribution, City-wise distribution, Business Impact analysis
- **Incident Details Table**: Full incident data with status badges, descriptions, and corrective actions
- **Client MOM Table**: On-going issues, appreciation, and sales expansion details per client

## Usage

Open `dashboard.html` in any modern web browser. Use the filter dropdowns at the top to slice data by city (e.g., Gurugram only), site, month, category, status, or client. All visualizations and tables update in real-time.

## Data Source

Data is extracted from `Client Tracker - NCR.xlsm` which contains:
- **Incidents** sheet: 355 incident records with 22 columns
- **Client MOM** sheet: 95 client records with on-going issues