# Session Test Cases

This document contains the manual test cases executed for SauceDemo session and access control behavior.

## TC-SESSION-006 — Browser Back After Logout

**Test:** Log out and use the browser Back button.

**Expected Result:**
The application should prevent access to protected pages after logout.

**Actual Result:**
The application displayed:

`Epic sadface: You can only access '/inventory.html' when you are logged in.`

**Status:** PASS

## TC-SESSION-007 — Browser Forward After Logout

**Test:** Log out and use the browser Forward button.

**Expected Result:**
The application should prevent access to protected pages after logout.

**Actual Result:**
The application displayed:

`Epic sadface: You can only access '/inventory.html' when you are logged in.`

**Status:** PASS

## TC-SESSION-008 — Direct Access to Products Page While Logged Out

**Test:** Attempt to access `/inventory.html` directly while logged out.

**Expected Result:**
The application should prevent access to the protected Products page.

**Actual Result:**
The application displayed:

`Epic sadface: You can only access '/inventory.html' when you are logged in.`

**Status:** PASS

## TC-SESSION-009 — Login After Access Denial

**Test:** Log in after being blocked from accessing the Products page while logged out.

**Expected Result:**
The user should be able to log in successfully and access the Products page.

**Actual Result:**
The user successfully logged in and reached the Products page.

**Status:** PASS
