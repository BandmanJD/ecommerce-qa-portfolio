# Regression Test Suite

## Purpose

This document identifies the critical test cases that should be executed after future application updates to verify that existing functionality continues to operate as expected.

---

## Skills Demonstrated

- Regression Test Planning
- Risk-Based Testing
- Test Prioritization
- Critical Path Validation

---

## Regression Strategy

The following test cases represent the application's core business workflows. These tests should be executed whenever changes are made to authentication, inventory management, shopping cart functionality, or the checkout process.

---

## Regression Test Suite

| Test Case ID | Module | Test Case | Priority |
|--------------|--------|-----------|----------|
| TC_LOG_001 | Login | Verify valid login | High |
| TC_LOG_002 | Login | Verify invalid login displays error message | High |
| TC_LOG_003 | Login | Verify locked-out user cannot log in | High |
| TC_INV_001 | Inventory | Verify products load successfully | High |
| TC_INV_002 | Inventory | Verify product sorting functionality | Medium |
| TC_INV_015 | Inventory | Verify product card layout displays correctly on mobile viewport | Medium |
| TC_CART_001 | Cart | Verify item can be added to cart | High |
| TC_CART_002 | Cart | Verify item can be removed from cart | High |
| TC_CHK_001 | Checkout | Verify checkout information page loads | High |
| TC_CHK_002 | Checkout | Verify checkout overview displays correct order information | High |
| TC_CHK_003 | Checkout | Verify order can be completed successfully | Critical |
| TC_LOGOUT_001 | Logout | Verify user can successfully log out | High |

---

## Regression Scope

The regression suite focuses on validating:

- User authentication
- Product inventory
- Shopping cart functionality
- Checkout workflow
- Session management
- Responsive UI validation

---

## Regression Execution Criteria

The regression suite should be executed after:

- New feature implementation
- Bug fixes
- UI enhancements
- Production releases
- Major application updates

---

## Expected Outcome

Successful execution of this regression suite provides confidence that critical business functionality remains stable following application changes.
