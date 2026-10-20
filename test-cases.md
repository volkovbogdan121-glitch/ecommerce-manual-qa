# Manual Testing — PawMart Online Store

## About the project

This is a practice project for manual testing of a small online store that sells pet supplies.

The goal is to check whether the main shopping features work as expected and whether users can complete a basic purchase flow.

**Testing type:** Manual, functional  
**Platform:** Web  
**Areas covered:** Product catalog, product details, shopping cart, checkout

## Test Case 1 — Add a product to the cart

**Test Case ID:** TC-001  
**Priority:** High  
**Preconditions:** The product catalog is open and at least one product is available.

**Steps:**
1. Open the product catalog.
2. Select any available product.
3. Click the "Add to cart" button.
4. Open the shopping cart.

**Expected result:**
- The selected product appears in the cart.
- The product name and price are displayed correctly.
- The cart item count is updated.

**Actual result:** Not tested yet.  
**Status:** Not Run.

## Test Case 2 — Update product quantity

**Test Case ID:** TC-002  
**Priority:** Medium  
**Preconditions:** The shopping cart contains at least one product.

**Steps:**
1. Open the shopping cart.
2. Change the quantity of the product from 1 to 2.
3. Check the displayed quantity and total price.

**Expected result:**
- The quantity changes to 2.
- The total price is recalculated correctly.
- The cart displays the updated information.

**Actual result:** Not tested yet.  
**Status:** Not Run.

## Test Case 3 — Submit checkout form with empty fields

**Test Case ID:** TC-003  
**Priority:** High  
**Preconditions:** A product has been added to the cart and the checkout form is accessible.

**Steps:**
1. Open the checkout form.
2. Leave all required fields empty.
3. Click the button to continue.

**Expected result:**
- The order cannot proceed.
- The user sees a clear validation message indicating which required information is missing.

**Actual result:** Not tested yet.  
**Status:** Not Run.

## Notes

These test cases are prepared for practice. They have not been executed against a live application, so actual results and final statuses will be added after testing.  
