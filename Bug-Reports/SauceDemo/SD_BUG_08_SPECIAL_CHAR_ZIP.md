# Bug Report: System Allowing Special Characters in the Zip Code Field

**Bug ID:** SD_BUG_08<br>
**Severity:** High<br>
**Priority:** High<br>
**Reported On:** 2025-06-19

**Environment:** 
- Browser: Google Chrome 137.0.7151.69 (64-bit)
- OS: Windows 10
- URL: https://www.saucedemo.com/

**Link to Test:** [TC_SD_37](/Test-Cases/SauceDemo/4-Checkout-Page/TC_SD37_SPECIAL_CHAR_ZIP.md)

---
## Description:
The system accepts special characters into the zip code field as valid characters, and allows the user to proceed to checkout.

---
## Precondition:
The user must be logged into the SauceDemo website and on the checkout page.

---
## Steps to Reproduce: 
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Find `Sauce Labs Backpack`
6. Click `Add to cart`
7. Click shopping cart icon on the top right
8. Click `Checkout`
9. Enter first name: `John` 
10. Enter last name: `Smith`
11. Enter zip code: `<>?!@#` 
12. Click `Continue`

---
## Expected Result(s):
The system prevents the user from continuing, and provides an error message for invalid characters in the zip code field.

---
## Actual Result(s):
The system allows the user to proceed to the Checkout: Overview screen with invalid characters in the zip code field.

---
## Screenshots:
![spec_char_zip](https://github.com/user-attachments/assets/1fa1e9c3-2a18-426e-acc2-7ce69d9c37ac)
![successful_redirect](https://github.com/user-attachments/assets/bc5de29f-a4f5-4ff9-b96e-5a3ae3b1e1ab)

---
## Reproducibility:
100% — occurs consistently across Chrome and Firefox

---
## Notes:
- This may be an intentional design decision in the app
- However, most e-commerce platforms prohibit the use of special characters in the zip code to prevent fraud, and reinforce order accuracy.
