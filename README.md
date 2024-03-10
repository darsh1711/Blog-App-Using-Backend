

---

# MERN Blog Application - Backend

This is the backend portion of a blog application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack.

## Features

- Create, read, update, and delete blog posts.
- Add, edit, and delete comments on blog posts.
- User authentication for registering, logging in, and logging out.
- User profiles.

## Technologies Used

- MongoDB: NoSQL database for storing blog posts, comments, and user data.
- Express.js: Web application framework for Node.js.
- Node.js: JavaScript runtime environment.

## Getting Started

To run the backend portion of this MERN stack application locally, follow these steps:

1. Clone this repository:

```bash
git clone https://github.com/yourusername/mern-blog-backend.git
```

2. Install dependencies:

```bash
cd mern-blog-backend
npm install
```

3. Set up environment variables:

Create a `.env` file in the root directory and add the following variables:

```env
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
```

Replace `your_mongodb_connection_string` with your MongoDB connection string and `your_session_secret` with a secret key for session management.

4. Run the application:

```bash
npm start
```

The backend server will start running on `http://localhost:3000`.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request to the `main` branch of the original repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

