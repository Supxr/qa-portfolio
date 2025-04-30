# Test Case: Unsuccessful Login Attempt With Incorrect Password

**Test Case ID:** TD_SD_02 <br>
**Test Objectives:** To verify that the system denies invalid credentials, and provides the user with an error message. <br>
**Preconditions:** The user must be on the login page of the SauceDemo website. <br><br>
**Test Steps:** <br>
1. Navigate to https://saucedemo.com/
2. Enter username: `standard_user`
3. Enter password: `password`
4. Click `Login` button

**Expected Result(s):**
User is denied access due to invalid username or password, and is provided an error message that reads `Epic sadface: Username and password do not match any user in this service`.

**Actual Result(s):**
User is denied access due to invalid username or password, and is provided an error message that reads `Epic sadface: Username and password do not match any user in this service`.

**Status:** Pass
