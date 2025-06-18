# SauceDemo – Checkout Page Test Cases

This folder contains a detailed set of **manual test cases** focused on the **Checkout Page** of the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. The checkout flow represents the final step in the user journey and includes critical data entry for personal and shipping information.

These test cases validate the **input fields**, **error messaging**, **checkout cancellation**, and **completion logic** of the multi-step checkout process.

## ✅ What Was Tested

The following aspects of the Checkout Page were validated:

|Test Case ID                                       |Test Case                                                |Description  |
|---------------------------------------------------|---------------------------------------------------------|-------------|
|[TC_SD_28](./TC_SD28_CANCEL_INFO_FORM.md)          |Cancelling the Order from the Information Request Form   | (first name, last name, postal code)|
|[TC_SD_29](./TC_SD29_EMPTY_FIRST_NAME.md)          |Blank fields                                             | Sample Text |
|[TC_SD_30](./TC_SD30_EMPTY_LAST_NAME.md)           |Special characters                                       | Sample Text |
|[TC_SD_31](./TC_SD31_EMPTY_ZIP.md)                 |Numeric and string length limits                         | Sample Text |
|[TC_SD_32](./TC_SD32_SPECIAL_CHAR_FIRST_NAME.md)   |Checkout overview accuracy (item summary before payment) | Sample Text |
|[TC_SD_33](./TC_SD33_SPECIAL_CHAR_LAST_NAME.md)    |Successful and canceled checkout flows                   | Sample Text |
|[TC_SD_34](./TC_SD34_BLANK_FIRST_NAME.md)          |Error messages and user feedback                         | Sample Text |
|[TC_SD_35](./TC_SD35_BLANK_LAST_NAME.md)           |Final order confirmation screen                          | Sample Text |
|[TC_SD_36](./TC_SD36_BLANK_ZIP.md)                 |Error messages and user feedback                         | Sample Text |
|[TC_SD_37](./TC_SD37_SPECIAL_CHAR_ZIP.md)          |Final order confirmation screen                          | Sample Text |
|[TC_SD_38](./TC_SD38_SHORT_ZIP.md)                 |Error messages and user feedback                         | Sample Text |
|[TC_SD_39](./TC_SD39_LONG_ZIP.md)                  |Final order confirmation screen                          | Sample Text |
|[TC_SD_40](./TC_SD40_INVALID_POSTAL_CODE.md)       |Error messages and user feedback                         | Sample Text |
|[TC_SD_41](./TC_SD41_CHECKOUT_OVERVIEW_DETAILS.md) |Final order confirmation screen                          | Sample Text |
|[TC_SD_42](./TC_SD42_FINISH_ORDER.md)              |Final order confirmation screen                          | Sample Text |

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



