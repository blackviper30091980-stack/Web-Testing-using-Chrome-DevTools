1. INTRODUCTION

This document contains valid and invalid test data used during manual testing of the SauceDemo application.

The data supports functional testing ,validation testing,positive and negative scenarios, and different test design techniques,uncluding Equivalance Partitioning,Boundary Value analysis,Decision Table Testing,Error Guessing and Exploratory Testing.

2.LOGIN TEST DATA

Valid Credentials

USERNAME  /  PASSWORD  /  NOTE

standart_user  /  secret_sauce  /  Satandart user

problem_user  /   secret_sauce  /  Used for UI issue testing

visual_user  /    secret_sauce  /  Used for visual testing

performance_glitch_user  /  secret_sauce  /  Used for performance testing


Invalid Credentials

USERNAME  /  PASSWORD  /  TEST PURPOSE

standart_user  /  wrong_password  /  invalid password

non-existing_username  /  secret_sauce  /  invalid username

non-existing_usernme  /  wrong_password  /  both credentials invalid

(empty)  /  secret_sauce /  empty username

standart_user  /  (empty)  /  empty password

(empty)  /  (empty)  /  both fields empty


3. CHECKOUT TEST DATA

First Name/Last name

Valid data: Latin lowecase and capital letters, hyphen,apostrophes,diacritics

invalid data: figures,special symbols( excepting hyphen and apostrophes),null,empty field,very long value

Zip/Postal Code

Valid data: integer value

Invalid data: empty value, letters,letters+ numbers,special symbols,too long value

 4. BROWSER TEST DATA

Cookies

Test Data   /   Purpose

Existing cookies  /  Verify authentification session

Deleted cookies  /  Verify user logout/session expiration


Local Storage

Test Data  /  Purpose

Existing Local Storage  /  Verify saved session or preferences

Cleared Local Storage  /  Verify application behavior after Storage reset

Cache

Test Data  /  Purpose

Cached resources  /  Verify normal page loading

Cleared cache  /   Verify application loads fresh resources

Browser Conditions

Test Data  /  Purpose

Normal network  /  Standart application behavior

Slow 3G  /  verify loading under poorr network conditions

Offline mode  /  Verify application behavior without Internet

Viewport Sizes /  Purpose

Desktop(1920-1080)  /  Desktop UI

Laptop(1366-768)  /  Common laptop resolution

Mobile(390-844)  /  Mobile responsive layout


