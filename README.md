# Data Professional

#### Technical Skills: Python, SQL, Data Analysis, Data Visualization, R, JavaScript, CSS, HTML, Pandas, Matplotlib, Seaborn, Tableau, Project Management, Product Management, Problem Solving, Fast Paced Detail Oriented Multitasking

## Education
- CodeCademy - Business Intelligence Data Analyst Certificate
- Google - Data Analytics Career Certificate
- B.A., Sociology - Hiram College

## Work Experience
**Operations Project Manager (Data Analytics & Reporting)<br/>Audience Rewards (_January 2024 - Present_)**
- Ensured with 99% accuracy members earned eligible bonus points based on spend criteria on a weekly basis
- ETL, cleaning & processing member transactions to provide data for decision processes
- Developed and documented SOPs for company wide digital playbook
- Successfully migrated 5 million+ members to a new third party front and backend platform
- Launched product improvements enabling cross functional teams to enhance the customer experience without increasing workload
- Overhauled and maintained a company wide Jira - effectively alleviating 90%+ tech debt
- Led process improvements and project management initiatives using data-driven decision-making and performance analysis.
- Managed the launch of the Official Tony Awards Challenge with no negative impact to user experience year over year

**Clinic Launch Manager (Technical Operations & Data Quality)<br/>Bond Vet (_March 2021 - September 2023_)**
- Led the launch of over 10 veterinary clinics in a time-critical, high-stakes operational
environment, serving as the primary escalation point during go-live weeks.
- Built and standardized SOPs for the clinic launch process and introduced dashboards to
track readiness, execution, and post-launch issues.
- Improved launch execution by making processes more predictable and less error-prone
through data-driven visibility and operational refinement.
- Managed external vendors during launch and coordinated cross-functionally with Real
Estate, Facilities, Design, Marketing, HR, Legal, Product/Tech, and executive leadership.

## Projects
### [Bonus Audit](https://github.com/jdgha/portfolio/blob/main/BonusAudit.ipynb)
Weekly task to capture bonus build or programming errors. Combines three documents:
1. Manually edited google sheet (regularly updated)
2. Sales data (pulled from databricks
3. An existing excel output file to track the outcome of this audit - in this file exists additional formulas to calculate accuracy. This file is manually updated with accurate data from the above google sheet to ensure up to date data on a weekly basis


Notebook provides code for date/time format to prevent errors, files to data frames, row indexing to separate shows by name, etc. Show names and associated bonuses are added to the existing excel document manually for the code to paste starting in the correct locations, as well as create a summary of an error count (on each tab and into a new "summary" tab) to be manually checked after the notebook runs. Moving this process from manual to a notebook shortened the time needed to about 1/6th.

### [Bonus Analysis](https://github.com/jdgha/portfolio/blob/main/BonusAnylsis.ipynb)

Ad hoc request from the marketing team to provide analysis of bonus performance. Differing amounts of bonus points are awarded to members based on purchase criteria (start date, end date, time, minimum price, maximum price, etc.) and performance criteria (start date, end date, valid days of the week, blackout dates, etc.). Request could come in after bonus purchase window has closed (full analysis) or during the purchase window (partial analysis). Notebook provides summary of average ticket price, yield of ticket price over industry average, total bonus sales, cost to the buyer (based on rates of main loyalty currency and partner points currency) (total sales - cost = ROI), and additional days of the week included at the bottom of the analysis to track trends during days of the week if applicable. 
