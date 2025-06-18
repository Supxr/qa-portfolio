# SauceDemo – Checkout Page Test Cases

This folder contains a detailed set of **manual test cases** focused on the **Checkout Page** of the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. The checkout flow represents the final step in the user journey and includes critical data entry for personal and shipping information.

These test cases validate the **input fields**, **error messaging**, **checkout cancellation**, and **completion logic** of the multi-step checkout process.

## ✅ What Was Tested

The following aspects of the Checkout Page were validated:

|Test Case ID |Test Case                                                |Description  |
|-------------|---------------------------------------------------------|-------------|
|TC_SD_28     |Required field validation                                | (first name, last name, postal code)|
|TC_SD_29     |Blank fields                                             | Sample Text |
|TC_SD_30     |Special characters                                       | Sample Text |
|TC_SD_31     |Numeric and string length limits                         | Sample Text |
|TC_SD_32     |Checkout overview accuracy (item summary before payment) | Sample Text |
|TC_SD_33     |Successful and canceled checkout flows                   | Sample Text |
|TC_SD_34     |Error messages and user feedback                         | Sample Text |
|TC_SD_35     |Final order confirmation screen                          | Sample Text |

> 🧪 **Total Test Cases:** 15  
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

- These test cases assume the user has already logged in and added items to the cart.
- Tests were performed on **Google Chrome Version 137.0.7151.69 (64-bit)**.
- This test set does not include automated or API-based tests.



