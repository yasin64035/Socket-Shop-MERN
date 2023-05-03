
# MERN Stack E-commerce Website

This is a fully functional e-commerce website built using the MERN stack (MongoDB, Express, React, Node.js) and Socket.io for real-time communication. The website allows users to browse products, add them to their cart, and checkout securely using Stripe payment gateway.


## Features
* User authentication and  authorization using JWT tokens
* Real-time communication using Socket.io
* Product search and filtering
* Product reviews and ratings
* Shopping cart and checkout functionality
* Integration with Stripe payment gateway
* Admin dashboard for managing products, orders, and users ,  analytics , chat, products.


## Technologies Used
MongoDB
Express.js
React.js
Node.js
Socket.io
Stripe API
## Installation

* Clone the repository
* Install dependencies using npm install
* Create a .env file in the root directory and add the following environment variables:

```bash
  NODE_ENV=development
PORT=5000
MONGO_URI=<your_mongodb_uri>
JWT_SECRET=<your_jwt_secret>
STRIPE_SECRET_KEY=<your_stripe_secret_key>

```

* Run the full app from the backend using npm run dev
* Run the client using npm run client
* Open http://localhost:3000 in your browser
    
