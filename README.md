# Education Management Data Analysis
> Interactive Power BI dashboard to monitor schools, students and assessments — built to surface actionable insights and identify at-risk students quickly.

**Author:** Khushi Agrawal  
**Status:** Portfolio project · Power BI `.pbix` included

---

## 1. Project headline / short description
What if you could spot at-risk students and act in **days** instead of months?  
This Education Management Dashboard consolidates school, student and assessment data into an executive Overview, Student Insights, and Assessment Analysis pages — built for quick decisions, intervention prioritization and performance monitoring.

---

## 2. Purpose
- Provide school leaders and program managers with a single interactive view of student outcomes, assessment effectiveness, and resource allocation.
- Help identify at-risk cohorts early and prioritize interventions.
- Monitor operational KPIs (student counts, teacher counts, average scores, assessment cost) and agent/teacher level metrics.

---

## 3. Tech Stack
The dashboard was built using the following tools and technologies:
- 📊 Power BI Desktop – Primary platform for building interactive dashboards and reports.
- 📂 Power Query – Used for data transformation, cleaning, merging tables, and preparing the final model.
- 🧠 DAX (Data Analysis Expressions) – Created custom measures (Average Score, Assessment Cost, Total Students, Grading Logic, etc.) and dynamic calculations for visuals.
- 🗂️ Data Modeling – Relationships created among tables such as Schools, Students, Teachers, Tests, Assessment Details, and Grading Groups to enable accurate filtering and drilldowns.
- 📁 File Formats – .pbix for the main dashboard file and .png for screenshots used in documentation.
- 🖥️ Power BI Visuals – KPI Cards, Bar Charts, Donut Charts, Slicers, Drilldowns, and Navigation Buttons for an intuitive user experience.

---

## 4. Data Sources
Source: Dataset provided by my mentor for learning and portfolio development.
The data includes anonymized information on schools, students, teachers, assessments, and grading groups. It was structured across multiple tables to simulate a real education management system.

---

## 5. Features / Highlights
- **3 core pages**
  - **Education Overview** — executive KPIs: total schools, total students, total teachers, average score, assessment cost.
  - **Student Insights** — distribution of scores, at-risk cohort identification, filters by school/grade.
  - **Assessment Analysis** — assessment type/group analysis, cost vs performance, grading buckets.
- **Key metrics / measures**
  - `Count of Students`, `Count of Schools`, `Count of Teachers`
  - `Average Score`, `Sum of Standard Score`, `Sum of Assessment Cost`
  - `Tickets`-style running totals (if used for time series), running averages and “closed faster than avg”-style measures
- **Interactivity**
  - Slicers (School, Grade, Assessment Type)
  - Drillthroughs / tooltips for student-level details
  - Clickable KPI cards and bookmarks / action buttons for quick navigation
- **Actionable insights**
  - Rapidly identify at-risk students by score thresholds
  - Compare assessment cost vs impact
  - Visibility over assessment performance by group

---

## 6. Screenshots / Demos
The assets to the repository and reference are here.

**Preview images**
- Overview page (hero KPIs + trend chart): ![Dashboard Preview](https://github.com/khushiagrawal893/Education-Management-Data-Analysis/blob/main/Education%20Performance%20Overview.png)
- Close-up KPI row: ![Dashboard Preview](https://github.com/khushiagrawal893/Education-Management-Data-Analysis/blob/main/Student%20Assessment%20Insights.png)
- Student Insights (score distribution / at-risk cohort)
