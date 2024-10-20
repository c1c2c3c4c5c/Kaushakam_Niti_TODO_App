# MERN TODO List App

This is a TODO List application built using the MERN stack. It allows users to manage their tasks effectively.
The frontend part is the src and public folder, while the backend files are uploaded separately in the branch itself.
 

## Usage

- Open your web browser and go to `http://localhost:3000`.
- You can add ,update tasks, mark them as completed or delete them.

## Prerequisites

Before running the application, ensure you have the following installed:
- Node.js and npm (Node Package Manager)
- MongoDB
- MongoDB Compass (for database management)

## Setup Instructions

### 1. Install dependencies

```bash
cd mern-todo-app

# Install backend dependencies
cd todo_backend
npm install

# Install frontend dependencies
cd todo_frontend
npm install
```

### 2. MongoDB Setup

- Open MongoDB Compass
- Create a new database named `TODO`
- Inside the `TODO` database, create a collection named `tasks`

### 3. Server setup for database connection

```bash
PORT=5000  
MONGO_URI=mongodb://127.0.0.1:27017/Todo 
```

### 4. Running the App

```bash
# Start the server (from the 'todo_backend' directory)
npm start

# Start the client (from the 'todo_frontend' directory)
npm start
```

The server will run on `http://localhost:5000` and the client on `http://localhost:3000`.



