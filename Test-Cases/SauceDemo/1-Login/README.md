# SauceDemo – Login Page Test Cases

This folder contains a detailed set of **manual test cases** focused on the **Login** of the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. The login flow allows the user to input user information in order to access the product page of the website. 
These test cases validate the **input fields**, **valid credential responses**, **invalid credential responses**, **valid/invalid/empty/blank credential combinations**, **login button functionality**, and **suspended credential responses** during the website login process.

## ✅ What Was Tested

The following aspects of the Login page were tested:

|Test Case ID                            |Test Case                                             |
|----------------------------------------|------------------------------------------------------|
|[TC_SD_01](./TC_SD01_LOGIN_SUCCESS.md)  |Successful Login with Valid Credentials               |
|[TC_SD_02](./TC_SD02_INCORRECT_PW.md)   |Unsuccessful Login Attempt With Incorrect Password    |
|[TC_SD_03](./TC_SD03_BLANK_FIELDS.md)   |Login Attempt Using Blank Username/Password           |
|[TC_SD_04](./TC_SD04_BLANK_USERNAME.md) |Login Attempt with Blank Username and Valid Password  |
|[TC_SD_05](./TC_SD05_BLANK_PASSWORD.md) |Login Attempt Using Valid Username and Blank Password |
|[TC_SD_06](./TC_SD06_SUSPENDED_USER.md) |Login Attempt Using Suspended Credentials             |

> 🧪 **Total Test Cases:** 6  
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





