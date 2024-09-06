<h1 align="center">E-Commerce Store </h1>
EverCart is a robust e-commerce platform that provides a seamless shopping experience for users and powerful management tools for administrators. With a modern tech stack and comprehensive features, EverCart offers a scalable solution for online retail.

### Features
Sign up / Sign in: Complete user authentication system, allowing users to register, log in, and manage profiles.
Product Browsing: Foundation of the e-commerce system, supporting product browsing, searching, and purchasing.
Shopping Cart: Intuitive shopping cart allowing users to add, remove, and update items before checkout.
Secure Checkout: Integrated Stripe to securely process payments, ensuring a smooth checkout experience with support for multiple currencies.
Discount Codes: Support for discount and promotional codes, allowing users to apply special deals at checkout.

### Admin Capabilities

Product Management: Admins can create, update, and manage products and categories easily through the platform.
Admin Dashboard: A dedicated dashboard for administrators to manage users, products, orders, and perform various administrative tasks.
Analytics: Visual sales data analytics to monitor performance, conversion rates, and other business metrics.

Technical Features

Authentication: Token-based authentication with JWT for session management, providing both access and refresh tokens.
Database: Integrated MongoDB as the primary database with Redis for caching to improve performance and handle large-scale operations.
Responsive Design: Clean, responsive, and customizable design using Tailwind CSS to ensure a great user experience across devices.
Performance Optimization: Using Redis to improve the performance of frequently accessed data, reducing load times.
Image Management: Integrated Cloudinary for efficient storage and delivery of product images.

### Tech Stack

Frontend: React, Redux
Backend: Node.js, Express.js
Authentication: JWT (JSON Web Tokens)
Database: MongoDB
Caching: Redis
Payment Processing: Stripe
Image Storage: Cloudinary
CSS Framework: Tailwind CSS

### Getting Started
```bash
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```
