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

Test Data: 



