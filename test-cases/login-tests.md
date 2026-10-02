# Login Test Cases

## TC-LOGIN-001 — Valid Login

**Precondition:** User is on the SauceDemo login page.

**Steps:**

1. Enter `standard_user` as the username.
2. Enter `secret_sauce` as the password.
3. Click **Login**.

**Expected Result:** User is successfully logged in and the Products page is displayed.

**Actual Result:** Products page was displayed.

**Status:** PASS

---

## TC-LOGIN-002 — Invalid Password

**Steps:**

1. Enter `standard_user` as the username.
2. Enter an incorrect password.
3. Click **Login**.

**Expected Result:** An error message should indicate that the username and password do not match.

**Actual Result:** `Epic sadface: Username and password do not match any user in this service`

**Status:** PASS

---

## TC-LOGIN-003 — Empty Password

**Steps:**

1. Enter `standard_user` as the username.
2. Leave the password field empty.
3. Click **Login**.

**Expected Result:** A password-required error should be displayed.

**Actual Result:** `Epic sadface: Password is required`

**Status:** PASS

---

## TC-LOGIN-004 — Empty Username

**Steps:**

1. Leave the username field empty.
2. Enter `secret_sauce` as the password.
3. Click **Login**.

**Expected Result:** A username-required error should be displayed.

**Actual Result:** `Epic sadface: Username is required`

**Status:** PASS

---

## TC-LOGIN-005 — Empty Username and Password

**Steps:**

1. Leave the username field empty.
2. Leave the password field empty.
3. Click **Login**.

**Expected Result:** A username-required error should be displayed.

**Actual Result:** `Epic sadface: Username is required`

**Status:** PASS
