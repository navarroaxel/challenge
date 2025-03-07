# Challenge

1. Objective:
Write a basic shopping cart in React and Redux.

1.2. Supplied: Products in an array (these do not require any editing).
```js
const products = [{
    name: “Sledgehammer”,
    price: 125.75
    }, {
    name: “Axe”,
    price: 190.50
    }, {
    name: “Bandsaw”,
    price: 562.13
    }, {
    name: “Chisel”,
    price: 12.9
    }, {
    name: “Hacksaw”,
    price: 18.45
}]
```
1.3.  Requirements: 
* The cart will need to keep it’s state during page loads / refreshes1
* List Products – these should be listed at all times to allow adding ofproducts
* Products should be listed in this format: product name, price, link to addproduct
* Must be able to add a product to the cart
* Must be able to view current products in the cart
* Cart products should be listed in this format: product name, price, quan-tity, total, remove link
* Product totals should be tallied to give an overall total
* Must be able to remove a product from the cart
* Adding an existing product will only update existing cart product quantity(e.g. adding the same product twice will NOT create two cart items)
* All prices should be displayed to 2 decimal places
* Error checking will be set to strict for viewing completed code
* Project will work as expected with the latest version of React
* Use best practices
