📝 `NOTE` Use this template to initialize the contents of a README.md file for your application. As you work on your assignment over the course of the week, update the required or stretch features lists to indicate which features you have completed by changing `[ ]` to `[x]`. (🚫 Remove this paragraph before submitting your assignment.)

## Week 2 Assignment: Student Store

Submitted by: **NAME**

Estimated time spent: **#** hours spent in total

Deployed Application (optional): [Student Store Deployed Site](https://natural-zipper.surge.sh)

### Application Features

#### REQUIRED FEATURES

- [x] The API should contain an endpoint that serves an array of all products in the store
- [x] An endpoint should exist for creating orders and saving them to a JSON file. Each order should contain the email of the person placing the order, the items associated with the order, and the quantity of each item purchased.
- [x] A Store model should handle all data management logic for the API and be the interface for read/write operations to the JSON file.
- [x] The frontend should include a landing page that displays the products available for purchase.
- [x] There should be a `Sidebar` component that appears on every page and has two states - `open` and `closed`. When the sidebar is opened, it should display a shopping cart of all the products the user currently has in their cart. It should also calculate and display the total amount in dollars for the checked-out items. When it's closed, the sidebar should be much thinner and not display its internal content.
- [x] Each product should have an individual page that shows the details of the product and allows the user to add that product to their shopping cart.
- [x] A checkout form should be available that allows the user to enter their email and send their order to the API.

#### STRETCH FEATURES

- [x] Deploy your website with Heroku & Surge. 
- [x] Create an endpoint that serves only a single product based on the product's id
- [x] Create an endpoint for fetching all orders in the database, and an endpoint for serving an individual order based on its id.
- [x] Build a page in the UI that displays the list of all past orders and lets the user click on any individual order to take them to a more detailed page of the transaction.
- [x] Allow users to use an input to filter orders by the email of the person who placed the order.

### Walkthrough Video
![ezgif com-gif-maker (9)](https://user-images.githubusercontent.com/68205883/171754798-dd09ee1b-9268-48e5-90c5-a1faf5309fd5.gif)

![ezgif com-gif-maker (8)](https://user-images.githubusercontent.com/68205883/171754088-963cbd03-5849-4e29-b221-f2ca25ea5045.gif)

![ezgif com-gif-maker (7)](https://user-images.githubusercontent.com/68205883/171754090-900573e7-7add-4128-b779-ec7caf739649.gif)

![ezgif com-gif-maker (6)](https://user-images.githubusercontent.com/68205883/171754095-c39b06dc-62f9-417b-94a6-2cf2f16f44d7.gif)
