# Test Case: Order details in the Checkout Overview Page

**Test Case ID:** TC_SD_41<br>
**Test Objectives:** To verify that the system shows details such as: payment information, shipping information, and total cost in the overview page.<br>
**Pre-conditions:** The user must be logged into the SauceDemo website and on the checkout page.<br><br>

**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Find `Sauce Labs Backpack`
6. Click `Add to cart`
7. Click shopping cart icon on the top right
8. Click `Checkout`
9. Enter first name: `John`
10. Enter last name: `Smith` 
11. Enter zip code: `12345`
12. Click `Continue`

**Expected Result(s):** The system shows the `product quantity`,`product description`, `payment information`, `shipping information`, and `price total`.<br>

**Actual Result(s):** The system shows the `product quantity`,`product description`, `payment information`, `shipping information`, and `price total`.<br><br>

**Status:** Pass
