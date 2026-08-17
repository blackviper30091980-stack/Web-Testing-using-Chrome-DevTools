FLOW TESTING

Complete E2E shopping flow with DevTools checkpoints

Modul: End-to-End/Shopping flow

Test Data: 
- username: standart_user

- password: valid password

- product: Sauce Lab Backpack

- checkout data: valid First Name,Last Name,Zip/Postal Code


Preconditions: User account exists.User is logged out.Shopping cart is empty. Network connection is available.Chrome DevTools is open.


Steps: 1.Login

- log in with valid credentials

Expected: User is successfully authenticated and redirected to the Product page.

2.Product Catalog

- Browse the product catalog

 Expected: Product catalog is displayed and products are available for selection
