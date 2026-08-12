1. AUTHENTICATION

NTC-01 Login with invalid credentials

Modul: Authentication

Test Data: Username: invalid_user; password: wrong_password

Preconditions: SauceDemo website is available

Steps: 
- open the login page

- enter an invalid username

- enter an invalid password

- click Login

Expected Result: Login is not performed.The validation message is displayed indicating that the username and password do not match any user in this servise.

Test Type: Functional

Test Design Technique: Equivalance Partitioning


NTC-02 Login with empty required fields

Modul: Authentication

Test Data: Username: empty value; password: empty value

Preconditions: SauceDemo website is available

Steps: 
- open the Login page

-leave the Username field empty

- leave the Password field empty

- click the Login button

Expected Result: Login is not performed.A validation message is displayed indicating that the Username field is required.

Test Type: Functional

Test Technique: Equivalence Partitioning


2. PRODUCT CATALOG

NTC-03 Verify product catalog behavior with visual_user

Modul: Product Catalog

Test Data: Username: visual_user; password: secret_sauce

Precondition: The user is logged in as a visual_user.

Steps: 


- open the product page

- browse the product catalog

- verify the product images and layout

Expected Result: The product catalog remains functional.The visual defects do not prevent the user from browsing products.

Test Type: UI/Visual Testing

Test Technique: Checklist-based


 NTC-04 Verify product catalog behavior with incorrect product data

 Modul: Product Catalog

 Test Data: Username: problem_user; password: secret_sauce

 Preconditions: The user is logged out.Application is available.Valid problem_user credentials are available.

 Steps:
 - log in to the application using problem_ user credentials

 - verify that the product catalog page is displayed

 - review the displayed product cards in the catalog

 - compare the displayed product images,names,descriptions and prices with the corresponding product name and price

 - verify several products in the catalog

 Expected Result: Product image,name,description and price corresponds to the displayed product

 Test Type: Functional Testing

 Test Technique: Exploratory Testing

 3. SHOPPING CART

NTC-05  Attempt to proceed to checkout with an empty cart

Modul: Shopping Cart/Checkout

Test Data: Username: standart user; password: secret_sauce

Preconditions: User is logged in.Shopping cart is empty.

Steps: 
- open the shopping cart

- verify that the cart is empty

- attempt to proceed to checkout

Expected Result: The system prevent the user from proceeding to checkout with an empty cart and the checkout page is not opened.

Test Type:  Functional

Test Technique: Error Guessing


NTC-06 Verify remove product action is unavailable when the cart is empty

Module: Shopping Cart

Test Data: Username: standart_user; password: valid password

Preconditions: User is logged in.Shopping cart is empty.

Steps: 
- open the shopping cart

- verify that the shopping cart is empty

- verify that no Remove button/ action is available for product removal

Expected Result: The system does not provide a Remove action when the shopping cart is empty.

Test Type: Functional Testing

Test Technique: Negative Testing


4. CHECKOUT

NTC-07 Complete checkout with empty required field

Modul: Checkout

Test Data:- Username: standart_user;passworrd: secret_sauce

- Product: any available product

- User data: username

Preconditions: User is logged in.At least one product is added to the shopping cart.Shopping cart is not empty.

Steps: 
- open the shopping cart

- click Checkout

- leave the Last name field empty

- enter valid data into remaining required field

- click Continue

Expected Result: The system prevents the user from proceeding to the checkout overview and displays a validation message indicating that the Last Name field is required

Test Type: Functional Testing

Test Technique: Negative Testing







 

  

     



