# SauceDemo QA Test Suite

This folder contains a comprehensive set of **manual test cases** created for the [SauceDemo](https://www.saucedemo.com/) web application. The goal of this testing effort is to validate the functionality, input validation, and business logic across multiple key areas of the application.

## 🔍 Application Overview

SauceDemo is an e-commerce demo app used for UI automation and QA training. It includes:
- A login system with various user roles
- Product listings with cart functionality
- A multi-step checkout flow
- Navigation through a hamburger menu

## ✅ What Was Tested

The following functional areas were covered in this test suite:

| Module           | Description                                         |
|------------------|-----------------------------------------------------|
| **Login**         | Valid and invalid logins, blank fields, edge cases |
| **Product Page**  | Sorting, add/remove to cart, product detail views  |
| **Shopping Cart** | Quantity changes, empty carts, cart-to-checkout flow |
| **Checkout Page** | Field-level validation and order completion        |
| **Hamburger Menu**| Reset app state, logout, about/all items pages     |
| **Continuity**    | Cart and state retention across sessions/pages     |

> 💡 **Total Test Cases:** 40+  
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

- All tests were performed on [browser info if you want to include it, e.g., Chrome 123, Windows 11].
- No automation or API testing was used in this phase.
- Bug reports available in the `/Bug-Reports` directory [if applicable].


