# [Mxx - Chat]

A modern, real-time chat application built with the MERN stack (MongoDB, Express.js, React, Node.js) and Socket.IO for instant messaging.

## ✨ Features

* **Real-time Messaging:** Send and receive messages instantly with Socket.IO.
* **User Authentication:** Secure user registration and login.
* **User Management:** View a list of registered users.
* **Private Chats:** Initiate one-on-one conversations.
* **Message History:** Load previous messages for ongoing conversations.
* **Online/Offline Status:** See which users are currently online.
* **[Optional: Add Features You've Implemented or Plan To]**
    * Typing indicators.
    * Message timestamps.
    * User avatars.
    * Responsive design for various devices.


### Frontend
* **React.js:** A JavaScript library for building user interfaces.
* **Vite:** A fast build tool for modern web projects.
* **Zustand:** A small, fast, and scalable bear-necessity state-management solution for React.
* **Tailwind CSS:** A utility-first CSS framework for rapidly styling.
* **DaisyUI:** A Tailwind CSS component library for beautiful UI elements.
* **React Router DOM:** For declarative routing in React applications.
* **Axios / Fetch API:** For making HTTP requests to the backend.
* **React Hot Toast:** For beautiful and responsive notifications.
* **Lucide React Icons:** A collection of beautiful open-source icons.

### Backend
* **Node.js:** A JavaScript runtime built on Chrome's V8 JavaScript engine.
* **Express.js:** A fast, unopinionated, minimalist web framework for Node.js.
* **MongoDB:** A NoSQL, document-oriented database.
* **Mongoose:** An ODM (Object Data Modeling) library for MongoDB and Node.js.
* **Socket.IO:** A library that enables real-time, bidirectional, event-based communication.
* **JSON Web Tokens (JWT):** For secure authentication.
* **Bcrypt.js:** For hashing passwords.
* **Dotenv:** To load environment variables from a `.env` file.
* **[Optional: Any other backend libraries, e.g., Validator.js, Cookie Parser]**

## ⚙️ Setup and Installation

Follow these steps to get the project up and running on your local machine.

### Prerequisites

* Node.js (v18 or higher recommended)
* npm or Yarn (npm is used in these instructions)
* MongoDB (running locally or a cloud instance like MongoDB Atlas)


1. Backend Setup
  mkdir chat-app
  cd chat-app
  mkdir backend
  cd backend

  Install dependencies:
  npm install
  
  .env
  MONGO_DB_URI=[Your MongoDB URI]
  PORT=[Your Port]
  JWT_SECRET=[Your jwt secret key]
  NODE_ENV= [Your node env]
  CLOUDINARY_CLOUD_NAME=[Your cloudinary cloud name]
  CLOUDINARY_API_KEY=[Your cloudinary api key]
  CLOUDINARY_API_SECRET=[Your cloudinary api secret]
  
  Run the backend server:
  npm run dev

2. Frontend Setup
   
  cd chat-app
  mkdir frontend
  
  Install dependencies:
  npm install
  
  Run the frontend development server:
  npm run dev


🌍 Usage
  
  Register: Navigate to http://localhost:your_port/signup and create a new account.
  Login: Use your credentials to login.
  Chat: Select a user from the sidebar to start a conversation. Messages will appear in real-time.
