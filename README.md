
# Shopper

**Shopper** is an e-commerce web application for selling watches online. It includes features for product management, user authentication, shopping cart functionality, and order management.

## Features

- **Product Management:** Add, update, delete, and view watches. Admin interface for managing products.
- **User Authentication:** User registration, login, and JWT-based authentication with session management. Role-based access (admin and customer).
- **Shopping Cart & Checkout:** Add products to the cart, complete the checkout process, and integrate with payment gateways (e.g., Stripe or PayPal).
- **Order Management:** View and manage orders, track order status.

## Installation

### Prerequisites

- Node.js (v12 or higher)
- MongoDB
- NPM

### Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/MujtabaCoder/shopper
   cd Shopper
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Set Up Environment Variables:**

   Create a `.env` file with the following:

   ```env
   MONGO_URI=mongodb://localhost:27017/shopper
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. **Start MongoDB:**

   ```bash
   mongod
   ```

5. **Seed the Database (optional):**

   ```bash
   npm run seed
   ```

6. **Start the Application:**

   ```bash
   npm start
   ```

   Open `http://localhost:3000` in your browser.

## Screenshots

![Homepage](src/public/images/scrshoot1.png)
*Homepage*

![Product Listing](src/public/images/scrshoot2.png)
*Product Listing*

![Single Product Listing](src/public/images/scrshoot3.png)
*Single Product Listing*

![Shopping Cart](src/public/images/scrshoot4.png)
*Shopping Cart*

![Checkout](src/public/images/scrshoot5.png)
*Checkout*

![Payment](src/public/images/scrshoot6.png)
*Payment*

![admin for uplodaing product Dashboard](src/public/images/scrshoot7.png)
*Admin Dashboard*

![admin  Dashboard for product lisitng ](src/public/images/scrshoot8.png)
*Admin Dashboard*

![admin Dashboard to manage  order management ](src/public/images/scrshoot9.png)
*admin Dashboard to manage  order  management*





## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. .
```
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.