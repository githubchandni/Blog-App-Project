# Blog App

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
The Blog App is a full-stack web application that allows users to create, read, update, and delete blog posts. It also supports user authentication, allowing users to register, log in, and manage their own posts. This project is built using the MERN stack (MongoDB, Express.js, React, and Node.js).

## Features
- User authentication (register, login, logout)
- Create, read, update, and delete blog posts
- Responsive design
- User-friendly interface

## Installation

### Prerequisites
- Node.js
- npm 
- MongoDB

### Backend Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/githubchandni/Blog-App-Project.git
    ```
2. Navigate to the backend directory:
    ```bash
    cd Blog-App-Project/server
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```
4. Set up your environment variables. Create a `.env` file in the `backend` directory and add the following:
    ```env
    PORT=5000
    MONGO_URI=your_mongo_db_connection_string
    JWT_SECRET=your_jwt_secret
    ```
5. Start the server:
    ```bash
    npm start
    ```
    The server will be running on `http://localhost:5000`.

### Frontend Setup
1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```
2. Install the dependencies:
    ```bash
    npm install
    ```
3. Start the frontend server:
    ```bash
    npm start
    ```
    The app will be running on `http://localhost:3000`.

## Usage
1. Open your browser and navigate to `http://localhost:3000`.
2. Register a new account or log in with an existing account.
3. Start creating, editing, and deleting blog posts!

## API Endpoints
### Auth
- **POST /api/auth/register**: Register a new user
- **POST /api/auth/login**: Log in a user

### Posts
- **GET /api/posts**: Get all posts
- **GET /api/posts/:id**: Get a specific post by ID
- **POST /api/posts**: Create a new post
- **PUT /api/posts/:id**: Update a post by ID
- **DELETE /api/posts/:id**: Delete a post by ID

## Technologies Used
- **Frontend**: React, Redux, Axios, Bootstrap (or any other CSS framework)
- **Backend**: Node.js, Express.js, MongoDB, Mongoose, JSON Web Token (JWT)
- **Others**: 
  - **Testing**: Jest, Supertest
  - **Linting**: ESLint, Prettier

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes.
4. Commit your changes: `git commit -m 'Add some feature'`.
5. Push to the branch: `git push origin feature/your-feature-name`.
6. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
- **Your Name** - [Your LinkedIn](https://www.linkedin.com/in/yourprofile)
- **Project Link**: https://github.com/yourusername/blog-app