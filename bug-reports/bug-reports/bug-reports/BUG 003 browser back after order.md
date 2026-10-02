# BUG-003 — Browser Back After Completed Order Returns to Empty Checkout

## Bug Summary

After successfully completing an order, using the browser Back button returns the user to the Checkout Overview page, but the checkout page is empty.

## Test Case

TC-CHECKOUT-028 — Browser Back After Completed Order

## Preconditions

The user is logged in and has completed a valid order.

## Steps to Reproduce

1. Log in to SauceDemo.
2. Add a product to the cart.
3. Proceed through checkout.
4. Enter valid checkout information.
5. Complete the order.
6. Confirm that the order confirmation page is displayed.
7. Click the browser Back button.
8. Observe the page that loads.

## Expected Result

The application should handle browser history appropriately after the order has been completed.

## Actual Result

The browser returns to the Checkout Overview page, but the Checkout Overview is empty.

## Severity

Medium

## Priority

Medium

## Status

Open

## Reproducibility

Reproduced consistently during testing.

## Evidence

The behavior was manually reproduced after completing an order.

## Notes

The issue concerns browser history behavior after order completion. The test did not establish any loss of the completed order itself.
