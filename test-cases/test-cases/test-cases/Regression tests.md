# Regression Test Cases

This document contains regression tests performed to verify that previously tested functionality continued to work after other actions were performed.

## TC-REGRESSION-001 — Cart After Re-Login

**Test:** Add a product to the cart, log out, and log back in.

**Expected Result:**
The previously added product should remain available in the cart.

**Actual Result:**
The product remained in the cart after logging in again.

**Status:** PASS

## TC-REGRESSION-002 — Cart Persistence Through Logout and Login

**Test:** Add a product, navigate to the Cart, log out, log back in, and return to the Cart.

**Expected Result:**
The cart should retain the previously added product.

**Actual Result:**
The same product was still present in the Cart after logging in again.

**Status:** PASS
