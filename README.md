# GoalSetter-MERN-APP
This is a Goal Setter App built using the MERN stack (MongoDB, Express, React, Node.js), along with Redux Toolkit for state management. It is a project developed to learn and practice full-stack development.

## Features
- User Authentication: Users can sign up, log in, and manage sessions.
- Create & Manage Goals: Users can set, view, update, and delete their goals.
- State Management: Utilizes Redux Toolkit for efficient state management.
- Responsive Design: The app is designed to be mobile-friendly and user-friendly.

## Tech Stack
- MongoDB: NoSQL database to store user and goal data.
- Express: Web application framework for Node.js.
- React: Frontend library for building user interfaces.
- Node.js: JavaScript runtime to handle backend logic and API requests.
- Redux Toolkit: State management tool for the frontend.
- JWT: JSON Web Tokens for secure user authentication.

## Installation
### Prerequisites
Make sure you have the following installed:

- Node.js
- MongoDB (or use MongoDB Atlas for cloud database)

### Setup
- Clone this repository:
``` bash
git clone https://github.com/kunj-10/GoalSetter-MERN-APP.git
```

- Navigate to the project directory:

``` bash
cd GoalSetter-MERN-APP
```

- Install dependencies for both the backend and frontend:

  - For the backend (Node/Express):

``` bash
cd backend
npm install
```
  - For the frontend (React with Redux Toolkit):

``` bash
cd frontend
npm install
```

- Set up the environment variables for MongoDB, JWT secret, and NODE_ENV in a ``.env`` file (example):

```` makefile
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
NODE_ENV=development
````

- Run the backend and frontend servers:

```bash
npm run dev
```

*Open your browser and go to http://localhost:3000 to view the app.*

## Credits
This project was created by following a tutorial by [Traversy Media](https://www.youtube.com/@TraversyMedia).
