# Synthesizing Data

**Project Overview**

Developing the capability to generate synthetic yet realistic datasets serves multiple purposes, including but not limited to
- pay equity audit enablement: developing and validating pay equity audit pipelines, enabling BI and HR analytics teams to build bias-detection workflows in a zero-PII (personal identifiable information) environment
- ERP system implementation: safe testing data, enabling functional QA of modules and environments prior to production deployment
- AI output testing: more and more AI models are integrated into entreprise decision-making, leading to an increased need for validation of their output via datasets with configurable biases or flaws

**Datasets & Key Features:**
1. Core HR dataset with configurable scenarios
   - realistic personal and job information
   - realistic and customizable DEI characteristics (age, gender, ethnicity)
   - realistic and customizable tenure, departments and industry distributions
2. Total Rewards / payroll dataset (*in progress*)
   - realistic personal and job information
   - realistic organizational information
   - payroll cycle dates
   - compensation data (base salary, bonuses, stock options, etc.)
   - payroll adjustments & hours worked
   - Total Rewards data (benefits & non-cash benefits)
3. Timesheet / attendance dataset (*in progress*)
   - realistic personal information
   - realistic organizational information
   - date and time details (start time, end time, break times)
   - work hours (total hours, regular hours, overtime)
   - work details (project name and/or code, billable vs non-billable hours)
   - supervisor information & approval status

**Tools used:**
- Python libraries: NumPy, Pandas, Faker, Datetime, Random
- Anaconda's Jupyter Lab notebooks
