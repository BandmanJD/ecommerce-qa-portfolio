## Title:
Verify if user can login with valid credentials

Precondition:
1. User is on login page

Steps:
1. Enter valid username
2. Enter valid password
3. Click Login

Expected Result:
1. User is redirected to Products page

## Title:
Verify error message for an invalid password

Precondition:
1. User is on login page

Steps:
1. Enter valid username
2. Enter invalid password
3. Click Login

Expected Result:
1. Error message displayed

## Title:
Verify error message for an invalid username

Precondition:
1. User is on login page

Steps:
1. Enter invalid username
2. Enter valid password
3. Click Login

Expected Result:
1. Error message displayed

## Title: 
Verify Product Description is Displayed

Precondition: 
1. User is logged in

Steps:
1. Navigate to the "Products" Page
2. Review each product description

Expected Result:
1. Each producty displays a product description

Title: 
Verify Product Price is Displayed

Precondition:
1. User is logged in

Steps:
1. Navigate to "Products" page
2. Review each product card

Expected Result:
1. Each product displays a price
2. Price format is consistent

Title:
Verify Product Image is Displayed

Precondition:
1. User is logged in

Steps:
1. Navigate to the "Products" page
2. Review each product card

Expected Result:
1. Product image is displayed for each product
2. Images load without distortion or broken links

Title:
Verify Products Can be Sorted A to Z

Preconditon:
1. User is logged in

Steps: 
1. Navigate to "Products" page
2. Open the Sort dropdown in the top right corner
3. Select "Name (A to Z")

Expected Result:
1. Products are sorted alphabetically from A to Z

Title:
Verify Products Can be Sorted Z to A

Precondition:
1. User is logged in

Steps:
1. Navigate to "Products" page
2. Open the Sort dropdown
3. Select "Name (Z to A)"

Expected Result:
1. Products are sorted alphabetically from to Z to A

Title:
Verify Products Can Be Sorted by Price (Low to High)

Preconditon:
1. User is logged in

Steps:
1. Navigate to "Products" page
2. Open the Sort dropdown
3. Select "Price (Low to High)"

Expected Result:
1. Products are sorted by ascending price

Title:
Verify Products Can Be Sorted by Price (High to Low)

Preconditon:
1. User is logged in

Steps:
1. Navigate to "Products" page
2. Open the Sort dropdown
3. Select "Price (High to Low)"

Expected Result:
1. Products are sorted by decending price

Title:
Verify User Cna View Product Details

Precondition:
1. User is logged in

Steps:
1. Navigate to the "Products" page
2. Click a product name or image

Expected Result:
1. Product detail page opens
2. Correct product information is displayed

Title:
Verify User can Return to Product page from product details

Precondition:
1. User is viewing a product detail page

Steps:
1. Click the "Back to Products" button

Expected Result:
1. User is returned to the product page

Title:
Verify that the "Add To Cart" button is displayed

Precondition:
1. User is logged in

Steps:
1. Click on the "Add to cart" CTA
2. Review each product card

Expected Result:
1. "Add to Cart" button is visible for each product not already in the cart

Title:
Verify "Product" page on mobile viewport

Precondition:
1. User is logged in
2. Blisk is congifured to an iphone viewport

Steps:
1. Open the products page
2. Review layout and content

Expected Result:
1. Products display correctly
2. No overlapping elements
3. No horizontal scrolling
4. Page remians usuable on mobile

Title:
Verify the "Add to cart" CTA changes to "Remove" CTA after being clicked

Precondition:
1. User is logged in
2. User is on products page

Steps:
1. Navigate the produts page
2. Click a product name or image
3. Click on "Add to cart" CTA

Expected Result:
1. CTA changes to "Remove"


Title:
Verify the "Remove" CTA changes back to "Add to cart" CTA after being clicked

Precondition:
1. User is logged in
2. User is on products page

Steps:
1. Navigate the products page
2. Click on a product that's been previously added to cart
3. Click on "Remove" CTA

Expected Result:
1. CTA changes back to "Add to cart"

Title:
Verify the "Remove" CTA removes a product from "your cart" page

Precondition:
1. User is logged in
2. User has added product(s) to their cart

Steps:
1. Navigate the products page
2. Add 1-3 products to shopping cart
3. Click on cart located in top right corner
4. Click on "Remove" CTA

Expected Result:
1. Product should be removed from cart

Title:
Verify "Continue Shopping" CTA directs user to "Products" page

Precondition:
1. User is logged in
2. User is in "your cart" page

Steps:
1. Locate the "Continue Shopping" cta at the bottom left of the page
2. Click on CTA

Expected Result:
1. User should be redirected to "Products" page

Title:
Verify "Checkout" CTA directs user to "Your Information" page

Precondition:
1. User is logged in
2. User is in "your cart" page with product(s)

Steps:
1. Locate the "Checkout" CTA at the bottom right of the page
2. Click on CTA

