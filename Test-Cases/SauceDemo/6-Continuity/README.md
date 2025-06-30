# SauceDemo – Continuity Test Cases

This folder contains a detailed set of **manual test cases** focused on the **hamburger menu** of the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. After logging in, the user is redirected to the product page where they can use the hamburger menu to access different webpages, navigate functionalities, ot reset the state of the application.
These test cases validate the **`logout` button**, **`About` button**, **page redirection**, and the **system's behaviour when resetting the state of the app**. 

## ✅ What Was Tested

The following aspects of the shopping cart were tested:

|Test Case ID                                    |Test Case                                                        |
|-----------------------------------------------|-----------------------------------------------------------------|
|[TC_SD_20](./TC_SD20_CART_CONTINUITY.md)       |Reset app state using the Reset App State Button                 |
|[TC_SD_21](./TC_SD21_MULTI_ITEM_CONTINUITY.md) |Redirecting back to the Products Page using the All Items button | 
|[TC_SD_22](./TC_SD22_CART_RELOG.md)            |Redirecting to external website using About button               |

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

