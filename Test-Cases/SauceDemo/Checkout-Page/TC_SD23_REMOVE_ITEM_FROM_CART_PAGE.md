# Test Case: Removing individual Items from the shopping cart through the checkout page.

**Test Case ID:** TC_SD_23<br>
**Test Objectives:** To verify that items can be removed from the shopping cart page.<br>
**Pre-conditions:** The user must be logged into the SauceDemo website with at least one item in the shopping cart.<br><br>

**Test Steps**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Find `Sauce Labs Backpack`
6. Click `Add to cart` button
7. Click shopping cart icon on the top right
8. Find `Sauce Labs Backpack`
9. Click `Remove` button

**Expected Result(s):** The item is successfully removed from the cart, and the shopping cart badge count is updated accordingly. <br>

**Actual Result(s):** The item is successfully removed from the cart, and the shopping cart badge count is updated accordingly. <br><br>

**Status:** Pass
