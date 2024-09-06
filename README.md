<h1 align="center">E-Commerce Store</h1>

<p>EverCart is a robust e-commerce platform that provides a seamless shopping experience for users and powerful management tools for administrators. With a modern tech stack and comprehensive features, EverCart offers a scalable solution for online retail.</p>

<h2 id="features">Features</h2>

<ul>
  <li>
    <h3 id="sign-up--sign-in">Sign up / Sign in</h3>
    <p>Complete user authentication system, allowing users to register, log in, and manage profiles.</p>
  </li>
  <li>
    <h3 id="product-browsing">Product Browsing</h3>
    <p>Foundation of the e-commerce system, supporting product browsing, searching, and purchasing.</p>
  </li>
  <li>
    <h3 id="shopping-cart">Shopping Cart</h3>
    <p>Intuitive shopping cart allowing users to add, remove, and update items before checkout.</p>
  </li>
  <li>
    <h3 id="secure-checkout">Secure Checkout</h3>
    <p>Integrated Stripe to securely process payments, ensuring a smooth checkout experience with support for multiple currencies.</p>
  </li>
  <li>
    <h3 id="discount-codes">Discount Codes</h3>
    <p>Support for discount and promotional codes, allowing users to apply special deals at checkout.</p>
  </li>
</ul>

<h2 id="admin-capabilities">Admin Capabilities</h2>

<ul>
  <li>
    <h3 id="product-management">Product Management</h3>
    <p>Admins can create, update, and manage products and categories easily through the platform.</p>
  </li>
  <li>
    <h3 id="admin-dashboard">Admin Dashboard</h3>
    <p>A dedicated dashboard for administrators to manage users, products, orders, and perform various administrative tasks.</p>
  </li>
  <li>
    <h3 id="analytics">Analytics</h3>
    <p>Visual sales data analytics to monitor performance, conversion rates, and other business metrics.</p>
  </li>
</ul>

<h2 id="technical-features">Technical Features</h2>

<ul>
  <li>
    <h3 id="authentication">Authentication</h3>
    <p>Token-based authentication with JWT for session management, providing both access and refresh tokens.</p>
  </li>
  <li>
    <h3 id="database">Database</h3>
    <p>Integrated MongoDB as the primary database with Redis for caching to improve performance and handle large-scale operations.</p>
  </li>
  <li>
    <h3 id="responsive-design">Responsive Design</h3>
    <p>Clean, responsive, and customizable design using Tailwind CSS to ensure a great user experience across devices.</p>
  </li>
  <li>
    <h3 id="performance-optimization">Performance Optimization</h3>
    <p>Using Redis to improve the performance of frequently accessed data, reducing load times.</p>
  </li>
  <li>
    <h3 id="image-management">Image Management</h3>
    <p>Integrated Cloudinary for efficient storage and delivery of product images.</p>
  </li>
</ul>

<h2 id="tech-stack">Tech Stack</h2>

<ul>
  <li>
    <h3 id="frontend">Frontend</h3>
    <p><strong>React</strong>, <strong>Redux</strong></p>
  </li>
  <li>
    <h3 id="backend">Backend</h3>
    <p><strong>Node.js</strong>, <strong>Express.js</strong></p>
  </li>
  <li>
    <h3 id="authentication-1">Authentication</h3>
    <p><strong>JWT (JSON Web Tokens)</strong></p>
  </li>
  <li>
    <h3 id="database-1">Database</h3>
    <p><strong>MongoDB</strong></p>
  </li>
  <li>
    <h3 id="caching">Caching</h3>
    <p><strong>Redis</strong></p>
  </li>
  <li>
    <h3 id="payment-processing">Payment Processing</h3>
    <p><strong>Stripe</strong></p>
  </li>
  <li>
    <h3 id="image-storage">Image Storage</h3>
    <p><strong>Cloudinary</strong></p>
  </li>
  <li>
    <h3 id="css-framework">CSS Framework</h3>
    <p><strong>Tailwind CSS</strong></p>
  </li>
</ul>

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
