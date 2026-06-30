# Bug Reports

## Purpose

This document contains defects identified during manual testing of the Sauce Demo e-commerce application.

---

## Skills Demonstrated

- Defect Identification
- Defect Documentation
- UI Testing
- Responsive Testing
- Root Cause Analysis
- Clear Technical Communication
- Severity & Priority Assessment

---

## Defect Tracking Process

Each defect is documented with:
- Bug ID
- Title
- Environment
- Severity
- Priority
- Preconditions
- Steps to Reproduce
- Expected Result
- Actual Result
- Status

---

# BUG-001

## Title

Excessive vertical spacing within product cards on mobile viewport

### Bug Type

UI / Responsive Layout

### Severity

Low

### Priority

Low

### Environment

- Application: Sauce Demo
- Browser: Google Chrome (Chromium - based)
- Primary Tool: Blisk
- Additonal Tool: Mobile Simulator - Responsive Testing Tool
- Devices: iPhone 16 & iPhone 14 Pro
- Viewport: 393 × 852 & 390 × 844 (CSS pixels)
- OS: Windows 11

### Preconditions

- User is logged in.
- User is on the Inventory page.

### Steps to Reproduce

1. Log into the application.
2. Navigate to the Inventory page.
3. Open the application in an iPhone mobile viewport (393 × 852).
4. Observe the spacing between the product description, price, and action button.

### Expected Result

Product information should be evenly spaced with consistent alignment throughout each product card.

### Actual Result

Large vertical gaps appear between the product description and price/button, creating an inconsistent layout and reducing visual polish.

### Status

Open

### Evidence

The issue was reproduced in:
- Blisk (iPhone 16 viewport)
- Mobile Simulator - Responsive Testing Tool (iPhone 14 Pro viewport)

### Notes

This issue does not affect application functionality but negatively impacts the user experience on mobile devices by creating excessive unused space within product cards.

---

## Overall Defect Summary

| Metric | Count |
|--------|------:|
| Total Defects Identified | 1 |
| Critical | 0 |
| High | 0 |
| Medium | 0 |
| Low | 1 |

---

## Conclusion

Manual testing identified one reproducible UI defect affecting the mobile presentation of the Inventory page. Core application functionality operated as expected throughout the remaining test scenarios.
