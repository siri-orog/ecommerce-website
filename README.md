# 🛒 E-Commerce Website

A full-stack **E-Commerce Web Application** built using **React.js, Node.js, Express.js, MongoDB, and Mongoose**. The project demonstrates frontend development, backend REST APIs, database integration, and product management.

## 📌 Project Overview

This project is designed as a full-stack e-commerce application where the React frontend communicates with a Node.js/Express backend through REST APIs, while MongoDB is used for storing product-related data.

---

## ✨ Features

* 🛍️ E-commerce product interface
* 📦 Product management
* 🔌 REST API integration
* ⚛️ React.js frontend
* 🟢 Node.js backend
* 🚀 Express.js server
* 🍃 MongoDB database integration
* 🧩 Mongoose data modeling
* 🔄 Frontend-to-backend API communication
* 📁 Modular routing and model structure

---

## 🛠️ Technologies Used

### Frontend

* React.js
* JavaScript
* HTML5
* CSS

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB
* Mongoose

### Tools

* Visual Studio Code
* Git
* GitHub
* npm

---

## 📂 Project Structure

```text
ecommerce-website/
│
├── backend/
│   └── Backend application files
│
├── frontend/
│   └── React frontend application
│
├── model/
│   └── MongoDB/Mongoose data models
│
├── routes/
│   └── API route definitions
│
├── .gitignore
└── README.md
```

---

# 🚀 How to Run the Project

Follow the steps below to run the application locally.

## 1. Prerequisites

Make sure the following are installed:

* **Node.js**
* **npm**
* **MongoDB**
* **Git**

Check the installations:

```bash
node --version
npm --version
git --version
```

---

## 2. Clone the Repository

```bash
git clone https://github.com/siri-orog/ecommerce-website.git
```

Go into the project directory:

```bash
cd ecommerce-website
```

---

## 3. Start MongoDB

Make sure your MongoDB server is running locally.

The application uses MongoDB to store product data.

If MongoDB is installed as a Windows service, you can start it from the Windows Services application.

---

## 4. Start the Backend

Open **Terminal 1**.

Navigate to the backend:

```bash
cd backend
```

Install backend dependencies:

```bash
npm install
```

Start the backend server using the script configured in `backend/package.json`.

For example:

```bash
npm start
```

or, if the project uses a development script:

```bash
npm run dev
```

The backend API will then run on the port configured in the project.

---

## 5. Start the Frontend

Open **Terminal 2**.

From the project root:

```bash
cd frontend
```

Install frontend dependencies:

```bash
npm install
```

Start the React application:

```bash
npm start
```

The frontend will normally open in your browser at:

```text
http://localhost:3000
```

---

## 6. Application Flow

Once both servers are running:

```text
                ┌─────────────────┐
                │  React Frontend │
                │ localhost:3000  │
                └────────┬────────┘
                         │
                         │ REST API
                         ▼
                ┌─────────────────┐
                │ Node + Express  │
                │     Backend     │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │     MongoDB     │
                │     Database    │
                └─────────────────┘
```

Open the frontend URL in your browser and the application should communicate with the backend API.

---

## 🔐 Environment Variables

If environment variables are required, create a `.env` file inside the appropriate backend directory.

Example:

```env
MONGO_URI=your_mongodb_connection_string
PORT=your_backend_port
```

**Never upload your real `.env` file or database credentials to GitHub.**

---

## 📸 Screenshots

Screenshots can be added to demonstrate the application.

Recommended structure:

```text
screenshots/
├── homepage.png
├── products.png
├── product-details.png
└── backend-api.png
```

Then add them to the README:

```markdown
![Homepage](screenshots/homepage.png)
```

---

## 🔄 Application Workflow

```text
User
 ↓
React Frontend
 ↓
HTTP Request
 ↓
Express REST API
 ↓
Mongoose
 ↓
MongoDB
 ↓
JSON Response
 ↓
React Frontend
 ↓
Display Data
```

---

## 🔮 Future Enhancements

* 🔐 User authentication and authorization
* 🛒 Shopping cart
* 💳 Payment gateway
* 📦 Order management
* ❤️ Wishlist
* 🔎 Product search and filtering
* ⭐ Product reviews and ratings
* 🤖 AI-based product recommendation system
* 📊 Admin analytics dashboard
* ☁️ Cloud deployment

---

## 🎯 Learning Outcomes

* Full-stack web application development
* React.js development
* REST API development
* Node.js and Express.js
* MongoDB database integration
* Mongoose data modeling
* Frontend-backend communication
* Git and GitHub
* Modular project development

---

## 👩‍💻 Author

**Siri Reddy**

B.Tech — Artificial Intelligence & Machine Learning

GitHub: https://github.com/siri-orog

---

## 📄 License

This project is intended for educational and portfolio purposes.
