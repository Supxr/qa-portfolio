# Bug Report: System Not Performing a Full Reset of the App State

**Bug ID:** SD_BUG_12<br>
**Severity:** Medium<br>
**Priority:** Low<br>
**Reported On:** 2025-06-19

**Environment:** 
- Browser: Google Chrome 137.0.7151.69 (64-bit)
- OS: Windows 10
- URL: https://www.saucedemo.com/

**Link to Test:** [TC_SD_07](/Test-Cases/SauceDemo/4-Checkout-Page/TC_SD07_RESET_APP_STATE.md)

---
## Description:
The system clears the cart of all items, and removes the number badge from the cart icon, but does not change the `Remove` buttons back to `Add to cart`.

---
## Precondition:
The user must be logged into the SauceDemo website, and on the checkout page with at least one item in the cart.

---
## Steps to Reproduce: 
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Find `Sauce Labs Backpack` and click `Add to cart`
6. Find `Sauce Labs Bike Light` and click `Add to cart`
7. click Menu Icon on the top left of the page
8. click `Reset App State`

---
## Expected Result(s):
The system must clear the cart of all items, remove the number badge from the cart icon, and reset all `Remove` buttons to `Add to cart`.

---
## Actual Result(s):
The system clears the cart of all items, and removes the number badge from the cart icon, but does not change the `Remove` buttons back to `Add to cart`.

---
## Screenshots:
![failed_reset](https://github.com/user-attachments/assets/0330318e-b45c-414f-a22a-34da18c54c5b)

---
## Reproducibility:
100% — occurs consistently across Chrome and Firefox
