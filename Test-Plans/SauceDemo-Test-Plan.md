# 🧪 SauceDemo – Test Plan

## 1. Introduction
This document outlines the test strategy and execution approach for validating the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) e-commerce web application. The site is designed by Sauce Labs for QA practice and demonstration, simulating a basic product catalog, shopping cart, and checkout experience.

---

## 2. Objectives & Scope

### ✅ In Scope
- User login/logout functionality
- Product browsing and sorting
- Adding/removing items to/from cart
- Shopping cart state and item quantity
- Checkout form field validation
- Order completion flow
- Reset App State behavior
- Hamburger menu navigation

### ❌ Out of Scope
- Mobile responsiveness
- Payment gateway testing (no real transaction occurs)
- Backend or API-level testing (handled separately)

---

## 3. Test Types

- ✅ **Manual Functional Testing** – Core business workflows and UI behavior
- ⚠️ **Negative Testing** – Blank fields, invalid data, edge cases
- 🔁 **State Continuity Testing** – Session retention, cart preservation
- 🧪 **Bug Reporting** – Defect documentation with screenshots and traceability
- 🔍 *(Planned)*: API Testing (Postman), Automation (Selenium)

---

## 4. Test Environment

- **Browser:** Google Chrome v137.0.7151.69 (64-bit), Firefox (latest)
- **OS:** Windows 11
- **Display:** 1920x1080 resolution
- **Network:** Standard residential Wi-Fi

---

## 5. Test Deliverables

| Artifact            | Description                               |
|---------------------|-------------------------------------------|
| `/Test-Cases/`      | 40+ detailed manual test cases grouped by module |
| `/Bug-Reports/`     | Documented test failures with screenshots |
| `/Test-Docs/`       | This test plan and future documentation   |
| *(Upcoming)*        | API test cases, Selenium scripts          |

---

## 6. Entry & Exit Criteria

### ✅ Entry Criteria
- Access to SauceDemo website
- Test case framework and folder structure established
- Browser and system compatibility confirmed

### 🛑 Exit Criteria
- All critical test cases executed
- All high/medium severity bugs logged
- All documentation complete and reviewed

---

## 7. Timeline

| Date        | Task                         |
|-------------|------------------------------|
| Week 1      | Manual test case writing & execution |
| Week 2      | Bug reports & Test Plan creation |
| Week 3      | API Testing with Postman (planned) |
| Week 4      | Selenium automation setup (planned) |

---

## 8. Roles & Responsibility

| Role             | Name         | Responsibility                |
|------------------|--------------|-------------------------------|
| QA Analyst       | Erik Lagman  | Test design, execution, reporting |
| Documentation    | Erik Lagman  | Test Plan, Bug Reports        |
| Automation Dev   | Erik Lagman  | Selenium Scripting (upcoming) |

