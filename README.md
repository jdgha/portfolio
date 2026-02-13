# Data Professional

#### Technical Skills: Python, SQL, Data Analysis, Data Visualization, R, JavaScript, CSS, HTML, Pandas, Matplotlib, Seaborn, Tableau, Project Management, Product Management, Problem Solving, Fast Paced Detail Oriented Multitasking

## Education
-CodeCademy - Data Scientist: Analytics
- CodeCademy - Business Intelligence Data Analyst Certificate
- Google - Data Analytics Career Certificate
- B.A., Sociology - Hiram College

## Work Experience
**Operations Project Manager (Data Analytics & Reporting)<br/>Audience Rewards (_January 2024 - Present_)**
- Own production data validation across customer transactions, loyalty points, and partner data feeds.
- Investigated and corrected 1M+ missing loyalty points by analyzing transactional discrepancies using Python, mitigating financial and customer impact.
- Perform ad hoc and recurring analyses on sales, bonus incentives, and customer behavior to support operational and leadership decisions.
- Analyze marketing A/B test results to evaluate performance and inform campaign adjustments.
- Partner with engineering and data leadership to troubleshoot pipeline and reporting inconsistencies.
- Build Python notebooks to automate recurring reconciliation tasks and reduce manual effort.
- Serve as Jira administrator, redesigning workflows and improving issue visibility across technical teams.
- In addition to core responsibilities, regularly support the Data function with ad hoc analysis, validation, and reconciliation initiatives


**Clinic Launch Manager (Technical Operations & Data Quality)<br/>Bond Vet (_March 2021 - September 2023_)**
- Led 10+ operational launches, tracking KPIs and post-launch performance metrics.
- Built dashboards to monitor execution, issue trends, and financial performance indicators.
- Conducted root cause analysis on operational bottlenecks and implemented process improvements.
- Coordinated cross-functionally with Product/Tech, Finance, Marketing, HR, and executive teams.


## Projects
### [Bonus Audit](https://github.com/jdgha/portfolio/blob/main/BonusAudit.ipynb)
Weekly task to capture bonus build or programming errors. Combines three documents:
1. Manually edited google sheet (regularly updated)
2. Sales data (pulled from databricks
3. An existing excel output file to track the outcome of this audit - in this file exists additional formulas to calculate accuracy. This file is manually updated with accurate data from the above google sheet to ensure up to date data on a weekly basis


Notebook provides code for date/time format to prevent errors, files to data frames, row indexing to separate shows by name, etc. Show names and associated bonuses are added to the existing excel document manually for the code to paste starting in the correct locations, as well as create a summary of an error count (on each tab and into a new "summary" tab) to be manually checked after the notebook runs. Moving this process from manual to a notebook shortened the time needed to about 1/6th.

### [Bonus Analysis](https://github.com/jdgha/portfolio/blob/main/BonusAnylsis.ipynb)

Ad hoc request from the marketing team to provide analysis of bonus performance. Differing amounts of bonus points are awarded to members based on purchase criteria (start date, end date, time, minimum price, maximum price, etc.) and performance criteria (start date, end date, valid days of the week, blackout dates, etc.). Request could come in after bonus purchase window has closed (full analysis) or during the purchase window (partial analysis). Notebook provides summary of average ticket price, yield of ticket price over industry average, total bonus sales, cost to the buyer (based on rates of main loyalty currency and partner points currency) (total sales - cost = ROI), and additional days of the week included at the bottom of the analysis to track trends during days of the week if applicable. 
