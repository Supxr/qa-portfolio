# Test Case: Removing Product from Shopping Cart from the Product Details Page

**Test Case ID:** TC_SD_15<br>
**Test Objectives:** The user must be able to remove an item from the shopping cart through the product details page.<br>
**Pre-conditions:** The user must be logged into the SauceDemo Website in a product details page with at least one item in the shopping cart. <br><br>

**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login`
5. Find `Sauce Labs Backpack`
6. Click `Sauce Labs Backpack`
7. Click `Add to cart`
8. Click `Remove`

**Expected Result(s):** From the product page, the `Remove` button is changed to `Add to cart` and the shopping cart badge is reduced by the appropriate number of items.<br>

**Actual Result(s):** From the product page, the `Remove` button is changed to `Add to cart` and the shopping cart badge is reduced by the appropriate number of items.<br><br>

**Status:** Pass
