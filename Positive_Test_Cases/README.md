1. AUTHENTIFICATION

TC-P-001 Login with valid credentials

- Module: Authentification

- Preconditions: SauceDemo website is available

- Test Data: username- standart_user/ password- secret_sauce

- Steps: - open the login page

- enter a valid username

- enter a valid password

- click Login

- Expected Result: User is successfully logged in and redirected tothe Product page

- Test Type: Functional

- Test Desing Technique: Equivalance Partitioning


TC-P-002   Verify  susseccful logout

- Module: Authentification

- Preconditions: Saucedemo is available. The user is already logged in the system

- Test Data : username - standart_user/ password - secret_sauce

- Steps:- log in the system

- open the menu

- click Logout

- Expected Result: User is redirected to the Login page.Session is terminated.Protected pages are no longer accessible without loggining in again.

- Test Type: Functional

- Test Design Technique: State Transition testing


 2. PRODUCT CATALOG

TC-P-003  Verify product catalog browsing

- Module: Product Catalog

- Preconditions: The user is successfuly logged in the application

- Test Data: username - standart_user/ password - secret_sauce

- Steps:

- open the Product page

- browse the product catalog

- verify that product names,images and prices are displayed

- Expected Result: The Product page is displayed.The product catalog is loaded successfuly.Product images,names,prices and Add to the cart button is displayed correctly

- Test Type: Functional

- Test Design Technique: Exploratory Testing


TC-P-004 Verify that product details are displayed correctly

- Module: Product Catalog

- Preconditions: User is successfuly logged in the application.The Products page is displayed.

- Test Data: Product: any available product

- Steps:

- select a product from the product catalog

- click on the product image

- verify that product details are displayed

- Expected Result: The product name,description,price and Add to the cart button are dispalyed after the user clickcs on the product image

- Test Type: Functional

- Test Design Technique: Exploratory Testing


TC-P-005 Verify  UI using visual_user

- Module: Product catalog

- Preconditions: The user is successfuly logged in the application using visual_user.The Products page is displayed

- Test Data: username - visual_user / password - secret_sause

- Steps: - browse the product catalog

- verify the visibility and visual rendering of the product images,names,prices and Add to the Cart buttons.

- Expected Result: The Product Page  and its UI elenents are displayed correctly without visible alignment or rendering issues.

- Test Type: UI Testing

- Test Techniques: Exploratory Testing



3. SHOPPING CART

TC-P-006 Verify that the user can add one item to the cart

Module: Shopping Cart

Preconditions: The user is logged in the application.The Product page  and its UI elements are displayed.

Test Data: Product: Sauce Labs Backpack

Quantity: 1

Steps: - log in the application

- open the Product Page

- click " Add to cart" button for sauce Labs Backpack

- open the shopping cart

Expected Result: The selected product is displayed in the shopping cart with the correct name,price and quantity.

Test Type: Functional

Test Technique: State Transition 


TC-P-007 Verify that the  user can add several items to the cart

Module: Shopping Cart

Preconditions: The user is logged in the application. The Product Page and its UI elements are displayed

Test Data: Products: Sauce Labs Backpack,Sauce Labs Bike Light,Sauce Labs Bolt T-Shirt

Quantity: 1 each

Steps: - log in the application

- open the product page

- click "Add to the cart" button for each item

- open the shopping cart

Expected Result: The selected products are displayed in the shopping cart with correct name,price and quantity

Test Type: Functional

Test Technique: State Transition



TC-P-008 Verify that the user can remove the product from the cart

Module: Shopping Cart

Preconditions: The products are displayed in the shopping cart

Test Data: Product: Sauce Labs Bolt T-Shirt

Quantity: 1

Steps: - log in the application

- open the Product Page

- click "Add to the cart" button

- open the shopping cart

- click on "Remove" button

Expected Result: The product is successfully removed from the shopping cart.The product is no longer displayed in the shopping cart.

Test Type: Functional

Test Technique: State Transition


4. CHECKOUT

TC-P-009 Verify the checkout completion

Modul: Checkout

Preconditions: The product is displayed in the shopping cart

Test Data: first name,last name,zip/postal code

Steps: - log in the application

- open the product page

- click on the "Add to the cart" button

- open the shopping cart

- click on "Checkout" button

- enter the user data: fist name,last name,zip/postal code

- click on "Continue" button

- verify the order overview

- click " Finish"

Expected Result:The checkout is successfully completed.The order confirmation message  is displayed.

Test Type: Functional

Test Technique: State Transition


TC-P-010 Verify order details on checkout overview page

Module: Checkout

Preconditions: The user is logged into application.At least one product is added to the shopping cart.

Test Data:user data: first name,last name,zip/postal code

Steps: - open the shopping cart

- click" Checkout"

- enter valid customer information

- click "Continue"

- verify the order details

Expected Result: The Checkout overview is displayed with the correct product and its description,correct product quantity,correct price including item total,tax and total price,also the " Finish" button is displayed.

Test Type: Functional

Test Technique: Decision Table Testing


5.CHROME DEvTOOLS

TC-P-011 Verify Network request when opening the Product Page

Module: Chrome DevTools

Preconditions: The user is successfully logged in to the application.Chrome DevTools is opened.The Network tab is selected.

Test Data: Username: standart_user; password: secret_sauce

Steps:
- log into the application

- open the product page

- open Chrome DevTools

- navigate to the Network tab

- select the Doc filter

- select the page document request

- open the Headers tab

- verify the status code is 200 OK

- verify the Content-Type response headers is text/html

- open the Response tab

-verify that the response contains HTML content

Expected Result: The page document request is successfully completed with status code 200 OK.The Response contains HTML content and the Content-Type header is text/html.

Test Type: Functional

Test Technique: Checklist-based Testing


TC-P-012 Verify Cookies



