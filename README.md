# Real-time Chat Application

This is a real-time chat application built with Node.js, Express, and Socket.IO.

## Features

*   Real-time messaging
*   User authentication
*   Multiple chat rooms

## Installation

1.  Clone the repository.
2.  Install dependencies: `npm install`
3.  Start the server: `npm start`

## Configuration

The following environment variables need to be set:

*   `PORT`: The port the server will listen on (default: 3000)
*   `JWT_SECRET`: A secret key for signing JWTs
*   `MONGODB_URI`: The MongoDB connection string

## File Structure


├── README.md
├── server.js
├── routes
│   └── auth.js
├── controllers
│   └── authController.js
├── models
│   └── User.js
├── middlewares
│   └── authMiddleware.js
├── utils
│   └── jwt.js


## Dependencies

*   express
*   socket.io
*   jsonwebtoken
*   bcrypt
*   mongoose