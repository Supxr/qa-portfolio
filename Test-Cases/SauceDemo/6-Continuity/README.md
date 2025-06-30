# SauceDemo – Continuity Test Cases

This folder contains a detailed set of **manual test cases** focused on the **state continuity** of the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. These test cases validate the shopping cart's **state persistence** when navigating between pages with a single or multiple items, and logging out and back into the website.

## ✅ What Was Tested

The following aspects of the shopping cart were tested:

|Test Case ID                                   |Test Case                                            |
|-----------------------------------------------|-----------------------------------------------------|
|[TC_SD_20](./TC_SD20_CART_CONTINUITY.md)       |Shopping Cart Continuity Between Pages               |
|[TC_SD_21](./TC_SD21_MULTI_ITEM_CONTINUITY.md) |Shopping Cart Continuity with Multiple Items Present | 
|[TC_SD_22](./TC_SD22_CART_RELOG.md)            |Shopping Cart State After Relogging Into Website     |

> 🧪 **Total Test Cases:** 3  
> 👁️ All tests are documented in individual `.md` files following a consistent format.

## 🧪 Test Case Format

Each test case follows this structure:
- **Test Case Name**
- **Test Case ID**
- **Test Objective**
- **Preconditions**
- **Test Steps**
- **Expected Result**
- **Actual Result**
- **Pass/Fail Status**

## 📄 Notes

- Tests were performed on **Google Chrome Version 137.0.7151.69 (64-bit)**.
- This test set does not include automated or API-based tests.

