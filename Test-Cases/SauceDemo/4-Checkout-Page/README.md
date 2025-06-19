# SauceDemo – Checkout Page Test Cases

This folder contains a detailed set of **manual test cases** focused on the **Checkout Page** of the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. The checkout flow represents the final step in the user journey and includes critical data entry for personal and shipping information.

These test cases validate the **input fields**, **error messaging**, **checkout cancellation**, and **completion logic** of the multi-step checkout process.

## ✅ What Was Tested

The following aspects of the Checkout Page were validated:

|Test Case ID                                       |Test Case                                                                        |
|---------------------------------------------------|---------------------------------------------------------------------------------|
|[TC_SD_28](./TC_SD28_CANCEL_INFO_FORM.md)          |Cancelling the Order from the Information Request Form                           |
|[TC_SD_29](./TC_SD29_EMPTY_FIRST_NAME.md)          |Submitting Information Form with Empty First Name Field                          |
|[TC_SD_30](./TC_SD30_EMPTY_LAST_NAME.md)           |Submitting Information Form with Empty Last Name Field                           |
|[TC_SD_31](./TC_SD31_EMPTY_ZIP.md)                 |Submitting Information Form with Empty Zip/Postal Code Field                     |
|[TC_SD_32](./TC_SD32_SPECIAL_CHAR_FIRST_NAME.md)   |Submitting Information Form with Special Characters in the First Name Field      |
|[TC_SD_33](./TC_SD33_SPECIAL_CHAR_LAST_NAME.md)    |Submitting Information Form with Special Characters in the Last Name Field       |
|[TC_SD_34](./TC_SD34_BLANK_FIRST_NAME.md)          |Submitting Information Form with Blankspaces in the First Name Field             |
|[TC_SD_35](./TC_SD35_BLANK_LAST_NAME.md)           |Submitting Information Form with Blankspaces in the Last Name Field              |
|[TC_SD_36](./TC_SD36_BLANK_ZIP.md)                 |Submitting Information Form with Blankspaces in the Zip/Postal Code Field        |
|[TC_SD_37](./TC_SD37_SPECIAL_CHAR_ZIP.md)          |Submitting Information Form with Special Characters in the Zip/Postal Code Field |
|[TC_SD_38](./TC_SD38_SHORT_ZIP.md)                 |Submitting Information Form with a Short Zip                                     |
|[TC_SD_39](./TC_SD39_LONG_ZIP.md)                  |Submitting Information Form with a Long Zip Code                                 |
|[TC_SD_40](./TC_SD40_INVALID_POSTAL_CODE.md)       |Submitting Information Form with an Invalid Postal Code                          |
|[TC_SD_41](./TC_SD41_CHECKOUT_OVERVIEW_DETAILS.md) |Order details in the Checkout Overview Page                                      |
|[TC_SD_42](./TC_SD42_FINISH_ORDER.md)              |Finishing an Order                                                               |

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




