# Chit-Chat

A real-time chat application built using the MERN (MongoDB, Express, React, Node.js) stack, along with Socket.io for real-time communication, TailwindCSS, Daisy UI for styling, and Zustand for global state management.

## 🌟 Features

- **Authentication & Authorization**: Secure login and registration with JWT (JSON Web Tokens).
- **Real-time Messaging**: Powered by Socket.io, enabling instant communication between users.
- **Online User Status**: Tracks and displays online users using Socket.io and React Context.
- **Global State Management**: Handled with Zustand for an efficient and simple state management solution.
- **Error Handling**: Robust error handling on both the server and client sides to ensure smooth operation.
- **Responsive UI**: Styled with TailwindCSS and Daisy UI for a modern and responsive design.
- **Scalability**: Built with best practices for scaling and performance optimization.

## 🚀 Getting Started

### Prerequisites

- **Node.js**: Ensure that Node.js is installed on your machine.
- **MongoDB**: A MongoDB instance is required for database operations.

### Setup .env File

Create a `.env` file in the root directory of your project and configure the following environment variables:

```env
PORT=your_desired_port
MONGO_DB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development_or_production
```

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-repo-url.git
   cd your-repo-directory
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

### Build the App

To build the app for production, run:

```bash
npm run build
```

### Start the App

To start the app, run:

```bash
npm start
```

The application will start on the port specified in the `.env` file.

## 🛠️ Tech Stack

- **Frontend**: React.js, TailwindCSS, Daisy UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-time Communication**: Socket.io
- **State Management**: Zustand
- **Authentication**: JWT (JSON Web Tokens)
- **Error Handling**: Custom error handling on both server and client sides

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
