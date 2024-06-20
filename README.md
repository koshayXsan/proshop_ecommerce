# E-commerce Website (Clone from bradtraversy MERN COURSE)

This project is a fully functional e-commerce website built using the MERN stack (MongoDB, Express, React, Node.js). The platform features user authentication, product listings, a shopping cart, and secure payment processing.
I built this project to hone my web development skills and gain a strong foundation in this field.

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
   
Usage

- Create a MongoDB database and obtain your MongoDB URI - MongoDB Atlas
- Create a PayPal account and obtain your Client ID - PayPal Developer

Env Variables
- Rename the .env.example file to .env and add the following

- NODE_ENV = development
- PORT = 5000
- MONGO_URI = your mongodb uri
- JWT_SECRET = 'abc123'
- PAYPAL_CLIENT_ID = your paypal client id
- PAGINATION_LIMIT = 8
- Change the JWT_SECRET and PAGINATION_LIMIT to what you want



Install Dependencies (frontend & backend)
npm install
cd frontend
npm install

# Run 
- frontend (:3000) & backend (:5000)
- npm run dev


# Run backend only
- npm run server


# Build & Deploy
- Create frontend prod build
- cd frontend
- npm run build

  
## Acknowledgments

This project is based on the work of bradtraversy Their original project can be found https://github.com/bradtraversy/proshop-v2/tree/main .



# License
-This is the original license of the author whose work I have followed to create this project
- The MIT License
Copyright (c) 2023 Traversy Media https://traversymedia.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

