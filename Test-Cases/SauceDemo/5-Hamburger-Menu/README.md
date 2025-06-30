# SauceDemo – Shopping Cart Test Cases

This folder contains a detailed set of **manual test cases** focused on the **Shopping cart** of the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. After logging in, the user is redirected to the product page where they can browse through the product gallery and select items to add to or remove from the shopping cart. Once in the shopping cart page, the user will have the option to add or remove items, continue shopping, or checkout. 
These test cases validate the **`Continue Shopping` button**, **product addition/removal functionality**, **`Checkout` button**, and **system behavior when attempting to check out with an empty cart**. 

## ✅ What Was Tested

The following aspects of the shopping cart were tested:

|Test Case ID                                        |Test Case                                                       |
|----------------------------------------------------|----------------------------------------------------------------|
|[TC_SD_23](./TC_SD23_REMOVE_ITEM_FROM_CART_PAGE.md) |Removing individual Items from the shopping cart                |
|[TC_SD_24](./TC_SD24_ADDING_QUANTITY.md)            |Raising order quantity for identical items                      | 
|[TC_SD_25](./TC_SD25_CONTINUE_SHOPPING.md)          |Returning to the main products page from the shopping cart page |
|[TC_SD_26](./TC_SD26_CHECKOUT_BUTTON.md)            |Accessing the Checkout Page from the Shopping Cart Page         |
|[TC_SD_27](./TC_SD27_EMPTY_CHECKOUT.md)             |Attempting to Checkout an Empty Shopping Cart                   |

> 🧪 **Total Test Cases:** 5  
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
