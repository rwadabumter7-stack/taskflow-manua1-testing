# 🚀 TaskFlow - Manual QA Testing Project

## 📌 Project Overview
This repository contains a comprehensive **Manual Testing Artifact** developed for **TaskFlow**, a corporate task management and role distribution system. The goal of this project is to apply structural QA methodologies to validate critical paths, edge cases, and security vulnerabilities within the task creation workflow.

---

## 🛠️ What Was Tested (Scope of Work)
The testing focused heavily on the **Create New Task** modules, tracking both standard and critical operational paths:
1. **Mandatory Field Validations** (Title and description checks).
2. **Boundary Value Analysis (BVA)** on text fields to enforce system character limits.
3. **Date Picker Validation** focusing on preventing illogical past dates and leap-year compliance.
4. **Security Testing on File Uploads** to capture vulnerabilities related to corrupted files (0 KB) and dangerous execution extensions (`.exe`, `.js`).

---

## 📊 Deliverables Included
* **`rwad(1).xlsx`**: The official Test Cases spreadsheet containing **5 high-density test cases**, featuring:
  * Comprehensive steps and pre-conditions.
  * Explicit expected vs. actual behavior mapping.
  * **Conditional Formatting** highlighting passing paths in green and discovered defects (Bugs) in red for maximum scannability.

---

## 🚀 Key QA Skills Demonstrated
* **Test Case Design** (Functional, Negative, and Edge Case testing).
* **Defect Reporting & Severity Mapping**.
* **Understanding of Security Testing Fundamentals** (File type restriction enforcement).
