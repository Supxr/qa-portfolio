# Test Case: Submitting Information Form with Empty Zip/Postal Code Field

**Test Case ID:** TC_SD_31<br>
**Test Objectives:** To verify that the system prevents user from submitting the checkout information form if the zip/postal code field is empty then provides an error message.<br>
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
11. Click `Continue`

**Expected Result(s):** The system prevents the user from continuing, and provides an error message for the missing field.<br>

**Actual Result(s):** The system prevents the user from continuing, and provides the error message: `Error: Postal Code is required`.<br><br>

**Status:** Pass
