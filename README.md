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
I. Prerequisites

Node.js: Ensure you have Node.js version 18 or higher installed on your system.

npm or Yarn: You'll use npm (which comes with Node.js) to manage project dependencies.

MongoDB: You need a running MongoDB instance. This can be:

A local installation of MongoDB Community Server.

A cloud-based instance, such as a free tier cluster from MongoDB Atlas (recommended for easier setup).

II. Backend Setup

Project Folder Creation (if starting new):

First, create a main project folder (e.g., chat-app) in your desired location.

Enter this chat-app folder.

Inside chat-app, create a new folder named backend.

Navigate into the newly created backend folder.

Install Dependencies:

In your terminal, while in the backend folder, install all required Node.js packages.

Configure Environment Variables (.env file):

Create a file named .env directly within the backend folder.

Add the following variables to this .env file, replacing the bracketed placeholders with your actual details:

MONGO_DB_URI: Your MongoDB connection string (e.g., mongodb://localhost:27017/my_chat_db for local, or your Atlas URI).

PORT: The port your backend server will listen on (e.g., 5000).

JWT_SECRET: A strong, random secret key for JSON Web Token authentication.

NODE_ENV: Set this to development for local work.

CLOUDINARY_CLOUD_NAME: Your Cloudinary cloud name.

CLOUDINARY_API_KEY: Your Cloudinary API key.

CLOUDINARY_API_SECRET: Your Cloudinary API secret.

Run Backend Server:

Start the backend server. It should begin running on the port you specified (e.g., http://localhost:5000).

III. Frontend Setup

Project Folder Creation (if starting new):

From the backend folder, navigate back to your main chat-app project folder.

Inside chat-app, create a new folder named frontend.

Navigate into the newly created frontend folder.

Install Dependencies:

In your terminal, while in the frontend folder, install all required React and frontend packages.

Run Frontend Development Server:

Start the frontend development server. The chat application should automatically open in your web browser (typically at http://localhost:5173).

🌍 Usage
  
  Register: Navigate to http://localhost:your_port/signup and create a new account.
  Login: Use your credentials to login.
  Chat: Select a user from the sidebar to start a conversation. Messages will appear in real-time.
