# SauceDemo – Hamburger Menu Test Cases

This folder contains a detailed set of **manual test cases** focused on the **hamburger menu** of the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. After logging in, the user is redirected to the product page where they can use the hamburger menu to access different webpages, navigate functionalities, ot reset the state of the application.
These test cases validate the **`logout` button**, **`About` button**, **page redirection**, and the **system's behaviour when resetting the state of the app**. 

## ✅ What Was Tested

The following aspects of the shopping cart were tested:

|Test Case ID                             |Test Case                                                        |
|-----------------------------------------|-----------------------------------------------------------------|
|[TC_SD_07](./TC_SD07_RESET_APP_STATE.md) |Reset app state using the Reset App State Button                 |
|[TC_SD_17](./TC_SD17_ALL_ITEMS.md)       |Redirecting back to the Products Page using the All Items button | 
|[TC_SD_18](./TC_SD18_ABOUT_BUTTON.md)    |Redirecting to external website using About button               |
|[TC_SD_19](./TC_SD19_LOGOUT.md)          |Logging Out Using the Logout Button in the Hamburger Menu        |

> 🧪 **Total Test Cases:** 4  
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