Expected Result:
1. User should be redirected to "Your Information" page

Title:
Verify if user can enter valid credentials in "Your Information" page

Precondition:
1. User is logged in
2. User is in "Checkout: Your Information" page

Steps:
1. Enter your first name
2. Enter your last name
3. Enter your zip code

Expected Result:
1. User should be redirected to the "Checkout: Overview" page

Title:
Verify user cannot proceed to the "Checkout: Overview" page when the First Name field is blank

Precondition:
1. User is in "Checkout: Your Information" page

Steps:
1. Enter your last name
2. Enter your zip code

Expected Result:
1. Message "Error: First Name is required" should show

Title:
Verify user cannot proceed to the "Checkout: Overview" page when the Last Name field is blank

Precondition:
1. User is in "Checkout: Your Information" page

Steps:
1. Enter your First name
2. Enter your zip code

Expected Result:
1. Message "Error: Last Name is required" should show

Title:
Verify user cannot proceed to the "Checkout: Overview" page when the postal code field is blank

Precondition:
1. User is in "Checkout: Your Information" page

Steps:
1. Enter your First Name
2. Enter your Last Name

Expected Result:
1. Message "Error: "Postal code is required" should show

Title:
Verify Checkout Overview page displays successfully

Precondition:
1. User has added at least one item to the cart and completed the Checkout:Your Information step

Steps:
1. Proceed to Checkout: Overview

Expected Result:
1. Checkout Overview page loads successfully with no errors

Title:
Verify selected products are displayed on Checkout Overview page

Preconditon:
1. User is on Checkout: Overview

Steps:
1. Review the list of products

Expected Results:
1. All products added to the cart are displayed with the correct name, quantity, description, and price

Title:
Verify payment information is displayed

Precondition:
1. User is on Checkout: Overview

Steps:
1. Locate the Payment Information section

Expected Result:
1. Payment Information is displayed according to the application's expected behavior

Title:
Verify shipping information is displayed

Preconditions:
1. User is on Checkout: Overview

Steps:
1. Locate thr Shipping Information section

Expected Result:
1. Shipping Information is displayed correctly

Title:
Verify item total is calculated correctly

Precondition:
1. User has multiple items in the cart

Steps:
1. Calculate the sum of all product prices
2. Compare with the displayed item total

Expect Result:
1. The displayed Item Total matches the sum of the selected products

Title:
Verify tax amount is displayed

Preconditon:
1. User is on Checkout: Overview

Steps:
1. Review the Summary Information section

Expected Result:
1. Tax is displayed in the order summary

Title:
Verify total amount is calculated correctly

Preconditon:
1. User is on Checkout: Overview

Steps:
1. Add the Item Total and Tax
2. Compare with the displayed Total

Expected Result:
1. Total equals Item total plus Tax

Title:
Verify Cancel button returns user to the Inventory page

Preconditon:
1. User is on Checkout: Overview

Steps:
1. Click Cancel

Expected Result:
1. User is returned to the Inventory page and the checkout process is canceled

Title:
Verify Finish button completes the order

Preconditon:
1. User is on Checkout: Overview

Steps:
1. Click Finish

Expected Result:
1. Order is completed successfully and the Checkout Complete page is displayed

Title:
Verify Checkout Overview page displays correctly on mobile viewport

Precondition:
1. User is on Checkout: Overview in Blisk using an Iphone viewport

Steps:
1. Review page layout and content

Expected Result:
1. All order information, buttons, and summary sections are displayed correctly with no overlapping elements or horizontal scrolling


Title:
Verify user can log out successfully

Precondition:
1. User is logged in and on the Products page

Steps:
1. Open the navigation menu in the top left corner
2. Click Logout

Expected Result:
1. Use is redirected to the Login page and the session is terminated

Title:
Verify user cannot access the Products page after logging out

Precondition:
1. User has logged out successfully

Steps:
1. Click the browser's back button

Expected Result:
1. User is not able to access the Products page. User is redirected to the Login page or prompted to log in again

Title:
Verify protected pages cannot be accessed using the URL after logout

Precondition:
1. User has logged out successfully

Steps:
1. Enter thr Products page URL directly into the browser's address bar

Expected Result:
1. Access is denied and the user is redirected to Login page

Title:
Verify shopping cart contents persist after logut and subsequent login

Precondition:
1. User has added one or more items to the cart

Steps:
1. Add products to the cart
2. Log out
3. Log back in with the same account

Expected Result:
1. Cart contents are retained after logging back in.

Title:
Verify Logout option is available in the navigaiton menu

Precondition:
1. User is logged in

Steps:
1. Open the navigation menu

Expected Result:
1. Logout option is visible and selectable

Title:
Verify logout functionality on mobile viewport


Precondition:
1. User is logged in using Blisk with an iPhone viewport

Steps:
1. Open the navigation menu
2. Tap Logout

Expected Result:
1. User is logged out successfully and redirected to the Login page. Navigation menu functions c
