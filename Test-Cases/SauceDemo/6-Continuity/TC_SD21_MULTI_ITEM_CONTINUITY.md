# Test Case: Shopping Cart continuity with multiple items present

**Test Case ID:** TC_SD_21<br>
**Test Case Objectives:** The `Add to cart` and `Remove` buttons maintain their states, while the shopping cart maintains the appropriate count of items.<br>
**Pre-conditions:** The user must be logged into the SauceDemo website with all products added to the cart.<br><br>

**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Click `Add to cart` on all products
6. Click `Sauce Labs Backpack`
7. Click `Back to products` button

**Expected Result(s):** The `Add to cart` and `Remove` buttons maintain their states, and the shopping cart maintains count of added items.<br>

**Actual Result(s):** The `Add to cart` and `Remove` buttons maintain their states, and the shopping cart maintains count of added items.<br><br>

**Status:** Pass
