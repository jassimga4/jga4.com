Case Study 2: Timesheet Automation for HR Imports

Overview  
I built an automation workflow to pull timesheet data via the Clockify API, reformat it into a clean .csv, and prepare it for HR import. This removed repetitive manual entry and improved weekly payroll processing.

My Role  
Developer. I owned API integration, transformation logic, and the lightweight front-end used by the team.

Problem  
- HR relied on manual time entry into ADP from weekly timesheet exports.  
- The process was slow, error-prone, and repeated every week.

Approach  
- Used the Clockify API to extract timesheet data for 20 employees each week.  
- Wrote a Python script to transform and standardize the export into HR-ready .csv format.  
- Built a simple local front-end to trigger and verify the export.  
- Hosted the solution locally to keep data on-prem and minimize setup overhead.

Results  
- Saved 8 hours of manual entry time every week.  
- Improved consistency and reduced input errors by eliminating manual copy/paste.  
- Made HR imports predictable and repeatable.

Tech / Tools  
Clockify API, Python, CSV.
