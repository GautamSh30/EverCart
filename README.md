<h1 align="center">E-Commerce Store 🛒</h1>

Features

-Database & Integration
🗄️ MongoDB & Redis Integration
Seamlessly integrated MongoDB as the primary database with Redis for caching to improve performance and handle large-scale operations.

-Payment Processing

💳 Stripe Payment Setup
Integrated Stripe to securely process payments, ensuring a smooth checkout experience with support for multiple currencies.

-Authentication & Security

🔐 Robust Authentication System
Implemented a secure authentication flow for both users and admins, ensuring access control to sensitive areas.

🔑 JWT with Refresh/Access Tokens
Token-based authentication with JWT for session management, providing both access and refresh tokens.

🔒 Security
Designed with modern security practices such as password encryption, protection against SQL injection, and prevention of XSS attacks.

🛡️ Data Protection
Emphasizing user data privacy with encryption techniques and secure transmission protocols.

-User Management

📝 User Signup & Login
Complete user authentication system, allowing users to register, log in, and manage profiles.

-E-Commerce Core

🛒 E-Commerce Core
Foundation of the e-commerce system, supporting product browsing, searching, and purchasing.

📦 Product & Category Management
Admins can create, update, and manage products and categories easily through the platform.

🛍️ Shopping Cart Functionality
Interactive shopping cart allowing users to add, remove, and update items before checkout.

💰 Checkout with Stripe
Fully integrated checkout process with Stripe for handling payments securely.

🏷️ Coupon Code System
Discount and promotional code support, allowing users to apply special deals at checkout.

-Admin Dashboard

👑 Admin Dashboard
A dedicated dashboard for administrators to manage users, products, orders, and perform various administrative tasks.

📊 Sales Analytics
Visual sales data analytics to monitor performance, conversion rates, and other business metrics.
-User Experience & Design

🎨 Design with Tailwind
Clean, responsive, and customizable design using Tailwind CSS to ensure a great user experience across devices.

-Performance & Scalability

🚀 Caching with Redis
Using Redis to improve the performance of frequently accessed data, reducing load times.

-Shopping Experience

🛒 Cart & Checkout Process
Smooth cart and checkout flow, allowing customers to complete their orders efficiently.

### Setup .env file

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
