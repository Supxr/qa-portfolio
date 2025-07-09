# 🐞 Bug Report: Quantity Field in Cart Is Not Editable

**Bug ID:** SD_BUG_01
**Title:** Cart quantity field is immutable — users cannot increase item quantity  
**Severity:** Medium  
**Priority:** Medium  
**Reported On:** 2025-05-14  
**Environment:**  
- Browser: Google Chrome 137.0.7151.69 (64-bit)  
- OS: Windows 11  
- URL: https://www.saucedemo.com/

---

## 📝 Description:
The quantity field in the cart appears interactive but does not accept any input changes. Users cannot increase the quantity of identical items from within the cart page.

---

## ✅ Precondition:
User must be logged in and have at least one item in the cart

---

## 🔁 Steps to Reproduce:
1. Navigate to [https://www.saucedemo.com/](https://www.saucedemo.com/)
2. Log in using `standard_user` / `secret_sauce`
3. Add **Sauce Labs Backpack** to the cart
4. Click the cart icon to view cart
5. Attempt to change the quantity value from `1` to `5` by clicking or editing the quantity field

---

## 🧪 Expected Result:
The quantity value updates to `5`, and the total price is recalculated accordingly.

---

## ❌ Actual Result:
The quantity field is **not editable** — user input is ignored and the value remains `1`.

---

## 📸 Screenshot:
*Include if available (optional)*  
`/Bug-Reports/screenshots/BUG_SAUCE_001_cart_quantity_uneditable.png`

---

## 🔁 Reproducibility:
100% — occurs consistently across Chrome and Firefox

---

## 📚 Notes:
- This may be an intentional design decision in the app
- However, most e-commerce platforms support in-cart quantity updates before checkout
