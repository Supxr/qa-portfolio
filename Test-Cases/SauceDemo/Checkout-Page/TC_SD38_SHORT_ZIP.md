# Test Case: Submitting Information Form with a Short Zip

**Test Case ID:** TC_SD_38<br>
**Test Objectives:** To verify that the system prevents user from submitting the checkout information form if the zip code entered is less than 5 characters.<br>
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
11. Enter zip code: `1234`
12. Click `Continue`

**Expected Result(s):** The system prevents the user from continuing, and provides an error message for the incorrect zip code length.<br>

**Actual Result(s):** The system allows the user to proceed to the `Checkout: Overview` screen with a short zip code.<br><br>

**Status:** Fail
