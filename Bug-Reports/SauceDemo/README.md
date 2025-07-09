# SauceDemo – Bug Reports

This folder contains a curated collection of **bug reports** based on test execution against the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. The reports document functional and UI-related issues found during manual testing across key modules of the application.

SauceDemo is a sample e-commerce site created by [Sauce Labs](https://saucelabs.com/) to support QA practice and demonstration. These reports reflect both **real test failures** and **simulated defects** based on expected behavior in standard e-commerce platforms.

---

## Scope of Bugs

| Category                | Examples Included                                  |
|-------------------------|----------------------------------------------------|
| **Cart Behavior**       | Immutable quantity field, empty checkout flow      |
| **Checkout Validation** | Blank and special character inputs across fields   |
| **ZIP Code Rules**      | Edge cases for short, long, or invalid ZIP entries |
| **App State Handling**  | Failure to clear cart state after reset            |

---

## Folder Structure
Bug-Reports/<br>
└── SauceDemo/<br>
├── SD_BUG_01_IMMUTABLE_QUANTITY.md<br>
├── SD_BUG_02_EMPTY_CHECKOUT.md<br>
├── SD_BUG_03_SPEC_CHAR_FIRST_NAME.md<br>
├── SD_BUG_04_SPEC_CHAR_LAST_NAME.md<br>
├── SD_BUG_05_BLANK_FIRST_NAME.md<br>
├── SD_BUG_06_BLANK_LAST_NAME.md<br>
├── SD_BUG_07_BLANK_ZIP.md<br>
├── SD_BUG_08_SPECIAL_CHAR_ZIP.md<br>
├── SD_BUG_09_SHORT_ZIP.md<br>
├── SD_BUG_10_LONG_ZIP.md<br>
├── SD_BUG 11_INVALID_POSTAL_CODE.md<br>
├── SD_BUG_12_RESET_APP_STATE.md<br>

> 💡 Bug reports are organized using the `SD_BUG_##_TITLE.md` naming convention.

---
## Format

Each bug report follows a consistent format:
- **Bug ID**
- **Title**
- **Severity / Priority**
- **Environment details**
- **Link to related test case**
- **Description**
- **Preconditions**
- **Steps to Reproduce**
- **Expected vs Actual Result**
- **Attachments (Screenshots, if any)**
- **Additional Notes (if any)**

---

## 📎 Notes

- **12 legitimate bugs** are currently documented and traceable to related test cases.
- All bugs were tested manually on **Google Chrome 137.0.7151.69 (64-bit)** on **Windows 10/11**.
- Some reported bugs may be intentional
