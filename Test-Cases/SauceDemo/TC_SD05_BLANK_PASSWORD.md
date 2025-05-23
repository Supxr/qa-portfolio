# Test Case: Login Attempt Using Valid Username and Blank Password

**Test Case ID:** TC_SD_05<br>
**Test Objectives:** To verify that the system denies the user access if the password field is blank with a valid username.<br>
**Preconditions:** The user must be on the login page of the SauceDemo website.<br><br>

**Test Steps:**<br>
1. Navigate to https://saucedemo.com/
2. Enter username: `standard_user`
3. Click `login` button

**Expected Result(s):**<br>
The user is denied access and the system provides an error message to inform the user of the password requirement.<br><br>

**Actual Result(s):**<br>
The user is denied access and the system provides the following error message: `Epic sadface: Password is required`.<br><br>

**Status:** Pass
