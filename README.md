E-Commerce Backend API

A robust, scalable, and production-ready TypeScript-based backend API for modern e-commerce applications.
Built with Express.js, MongoDB, and industry best practices to ensure security, performance, and maintainability.

🌐 Live API: http://api.lunelwellness.com/

🦸‍♂️ Postman: https://drive.google.com/file/d/1TFe5hEn55Xo6e-o1uLba_K2UgSHndx_9/view?usp=sharing

📊 ERD Diagram: https://drive.google.com/file/d/1fjpdimzKwtbRu8H7dI4WK5D0BchM3NLx/view?usp=sharing

🚀 Features
🔐 Authentication & Authorization

JWT-based authentication

Role-based access control

Secure password hashing

Protected routes middleware

🛍 Product Management

Create, update, delete products

Product categories & collections

Image upload with Cloudinary

Product search & filtering

🛒 Shopping Cart

Persistent cart per user

Add / remove items

Update quantities

Auto price calculations

📦 Order Management

Complete order lifecycle

Order status tracking

Payment status handling

Order history per user

💳 Payment Integration

Secure Stripe payment integration

Payment verification

Webhook-ready structure

⭐ Reviews & Ratings

Add product reviews

Rating system

User-specific review tracking

❤️ Wishlist

Save favorite products

Manage wishlist items

📝 Blog System

Blog CRUD operations

Admin-controlled publishing

❓ FAQ Management

Dynamic FAQ handling

Admin-managed content

📬 Contact System

User inquiry submission

Email notification system

🔄 Real-Time Features

Socket.IO integration ready

Event-based architecture

🛠 Tech Stack
Category	Technology
Runtime	Node.js
Framework	Express.js
Language	TypeScript
Database	MongoDB + Mongoose
Authentication	JWT
Payment	Stripe
File Storage	Cloudinary
Email Service	Nodemailer
Validation	Zod
Scheduling	Node-cron
Real-time	Socket.IO
📦 Prerequisites

Make sure you have the following installed:

Node.js (v14 or higher)

MongoDB (v4.4 or higher)

npm (v7+) or yarn

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/parvesmosarof35/ecommarce-backend.git
cd ecommarce-backend

2️⃣ Install Dependencies
npm install
# or
yarn install

3️⃣ Configure Environment Variables

Create a .env file in the root directory and add:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key

🏃 Running the Application
🔧 Development Mode
npm run dev

🚀 Production Mode
npm run build
npm start

🧪 Running Tests
npm test

🧹 Code Quality
Linting
npm run lint

Formatting
npm run prettier

📂 Project Structure
src/
├── app/
│   ├── config/         # Configuration files
│   ├── errors/         # Custom error handlers
│   ├── helper/         # Helper functions
│   ├── interface/      # TypeScript interfaces
│   ├── middlewares/    # Express middlewares
│   ├── modules/        # Feature-based modules
│   │   ├── auth/
│   │   ├── cart/
│   │   ├── collections/
│   │   ├── order/
│   │   ├── payment/
│   │   ├── products/
│   │   ├── reviews/
│   │   ├── user/
│   │   └── wishlists/
│   ├── routes/         # API route definitions
│   ├── shared/         # Shared utilities
│   └── utils/          # Utility functions
│       └── emailcontext/
└── server.ts           # Entry point

🔐 Security Best Practices

Environment-based configuration

Secure JWT handling

Input validation with Zod

Centralized error handling

Role-based authorization

Secure payment processing

📈 Scalability & Architecture

Modular feature-based architecture

Separation of concerns

Service-controller pattern

Middleware-driven request lifecycle

Easily extendable for microservices migration

🤝 Contributing

Contributions are welcome!

Fork the repository

Create a feature branch

git checkout -b feature/AmazingFeature


Commit your changes

git commit -m "Add AmazingFeature"


Push to your branch

git push origin feature/AmazingFeature


Open a Pull Request

📄 License

This project is licensed under the MIT License.
See the LICENSE file for more details.

👨‍💻 Author

Parves Mosarof
Built with ❤️ using TypeScript & Express.js