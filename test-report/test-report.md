# SauceDemo Manual QA Test Report

## 1. Project Overview

This report summarizes the manual testing performed on the SauceDemo web application.

The testing focused on functional behavior, navigation, cart functionality, checkout, session management, browser history, regression testing, and defect identification.

## 2. Testing Type

Manual Functional Testing

## 3. Test Summary

A total of **84 documented test cases** were executed.

| Result  | Count |
| ------- | ----: |
| Passed  |    81 |
| Failed  |     3 |
| Blocked |     0 |

## 4. Areas Tested

Login and authentication

Product functionality

Product navigation

Cart functionality

Checkout process

Session and access control

Browser navigation and history

Regression testing

## 5. Confirmed Defects

### BUG-001 — Product Open in New Tab Opens General Products Page

Opening a product using the browser's **Open link in new tab** option opens the general Products page instead of the selected product's Details page.

**Severity:** Medium
**Priority:** Medium
**Status:** Open

### BUG-002 — Checkout Can Be Completed With an Empty Cart

The application allows a user to proceed through checkout and complete an order when the cart contains no products.

The Checkout Overview displays an Item Total, Tax, and Total of `$0`.

**Severity:** High
**Priority:** High
**Status:** Open

### BUG-003 — Browser Back After Completed Order Returns to Empty Checkout

After successfully completing an order, using the browser Back button returns to the Checkout Overview page, but the checkout is empty.

**Severity:** Medium
**Priority:** Medium
**Status:** Open

## 6. Testing Approach

Testing was performed through direct interaction with the application.

Expected results were compared against actual results.

Unexpected behavior was retested before being documented as a confirmed defect.

Screenshots were captured as evidence for the confirmed defects.

## 7. Conclusion

The testing identified three reproducible defects across navigation and checkout behavior.

The test results, individual test cases, defect reports, and supporting evidence are included in this repository.
