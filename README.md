# SauceDemo Manual QA Testing

A manual software testing project focused on testing the SauceDemo web application from a user's perspective.

The project covers functional testing, navigation, product functionality, cart behavior, checkout, session management, browser history, regression testing, and defect reporting.

## Application Tested

**Application:** SauceDemo
**URL:** https://www.saucedemo.com/

## Testing Type

Manual Functional Testing

## Testing Scope

The following areas were tested:

1. Login and authentication
2. Product display and sorting
3. Product navigation
4. Cart functionality
5. Checkout process
6. Session and access control
7. Browser navigation and history
8. Regression testing
9. Defect identification and reporting

## Test Execution Summary

| Result           | Count |
| ---------------- | ----: |
| Total Test Cases |    84 |
| Passed           |    81 |
| Failed           |     3 |
| Blocked          |     0 |

## Confirmed Defects

### BUG-001 — Product Open in New Tab Opens General Products Page

Opening a product using the browser's **Open link in new tab** option opens the general Products page instead of the selected product's Details page.

**Severity:** Medium
**Priority:** Medium

[View Bug Report](bug-reports/BUG-001-product-new-tab.md)

### BUG-002 — Checkout Can Be Completed With an Empty Cart

The application allows a user to proceed through checkout and complete an order when the cart contains no products.

The Checkout Overview displays an Item Total, Tax, and Total of `$0`.

**Severity:** High
**Priority:** High

[View Bug Report](bug-reports/BUG-002-empty-cart-checkout.md)

### BUG-003 — Browser Back After Completed Order Returns to Empty Checkout

After completing an order, using the browser Back button returns to the Checkout Overview page, but the checkout is empty.

**Severity:** Medium
**Priority:** Medium

[View Bug Report](bug-reports/BUG-003-browser-back-after-order.md)

## Project Structure

```text
SauceDemo-Manual-QA-Testing
│
├── test-cases
│   ├── login-tests.md
│   ├── product-tests.md
│   ├── navigation-tests.md
│   ├── cart-tests.md
│   ├── checkout-tests.md
│   ├── session-tests.md
│   └── regression-tests.md
│
├── bug-reports
│   ├── BUG-001-product-new-tab.md
│   ├── BUG-002-empty-cart-checkout.md
│   └── BUG-003-browser-back-after-order.md
│
├── test-execution
│   └── test-execution-summary.md
│
├── test-report
│   └── test-report.md
│
└── evidence
    ├── BUG-001-product-new-tab.png
    ├── BUG-002-empty-cart-checkout.png
    └── BUG-003-browser-back-after-order.png
```

## Test Approach

Testing was performed through direct interaction with the application.

For unexpected behavior, the test was repeated before documenting it as a confirmed defect.

Test evidence was captured for the confirmed defects and stored in the `evidence` folder.

## Skills Demonstrated

Manual test case design
Functional testing
Regression testing
Exploratory testing
Defect identification
Bug reporting
Test execution and documentation
Browser navigation testing
Session and access-control testing
GitHub documentation

## Tools

**Application:** SauceDemo
**Browser:** Web browser
**Documentation:** Markdown
**Repository:** GitHub

## Purpose

This project demonstrates practical manual QA testing skills through structured test cases, test execution, defect reporting, evidence collection, and test documentation.
