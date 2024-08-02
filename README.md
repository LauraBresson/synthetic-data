# Synthesizing data

**Datasets**
1. Core demographic HR dataset
2. Total Rewards dataset
3. Attrition dataset

**Dimension tables**
4. Date dimension table
5. Time dimension table
6. Geographical dimension table

## HR datasets

**Project overview**

Developing the capability to generate synthetic yet realistic HR data can serve multiple analytical and machine learning purposes as it combines scalability with data privacy. 

**Key features:**
1. Core HR data
   - realistic age and tenure distribution
   - customizable gender and ethnicity distributions
   - customizable departmenta / industries
2. Total Rewards data
   - base salary
   - bonuses
   - stock options
   - other benefits (health insurance, retirement contributions)
3. Attrition data
   - employee and employment attributes
   - performance ratings
   - binary attrition status for supervised learning purposes

**Tools used:**
- Python libraries: NumPy, Pandas, Faker, Datetime, Random
- Anaconda's Jupyter Lab notebooks

## Dimension tables

**Project overview**

Essential for data warehouses and for conducting time-series and location-based analysis, dimension tables are surprisingly straightforward to create using Python.

**Key features:**

4. Date dimension table
   - year, quarter, month and day information in number and plain letters format
   - hierarchical date information (e.g., day/week/month/quarter of the year)
   - other calendar frameworks (Julian & epoch time)
   - characterization such as leap year or weekend information
   - seasonality (fiscal & weather-related)

5. Time dimension tables
   - different time formats (ISO, AM/PM, 24h, military)
   - time granularity (hour, minute, second of the day)
   - classification of day (work shifts, time periods, identification of business hours)

7. Canadian geographical dimension tables (*in progress*)
