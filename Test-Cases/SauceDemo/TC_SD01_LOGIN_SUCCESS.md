# Test Case: Successful Login with Valid Credentials

**Test Case ID:** TC_SD_01 <br>
**Test Objective:** To verify that a user can login successfully when using valid credentials.<br>
**Pro-conditions:** The user must be on the login page of the SauceDemo website.<br>
**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Clik the `Login` button

**Expected Result(s):**<br>
Form is successfully submitted, the user is redirected to the Products page and the URL contains `/inventory.html`


**Actual Result(s):**<br>
Form is successfully submitted using the valid credentials:<br><br>
`username: standard_user`<br>
`password: secret_sauce`<br>

The URL contains `/inventory.html` which confirms successful redirection to the Products page.

**Status:**
Pass
