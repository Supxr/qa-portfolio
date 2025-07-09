# Bug Report: System Allowing Special Characters in First Name Field

**Bug ID:** SD_BUG_03<br>
**Severity:** Medium<br>
**Priority:** High<br>
**Reported On:** 2025-06-19

**Environment:** 
- Browser: Google Chrome 137.0.7151.69 (64-bit)
- OS: Windows 10
- URL: https://www.saucedemo.com/

**Link to Test:** [TC_SD_32](/Test-Cases/SauceDemo/4-Checkout-Page/TC_SD32_SPECIAL_CHAR_FIRST_NAME.md)

---
##Description:
The system accepts special characters (!@#$%^&*...) into the first name field as valid characters, and allows the user to proceed to checkout.

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
9. Enter first name: `!!!!!`
10. Enter last name: `Smith`
11. Enter zip code: `12345`
12. Click `Continue`

---
##Expected Result(s):
The system prevents the user from continuing, and provides an error message for invalid characters in the first name field.

---
##Actual Result(s):
The system allows the user to proceed to the Checkout: Overview screen with invalid characters in the first name field.

---
##Screenshots:
![fieldinput](https://github.com/user-attachments/assets/45c18caa-2684-45d9-bda2-e1c616f14245)
![successful_redirection](https://github.com/user-attachments/assets/a7226ab5-c7b3-4107-8d18-3d27c5afa1f1)

---
##Reproducibility:
100% — occurs consistently across Chrome and Firefox

---
##Notes:
- This may be an intentional design decision in the app
- However, most e-commerce platforms prohibit the use of special characters in the name fields to prevent fraud, and reinforce order accuracy.



