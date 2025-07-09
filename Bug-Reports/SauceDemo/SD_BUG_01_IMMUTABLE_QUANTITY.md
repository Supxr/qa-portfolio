# Bug Report: Quantity Field in Cart Is Not Editable

**Bug ID:** SD_BUG_01
**Severity:** Medium  
**Priority:** Medium  
**Reported On:** 2025-05-14  
**Environment:**  
- Browser: Google Chrome 137.0.7151.69 (64-bit)  
- OS: Windows 11  
- URL: https://www.saucedemo.com/
  
**Link to Test:** [TC_SD_24](/Test-Cases/SauceDemo/3-Shopping-Cart/TC_SD24_ADDING_QUANTITY.md)

---

## Description:
The quantity field in the cart appears interactive but does not accept any input changes. Users cannot increase the quantity of identical items from within the cart page.

---

## Precondition:
User must be logged in and have at least one item in the cart

---

## Steps to Reproduce:
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click `Login`
5. Add **Sauce Labs Backpack** to the cart
6. Click the cart icon to view cart
7. Attempt to change the quantity value from `1` to `5` by clicking or editing the quantity field

---

## Expected Result:
The quantity value updates to `5`, and the total price is recalculated accordingly.

---

## Actual Result:
The quantity field is **not editable** — user input is ignored and the value remains `1`.

---

## Screenshot:
![immutable_quantity](https://github.com/user-attachments/assets/4c9999c9-17d0-4425-9ad0-0428c845cfde)


---

## Reproducibility:
100% — occurs consistently across Chrome and Firefox

---

## Notes:
- This may be an intentional design decision in the app
- However, most e-commerce platforms support in-cart quantity updates before checkout
