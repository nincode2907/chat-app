# Simple Chat Application

## Overview
The **Simple Chat Application** is a real-time chat application built with Node.js, Express, and Socket.io on the backend, and React.js on the frontend. The application allows users to join chat rooms, send and receive messages instantly, and see real-time updates of other users' activities in the chat room.

## Features
- **Real-time Messaging:** Users can send and receive messages in real-time using WebSockets.
- **User Authentication:** JWT-based authentication for secure login and session management.
- **Multiple Chat Rooms:** Users can create and join multiple chat rooms.
- **Responsive UI:** A simple and responsive user interface built with React.js.
- **Deployed to Cloud:** The application is deployed using Heroku for the backend and Vercel/Netlify for the frontend.

## Technologies Used

### Backend
- **Node.js:** JavaScript runtime environment for server-side development.
- **Express.js:** Web framework for building RESTful APIs.
- **Socket.io:** Library for handling real-time, bi-directional communication between clients and server.
- **MongoDB:** NoSQL database for storing user data, chat rooms, and messages.
- **JWT (JSON Web Token):** For secure user authentication and session management.

### Frontend
- **React.js:** JavaScript library for building user interfaces.
- **Socket.io-client:** Client library for real-time communication with the server.
- **HTML/CSS:** For structuring and styling the application UI.
- **Bootstrap/Tailwind CSS (Optional):** CSS framework for responsive and modern design.

### DevOps and Deployment
- **Git:** Version control system to track changes in the project.
- **GitHub:** Platform for hosting the project's repository.
- **Heroku:** Cloud platform for deploying the backend.
- **Vercel/Netlify:** Cloud platform for deploying the frontend.
- **Docker (Optional):** Containerization for consistent deployment across different environments.

## Getting Started

### Prerequisites
- Node.js and npm installed on your local machine.
- MongoDB instance (local or cloud, e.g., MongoDB Atlas).
- Git installed for version control.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/chat-app.git
   cd chat-app
2. **Install backend dependencies:**
    ```bash
    cd back-end
    npm install
3. **Install frontend dependencies:**

    ```bash
    cd ../frontend
    npm install
4.  **Set up environment variables:**

Create a .env file in the backend directory and add your MongoDB connection string, JWT secret, and other necessary environment variables.

5. **Run the application:**

   - **Backend:**
     ```bash
     cd backend
     npm start
     ```

   - **Frontend:**
     ```bash
     cd ../frontend
     npm start
     ```
