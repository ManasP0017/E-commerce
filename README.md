## 👨‍💻 Created by: Manas Pant (22BBS0135)

This is a full-stack E-Commerce web application built as part of my learning and exploration of modern web development technologies. The project integrates secure authentication, payment processing, caching, and an intuitive admin dashboard.

---

## 📚 About This Project

- 🚀 **Project Setup & Structure**
- 🗄️ **MongoDB & Redis Integration**
- 💳 **Stripe Payment Gateway**
- 🔐 **Robust Authentication System**
- 🔑 **JWT with Refresh/Access Tokens**
- 📝 **User Signup & Login Functionality**
- 🛒 **Core E-Commerce Features**
- 📦 **Product & Category Management**
- 🛍️ **Shopping Cart System**
- 💰 **Checkout Integration with Stripe**
- 🏷️ **Coupon Code System**
- 👑 **Admin Dashboard with Management Tools**
- 📊 **Sales Analytics Dashboard**
- 🎨 **Frontend Styling with TailwindCSS**
- 🔒 **Security & Data Protection**
- 🛡️ **Role-based Access Control**
- 🚀 **Caching with Redis for Performance Boost**
- ⌛ **And Much More...**

---

## ⚙️ Setup Instructions

### 1. Configure Environment Variables

Create a `.env` file in the root of the project and add the following:

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
