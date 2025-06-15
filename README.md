# HR_Dashboard_PBIX
HR Dashboard - Power BI This repository features a Power BI dashboard for HR analytics. It offers insights into employee demographics, attrition trends, performance metrics, and organizational structure to support data-driven HR decisions and strategic planning with powerful visuals and models.

Structural Components
  Tables likely include key HR datasets:
    Employee demographics (age, gender, department, location)
    Attrition or turnover (hire dates, termination dates)
    Performance data (ratings, KPIs, appraisal scores)
    Possibly compensation, tenure, or training records

Relationships & Schema
  Defined foreign keys connecting employees to departments, managers, or performance records.
  Likely includes a star or snowflake schema for efficient querying.

Calculated Columns & Measures
  Metrics like "Attrition Rate", "Average Tenure", "Headcount by Department".
  Time intelligence likely built in for YoY or MoM trends, using DAX formulas.

Report Layer (Visualization)
  Rich set of interactive visuals:
    Bar charts for department headcount
    Line charts for attrition over time
    Pie/donut charts for demographics breakdown
    Cards or KPI tiles for metrics like "Total Employees", "Avg Tenure"
  Possibly includes slicers (filters) for Year, Department, Location to drill into visuals.

Security & Sharing
  SecurityBindings suggest row-level security (RLS):
    Ensures users view only permitted data segments (e.g., hiring managers see only their teams).
    Ensures data privacy compliance for sensitive HR information.

Layout & Customization
  DiagramLayout defines visual positioning of tables—useful for future schema updates.
  Report layout includes custom themes, color palettes, and font settings matching branding.

🔍 Why It Matters
  Efficient Design: Small file size with modular tables supports fast performance.
  Scalable: Schema design likely supports adding new metrics over time.
  Interactive & Secure: Built-in drilldown visuals and RLS support safe exploration.

