# Vue 3 Online Store

An online store built with Vue 3 that allows users to browse products, add them to a cart, and view their total amount. The app features a simple and responsive layout, with easy-to-use components for an intuitive shopping experience.

## Features
- Product Listing: Browse a variety of products with their names, prices, and images.
- Add to Cart: Easily add products to the cart, with quantities automatically adjusted for duplicate items.
- Cart Management: View cart items, remove items, and see the total price of items in the cart.
- Responsive Design: The layout adjusts for various screen sizes, making it mobile-friendly.

## Technologies Used
- Vue 3: For building reactive components.
- CSS & TailwindCSS: Styling the UI with a combination of custom CSS and utility-first TailwindCSS.
- Material Icons: Used for shopping cart, delete, and close icons.

## Components Overview
- App.vue: Main component managing the layout, data, and communication between child components.
- ProductList.vue: Displays the list of products and emits events when a product is added to the cart.
- CartList.vue: Manages and displays items in the cart, including total calculations and removal of items.

## Project Structure
```
bash
.
├── public                # Static assets (e.g., images)
├── src
│   ├── assets            # Application-specific assets
│   ├── components        # Vue components (ProductList, CartList)
│   ├── App.vue           # Main app component
│   ├── main.js           # Entry point for Vue app
├── package.json          # Project metadata and dependencies
└── README.md             # Project documentation
```

## Component Details
- App.vue: Contains the main layout, including the header and the dynamic cart view. Manages the cart state, including visibility, adding/removing items, and calculating totals.
- ProductList.vue: Displays each product with an "Add to Cart" button. Emits an event to the parent when a product is added.
- CartList.vue: Shows the items in the cart, their quantity, and total cost. Provides functionality to remove items from the cart.

## Installation

1. Clone the repository:
 ```
git clone https://github.com/your-username/vue-online-store.git
cd vue-online-store
```  

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
