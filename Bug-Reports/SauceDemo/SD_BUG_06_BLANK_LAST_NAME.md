# Bug Report: System Allowing Blankspaces in the Last Name Field

**Bug ID:** SD_BUG_05<br>
**Severity:** Medium<br>
**Priority:** High<br>
**Reported On:** 2025-06-19

**Environment:** 
- Browser: Google Chrome 137.0.7151.69 (64-bit)
- OS: Windows 10
- URL: https://www.saucedemo.com/

**Link to Test:** [TC_SD_35](/Test-Cases/SauceDemo/4-Checkout-Page/TC_SD33_BLANK_LAST_NAME.md)

---
##Description:
The system accepts blankspaces into the last name field as valid characters, and allows the user to proceed to checkout.

---
##Precondition:
The user must be logged into the SauceDemo website and on the checkout page.

---
##Steps to Reproduce: 
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Find `Sauce Labs Backpack`
6. Click `Add to cart`
7. Click shopping cart icon on the top right
8. Click `Checkout`
9. Enter first name: `John` 
10. Enter last name: `     ` (5 blankspaces)
11. Enter zip code: `12345`
12. Click `Continue`

---
##Expected Result(s):
The system prevents the user from continuing, and provides an error message for invalid characters in the last name field.

---
##Actual Result(s):
The system allows the user to proceed to the Checkout: Overview screen with invalid characters in the last name field.

---
##Screenshots:
![blankspace_last_name](https://github.com/user-attachments/assets/8905fe17-bc11-4a61-8452-64006618ee88)
![successful_redirect](https://github.com/user-attachments/assets/bc5de29f-a4f5-4ff9-b96e-5a3ae3b1e1ab)

---
##Reproducibility:
100% — occurs consistently across Chrome and Firefox

---
##Notes:
- This may be an intentional design decision in the app
- However, most e-commerce platforms prohibit the use of special characters in the name fields to prevent fraud, and reinforce order accuracy.




