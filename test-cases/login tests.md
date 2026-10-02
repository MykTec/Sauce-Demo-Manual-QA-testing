# Login Test Cases

This document contains the manual test cases executed for the SauceDemo login functionality.

## TC-LOGIN-001 — Valid Login

**Test:** Log in using a valid username and password.

**Test Data:**
Username: `standard_user`
Password: `secret_sauce`

**Expected Result:**
The user should successfully log in and reach the Products page.

**Actual Result:**
The user successfully reached the Products page.

**Status:** PASS

## TC-LOGIN-002 — Incorrect Password

**Test:** Enter a valid username with an incorrect password.

**Expected Result:**
The application should reject the login and display an appropriate error message.

**Actual Result:**
The application displayed:
`Epic sadface: Username and password do not match any user in this service`

**Status:** PASS

## TC-LOGIN-003 — Empty Password

**Test:** Enter a valid username without entering a password.

**Expected Result:**
The application should display a password-required message.

**Actual Result:**
The application displayed:
`Epic sadface: Password is required`

**Status:** PASS

## TC-LOGIN-004 — Empty Username

**Test:** Leave the username field empty and enter a password.

**Expected Result:**
The application should display a username-required message.

**Actual Result:**
The application displayed:
`Epic sadface: Username is required`

**Status:** PASS

## TC-LOGIN-005 — Empty Username and Password

**Test:** Leave both login fields empty and attempt to log in.

**Expected Result:**
The application should prevent login and display a validation message.

**Actual Result:**
The application displayed:
`Epic sadface: Username is required`

**Status:** PASS
