# Test Scenarios

## Purpose
This document outlines high-level test scenarios used to validate the core functionality of the Sauce Demo e-commerce application. These scenarios serve as the foundation for detailed test case design.

---

## Skills Demonstrated
- Test Scenario Design
- Functional Coverage
- Requirement Analysis
- Positive & Negative Testing Strategy

---

## Login Module

- Verify valid login with correct credentials
- Verify invalid login shows appropriate error message
- Verify locked-out user is prevented from logging in
- Verify login with blank username field
- Verify login with blank password field

---

## Product (Inventory) Module

- Verify products load successfully on page
- Verify product names, prices, and images are displayed correctly
- Verify product sorting functionality (A–Z)
- Verify product sorting functionality (Z–A)
- Verify product sorting by price (low to high)
- Verify product sorting by price (high to low)
- Verify product details display correctly when selected

---

## Cart Module

- Verify user can add items to cart
- Verify user can remove items from cart
- Verify cart badge updates correctly when items are added/removed
- Verify multiple items can be added to cart

---

## Checkout Module

- Verify user can proceed to checkout from cart
- Verify checkout information form validation
- Verify order overview displays correct item details and pricing
- Verify user can complete checkout successfully

---

## Logout Module

- Verify user can log out successfully from navigation menu
- Verify user is redirected to login page after logout
- Verify session is cleared after logout
