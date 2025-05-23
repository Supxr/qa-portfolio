#Test Case: Login Attempt with Blank Username and Valid Password

**Test Case ID:** TC_SD_04<br>
**Test Objectives:** To verify that the system denies the user access if the username field is blank with a valid password.<br>
**Preconditions:** The user must be on the login page of the SauceDemo website.<br><br>

**Test Steps:**<br>
1. Navigate to https://saucedemo.com/
2. Enter password: `secret_sauce`
3. Click `login` button

**Expected Result(s):**<br>
The user is denied access and the system provides an error message to inform the user of the username requirement.<br><br>

**Actual Result(s):**<br>
The user is denied access and the system provides the following error message: `Epic sadface: Username is required`.<br><br>

**Status:** Pass
