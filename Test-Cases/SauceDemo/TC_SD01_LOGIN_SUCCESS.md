# Test Case: Successful Login with Valid Credentials

**Test Case ID:** TC_SD_01
**Test Objective:** To verify that a user can login successfully when using valid credentials.
**Pro-conditions:** The user must be on the login page of the SauceDemo website.
**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Clik the `Login` button

**Expected Result(s):**
Form is successfully submitted, the user is redirected to the Products page and the URL contains `/inventory.html`

**Actual Result(s):**
Form is successfully submitted using the valid credentials: /n
`username: standard_user`/n
`password: secret_sauce`, the URL contains `/inventory.html` which confirms successful redirection to the Products page.

**Status:**
Pass
