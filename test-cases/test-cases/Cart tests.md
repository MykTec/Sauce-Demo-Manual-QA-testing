# Cart Test Cases

This document contains the manual test cases executed for the SauceDemo shopping cart.

## TC-CART-001 — Add One Product

**Test:** Add one product to the cart.

**Expected Result:**
The product should be added and the cart count should increase.

**Actual Result:**
The product was added, the cart count became 1, and the button changed from Add to Cart to Remove.

**Status:** PASS

## TC-CART-002 — Remove Product

**Test:** Remove a product from the cart.

**Expected Result:**
The selected product should be removed from the cart.

**Actual Result:**
The product was successfully removed.

**Status:** PASS

## TC-CART-003 — Cart Contents

**Test:** Check the information displayed for a product in the cart.

**Expected Result:**
The cart should display the product name, price, quantity, and Remove control.

**Actual Result:**
The product name, price, quantity, and Remove control were displayed.

**Status:** PASS

## TC-CART-004 — Cart Persistence After Refresh

**Test:** Refresh the Cart page.

**Expected Result:**
Products in the cart should remain after the refresh.

**Actual Result:**
The product remained in the cart after refreshing.

**Status:** PASS

## TC-CART-005 — Cart Persistence During Navigation

**Test:** Navigate from the cart to Product Details and back to Products, then return to the cart.

**Expected Result:**
The cart contents should remain unchanged.

**Actual Result:**
The product remained in the cart during navigation.

**Status:** PASS

## TC-CART-006 — Cart Persistence After Logout and Login

**Test:** Log out and then log back in after adding a product.

**Expected Result:**
The cart should retain the previously added product.

**Actual Result:**
The product remained in the cart after logging in again.

**Status:** PASS

## TC-CART-007 — Cart Quantity Display

**Test:** Check the quantity displayed for a cart item.

**Expected Result:**
The cart should display the quantity of the selected product.

**Actual Result:**
The quantity was displayed as 1.

**Status:** PASS

## TC-CART-008 — Multiple Products

**Test:** Add two different products to the cart.

**Expected Result:**
Both products should appear separately in the cart.

**Actual Result:**
Two products were displayed, each with a quantity of 1.

**Status:** PASS

## TC-CART-009 — Remove One Product From Multiple Products

**Test:** Remove one product when multiple products are in the cart.

**Expected Result:**
Only the selected product should be removed.

**Actual Result:**
One product was removed while the other remained in the cart.

**Status:** PASS

## TC-CART-010 — Continue Shopping

**Test:** Click Continue Shopping from the Cart.

**Expected Result:**
The Products page should open.

**Actual Result:**
The Products page opened successfully.

**Status:** PASS

## TC-CART-011 — Cart Item Price Consistency

**Test:** Compare the product price on the Products page with the price displayed in the Cart.

**Expected Result:**
The prices should match.

**Actual Result:**
The product price matched the price displayed in the Cart.

**Status:** PASS

## TC-CART-012 — Product Name Consistency

**Test:** Compare the product name between the Products page and the Cart.

**Expected Result:**
The product name should remain consistent.

**Actual Result:**
The product name was displayed consistently.

**Status:** PASS
