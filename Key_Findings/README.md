BROWSER-SIDE BEHAVIOR OBSERVED DURING TESTING SAUCEDEMO:

- A session cookie is created after successful authentication.

- Deleting the session cookie during an active session redirects the user to the Logi page.

- The cart-contents value in Local Storage changes when products are added or removed from the cart.

- Modifying the cart-contents value directly in Local Storage can cause the browser-side cart counter to display a product while the actual cart remains empty.

- When the network is switched to Offline mode, the application continues attempting network requests,but the requests fail and the response data is unavailable.

- Some user accounts demostrate different application behavior,sugh as incorrect product images/descriptions for problem_user.

- Checkout form validation accepts any non-empty values for the required fields.Validation is triggered only when a required field is left empty.
