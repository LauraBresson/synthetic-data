# Synthesizing data

**Datasets**

1. Core HR dataset
2. Total Rewards / payroll dataset *in progress*
3. Position dataset *in progress*
4. Timesheet / attendance dataset *in progress*
5. Talent Acquisition dataset *in progress*
6. performance dataset *in progress*

**Dimension tables**

7. Date dimension table
8. Time dimension table

## HR datasets

**Project overview**

Developing the capability to generate synthetic yet realistic HR data can serve multiple analytical and machine learning purposes as it combines scalability with data privacy. 

**Key features:**
1. Core HR dataset
   - realistic personal and job information
   - realistic and customizable DEI characteristics (age, gender, ethnicity)
   - realistic and customizable tenure, departments and industry distributions
2. Total Rewards / payroll dataset *in progress*
   - realistic personal and job information
   - realistic organizational information
   - payroll cycle dates
   - compensation data (base salary, bonuses, stock options, etc.)
   - payroll adjustments & hours worked
   - Total Rewards data (benefits & non-cash benefits)
3. Position dataset *in progress*
   - realistic personal information
   - realistic organizational information
   - complement status & complement type
   - employment type & job description
   - parent position information
   - vacancy information
4. Timesheet / attendance dataset *in progress*
   - realistic personal information
   - realistic organizational information
   - date and time details (start time, end time, break times)
   - work hours (total hours, regular hours, overtime)
   - work details (project name and/or code, billable vs non-billable hours)
   - supervisor information & approval status
6. Talent Acquisition dataset *in progress*
   - realistic personal contact information
   - professional background (employment history, total experience, education/certifications)
   - skills and qualifications
   - application details
   - assessment data
   - recruitment process tracking
7. performance dataset *in progress*
   - realistic personal information
   - realistic organizational information
   - performance metrics (KPIs per role, performance reviews, eNPS)
   - attendance rates
   - training & development hours 

**Tools used:**
- Python libraries: NumPy, Pandas, Faker, Datetime, Random
- Anaconda's Jupyter Lab notebooks

## Dimension tables

**Project overview**

Essential for data warehouses and for conducting time-series and location-based analysis, dimension tables are surprisingly straightforward to create using Python.

**Key features:**

7. Date dimension table
   - year, quarter, month and day information in number and plain letters format
   - hierarchical date information (e.g., day/week/month/quarter of the year)
   - other calendar frameworks (Julian & epoch time)
   - characterization such as leap year or weekend information
   - seasonality (fiscal & weather-related)

8. Time dimension tables
   - different time formats (ISO, AM/PM, 24h, military)
   - time granularity (hour, minute, second of the day)
   - classification of day (work shifts, time periods, identification of business hours)
