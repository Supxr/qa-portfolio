# Test Case: Login Attempt Using Blank Username/Password

**Test Case ID:** TC_SD_03<br>
**Test Objectives:** To verify that the system denies access to the Product page when the username and input fields are left blank and empty. <br>
**Preconditions:** The user must be on the login page of the SauceDemo website.<br><br>

**Test Steps:**
1. Navigate to https://www.saucedemo.com/
2. Click `Login` Button<br><br>

**Expected Result(s):**<br>
System denies user access, and provides the error message `Epic sadface: Username is required`. <br><br>

**Actual Result(s):**<br>
System denies user access, and provides the error message `Epic sadface; Username is required`. <br><br>

**Status:** Pass
