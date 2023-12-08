# Todo Application with React and MongoDB

This is a simple Todo application built using React for the frontend, MongoDB for the database, and Node.js for the backend. The application includes user authentication (login, register, and logout) and CRUD (Create, Read, Update, Delete) functionality for managing todos.

## Table of Contents

1. [Features](#features)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Configuration](#configuration)
5. [Usage](#usage)
6. [Folder Structure](#folder-structure)
7. [Contributing](#contributing)
8. [License](#license)

## Features

- User authentication (Login, Register, Logout)
- Create, Read, Update, and Delete (CRUD) functionality for Todos
- Responsive and user-friendly interface
- Data stored in MongoDB for persistence

## Requirements

- Node.js (v12 or higher)
- npm (v6 or higher)
- MongoDB (Make sure MongoDB is installed and running on your machine)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-app.git
   cd todo-app
   ```

2. Install dependencies for both the client and server:

   ```bash
   cd client
   npm install

   cd backend
   npm install
   ```

## Configuration

1. Create a `.env` file in the `server` directory with the following content:

   ```env
   PORT=4000
   MONGODB_URL= your mongodb Atlas url
   SECRET=your_secret_key
   ```

   - `PORT`: Port number for the server (default is 4000).
   - `MONGODB_URI`: Connection URI for your MongoDB Atlas
   - `SECRET`: Secret key for JWT token generation.



## Usage

1. Start the server:

   ```bash
   cd server
   npm start
   ```

   This will start the server at `http://localhost:3001`.

2. Start the client:

   ```bash
   cd client
   npm start
   ```

   This will open the application in your default web browser.

3. Register a new account, login, and start managing your todos!

## Folder Structure

- **client**: React frontend code.
- **backend**:  backend code.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Follow the [CONTRIBUTING.md](CONTRIBUTING.md) guideline


<img src="https://github.com/125Akash/TodoApp-/blob/main/Image6.png" alt="Login" width="500" height="300" >







