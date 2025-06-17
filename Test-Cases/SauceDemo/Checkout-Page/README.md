# SauceDemo QA Test Suite

This folder contains a comprehensive set of **manual test cases** created for the [SauceDemo](https://www.saucedemo.com/) web application. SauceDemo or sometimes known as Swag Labs is a demo e-commerce site created by [Sauce Labs](https://saucelabs.com/). The website provides a platform for not only automated, but also manual testing practice by featuring the basic end-to-end functions of an e-commerce website such as logging in, browsing products, populating a shopping cart, facilitating and completing a checkout. The goal of this testing effort is to validate the functionality, input validation, and business logic across multiple key areas of the application.

## ✅ What Was Tested

The following functional areas were covered in this test suite:

| Module                             | Description                                          |
|------------------------------------|------------------------------------------------------|
| [Login](./Login)                   | Valid and invalid logins, blank fields, edge cases   |
| [Product Page](./Product-Page)     | Sorting, add/remove to cart, product detail views    |
| [Shopping Cart](./Shopping-Cart)   | Quantity changes, empty carts, cart-to-checkout flow |
| [Checkout Page](./Checkout-Page)   | Field-level validation and order completion          |
| [Hamburger Menu](./Hamburger-Menu) | Reset app state, logout, about/all items pages       |
| [Continuity](./Continuity)         | Cart and state retention across sessions/pages       |

> 💡 **Total Test Cases:** 42  
> 📂 Each module contains its own folder with detailed test cases and a `README.md`.

## 🧪 Test Approach

All test cases follow a structured format:
- **Test Case Name**
- **Test Case ID**
- **Test Objectives**
- **Precondition(s)**
- **Step-by-step instructions**
- **Expected vs Actual Result(s)**
- **Pass/Fail Status**

Test coverage includes:
- Positive & negative flows
- Field validation
- Session and UI state behavior

## 📁 Folder Structure

SauceDemo/<br>
├── Login/<br>
├── Product-Page/<br>
├── Shopping-Cart/<br>
├── Checkout-Page/<br>
├── Hamburger-Menu/<br>
├── Continuity/<br>
└── README.md<br>
**Each subfolder includes a set of test cases relevant to its feature set.**

## 👤 Tester Notes

- All tests were performed on Version 137.0.7151.69 (Official Build) (64-bit).
- No automation or API testing was used in this phase.
- Bug reports available in the `/Bug-Reports` directory.



