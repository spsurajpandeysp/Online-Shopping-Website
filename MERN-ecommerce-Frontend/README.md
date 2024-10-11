
# Online Shopping Website

## Project Overview
The **Online Shopping Website** is a full-stack application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It simplifies online shopping operations by providing two distinct modes: **User** and **Admin**. The User mode allows browsing products, placing orders, and making payments, while the Admin mode enables the management of products, orders, and user accounts.

### Admin Mode
- **Product Management**: Add, edit, and delete products (name, price, stock, images).
- **Order Management**: View, update, and manage customer orders.
- **User Management**: View user profiles and order histories.

### User Mode
- **Product Browsing**: Users can browse products, filter, and sort them by category, price, and rating.
- **Cart Management**: Add or remove items from the cart and update quantities.
- **Secure Payment**: Pay using Stripe integration with both card and cash-on-delivery options.
- **Place Order**: User can place order.
- **Order Tracking**: View order status and history in the user profile.

---

## Features
- **Admin Panel**: Full control over products, users, and orders.
- **User Interface**: Clean, user-friendly design built with React and Tailwind CSS.
- **Secure Payments**: Stripe integration for safe and secure transactions.
- **Email Notifications**: Order confirmation and password reset emails via Nodemailer.
- **Cloud Deployment**: Fully deployed on Vercel (frontend) and MongoDB Atlas (backend).
- **Authentication**: User authentication using Passport JS and JWT.

---

## Technologies Used
- **React.js**: For building the user interface.
- **Node.js & Express.js**: Backend for handling server requests.
- **MongoDB & Mongoose**: Database and ORM for storing product, order, and user information.
- **Stripe**: Payment processing integration.
- **Redux Toolkit**: State management with asynchronous thunk actions.
- **Tailwind CSS**: Styling the application.
- **JWT & Passport.js**: For user authentication and secure API access.
- **Nodemailer**: Email services for order and password reset notifications.

---

## System Requirements
- **Node.js**: Version 16 or higher
- **MongoDB**: Version 5.0 or higher
- **Stripe Account**: For payment processing
- **IDE**: VS Code or any other text editor

---

## Installation and Setup

1. **Clone the Repositories**:
   ```bash
   git clone https://github.com/coderdost/MERN-ecommerce-Frontend.git
   git clone https://github.com/coderdost/MERN-ecommerce-backend.git
   ```

2. **Configure the Environment**:
   - Create a `.env` file in the backend project with the following variables:
     ```
     MONGO_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret
     STRIPE_SECRET_KEY=your_stripe_secret_key
     ```

3. **Install Dependencies**:
   - For both the frontend and backend, run the following command in the respective directories:
     ```bash
     npm install
     ```

4. **Run the Application**:
   - Start the backend:
     ```bash
     npm run dev
     ```
   - Start the frontend:
     ```bash
     npm start
     ```

5. **Access the App**:
   - Frontend: `http://localhost:3000`
   - Backend: `http://localhost:5000`

---

## Database Schema

- **Product Table**: Stores product details such as name, description, price, and stock.
- **Order Table**: Contains customer order information, including products ordered, total cost, and payment status.
- **User Table**: Stores user credentials and order history.
- **Brand Table**:Stores brand name.
- **Category Table**:Stores Category name.

  
---

## Contact
For any inquiries or support, feel free to contact:
- **Name**: [Suraj Pandey]
- **Email**: [surajpandey7493@gmail.com]
- **GitHub**: [https://github.com/spsurajpandeysp](https://github.com/spsurajpandeysp)
- **My Portfolio**: [https://surajpandey.vercel.app](https://surajpandey.vercel.app)

🌟 **Thank You for Exploring Our Project!** 🌟
