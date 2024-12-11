# Blog App

A full-stack blog application where users can create, edit, delete, and view blog posts with robust authentication and authorization features. The app is built to deliver a responsive and dynamic user experience.

## Features

- **User Authentication & Authorization**
  - Secure login and signup functionality using JWT.
  - Role-based access control for users (e.g., admin privileges).

- **Blog Management**
  - Users can create, edit, and delete blog posts.
  - View all blog posts with dynamic content updates.

- **Comments**
  - Users can add comments to blog posts.
  - Real-time updates to display new comments dynamically.

- **Responsive UI**
  - Built using React for a seamless and interactive user experience.
  - Fully responsive design across different devices and screen sizes.

## Tech Stack

The Blog App leverages the MERN stack for a scalable and efficient full-stack solution:

- **MongoDB**: NoSQL database to store user data, blog posts, and comments.
- **Express.js**: Backend framework for building RESTful APIs.
- **React.js**: Frontend library for building dynamic and interactive UIs.
- **Node.js**: JavaScript runtime for backend development.

## Installation & Setup

Follow these steps to set up the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Anchal82-del/Blog_App.git
   cd Blog_App
   ```

2. **Install dependencies**
   - Backend:
     ```bash
     cd server
     npm install
     ```
   - Frontend:
     ```bash
     cd client
     npm install
     ```

3. **Set up environment variables**
   - Create a `.env` file in the `server` folder with the following:
     ```env
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     PORT=5000
     ```

4. **Run the project**
   - Start the backend server:
     ```bash
     cd server
     npm start
     ```
   - Start the frontend client:
     ```bash
     cd client
     npm start
     ```

   - The app will be available at `http://localhost:3000`.

## Folder Structure

```
Blog_App/
|-- client/            # React frontend
|   |-- public/        # Public assets
|   |-- src/           # React components, pages, and utilities
|
|-- server/            # Backend with Node.js and Express
|   |-- models/        # Mongoose schemas for User, Blog, Comment
|   |-- routes/        # API routes
|   |-- controllers/   # Request handling logic
|   |-- middleware/    # Authentication middleware
|
|-- .gitignore         # Files to ignore in version control
|-- README.md          # Project documentation
```

