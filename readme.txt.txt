================================================================================
                    ATTENDANCE MANAGER — README
================================================================================

OVERVIEW
--------
Attendance Manager is a complete, offline-capable workforce attendance tracking
system. It runs entirely in your web browser with no server, no database, and
no internet connection required after the initial file load.

HOW TO USE
----------
1. Extract all three files from the ZIP into the same folder.
2. Double-click Attendance_Manager.html to open it in your browser.
   (Recommended: Chrome, Edge, Firefox, or Safari.)
3. All data is stored in your browser's localStorage and auto-saves on every
   change.

FEATURES
--------
- Dashboard with real-time stats, attendance breakdown chart, and weekly trends
- Employee Management (add, edit, delete, search)
- Clock In / Clock Out with live digital clock
- Lunch Start / Lunch End tracking
- Leave Management: Sick Leave, Vacation, Family Emergency, Call-In, No Call No Show
  (Call-In and No Call No Show are auto-approved)
- Day-Off Tracking: Paid, Unpaid, Public Holiday, Personal Day
- Lunch Voucher issuance and tracking (issue, mark used, delete)
- Payroll Calculator with regular/overtime hours, gross/net pay, CSV export
- Activity Log with filtering by action type
- JSON Backup / Restore (full data export and import)
- Data summary and clear-all with confirmation
- Fully responsive (desktop, tablet, mobile)
- Auto-save to localStorage

PRELOADED EMPLOYEES
--------------------
  Crystal Turnquest    — Operations Lead           — $18.00/hr
  Anastasia Morris     — Customer Service Rep      — $14.00/hr
  Britney Green        — Administrative Assistant   — $15.00/hr
  Gaylyn Cox           — Sales Associate           — $14.00/hr
  Demarchka Campbell   — Warehouse Staff            — $13.00/hr
  Arsini Fox           — Accountant                 — $20.00/hr
  Jacqueline Levarity  — HR Coordinator            — $17.00/hr
  Heynis Stuart        — IT Support                — $19.00/hr
  Pawan Kumar          — Maintenance Technician    — $13.00/hr

FILE STRUCTURE
--------------
  Attendance_Manager.html   — The complete application (single file)
  README.txt                — This file
  Sample_Backup.json        — Example backup file for restore testing

BACKUP & RESTORE
----------------
- Export: Go to Backup / Restore → click "Download Backup JSON"
- Import: Go to Backup / Restore → click "Choose JSON File" → select a backup
- WARNING: Importing replaces ALL current data. Export first if unsure.
- The Sample_Backup.json file can be used to test the restore feature.

PAYROLL CALCULATOR
------------------
1. Select a pay period (start and end dates).
2. Click "Calculate" to see per-employee breakdown.
3. Regular hours: up to 8 per day. Overtime: anything over 8/day at 1.5x rate.
4. Click "Export CSV" to download a spreadsheet-compatible file.

BROWSER COMPATIBILITY
---------------------
- Google Chrome 80+
- Microsoft Edge 80+
- Mozilla Firefox 78+
- Safari 14+

DATA STORAGE
------------
All data is stored in your browser's localStorage under the key
"attendanceManagerData". Clearing browser data will erase everything.
Use the Backup / Restore feature regularly to keep external copies.

TROUBLESHOOTING
---------------
- If the page appears blank, try a different browser or disable extensions.
- If data seems missing, check that you haven't cleared browser data.
- If the file won't open, ensure it was saved with the .html extension.
- localStorage has a ~5MB limit per origin. For very large datasets,
  export and archive backups regularly.

================================================================================