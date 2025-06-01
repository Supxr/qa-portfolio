# Test Case: Attempting to Checkout an Empty Shopping Cart

**Test Case ID:** TC_SD_27<br>
**Test Objectives:** To verify that the system prevents the user from checking out an empty shopping cart, and prompts the user to add items. <br>
**Pre-conditions:** The user must be logged into the SauceDemo website, and on the shopping cart page.<br>

**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Click shopping cart menu on the top right
6. Click `Checkout`

**Expected Result(s):** The system prevents checkout of an empty cart and prompts the user to add items to the cart before checking out.<br>

**Actual Result(s):** The system allows the user to proceed to the information request form with an empty cart. <br><br>

**Status:** Fail
