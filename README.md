# 🪑 E-Commerce-furniture – Full-Stack E-commerce Platform

🌐 Live Demo
[🔗 Visit the Live Website – Furniture E-Commerce App](https://E-Commerce-furniture.onrender.com/)

📌 Project Status

Internship Project – Completed & Archived
The live Render deployment has been removed after completion of the internship project.

💼 Looking for real-world freelance projects?
Visit my Portfolio to explore my latest freelance work and projects.

💬 Need help with Render deployment, production setup, or web development projects? Feel free to reach out.

A modern, full-featured e-commerce web application built from scratch using the MERN stack (MongoDB, Express.js, React, Node.js).
This project transforms a static furniture design into a dynamic online store with user authentication, persistent cart, multi-step checkout, and secure payment integration.

📌 Project Overview

E-Commerce-furniture allows customers to:

Browse a dynamic catalog of furniture products with real-time search and category filters  
Register and log in securely with hashed passwords and JWT-based authentication  
Maintain a persistent shopping cart across sessions and devices  
Complete a multi-step checkout, including shipping details  
Make secure online payments via Razorpay integration  
Access a fully responsive UI optimized for mobile, tablet, and desktop  

This project demonstrates end-to-end full-stack development skills, including database modeling, RESTful API design, secure authentication, state management, and pixel-perfect responsive UI.

🚀 Core Features
Front-End Features

✅ Dynamic Product Catalog – Fetches products from MongoDB and displays them with filtering and search  
✅ Responsive Design – Mobile-first, modern layouts using CSS Flexbox and Grid  
✅ Protected Routes – Shipping and checkout pages accessible only to logged-in users  
✅ Multi-Step Checkout – Cart → Shipping → Order Summary → Payment  
✅ Reusable Components – Navbar, Footer, ProductCard, ProtectedRoute, etc.  
✅ State Management – AuthContext & CartContext for global state across the app  

Back-End Features

✅ Secure User Authentication – JWT tokens & bcrypt.js password hashing  
✅ Persistent Shopping Cart – Server-side cart stored in MongoDB  
✅ Order Management – Creates orders and updates status after payment verification  
✅ Payment Gateway Integration – Razorpay checkout modal and server-side verification  
✅ RESTful API – Organized, secure endpoints for users, products, cart, and orders  
✅ Middleware – Custom authentication middleware protects sensitive routes  

🛠️ Technology Stack
Frontend

⚛ React.js – Component-based UI

🧠 JavaScript (ES6+) – Interactive UI logic

💨 CSS3 – Custom responsive styling

🔗 React Router – Client-side routing

📡 Axios – API requests to backend

🔒 React Context API – Global state management

Backend

⚡ Node.js & Express.js – RESTful API development

🗄 MongoDB & Mongoose – Database modeling & storage

🔐 bcrypt.js – Password hashing

📝 jsonwebtoken (JWT) – Secure user authentication

🛡 Custom middleware – Route protection

💳 Razorpay – Payment gateway integration

Tools & Deployment

🖥 VS Code – Development IDE

📦 npm – Package management

🌐 dotenv – Secure environment variable management

🚀 Ready for production build and deployment
```
📂 Project Structure
E-Commerce-furniture/
├── client/                 # React front-end
│   ├── public/             # Static assets & HTML shell
│   └── src/
│       ├── assets/         # Images, icons, products
│       ├── components/     # Reusable UI components
│       ├── context/        # Global state (Auth & Cart)
│       ├── pages/          # Main pages (Home, Products, Cart, etc.)
│       ├── App.js          # Main React component with routing
│       └── index.js        # React entry point
├── server/                 # Node.js + Express back-end
│   ├── config/             # DB connection, Stripe config
│   ├── data/   
│   ├── controllers/        # API route logic
│   ├── models/             # Mongoose schemas (User, Product, Order)
│   ├── routes/             # Express routes
│   ├── middleware/         # Auth middleware
│   └── server.js           # Express server entry point
├── .gitignore
└── README.md
```
💻 Installation & Development
Prerequisites

Node.js & npm

MongoDB Atlas account (or local MongoDB)

VS Code (or preferred IDE)

Backend Setup

Clone the repository:
```
git clone https://github.com/Manas22-creator/E-Commerce-furniture.git
cd E-Commerce-furniture/server
```

Install dependencies:
```
npm install
```

Create a .env file in /server:

MONGO_URI=<your_mongo_connection_string>
JWT_SECRET=<your_jwt_secret>
RAZORPAY_KEY_ID=<your_razorpay_key_id>
RAZORPAY_KEY_SECRET=<your_razorpay_key_secret>
PORT=5000


Start the backend server:

```npm start```


Server runs at: http://localhost:5000

Frontend Setup

Navigate to client folder:

```cd ../client```


Install dependencies:

```npm install```


Start the React development server:

```npm start```


Frontend runs at: http://localhost:3000

🔮 Future Enhancements

Deploy frontend on Netlify/Vercel and backend on Render/Heroku

Implement admin panel for product management

Add user order history and profile management

Implement discount codes & offers

Optimize performance for large product catalogs

📷 Screenshots

(Add screenshots here: product catalog, cart, checkout, responsive views)

🙌 Credits

This project is built by Manas Pandey to showcase full-stack MERN development skills.
It demonstrates a real-world e-commerce workflow including authentication, cart management, multi-step checkout, and payment gateway integration.

<!--
Branding update audit for E-Commerce-furniture:
- [README.md](README.md): updated title, project name, repo path, and project structure text.
- [Project Structure.txt](Project%20Structure.txt): updated directory name references.
- [client/src/components/Navbar.js](client/src/components/Navbar.js): updated the brand label in the site header.
- [client/src/components/Footer.js](client/src/components/Footer.js): updated logo alt text, email, and footer copyright text.
- [client/src/pages/AboutPage.js](client/src/pages/AboutPage.js): updated story content and page copy.
- [client/src/pages/HomePage.js](client/src/pages/HomePage.js): updated brand narrative and contact details.
- [client/src/pages/ContactPage.js](client/src/pages/ContactPage.js): updated contact email details.
- [client/src/pages/PlaceOrderPage.js](client/src/pages/PlaceOrderPage.js): updated the Razorpay merchant label.
- [client/src/App.css](client/src/App.css): updated stylesheet header branding.
- [client/src/responsiveness.css](client/src/responsiveness.css): updated responsive CSS header branding.
- [server/controllers/productController.js](server/controllers/productController.js): replaced the old hosted fallback URL with a local backend default.
- [server/data/products.js](server/data/products.js): restored local product image paths to avoid the old brand domain.
- .env files were intentionally left unchanged as requested.
-->
