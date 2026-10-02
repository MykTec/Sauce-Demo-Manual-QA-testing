# Navigation Test Cases

This document contains the manual navigation tests executed on SauceDemo.

## TC-NAV-001 — Product Details Navigation

**Test:** Click a product from the Products page.

**Expected Result:**
The selected product's Details page should open.

**Actual Result:**
The selected product's Details page opened correctly.

**Status:** PASS

## TC-NAV-002 — Back to Products

**Test:** Navigate from Product Details back to the Products page.

**Expected Result:**
The Products page should open.

**Actual Result:**
The Products page opened successfully.

**Status:** PASS

## TC-NAV-003 — Open Product in New Tab

**Test:** Right-click a product and select Open in New Tab.

**Expected Result:**
The selected product's Details page should open in the new tab.

**Actual Result:**
The new tab opened the general Products page instead of the selected product's Details page.

The copied link address was:

`https://www.saucedemo.com/inventory.html#`

**Status:** FAIL

## TC-NAV-004 — Back to Products from Product Details

**Test:** Return from Product Details to the Products page.

**Expected Result:**
The Products page should load normally.

**Actual Result:**
The Products page loaded correctly.

**Status:** PASS

## TC-NAV-005 — Refresh Product Details

**Test:** Refresh the Product Details page.

**Expected Result:**
The same Product Details page should remain available after the refresh.

**Actual Result:**
The same product remained displayed. The product name, price, and description were still available.

**Status:** PASS

## TC-NAV-006 — Browser Back and Forward

**Test:** Use the browser Back and Forward buttons while navigating between Products and Product Details.

**Expected Result:**
Browser navigation should return to the appropriate pages.

**Actual Result:**
The controlled test returned to the product page after using Back and Forward.

**Status:** PASS

## TC-NAV-007 — Direct Product Details URL

**Test:** Copy a Product Details URL and open it in a new browser tab.

**Expected Result:**
The same product's Details page should load.

**Actual Result:**
The same product Details page loaded successfully.

**Status:** PASS

## TC-NAV-009 — Add to Cart from Product Details

**Test:** Add a product to the cart from its Details page.

**Expected Result:**
The cart count should increase and the button should change to Remove.

**Actual Result:**
The cart count increased and the Add to Cart button changed to Remove.

**Status:** PASS

## TC-NAV-010 — Remove Product from Product Details

**Test:** Remove a product using the Remove button on the Product Details page.

**Expected Result:**
The product should be removed and the cart count should decrease.

**Actual Result:**
The product was removed and the cart count returned to 0.

**Status:** PASS

## TC-NAV-011 — Product Details to Cart

**Test:** Add products from Product Details and open the cart.

**Expected Result:**
The cart should open and display the products that were added.

**Actual Result:**
Two products were added and both were displayed in the cart.

**Status:** PASS

## TC-NAV-012 — Cart to Product Details

**Test:** Click a product name from the Cart.

**Expected Result:**
The selected product's Details page should open.

**Actual Result:**
The correct product Details page opened.

**Status:** PASS

## TC-NAV-013 — Continue Shopping

**Test:** Click Continue Shopping from the Cart.

**Expected Result:**
The Products page should open.

**Actual Result:**
The Products page opened.

**Status:** PASS

## TC-NAV-014 — Products to Cart

**Test:** Click the cart icon from the Products page.

**Expected Result:**
The Cart page should open.

**Actual Result:**
The Cart page opened successfully.

**Status:** PASS

## TC-NAV-015 — Cart to Checkout

**Test:** Click Checkout from the Cart.

**Expected Result:**
Checkout: Your Information should open.

**Actual Result:**
Checkout: Your Information opened successfully.

**Status:** PASS

## TC-NAV-016 — Checkout Cancel

**Test:** Click Cancel from Checkout: Your Information.

**Expected Result:**
The checkout should be cancelled without completing an order.

**Actual Result:**
The user was returned to the Cart.

**Status:** PASS

## TC-NAV-017 — Checkout Browser Back

**Test:** Press the browser Back button from Checkout: Your Information.

**Expected Result:**
The previous page should be restored.

**Actual Result:**
The Cart page was restored.

**Status:** PASS

## TC-NAV-018 — Checkout Overview Cancel

**Test:** Click Cancel from Checkout: Overview.

**Expected Result:**
Checkout should be cancelled.

**Actual Result:**
The user was returned to the Products page.

**Status:** PASS

## TC-NAV-019 — Checkout Overview Browser Back

**Test:** Press browser Back from Checkout: Overview.

**Expected Result:**
The previous checkout page should be restored.

**Actual Result:**
Checkout: Your Information was restored.

**Status:** PASS

## TC-NAV-020 — Checkout Information Browser Forward

**Test:** Press browser Forward from Checkout: Your Information.

**Expected Result:**
The next checkout page should be restored.

**Actual Result:**
Checkout: Overview was restored.

**Status:** PASS
