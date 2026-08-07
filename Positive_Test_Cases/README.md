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
