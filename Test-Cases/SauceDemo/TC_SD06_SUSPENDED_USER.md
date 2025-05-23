# Test Case: Login Attempt Using Suspended Credentials

**Test Case ID:** TC_SD_06<br>
**Test Objectives:** To verify that the system denies access when using a suspended username.<br>
**Preconditions:** <br>
1. The user must be on the login page of the SauceDemo website.
2. The user account must be suspended or locked out. <br><br>

**Test Steps:**<br>
1. Navigate to https://www.saucedemo.com/
2. Enter username: `locked_out_user`
3. Enter password: `secret_sauce`
4. Click `login` button

**Expected Result(s):**<br>
The user is denied access and the system provides an error message to inform the user that the account is suspended and/or locked out.<br><br>

**Actual Result(s):**<br>
The user is denied access and the system provides the following error message: `Epic sadface: Sorry, this user has been locked out`.<br><br>

**Status:** Pass
