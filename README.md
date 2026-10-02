# SauceDemo Manual QA Testing

A manual QA testing project focused on testing the SauceDemo web application from a real user's perspective.

The project covers functional testing, product functionality, navigation, cart behavior, checkout, session management, browser history, regression testing, defect identification, and test documentation.

## Application Tested

**Application:** SauceDemo
**Website:** https://www.saucedemo.com/

## Testing Type

Manual Functional Testing

## Testing Scope

The testing covered:

1. Login and authentication
2. Product display and sorting
3. Product navigation
4. Cart functionality
5. Checkout process
6. Session and access control
7. Browser navigation and history
8. Regression testing
9. Defect identification and reporting
10. Test evidence collection

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
**Status:** Open

[Open Bug Reports](./bug-reports/)

## BUG-002 — Checkout Can Be Completed With an Empty Cart

The application allows a user to proceed through checkout and complete an order when the cart contains no products.

The Checkout Overview displays:

**Item Total:** $0
**Tax:** $0
**Total:** $0

**Severity:** High
**Priority:** High
**Status:** Open

[Open Bug Reports](./bug-reports/)

## BUG-003 — Browser Back After Completed Order Returns to Empty Checkout

After successfully completing an order, using the browser Back button returns the user to the Checkout Overview page, but the checkout is empty.

**Severity:** Medium
**Priority:** Medium
**Status:** Open

[Open Bug Reports](./bug-reports/)

## Test Cases

The test cases are organized by functional area.

[Open Test Cases](./test-cases/)

## Test Evidence

Screenshots and other testing evidence are stored in the evidence directory.

[Open Test Evidence](./evidence/)

## Project Structure

```text
SauceDemo-Manual-QA-Testing
│
├── bug-reports/
│   └── Bug reports
│
├── evidence/
│   ├── BUG-001 evidence
│   ├── BUG-002-empty-cart-checkout.png
│   ├── BUG-003-browser back after order.png
│   └── BUG-001-product-new-tab.png.PNG
│
├── test-cases/
│   └── Test cases
│
└── README.md
```

## Testing Approach

Testing was performed through direct interaction with the application.

Expected results were compared with the actual behavior observed during testing.

When unexpected behavior was discovered, the behavior was retested before being documented as a confirmed defect.

Evidence was captured for confirmed defects where applicable.

## Skills Demonstrated

Manual test case design

Functional testing

Regression testing

Exploratory testing

Defect identification

Bug reporting

Test execution

Test documentation

Browser navigation testing

Session and access-control testing

GitHub repository management

## Tools

**Application:** SauceDemo

**Browser:** Web browser

**Documentation:** Markdown

**Repository:** GitHub

## Purpose

This project demonstrates practical manual QA testing skills through structured test cases, real test execution, defect reporting, evidence collection, and organized documentation.
