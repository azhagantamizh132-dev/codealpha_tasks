# codealpha_task

 **Educational Performance & Resource Allocation – Power BI Dashboard**

**Overview**

This project presents a comprehensive **two-page Power BI dashboard** designed to analyze both **student academic performance** and **institutional resource allocation**. The goal is to enable **data-driven decision-making**, improve academic outcomes, and optimize resource utilization within an educational institution.

The project uses expert-level synthetic datasets that include:

* 60 students
* Multiple subjects
* Two academic terms
* Attendance & assignment metrics
* Resource consumption across 7 departments
* Cost & utilization data for 7 resource types

---

#  **Project Structure**

```
📁 powerbi-education-dashboard
│
├── 📄 student_performance_expert.csv
├── 📄 resource_allocation_expert.csv
├── 📄 dashboard.pbix              # (Your Power BI file)
├── 📄 README.md
└── 📁 /images                     # (Optional screenshots)
```

 **Dashboard Summary**

The Power BI report consists of **two pages**, each targeting a specific analytical need.


# 📄 **PAGE 1 — Student Performance Dashboard**

This dashboard focuses on identifying academic patterns, trends, and areas of concern in student outcomes.

## 🔍 **Key Features**

### ✔ **Student KPIs**

* Total number of students
* Average marks across subjects
* Average attendance
* Assignment completion percentage

### ✔ **Visual Insights**

* **Subject-Wise Average Marks**
  Compares academic performance across subjects to identify strengths and weaknesses.

* **Class-Wise Performance**
  Evaluates differences between Grade 9, Grade 10, and Grade 11.

* **Term Comparison Analysis**
  Shows improvement or decline from Term 1 to Term 2.

* **Attendance by Subject**
  Helps correlate attendance with academic outcomes.

* **Student Performance Details Table**
  Provides student-level insights for teachers and academic heads.

### 🎯 **Objective**

Enable academic staff to monitor performance gaps, track progress, and make informed curriculum or intervention decisions.



# 📄 **PAGE 2 — Resource Allocation & Gap Analysis Dashboard**

This dashboard analyzes how effectively resources are distributed and utilized across institutional departments.

## 🔍 **Key Features**

### ✔ **Resource KPIs**

* Total cost of resources
* Total resources available
* Total resources used
* Utilization percentage

### ✔ **Visual Insights**

* **Department-Wise Resource Usage**
  Highlights usage patterns and helps identify potential bottlenecks.

* **Available vs. Used (Shortage Detection)**
  Helps detect overuse or inventory shortages for each resource type.

* **Resource Type Distribution**
  Shows allocation of teachers, classrooms, computers, books, etc.

* **Cost by Department**
  Reveals spending patterns and budget-heavy departments.

* **Resource Matrix**
  A detailed overview of allocation and usage across resource types and departments.

### 🎯 **Objective**

Support administrators in resource planning, cost control, and identifying departments that require optimization or funding.


# 📊 **Datasets**

## 📁 **1. Student Performance Dataset**

**File:** `student_performance_expert.csv`
**Rows:** ~1440
**Columns:**

| Column               | Description                     |
| -------------------- | ------------------------------- |
| StudentID            | Unique ID for each student      |
| Name                 | Student name                    |
| Class                | Grade 9/10/11                   |
| Subject              | Class subject                   |
| Term                 | Academic term (Term 1 / Term 2) |
| Marks                | Student score in the subject    |
| AttendancePercent    | Attendance percentage           |
| AssignmentsCompleted | Number of assignments completed |
| MaxAssignments       | Total assignments               |

---

## 📁 **2. Resource Allocation Dataset**

**File:** `resource_allocation_expert.csv`
**Rows:** 49
**Columns:**

| Column            | Description                                        |
| ----------------- | -------------------------------------------------- |
| ResourceID        | Unique ID for each resource item                   |
| ResourceType      | Teacher, Classroom, Budget, Books, Computers, etc. |
| Department        | Science, Math, IT, Library, etc.                   |
| QuantityAvailable | Total resources available                          |
| QuantityUsed      | Resources currently used                           |
| Cost              | Resource cost                                      |


# 🛠 **Technologies Used**

| Tool                 | Purpose                             |
| -------------------- | ----------------------------------- |
| **Power BI Desktop** | Dashboard creation                  |
| **DAX**              | Measures and calculations           |
| **CSV**              | Data storage                        |
| **Git & GitHub**     | Version control and project hosting |



