# Bug Report: System Allowing a Long Zip Code

**Bug ID:** SD_BUG_10<br>
**Severity:** High<br>
**Priority:** High<br>
**Reported On:** 2025-06-19

**Environment:** 
- Browser: Google Chrome 137.0.7151.69 (64-bit)
- OS: Windows 10
- URL: https://www.saucedemo.com/

**Link to Test:** [TC_SD_39](/Test-Cases/SauceDemo/4-Checkout-Page/TC_SD39_LONG_ZIP.md)

---
## Description:
The system accepts a zip code that is too long (more than 5 charactesr), but does not follow ZIP+4 protocol and allows the user to proceed to checkout.

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
11. Enter zip code: `123456` 
12. Click `Continue`

---
## Expected Result(s):
The system prevents the user from continuing, and provides an error message for the incorrect zip code length.

---
## Actual Result(s):
The system allows the user to proceed to the Checkout: Overview screen with a long zip code.

---
## Screenshots:
![long_zip](https://github.com/user-attachments/assets/0ada3bcd-1d3c-495a-ad17-4a082c94f6a6)
![successful_redirect](https://github.com/user-attachments/assets/bc5de29f-a4f5-4ff9-b96e-5a3ae3b1e1ab)

---
## Reproducibility:
100% — occurs consistently across Chrome and Firefox

---
## Notes:
- This may be an intentional design decision in the app
- However, most e-commerce platforms prevents users from inputting a long zip code as it may cause an error in delivery.
