# Test Case: Reset app state using the Reset App State Button

**Test Case ID:** TC_SD_07<br>
**Test Objectives:** To reset the website app to its original state by pressing the Reset App State Button in the product page.<br>
**Pre-conditions:** User must be logged into the product page of the Sauce Demo website.<br><br>

**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `login` button
5. Find `Sauce Labs Backpack` and click `Add to cart`
6. Find `Sauce Labs Bike Light` and click `Add to cart`
7. click `Menu Icon` on the top left of the page
8. click `Reset App State`

**Expected Result(s):**<br>
The system must clear the cart of all items, remove the number badge from the cart icon, and reset all `Remove` buttons to `Add to cart`.

**Actual Result(s):**<br>
The system clears the cart of all items, and removes the number badge from the cart icon, but does not change the `Remove` buttons back to `Add to cart`

**Status:** Fail
