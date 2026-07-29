# 📝 ToDo List Application — QA Documentation

<p align="center">
  <img src="https://img.shields.io/badge/QA-Manual%20Testing-2E75B6?style=for-the-badge" alt="QA Manual Testing"/>
  <img src="https://img.shields.io/badge/Test%20Cases-40-1F3864?style=for-the-badge" alt="Test Cases"/>
  <img src="https://img.shields.io/badge/Pass%20Rate-90%25-1E7A34?style=for-the-badge" alt="Pass Rate"/>
  <img src="https://img.shields.io/badge/Open%20Bugs-4-B00020?style=for-the-badge" alt="Open Bugs"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=flat-square" alt="Version"/>
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square" alt="License"/>
  <img src="https://img.shields.io/badge/Made%20with-Excel%20%7C%20Word-orange?style=flat-square" alt="Made with"/>
</p>

> 📌 Complete QA deliverables for the **ToDo List Application** — test plan, manual test cases, bug reports, and a test summary report, produced as part of a manual testing / QA engineering practice cycle.

---

## 📂 Repository Contents

| 📄 File | 📋 Description |
|---|---|
| `Test-Plan.docx` | Software Test Plan — scope, approach, environment, and schedule |
| `Test-Cases.xlsx` | 40 manual test cases across 6 modules with steps, expected/actual results |
| `ManualTest-ToDoApp-ExactMatchingBorders_v4.xlsx` | Bug report sheet — defects logged from failed test cases |
| `Test-Summary-Report.docx` | Final QA summary — results, defect breakdown, and recommendations |

---

## 🎯 Project Overview

The **ToDo List Application** is a task management web app supporting user registration, login, and full task CRUD functionality. This repository documents the **manual QA testing cycle** performed against it, following a structured test plan and reporting process.

---

## ✅ Test Execution Summary

<p align="center">
  <img src="https://img.shields.io/badge/Total%20Test%20Cases-40-1F3864?style=flat-square"/>
  <img src="https://img.shields.io/badge/Passed-36-1E7A34?style=flat-square"/>
  <img src="https://img.shields.io/badge/Failed-4-B00020?style=flat-square"/>
  <img src="https://img.shields.io/badge/Pass%20Rate-90%25-2E75B6?style=flat-square"/>
</p>

| 🧩 Module | Total | ✅ Passed | ❌ Failed | Pass Rate |
|---|---|---|---|---|
| Authentication | 23 | 22 | 1 | 96% |
| Task Management | 6 | 5 | 1 | 83% |
| Backend | 5 | 5 | 0 | 100% |
| Home Page | 2 | 2 | 0 | 100% |
| Performance | 2 | 2 | 0 | 100% |
| Layout | 2 | 0 | 2 | 0% |

---

## 🐞 Defect Summary

| Bug ID | Module | Severity | Status |
|---|---|---|---|
| `BUG-001` | Authentication | 🔴 Critical | 🟥 Open |
| `BUG-002` | Task Management | 🟠 High | 🟥 Open |
| `BUG-003` | Layout | 🟡 Low | 🟥 Open |
| `BUG-004` | Layout | 🟡 Low | 🟥 Open |

> ⚠️ The **Layout** module has a 0% pass rate and needs attention before release. Priority fixes: `BUG-001` (Critical) and `BUG-002` (High).

---

## 🧪 Testing Approach

- **Type:** Manual (black-box) functional testing
- **Technique:** Equivalence partitioning & boundary value analysis
- **Modules covered:** Authentication, Task Management, Backend/Database, Home Page, Layout & Responsiveness, Performance
- **Tools used:**

<p align="left">
  <img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Word-2B579A?style=flat-square&logo=microsoftword&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB%20Atlas-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
</p>

---

## 📊 Deliverables Workflow

```
Test Plan  →  Test Case Design  →  Test Execution  →  Bug Reporting  →  Test Summary Report
```

---

## 👩‍💻 Author

**Hadeel Qodseya**
QA / Manual Testing • Front-End Development • UX/UI Design

<p align="left">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Behance-1769FF?style=flat-square&logo=behance&logoColor=white"/>
</p>

---

<p align="center"><i>⭐ If this documentation was helpful, consider starring the repo!</i></p>
