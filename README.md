﻿# flash-shop
# Flash Shop - A Simple E-commerce Application

Flash Shop is a basic, client-side e-commerce web application built using HTML, CSS, and vanilla JavaScript. It demonstrates core e-commerce functionalities such as product listing, adding items to a shopping cart, and a detailed price breakdown.

## Features

-   **Product Catalog:** Browse through a list of available products with details like name, brand, price, and rating.
-   **Product Details:** Each product card displays its image, brand, current price, original price, and discount percentage.
-   **Rating Filter:** Filter products based on their star ratings (e.g., 4 stars & above).
-   **Shopping Cart:** Add products to your cart.
-   **Cart Management:** View items in your cart and remove them.
-   **Price Summary:** Get a detailed breakdown of the total price, discount applied, and delivery charges on the cart page.
-   **Local Storage Persistence:** Cart data is stored in the browser's local storage, so items remain in the cart even after closing the browser tab.

## Technologies Used

-   **HTML5:** For structuring the web pages.
-   **CSS3:** For styling and layout, including a custom stylesheet and a UI component library (uilight.netlify.app).
-   **JavaScript (Vanilla JS):** For all dynamic functionalities, including DOM manipulation, event handling, and data management.
-   **Material Icons:** For various icons used throughout the application.

## Project Structure
flash-shop/
├── index.html            # Home page with product listings and filters
├── cart.html             # Shopping cart page with order summary
├── style.css             # Main stylesheet for the application
├── index.js              # JavaScript for home page logic (product rendering, add to cart, filtering)
├── cart.js               # JavaScript for cart page logic (cart display, remove from cart, price calculation)
├── createProductCard.js  # Utility to create vertical product cards for the home page
├── createHorizontalProductCard.js # Utility to create horizontal product cards for the cart page
└── db/
└── products.js       # Product data (mock database)
└── utils/
└── findProductInCart.js # Utility function to check if a product is in the cart
└── README.md             # Project documentation (this file)


## How to Run Locally

To get a copy of the project up and running on your local machine, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/flash-shop.git](https://github.com/YOUR_USERNAME/flash-shop.git)
    ```
    (Replace `YOUR_USERNAME` with your GitHub username)
2.  **Navigate to the project directory:**
    ```bash
    cd flash-shop
    ```
3.  **Open `index.html`:** Simply open the `index.html` file in your web browser. You can usually do this by double-clicking the file.

## Future Enhancements (Ideas for further development)

-   Implement full search functionality.
-   Add quantity increase/decrease for items in the cart.
-   Integrate a wishlist feature.
-   Implement actual order placement (backend integration).
-   Improve responsiveness for various screen sizes.
-   Add sorting options (e.g., by price, by discount).
-   Implement a basic authentication system.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and create a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).
