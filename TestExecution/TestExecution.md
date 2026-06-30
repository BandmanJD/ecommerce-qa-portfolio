# Test Execution Report

## Purpose
This document contains the execution results of manual test cases for the Sauce Demo e-commerce application. It validates whether the implemented functionality behaves as expected based on predefined test cases.

---

## Skills Demonstrated
- Test Execution
- Functional Validation
- Defect Identification
- Result Analysis
- QA Documentation

---

## Test Execution Summary

| Metric | Value |
|--------|------|
| Total Test Cases Executed |39|
| Passed | 38 |
| Failed | 1 |
| Blocked | 0 |

---

## Execution Approach

Test cases were executed manually using Google Chrome (Chromium-based browser) on Windows 11.

Responsive and cross-device validation was performed using:
- Blisk (primary tool for simultaneous desktop and mobile viewport simulation)
- Mobile Simulator - Responsive Testing Tool (Chrome Extension for device profile emulation)

Each test case was validated against expected results defined in the Test Cases document. Any discrepancies were investigated and documented as defects where applicable.

The Inventory module UI defect (BUG-001) was identified during responsive testing on mobile viewport simulation and verified across multiple tools.

---

## Modules Tested

- Login
- Inventory
- Cart
- Checkout
- Logout

---

## Defects Identified

### BUG-001 - UI Layout Issue on Product Cards (Mobile Viewport)

- **Test Case ID:** TC_INV_0011  
- **Module:** Inventory  
- **Severity:** Low  
- **Priority:** Low  
- **Environment:** Chrome (Chromium) + Blisk (iPhone 15 viewport)  
- **Status:** Open  

### Description
Excessive vertical spacing was observed between the product description and the price/action button on mobile viewport layouts.

### Impact
This issue affects UI consistency and visual presentation on mobile devices but does not impact core functionality.

### Reproduction
The issue is reproducible in:
- Blisk (iPhone 15 viewport simulation)
- Mobile Simulator - Responsive Testing Tool (Chrome Extention) (validated)

### Linked Test Case
- TC_INV_0011 → Failed

---

## Observations

- All core user flows functioned as expected
- UI rendered correctly across most tested views
- 1 low severity UI defect identified in mobile viewport (Inventory module)

---

## Conclusion

The Sauce Demo application passed the majority of executed test cases. Core functionality is stable and behaves as expected under tested conditions.

One low-severity UI defect was identified in the Inventory module affecting mobile layout consistency. This does not impact functionality but may affect user experience on smaller viewports.


