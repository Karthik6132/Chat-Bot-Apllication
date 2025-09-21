Chat-Bot Application
About The Project
This project details the creation of a full-stack, real-time chat application using the MERN stack (MongoDB, Express.js, React.js, Node.js) with WebSockets. The video emphasizes learning the full-stack development journey and proper production-approachable setup rather than just building a simple chat application. It includes features like user authentication (login/signup), user search, displaying online users, and real-time messaging.

Built With
The application is built using the following core technologies and libraries:

Frontend
React.js: For building the user interface.

Vite: As a build tool for a fast development experience.

Tailwind CSS: For efficient and utility-first styling.

DaisyUI: A Tailwind CSS component library for pre-built UI components.

Redux Toolkit: For state management, including asynchronous operations.

React Router DOM: For client-side routing.

React Icons: For various icons used in the UI.

React Hot Toast: For displaying toast notifications (success/error messages).

Axios: For making HTTP requests to the backend.

Socket.IO Client: For establishing and managing WebSocket connections.

Backend
Node.js: The JavaScript runtime environment.

Express.js: A web application framework for building RESTful APIs.

MongoDB: A NoSQL database for storing application data.

Mongoose: An ODM (Object Data Modeling) library for MongoDB and Node.js.

Bcrypt.js: For hashing and comparing passwords securely.

JSON Web Token (JWT): For user authentication and authorization.

Dotenv: For managing environment variables.

Nodemon: For automatically restarting the Node.js server during development.

CORS: For enabling Cross-Origin Resource Sharing.

Cookie Parser: Middleware for parsing cookies.

Socket.IO Server: For real-time, bidirectional communication using WebSockets.

Getting Started
To get a local copy of this project up and running, follow these steps.

Prerequisites
Ensure you have the following installed:

Node.js (LTS version recommended)

npm (Node Package Manager, usually comes with Node.js)

MongoDB Atlas Account: For setting up your database (free tier is sufficient).

Installation
Clone the repository:

Bash

git clone https://github.com/Karthik6132/Chat-Bot-Apllication.git
cd Chat-Bot-Apllication
Setup Frontend (Client):

Bash

cd client
npm install
Setup Backend (Server):

Bash

cd server
npm install
Configure Environment Variables:

In the server directory, create a .env file.

Add your MongoDB Atlas connection URI to this file (e.g., MONGO_URI="your_mongodb_connection_string").

Add a JWT secret (e.g., JWT_SECRET="supersecretjwtkey").

Define JWT_EXPIRES_IN (e.g., JWT_EXPIRES_IN="2d").

Add your client URL (e.g., CLIENT_URL="http://localhost:5173").

Define PORT for the server (e.g., PORT=5000).

In the client directory, create a .env file.

Add your backend server URL (e.g., VITE_BACKEND_URL="http://localhost:5000/api/v1"). (Note the VITE_ prefix is essential for Vite to expose the environment variable to the client-side code.)

How To Run The Application
Start the Backend Server:

Bash

cd server
npm run dev
The server will start on http://localhost:5000.

Start the Frontend Application:

Bash

cd client
npm run dev
The client application will typically start on http://localhost:5173.

Open your web browser and navigate to http://localhost:5173 to access the chat application.
