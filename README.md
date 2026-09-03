# Real-Time Chat Application

A modern, full-stack real-time messaging application built with the MERN stack, Socket.io, Tailwind CSS, and DaisyUI. The application provides secure authentication, real-time communication, online user status, and cloud-based image sharing.

## ✨ Features

* 🌟 **MERN Stack** — MongoDB, Express.js, React, and Node.js
* 💬 **Real-Time Messaging** — Instant communication powered by Socket.io
* 🔐 **Authentication & Authorization** — Secure JWT-based authentication
* 🟢 **Online User Status** — See which users are currently online
* 🗂️ **Global State Management** — Zustand for efficient application state management
* 🖼️ **Image Sharing** — Upload and share images using Cloudinary
* 🎨 **Responsive UI** — Styled with Tailwind CSS and DaisyUI
* 🛡️ **Error Handling** — Server-side and client-side error management
* 🚀 **Production Ready** — Build and deploy the application for free
* ⚡ **Real-Time Updates** — Messages and user presence update instantly

## 🛠️ Tech Stack

### Frontend

* React
* Tailwind CSS
* DaisyUI
* Zustand
* Socket.io Client

### Backend

* Node.js
* Express.js
* MongoDB
* Socket.io
* JWT Authentication

### Cloud Services

* Cloudinary for image storage and management

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* MongoDB

### Installation

Clone the repository:

```bash
git clone https://github.com/owizy/real-time-chat-application.git
cd real-time-chat-application
```

Install the dependencies:

```bash
npm install
```

## 🔐 Environment Variables

Create a `.env` file in the root directory and add the following variables:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

Replace the placeholder values with your actual MongoDB, JWT, and Cloudinary credentials.

## 🏗️ Build the Application

Create a production-ready build:

```bash
npm run build
```

## ▶️ Start the Application

Start the application:

```bash
npm start
```

The application will be available at:

```text
http://localhost:5001
```

## 📱 Application Highlights

The application is designed to provide a smooth and responsive messaging experience with:

* Secure user authentication
* One-to-one real-time conversations
* Instant message delivery
* Online/offline user indicators
* Image sharing
* Persistent conversations
* Responsive design for different screen sizes
* Centralized state management
* Robust error handling

## 📂 Project Structure

```text
real-time-chat-application/
├── backend/
├── frontend/
├── .env
├── package.json
└── README.md
```

> The exact structure may vary depending on your implementation.

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/your-feature
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add new feature"
```

5. Push the branch

```bash
git push origin feature/your-feature
```

6. Open a Pull Request

## 📄 License

This project is available under the **MIT License**.
a ⭐ on GitHub.
