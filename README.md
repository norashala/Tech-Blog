# Tech-Blog

## Description
This project allows users to publish blog posts. Users can sign up, log in, create, view, update, and delete their blog posts. They can also leave comments on existing blog posts.

## Features
- **Homepage**: 
    - Displays existing blog posts.
    - Navigation links for the homepage, dashboard, and login/logout option.
    - Option to log in or sign up.

- **User Authentication**:
    - Sign up: Users can create a username and password.
    - Sign in: Users can log in with their credentials.
    - Logout: Users can log out of the site.

- **Dashboard**:
    - View existing blog posts.
    - Add new blog posts.
    - Update or delete existing blog posts.

- **Blog Posts**:
    - Display post title, contents, creator's username, and date created.
    - Option to leave comments on posts.
    - Comments include username, content, and date created.

## Technologies Used
- Backend: [Node.js](https://nodejs.org/), [Express.js](https://expressjs.com/), [Passport.js](http://www.passportjs.org/) (for user authentication), [MongoDB](https://www.mongodb.com/) (or any other database of choice)
- Frontend: [React.js](https://reactjs.org/), [React Router](https://reactrouter.com/)

## Installation
1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies:
    ```bash
    npm install
    ```
4. Set up environment variables (e.g., database connection URI, session secret).

## Usage
1. Start the server:
    ```bash
    npm start
    ```
2. Access the site via your web browser at `http://localhost:3000`.
