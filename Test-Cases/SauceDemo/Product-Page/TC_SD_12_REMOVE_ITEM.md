# Test Case: Removing Product from the Shopping Cart

**Test Case ID:** TC_SD_12<br>
**Test Objectives:** To verify that removing a product updates the `Remove` button and the shopping cart badge.<br>
**Pre-conditions:** The user must be logged into the SauceDemo Website and have at least one product added to the cart.<br><br>

**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login`
5. Find `Sauce Labs Backpack`
6. Click `Add to cart`
7. Click `Remove`

**Expected Result(s):** The `Remove` button is changed to `Add to cart` and the badge number is reduced by the appropriate number of items removed.<br>

**Actual Result(s):** The `Remove` button is changed to `Add to cart` and the badge number is reduced by the appropriate number of items removed.<br><br>

**Status:** Pass
