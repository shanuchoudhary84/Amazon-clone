# Amazon Clone using MERN Stack with Stripe Integration

This project is a clone of the popular e-commerce platform Amazon, built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. Additionally, it integrates Stripe for payment processing.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Amazon Clone project aims to replicate the core functionalities of the Amazon website, including user authentication, product browsing, cart management, order placement, and payment processing. It utilizes the MERN stack to build a scalable web application and integrates Stripe for secure online transactions.

## Features

- **User Authentication**: Sign up, log in, and log out securely using bcrypt for password hashing.
- **Product Browsing**: Browse products, search for specific items, and filter products by category.
- **Product Details**: View detailed product information, including description, price, and images.
- **Shopping Cart**: Add products to the shopping cart, adjust quantities, and remove items.
- **Checkout Process**: Proceed to checkout, enter shipping and payment details, and place orders securely.
- **Stripe Integration**: Secure payment processing using Stripe for credit/debit card payments.

## Setup

To run this project locally, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install dependencies by running `npm install` in both the client and server directories.
4. Set up environment variables:
   - Create a `.env` file in the server directory.
   - Define the following variables:
     - `MONGODB_URI`: MongoDB connection URI.
     - `BCRYPT_SALT_ROUNDS`: Number of bcrypt salt rounds for password hashing.
     - `STRIPE_SECRET_KEY`: Secret key for accessing Stripe API.
5. Start the MongoDB server.
6. Start the server by running `npm start` in the server directory.
7. Start the client by running `npm start` in the client directory.

## Usage

Once the project is set up and running, you can access it in your web browser. Here's how to use it:

1. Sign up for a new account or log in with existing credentials.
2. Browse products by category or search for specific items.
3. Click on a product to view its details and add it to your cart.
4. Review items in your cart, adjust quantities if needed, and proceed to checkout.
5. Enter shipping information and payment details.
6. Place your order securely using Stripe.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

- Fork the repository and create a new branch for your feature or bug fix.
- Make your changes and test them thoroughly.
- Ensure your code follows the project's coding style and conventions.
- Write clear, concise commit messages.
- Submit a pull request, explaining the changes you've made and any potential impact.

## License

This project is licensed under the [MIT License](LICENSE).
#   A m a z o n  
 