# Environment setup
```
npm install -g @bigcommerce/stencil-cli

npm install -g grunt-cli

npm install
```
# Tasks

- Hover effect on Prodcut Image.

- Display customer Information.

- Add all products to cart.

- Remove products from cart.

# Code Overview

### `assets/js/theme/test/addRemoveProduct.js`
- **`getCartAndProductsProperty()`**: This function checks the cart properties to determine whether to show or hide the "Add all to cart" and "Remove all from cart" buttons.
- **`addAllProductsToCart()`**: This function adds all the products to the cart.
- **`removeAllItems()`**: This function removes all products from the cart.

### `templates/test/category/card.html`
A copy of the card component, enhanced with a hover effect.

### `templates/pages/category.html`
The customer's email and phone number have been added to the category page.

### `assets/js/app.js`
Connection between the page and the corresponding JavaScript file.

# Used Features

Store Front API,  Handlebars, Global Setting, etc..

# Getting started
```
stencil init

stencil start
```

# Public Store URL and Preview Code

### URL
https://logan-palmer.mybigcommerce.com

### Preview Code
rc7bggrrga
