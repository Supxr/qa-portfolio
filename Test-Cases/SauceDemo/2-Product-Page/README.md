# SauceDemo – Product Page Test Cases

This folder contains a detailed set of **manual test cases** focused on the **Product Page** of the [SauceDemo](https://www.saucedemo.com/) (Swag Labs) web application. After logging in, the user is redirected to the product page where they can browse through the product gallery and select items to add to or remove from the shopping cart. 
These test cases validate **product sorting via filters**, **product addition/removal from shopping cart**, **dedicated product details**, **`Add to cart`/`Remove`/`Back to products` button functionality**, and **alternative product addition/removal pathways**.

## ✅ What Was Tested

The following aspects of the product page were tested:

|Test Case ID                                      |Test Case                                                         |
|--------------------------------------------------|------------------------------------------------------------------|
|[TC_SD_08](./TC_SD08_SORT_ASC_PRICE.md)           |Sorting Product by Using Low-to-High Filter                       |
|[TC_SD_09](./TC_SD09_SORC_DESC_PRICE.md)          |Sorting Products by Using the High-to-Low Filter                  | 
|[TC_SD_10](./TC_SD10_Z_TO_A.md)                   |Sorting Product Names by Descending Order (Z-to-A)                |
|[TC_SD_11](./TC_SD11_ADD_TO_CART.md)              |Adding Products to the Shopping Cart                              |
|[TC_SD_12](./TC_SD12_REMOVE_ITEM.md)              |Removing Products from the Shopping Cart                          |
|[TC_SD_13](./TC_SD13_PRODUCT_DETAILS.md)          |Expanding Product Details                                         |
|[TC_SD_14](./TC_SD14_ADD_ITEM_FROM_DETAILS.md)    |Adding Product to Shopping Cart from the Product Details Page     |
|[TC_SD_15](./TC_SD15_REMOVE_ITEM_FROM_DETAILS.md) |Removing Product from Shopping Cart from the Product Details Page |
|[TC_SD_16](./TC_SD16_BACK_TO_PRODUCTS.md)         |Returning to the Products Page from the Product Details Page      |

> 🧪 **Total Test Cases:** 9  
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






