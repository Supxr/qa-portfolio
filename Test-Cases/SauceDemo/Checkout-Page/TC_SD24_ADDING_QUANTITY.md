# Test Case: Raising order quantity for identical items

**Test Case ID:** TC_SD_24<br>
**Test Objectives:** To verify that the user can add more than one item of the same kind.<br>
**Pre-conditions:** The user must be logged into the SauceDemo website checkout page with at least one item in the shopping cart.<br><br>

**Test Steps:** 
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Find `Sauce Labs Backpack`
6. Click `Add to cart`
7. Click shopping cart icon on the top right
8. Click `1` in the quantity column
9. Change value of quantity to `5`

**Expected Result(s):** The quantity is changed to the new value, and the new price is calculated.<br>

**Actual Result(s):** The quantity is immutable.<br>

**Status:** Fail
