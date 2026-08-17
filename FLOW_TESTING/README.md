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

 Expected: Product catalog is displayed and products are available for selection.

 3.Product Details

 - open the selected product

Expected: Product details page is displayed with the selected product information

4.Add Product to the Cart

- add Sauce Lab Backpack to the cart

Expected: Product is added to the shopping cart and cart indicator is updated.

5.Shopping Cart

- open the shopping cart

Expected: The selected product is displayed in the cart with the correct information.

6. Checkout

- Proceed to checkout and enter valid customer information

Expected: Checkout information is accepted and the user proceeds to the checkout overview page.

7. Order Overview

- review the order overview

Expected: The selected product,quantity,price and total amount are displayed correctly.

8.Complete Order

- click Finish

Expected: The order is successfully completed and the confirmation page is displayed.

