# Technical Interview Task - React

Welcome to the HomeServe Finance technical task. 

HomeServe Finance is the newest innovation under the globally recognised HomeServe banner. As a fresh venture, we aim to solve the problem of CO2 emissions created by home heating and cooling. Using our parent company’s robust infrastructure and extensive reach, we are redefinining the point-of-sale lending industry, making new renewable technology accessible and affordable to every homeowner. At HomeServe Finance, we are dedicated to developing secure, accessible, and tailored financial solutions that meet the planet’s need to transition away from fossil fuel home heating and accelerate the transition to efficient, renewable energy-powered homes.

> ⚠️ Please do not upload your solutions to public repositories on GitHub or
> other publicly available or indexed spaces on the internet. Doing so can allow
> future applicants to reference your solution and undermine the integrity of
> the test.
>
> Obviously we want all current and future candidates to be on an even playing
> field and we don't want to have to keep writing new tests (and new assessment
> notes and criteria) each time we do a round of interviews. We thank you for
> your understanding and cooperation in this respect. 🙂


## Objective
Build a small e-commerce product dashboard using React, where users can view products, search, filter by category, and add items to a shopping cart. The task uses the Fake Store API to fetch product data and simulate a basic e-commerce platform.

## API Information
This task uses a free online REST API - [FakeStoreAPI](https://fakestoreapi.com). Their API documentation can be found [here](https://fakestoreapi.com/docs).

## Requirements

### <ins>Functional Requirements</ins>

First 4 functionalities are required to be implemented as part of this technical task. Rest 3 are optional.

##### 1. Product Listing Page

- Fetch and display a list of products from the Fake Store API (`/products`).
- Each product card should display the product image, title, price, and a short description.
- Implement a "Load More" button to paginate through products (client-side pagination).

##### 2. Search Functionality

- Add a search bar that allows users to search products by title.

##### 3. Category Filter

- Fetch available categories from the `/products/categories` endpoint and allow users to filter products by category.

##### 4. Sorting

- Provide sorting options for:
    - Price (ascending/descending)
    - Alphabetical order by product title

##### 5. Shopping Cart

- Allow users to add products to a shopping cart.
- Show the cart with a summary of selected items (product title, quantity, total price).
- Store the cart in local storage so that the cart persists on page reloads.

##### 6. Product Detail View

- When a product card is clicked, display the product’s detailed information (e.g., full description, price, category) on a separate page.

##### 7. Error Handling & Loading States

- Display loading states while fetching data from the API.
- Gracefully handle and display errors in case of failed API requests.


### <ins>UI/UX Requirements</ins>

1. Use a clean, responsive design to ensure the dashboard looks good on both desktop and mobile devices.

2. The user interface should be intuitive, and actions such as adding to the cart should provide visual feedback.

### <ins>Technical Requirements</ins>

1. Use React and React Hooks. 

2. Use a state management solution of your choice (Context API, Redux, etc.).

3. Handle API requests using fetch or Axios.

4. Write modular and reusable components (e.g., ProductCard, ProductList, Cart, etc.).

5. Use CSS frameworks or libraries like Tailwind, Material UI, or Bootstrap for styling, or write custom CSS.

6. Ensure that the cart data is persistent using localStorage. (Only if cart functionality is implemented)

7. Write unit tests for at least one of the components using a testing library like Jest or React Testing Library.

### <ins>Bonus Features</ins>

- Wishlist: Implement a wishlist feature where users can mark favorite products.

- Product Reviews: Fetch and display reviews for each product.

## Submission

- Provide a link to a GitHub repository with your solution.

- Include a README file with instructions on how to set up and run the project.


## Evaluation Criteria

- Code quality, structure, and maintainability.

- Proper use of React components, hooks, and state management.

- User interface design and responsiveness.

- Error handling and feedback to users.

- Bonus points for additional features and good test coverage.