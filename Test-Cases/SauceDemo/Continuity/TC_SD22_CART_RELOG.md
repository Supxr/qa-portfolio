# Test Case: Shopping Cart State after Relogging into Website

**Test Case ID:** TC_SD_22<br>
**Test Objectives:** To verify that the shopping cart maintains its product count after relogging into the website.<br>
**Pre-conditions:** The user must be logged into the SauceDemo Website with all products added to the cart.<br><br>

**Test Steps:** 
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Click `Add to cart` on all products
6. Click hamburger menu on top left
7. Click `Logout`
8. Enter username: `standard_user`
9. Enter password: `secret_sauce`
10. Click `Login` button

**Expected Result(s):** The shopping cart maintains the product count after relogging into the website.<br>

**Actual Result(s):** The shopping cart maintains the product count after relogging into the website.<br><br>

**Status:** Pass
