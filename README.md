# E-commerce Website

This project is a fully functional e-commerce website built using the MERN stack (MongoDB, Express, React, Node.js). The platform features user authentication, product listings, a shopping cart, and secure payment processing.

## Features

- User authentication (registration and login)
- Product listings with detailed information
- Shopping cart functionality
- Secure payment processing
- Order management for users
- Admin panel for managing products, users, and orders
- Responsive design for mobile and desktop views

## Technologies Used

- **Frontend**: React, Redux, Bootstrap
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Payment Gateway**: Stripe
- **Deployment**: Deployed on a render

## Installation

1. **Clone the repository**:
   ```bash
   

Usage

- Create a MongoDB database and obtain your MongoDB URI - MongoDB Atlas
-Create a PayPal account and obtain your Client ID - PayPal Developer

Env Variables
Rename the .env.example file to .env and add the following

NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
PAGINATION_LIMIT = 8
Change the JWT_SECRET and PAGINATION_LIMIT to what you want



Install Dependencies (frontend & backend)
npm install
cd frontend
npm install
Run

# Run frontend (:3000) & backend (:5000)
npm run dev


# Run backend only
npm run server

Build & Deploy
# Create frontend prod build
cd frontend
npm run build


