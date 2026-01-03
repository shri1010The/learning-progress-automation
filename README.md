# learning-progress-automation
# Learning Progress & Assessment Validation System

## 📌 Project Overview
This project is a **Python-based SDET automation framework** designed to validate **learning progress, quiz evaluation, and certificate eligibility** in an e-learning platform.

The framework follows a **real-world, API-first testing approach**, with **minimal UI automation** to ensure frontend-backend consistency — exactly how mature QA/SDET teams operate.

---

## 🎯 Why This Project Matters

✔ Not a generic login / todo / ecommerce project  
✔ Based on real **LMS business workflows**  
✔ API-first → faster, stable, scalable tests  
✔ Demonstrates **SDET thinking**, not just tool usage  

---

## 🧠 Real-Life Scenarios Covered

### Scenario 1: Successful Certification Flow
- Learner completes all modules
- Progress reaches 100%
- Quiz score ≥ 60%
- Certificate becomes available

### Scenario 2: Quiz Failure Handling
- Quiz score < 60 → fail
- Certificate remains disabled
- Maximum 2 quiz attempts allowed

### Scenario 3: System Protection Rules
- Progress never exceeds 100%
- Quiz blocked after maximum attempts
- Invalid inputs handled gracefully

---

## 🧩 Business Rules Validated
- Progress updates only after module completion
- Pass percentage fixed at 60%
- Maximum quiz attempts = 2
- Certificate enabled only when:
  - Progress = 100%
  - Quiz is passed

---

## 🛠 Tech Stack
- **Language:** Python 3.x
- **Test Framework:** Pytest
- **API Automation:** Requests
- **UI Automation:** Playwright (minimal usage)
- **Design Pattern:** Page Object Model + API Client Layer
- **Reporting:** Pytest HTML / Allure (optional)

---

## 📁 Project Structure
