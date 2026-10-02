# BUG-001 — Product Open in New Tab Opens General Products Page

## Bug Summary

Opening a product in a new browser tab does not open the selected product's Details page. Instead, the new tab opens the general Products page.

## Test Case

TC-NAV-003 — Open Product in New Tab

## Preconditions

The user is logged in with a valid SauceDemo account.

## Steps to Reproduce

1. Log in to SauceDemo.
2. Open the Products page.
3. Right-click on a product.
4. Select **Open link in new tab**.
5. Switch to the newly opened tab.
6. Observe the page that loads.

## Expected Result

The selected product's Product Details page should open in the new tab.

## Actual Result

The new tab opens the general Products page instead of the selected product's Details page.

The copied link address was:

`https://www.saucedemo.com/inventory.html#`

## Severity

Medium

## Priority

Medium

## Status

Open

## Reproducibility

Reproduced consistently during testing.

## Evidence

The issue was manually reproduced and the link address was copied from the product link.

## Notes

Normal left-click navigation to the product Details page works correctly. The issue occurs when using the browser's **Open link in new tab** action.
