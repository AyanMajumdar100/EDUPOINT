# EduPoint

## Overview

EduPoint is an online education platform designed to facilitate learning and teaching through a user-friendly interface. The application allows users to sign up, log in, browse courses, and enroll in them. Instructors can create and manage courses. The platform supports various educational tools and resources to enhance the learning experience.

## Tech Stack - MERN STACK

- **Frontend**: 
  - React
  - Redux
  - MUI (Material-UI)
  - Axios

- **Backend**: 
  - Node.js
  - Express
  - MongoDB
  - Mongoose

- **Networking**: 
  - REST API

## Project Structure

The project consists of the following main components:

### Frontend
- **React**: For building the user interface.
- **Redux**: For state management.
- **Axios**: For making HTTP requests to the backend.
- **MUI**: For UI components and styling.

### Backend
- **Express**: For handling HTTP requests and routing.
- **MongoDB**: For database management.
- **Mongoose**: For MongoDB object modeling.
- **JSON Web Token (JWT)**: For authentication and authorization.

## Environment Variables

- **Frontend**: Configured using `.env` file.
  - `REACT_APP_API_URL`: URL of the backend API.

- **Backend**: Configured using `.env` file.
  - `PORT`: Port number for the server.
  - `MONGO_URI`: MongoDB connection string.
  - `JWT_SECRET`: Secret key for JWT.
  - `NODE_ENV`: Environment (development or production).

## Running the Project

1. **Clone the repository:**
    ```bash
    git clone https://github.com/AyanMajumdar100/Edupoint.git
    cd Edupoint
    ```

### Frontend

2. **Navigate to the frontend directory:**
    ```bash
    cd frontend
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Start the frontend server:**
    ```bash
    npm start
    ```

### Backend

5. **Navigate to the backend directory:**
    ```bash
    cd backend
    ```

6. **Install dependencies:**
    ```bash
    npm install
    ```

7. **Start the backend server:**
    ```bash
    npm start
    ```

## Features

### User Features
- **Sign Up and Login**: Users can create an account and log in to the platform.
- **Browse Courses**: Users can browse available courses.
- **Enroll in Courses**: Users can enroll in courses and access course materials.

### Instructor Features
- **Create and Manage Courses**: Instructors can create new courses and manage existing ones.
- **Upload Course Materials**: Instructors can upload videos, documents, and other resources for their courses.

### Admin Features
- **Manage Users**: Admins can view and manage all users.
- **Manage Courses**: Admins can view and manage all courses.

## Classes and Methods

### Frontend

#### Components

- **App.js**: Main component that sets up routes and renders other components.
- **Header.js**: Component for the header navigation bar.
- **Footer.js**: Component for the footer.
- **CourseList.js**: Displays a list of available courses.
- **CourseDetail.js**: Displays details of a specific course.
- **UserProfile.js**: Displays user profile and enrolled courses.

#### Redux

- **Actions**: Define actions for loading courses, user authentication, etc.
- **Reducers**: Handle state changes based on actions.
- **Store.js**: Configures and initializes Redux store.

### Backend

#### Models

- **User.js**: Schema for user data.
- **Course.js**: Schema for course data.

#### Routes

- **auth.js**: Handles authentication routes (login, signup).
- **courses.js**: Handles course-related routes (create, update, delete, get courses).
- **users.js**: Handles user-related routes (get user profile, update profile).

#### Controllers

- **authController.js**: Handles authentication logic.
- **courseController.js**: Handles course-related logic.
- **userController.js**: Handles user-related logic.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

---

Feel free to reach out if you have any questions or need further assistance with the project. Enjoy using EduPoint!
