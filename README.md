

# Adviteey

Adviteey is a full-stack e-commerce web application built with Node.js, Express, MongoDB, React, Redux, and Stripe. It includes user authentication, product browsing, cart and checkout flows, order management, admin controls, and payment integration.

## Features

- User registration, login, and password reset
- Product listing, search, filters, and product details
- Shopping cart and checkout with shipping information
- Stripe-based payment processing
- Order history and order detail views
- Admin dashboard for products, orders, users, and reviews
- Contact and About pages

## Tech Stack

- Frontend: React, Redux, Material UI, React Router
- Backend: Node.js, Express.js
- Database: MongoDB with Mongoose
- Authentication: JSON Web Tokens and cookies
- Payments: Stripe
- File uploads: Cloudinary

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/icarusburns/adviteey.git
   cd adviteey
   ```
2. Install backend dependencies
   ```bash
   npm install
   ```
3. Install frontend dependencies
   ```bash
   npm install --prefix frontend
   ```
4. Create a config file at backend/config/config.env and add the required environment variables.
5. Start the backend server
   ```bash
   npm run dev
   ```
6. Start the frontend development server
   ```bash
   npm start --prefix frontend
   ```

## Environment Variables

Create a file named config.env in the backend/config directory and add the following variables:

```env
PORT=4000
DB_URI=your_mongodb_connection_string
STRIPE_API_KEY=your_stripe_public_key
STRIPE_SECRET_KEY=your_stripe_secret_key
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=5d
COOKIE_EXPIRE=5
SMPT_SERVICE=gmail
SMPT_MAIL=your_email
SMPT_PASSWORD=your_email_password
SMPT_HOST=smtp.gmail.com
SMPT_PORT=465
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

## Project Structure

- backend/: Express server, routes, controllers, models, middleware
- frontend/: React application and UI components
- Procfile: Heroku deployment configuration

## Deployment

The project includes a Heroku-friendly Procfile and a production build step for the React frontend.

## Author

Built as a full-stack e-commerce project for Adviteey.


