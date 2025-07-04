InOffice Attendance & Payroll System

Files included:
- app_updated_with_backup.py: Main Streamlit application.
- data/employees.csv: Sample employee list.
- data/attendance.csv: Sample attendance data.
- data/advance_cash.csv: Sample advance loan data.
- backup/: Folder where backups will be created automatically.

How to Run:
1. Install Streamlit: pip install streamlit pandas
2. Run: streamlit run app_updated_with_backup.py
3. Login as:
   - Username: admin | Password: admin123
   - Username: hr    | Password: hr123

The app will automatically back up data each time you save.

Monthly Snapshots:
- Each time you save attendance, employees, or advance cash, a monthly snapshot is saved in `monthly_snapshots/`.
- Format: employees_YYYY-MM.csv, attendance_YYYY-MM.csv, advance_cash_YYYY-MM.csv