Memories
Memories is a social media web application built with the MERN stack (MongoDB, Express, React, Node.js) that allows users to post interesting events that happened in their lives.

Features
Authentication system allowing users to sign up and log in
CRUD functionality to create, read, update and delete memory posts
Like and comment on posts made by other users
Paginated home page showing posts from all users
User profile page with posts only by a specific user
Responsive design for use on mobile and desktop
Usage
Env Variables
Create a .env file in then root and add the following

Copy code

MONGO_URL = your mongodb uri
JWT_SECRET = 'abc123'
Install Dependencies
Copy code

npm install
Run
Copy code

# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
Built Using
React - Front-end framework
Node - Backend environment
Express - Node.js framework
MongoDB - Database
Redux - State management
Material UI - UI styling solution
