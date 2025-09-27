

# 🛍️ Forever Buy - Full Stack E-commerce Platform

**Forever Buy** is a modern, responsive, and fully-featured e-commerce application built from the ground up using the **MERN (MongoDB, Express, React, Node.js)** stack. It offers a seamless shopping experience for customers and a robust administration dashboard for product and order management.

## 🚀 Live Demo

| Component | Status | URL |
| :--- | :--- | :--- |
| **Frontend** | Deployed | `[LINK TO LIVE FRONTEND, e.g., Vercel/Netlify]` |
| **Backend API** | Deployed | `[LINK TO LIVE BACKEND API, e.g., Heroku/AWS]` |

## ✨ Key Features

### User Features (Frontend)

  * **Secure Authentication:** User sign-up, login, and profile management using JWT.
  * **Product Browsing:** Filter, sort, and search products by category, price, and rating.
  * **Shopping Cart:** Add, update, and remove items with persistent cart functionality.
  * **Product Reviews:** View and submit ratings and reviews for products.
  * **Checkout Flow:** Multi-step checkout process with shipping address and payment method selection.
  * **Order History:** View past orders and their current status.
  * **Responsive UI:** Built with **HTML, CSS, and vanilla JavaScript** principles, managed effectively by **React**.

### Admin Features (Backend/Dashboard)

  * **User Management:** View, edit, or delete registered users.
  * **Product CRUD:** Create, Read, Update, and Delete products, including image uploads.
  * **Order Management:** View all customer orders and update their delivery status (e.g., Processing, Shipped, Delivered).

## 💻 Tech Stack

This project is a true Full Stack application utilizing a JavaScript-centric ecosystem.

| Layer | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | **React.js** | Library for building the dynamic user interface. |
| **Frontend Core**| **HTML, CSS, JS**| Foundational web languages for structure, styling, and interactivity. |
| **Backend** | **Node.js** | JavaScript runtime environment. |
| **Server Framework**| **Express.js** | Fast, minimalist web framework for building REST APIs. |
| **Database** | **MongoDB** | Flexible NoSQL database used for storing all application data. |
| **State Mgmt** | `[e.g., Redux Toolkit / Context API]` | Manages application-wide state (e.g., Cart, User Info). |
| **Styling** | `[e.g., Tailwind CSS / Bootstrap / Custom CSS]` | Framework/methodology used for styling the components. |

## ⚙️ Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

  * Node.js (v14+)
  * MongoDB Atlas Account or local MongoDB installation.

### 1\. Cloning the Repository

```bash
git clone [YOUR_REPO_URL]
cd forever-buy
```

### 2\. Backend Setup (`/backend` folder)

```bash
cd backend
npm install
```

**Environment Variables (.env)**
Create a file named `.env` in the `/backend` directory and add your configuration details:

```env
NODE_ENV = development
PORT = 5000
MONGO_URI = YOUR_MONGODB_CONNECTION_STRING
JWT_SECRET = YOUR_SECRET_KEY
```

### 3\. Frontend Setup (`/frontend` folder)

```bash
cd ../frontend
npm install
```

**Environment Variables (.env)**
Create a file named `.env` in the `/frontend` directory:

```env
REACT_APP_BASE_URL = http://localhost:5000/api/v1
```

### 4\. Running the Project

Open **two separate terminal windows** for the backend and frontend:

**Terminal 1: Start Backend**

```bash
cd backend
npm start  # or npm run dev if you use nodemon
```

**Terminal 2: Start Frontend**

```bash
cd frontend
npm start
```

The frontend application will automatically open in your browser at `http://localhost:3000`.

## 🛠 Challenges & Learning

### Key Challenges Faced:

1.  **Authentication Flow:** Implementing secure, JWT-based authentication across a split React-Node architecture while protecting specific routes (Admin/User).
2.  **Image Handling:** Setting up **Multer** on the backend to manage product image uploads and storing their references in MongoDB.
3.  **State Synchronization:** Efficiently managing global state (like the shopping cart or user session) in React so that changes instantly reflect across different components.

### What I Learned:

1.  Mastered the **MERN** stack's data flow from front-end component state to Express routing and MongoDB schema design.
2.  Gained deeper experience in developing reusable and modular components using **React**.
3.  Practiced **RESTful API design** principles for a complex application with multiple resource types (Users, Products, Orders).

## 🤝 Contribution

Contributions, issues, and feature requests are welcome\! Feel free to check the [issues page]([LINK TO YOUR ISSUES PAGE]).
