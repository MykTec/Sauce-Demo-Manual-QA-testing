# SauceDemo Manual QA Test Report

## 1. Project Overview

This project documents manual quality assurance testing performed on the SauceDemo web application.

The purpose of the testing was to evaluate core user functionality, identify unexpected behavior, and document reproducible defects.

## 2. Testing Scope

The following areas were tested:

Login functionality
Product functionality
Navigation
Shopping cart
Checkout
Session and access control
Regression testing

## 3. Testing Approach

Testing was performed manually using defined test cases.

Each scenario was executed against the expected behavior and the actual result was recorded.

When unexpected behavior was observed, the scenario was retested to determine whether the behavior could be reproduced before being documented as a defect.

## 4. Test Results

A total of **84 documented test cases** were executed.

| Result  | Count |
| ------- | ----: |
| PASS    |    81 |
| FAIL    |     3 |
| BLOCKED |     0 |

## 5. Defects Identified

### BUG-001 — Product Open in New Tab

Opening a product in a new browser tab opens the general Products page instead of the selected product's Details page.

**Status:** Open

### BUG-002 — Checkout With Empty Cart

The application allows a user to proceed through checkout and complete an order when the cart contains no products.

The Checkout Overview displays a `$0` total and the order can still be completed.

**Status:** Open

### BUG-003 — Browser Back After Completed Order

After completing an order, using the browser Back button returns to an empty Checkout Overview page.

**Status:** Open

## 6. Regression Testing

Regression testing was performed on previously tested functionality after navigation, logout, login, checkout, and cart-related actions.

The tested regression scenarios completed successfully.

## 7. Conclusion

The manual testing identified three reproducible defects across navigation, checkout, and browser history behavior.

The remaining documented scenarios produced the expected results during execution.

Detailed test cases are available in the `test-cases` directory, while individual defect reports are available in the `bug-reports` directory.
