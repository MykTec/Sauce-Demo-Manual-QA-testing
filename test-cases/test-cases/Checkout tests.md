# Checkout Test Cases

This document contains the manual test cases executed for the SauceDemo checkout functionality.

## TC-CHECKOUT-001 — Empty Checkout Form

**Test:** Leave all checkout information fields empty and click Continue.

**Expected Result:**
The application should display a required-field validation message.

**Actual Result:**
The application displayed:
`Error: First Name is required`

**Status:** PASS

## TC-CHECKOUT-002 — Missing Last Name

**Test:** Enter a first name and leave the last name empty.

**Expected Result:**
The application should display a last-name-required message.

**Actual Result:**
The application displayed:
`Error: Last Name is required`

**Status:** PASS

## TC-CHECKOUT-003 — Missing Postal Code

**Test:** Enter a first name and last name but leave the postal code empty.

**Expected Result:**
The application should display a postal-code-required message.

**Actual Result:**
The application displayed:
`Error: Postal Code is required`

**Status:** PASS

## TC-CHECKOUT-004 — Valid Checkout Information

**Test:** Enter valid checkout information.

**Test Data:**
First Name: `Test`
Last Name: `User`
Postal Code: `100001`

**Expected Result:**
The user should proceed to the Checkout Overview page.

**Actual Result:**
The Checkout Overview page opened successfully.

**Status:** PASS

## TC-CHECKOUT-005 — Checkout Overview Details

**Test:** Verify the product, quantity, price, tax, and total displayed on the Checkout Overview page.

**Expected Result:**
The checkout summary should correctly display the selected product and calculate the total.

**Actual Result:**
The page displayed:

Product: `Sauce Labs Backpack`
Quantity: `1`
Price: `$29.99`
Item Total: `$29.99`
Tax: `$2.40`
Total: `$32.39`

The calculation was consistent.

**Status:** PASS

## TC-CHECKOUT-006 — Complete Order

**Test:** Complete an order using valid checkout information.

**Expected Result:**
The order should be completed and a confirmation message should be displayed.

**Actual Result:**
The application displayed the order confirmation message:
`Thank you for your order!`

**Status:** PASS

## TC-CHECKOUT-007 — Cancel Checkout Information

**Test:** Click Cancel from the Checkout: Your Information page.

**Expected Result:**
The user should return to the Cart page.

**Actual Result:**
The user returned to the Cart page.

**Status:** PASS

## TC-CHECKOUT-008 — Cancel Checkout Overview

**Test:** Click Cancel from the Checkout Overview page.

**Expected Result:**
The user should leave the checkout process.

**Actual Result:**
The user returned to the Products page and the cart contents remained intact.

**Status:** PASS

## TC-CHECKOUT-009 — Checkout With Empty Cart

**Test:** Open Checkout with no products in the cart and attempt to complete an order.

**Expected Result:**
The application should prevent checkout completion when there are no products in the cart.

**Actual Result:**
The application allowed checkout to continue with an empty cart. The Checkout O
