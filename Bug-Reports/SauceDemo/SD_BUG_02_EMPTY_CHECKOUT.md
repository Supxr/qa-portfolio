# Bug Report: System Allows Checkout with an Empty Cart

**Bug ID:** SD_BUG_02<br>
**Severity:** Medium<br>
**Priority:** Low<br>
**Reported On:** 2025-06-19<br>

**Environment:**
- Browser: Google Chrome 137.0.7151.69 (64-bit)
- OS: Windows 10
- URL: https://www.saucedemo.com/

**Link To Test:** [TC_SD_27](/Test-Cases/SauceDemo/3-Shopping-Cart/TC_SD27_EMPTY_CHECKOUT.md)

---

# Description:

The system allows the user to checkout with an empty shopping cart. There are no prevention measures present, and there is no error message provided.

---

# Precondition:

The user must be logged in and be on the shopping cart page without any items in the cart.

---

# Steps to Reproduce:

1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login` button
5. Click shopping cart menu on the top right
6. Click Checkout

---

# Expected Result(s):
The system prevents checkout of an empty cart and prompts the user to add items to the cart before checking out.

---

# Actual Result(s):
The system allows the user to proceed to the information request form with an empty cart.

---

# Screenshot(s):
![empty_shopping_cart](https://github.com/user-attachments/assets/c9d0dfb8-bac4-4fa1-ad04-d86566d7824e)
![checkout](https://github.com/user-attachments/assets/aa510852-8890-42a0-8d4d-7a88089c2feb)

---
#Reproducibility:
100% - occurs consistently across Chrome and Firefox

