# HR Analytics & Workforce Intelligence

## 📌 Project Overview

HR Analytics & Workforce Intelligence is an interactive Power BI project
designed to analyze employee and HR-related data.

The dashboard brings together employee information, recruitment,
attendance, leave, performance, training, compensation, and attrition
data in one place.

The main goal is to help HR teams understand workforce trends and
monitor important HR metrics through interactive dashboards.

---

## 🎯 Project Objectives

- Analyze employee demographics and workforce distribution
- Monitor recruitment and hiring performance
- Analyze employee performance and development
- Understand attendance and leave patterns
- Analyze salary, bonus, and salary hikes
- Identify employee exit and attrition patterns
- Provide interactive HR dashboards for analysis

---

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Git / GitHub
- Git LFS

---

## 📊 Dataset

The project uses multiple related HR tables covering:

- Employee information
- Departments
- Job roles
- Locations
- Attendance
- Leave
- Performance
- Compensation
- Training
- Recruitment
- Employee exits
- Date information

The dataset contains **500 employees** and supporting records across
multiple HR processes.

---

## 🧹 Data Preparation

Power Query was used to prepare the data before creating the dashboard.

Main activities included:

- Removing duplicate records
- Cleaning extra spaces
- Standardizing text values
- Correcting inconsistent spellings
- Converting columns to appropriate data types
- Handling meaningful missing values
- Creating relationships between tables

---

## 📈 Dashboard Pages

### 1. Executive Dashboard

Provides an overall view of workforce and HR metrics.

Includes:

- Total employees
- Attrition rate
- Average salary
- Total bonus
- High performers
- Recruitment metrics
- Department analysis
- Attendance analysis

### 2. Recruitment & Hiring

Analyzes:

- Applications
- Hiring
- Hiring rate
- Recruitment sources
- Interview scores
- Application status
- Offer status
- Joining status
- Hiring trends

### 3. Performance & Employee Development

Analyzes:

- Performance ratings
- Goal achievement
- Manager ratings
- High performers
- Promotion eligibility
- Training hours
- Training scores
- Training cost

### 4. Attendance & Leave Analytics

Analyzes:

- Attendance rate
- Absent days
- Late days
- Work-from-home days
- Leave types
- Leave status
- Attendance trends
- Leave trends

### 5. Compensation & Salary Analytics

Analyzes:

- Average salary
- Total salary
- Bonus
- Salary hike
- Salary by department
- Salary by job role
- Compensation trends

Also includes a **What-if parameter** to analyze projected salary
after a selected salary increase.

### 6. Employee Overview & Workforce Demographics

Analyzes:

- Total employees
- Active employees
- Gender distribution
- Job levels
- Departments
- Locations
- Age distribution
- Workforce trends

### 7. HR Insights & Advanced Analytics

Analyzes:

- Employee exits
- Exit reasons
- Exit types
- Attrition trends
- Notice periods

Advanced Power BI visuals include:

- Decomposition Tree
- Key Influencers

### 8. Employee Details

Provides employee-level information using:

- Drill-through
- Employee details table
- Salary information
- Performance information
- Training information
- Leave information

---

## 🔧 Power BI Features Used

- DAX Measures
- Power Query
- Interactive Slicers
- What-if Parameters
- Field Parameters
- Drill-through
- Report Page Tooltips
- Decomposition Tree
- Key Influencers
- Row-Level Security (RLS)

---

## 📌 Key KPIs

| Area | KPIs |
|---|---|
| Workforce | Total Employees, Active Employees |
| Recruitment | Applications, Hired Candidates, Hiring Rate |
| Performance | Average Performance Rating, High Performers |
| Attendance | Attendance Rate, Absent Days, Late Days |
| Training | Training Hours, Training Score, Training Cost |
| Compensation | Average Salary, Total Salary, Total Bonus |
| Attrition | Total Exits, Attrition Rate, Average Notice Period |

---

## 🔐 Row-Level Security

Row-Level Security was implemented in Power BI using an
**HR Department** role.

This demonstrates how report access can be restricted based on
department-level data.

---

## 📷 Dashboard Preview

Screenshots of the dashboard are available in the
`Screenshots` folder.

---

## 📁 Project Structure

```text
HR_Analytics_Workforce_Intelligence/
│
├── Dataset/
│   └── HR_Analytics_Dataset.xlsx
│
├── Documentation/
│   └── Project_Overview.pdf
│
├── PowerBI/
│   └── HR_Analytics_Workforce_Intelligence.pbix
│
├── Screenshots/
│   └── Dashboard screenshots
│
└── README.md
