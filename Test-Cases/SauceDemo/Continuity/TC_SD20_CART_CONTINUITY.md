# Test Case: Shopping Cart Continuity Between Pages

**Test Case ID:** TC_SD_20<br>
**Test Objectives:** To verify that the `Add to cart` button, `Remove` button, and shopping cart maintain their states when switching between different pages.<br>
**Pre-conditions:** The user must be logged into the SauceDemo website, and have at least one item in the cart.<br><br>

**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Find `Sauce Labs Backpack`
6. Click `Add to cart`
7. Click `Sauce Labs Backpack`
8. Click `Back to products` button

**Expected Result(s):** The `Add to cart` and `Remove` buttons maintain their state, and the shopping cart maintains the correct item count.<br>

**Actual Result(s):** The `Add to cart` and `Remove` buttons maintain their state, and the shopping cart maintains the correct item count.<br><br>

**Status:** Pass
