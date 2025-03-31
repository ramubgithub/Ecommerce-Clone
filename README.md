# E-commerce Website Clone

This project is a full-stack MERN (MongoDB, Express, React, Node.js) e-commerce web application, developed as part of an assignment for Mobishaala Edutech Pvt. Ltd. The application is a clone of [PrintMine.in](https://printmine.in/) with key e-commerce functionalities.

## Features

### Frontend
- Home page showcasing featured products and categories
- Product listing page with filtering and sorting options
- Product details page with image preview, customization options, and an "Add to Cart" button
- Shopping cart page with quantity modification and removal options
- Checkout page with address, payment method selection, and order summary
- User authentication (Signup/Login) via email and password

### Backend
- JWT-based user authentication
- Product management (CRUD operations for adding/updating products)
- Shopping cart management (Add/update/remove items)
- Order processing (Place an order, track order status)
- Payment integration (Optional: Razorpay/Stripe mock payments)

## Tech Stack
- **Frontend:** React.js, Redux Toolkit, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB
- **Database:** MongoDB Atlas
- **Deployment:** Vercel (Frontend), Render (Backend)

## Installation & Setup

### Prerequisites
- Node.js & npm installed
- MongoDB Atlas account setup

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ecommerce-clone.git
   cd ecommerce-clone
   ```
2. Install dependencies:
   ```sh
   cd backend
   npm install
   cd ../frontend
   npm install
   ```
3. Configure environment variables:
   - Create a `.env` file in the backend with MongoDB connection string and JWT secret.
4. Run the application:
   ```sh
   cd backend
   npm run dev
   cd ../frontend
   npm run dev
   ```
5. Open `http://localhost:3000` in your browser.

## Deployment
- **Backend:** Hosted on Render/Vercel/AWS EC2
- **Frontend:** Deployed on Vercel/Netlify
- **Database:** MongoDB Atlas

## Bonus Features
- Product search
- User reviews & ratings
- Admin panel for product/order management

## License
This project is for educational purposes only.

---

