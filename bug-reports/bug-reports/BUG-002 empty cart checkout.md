# BUG-002 Checkout Can Be Completed With an Empty Cart

## Bug Summary

The application allows a user to proceed through checkout and complete an order even when the cart contains no products.

## Test Cases

TC-CHECKOUT-009 — Checkout With Empty Cart

TC-CHECKOUT-010 — Checkout Button With Empty Cart

## Preconditions

The user is logged in and the cart contains no products.

## Steps to Reproduce

1. Log in to SauceDemo.
2. Open the Cart.
3. Make sure the cart is empty.
4. Click **Checkout**.
5. Enter valid checkout information.
6. Click **Continue**.
7. Observe the Checkout Overview.
8. Click **Finish**.

## Expected Result

The application should prevent checkout from continuing when there are no products in the cart.

## Actual Result

The application allows checkout to continue with an empty cart.

The Checkout Overview displays:

Item Total: `$0`

Tax: `$0`

Total: `$0`

The **Finish** button remains available and the order can be completed.

## Severity

High

## Priority

High

## Status

Open

## Reproducibility

Reproduced during testing.

## Evidence

The behavior was manually reproduced by starting checkout with an empty cart and completing the checkout flow.

## Notes

This report documents the observed behavior without assuming the intended business rule beyond the expected checkout behavior defined in the test case.
