# Test Execution Summary

## Project

SauceDemo Manual QA Testing

## Application Under Test

SauceDemo

## Testing Type

Manual Functional Testing

## Testing Scope

The testing covered the following areas:

Login functionality
Product functionality
Navigation
Shopping cart
Checkout
Session and access control
Regression testing

## Test Execution Summary

A total of **84 documented test cases** were executed during the testing process.

| Result  | Count |
| ------- | ----: |
| PASS    |    81 |
| FAIL    |     3 |
| BLOCKED |     0 |

## Confirmed Defects

Three reproducible defects were identified during testing.

### BUG-001 — Product Open in New Tab

Opening a product in a new browser tab opens the general Products page instead of the selected product's Details page.

### BUG-002 — Empty Cart Checkout

The application allows checkout and order completion when the cart contains no products, resulting in a `$0` order total.

### BUG-003 — Browser Back After Completed Order

Using the browser Back button after completing an order returns to an empty Checkout Overview page.

## Testing Outcome

The test execution identified three reproducible defects while the remaining executed scenarios produced the expected results.

All reported defects have been documented separately in the `bug-reports` directory.

## Test Approach

Testing was performed manually by interacting with the SauceDemo web application and comparing the observed behavior against the expected behavior defined in each test case.

Unexpected behavior was retested before being documented as a confirmed defect.
