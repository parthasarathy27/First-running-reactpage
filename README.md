# MERN Login Page

This project is a simple MERN stack login page implementation. It allows users to register, login, and logout using authentication tokens.

## Features

- User registration with email and password
- User login with email and password
- Authentication using JSON Web Tokens (JWT)
- Logout functionality

## Technologies Used

- MongoDB: Database to store user information
- Express.js: Backend framework to handle HTTP requests
- React.js: Frontend library for building user interfaces
- Node.js: JavaScript runtime environment
- bcryptjs: Library for hashing passwords securely
- jsonwebtoken: Library for generating and verifying JSON Web Tokens

## Installation

1. Clone the repository:

```
git clone <repository-url>
```

2. Install dependencies for both client and server:

```
cd client
npm install
cd ../server
npm install
```

3. Set up environment variables:

Create a `.env` file in the `server` directory and add the following variables:

```
MONGODB_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
```

Replace `<your-mongodb-uri>` with your MongoDB connection string and `<your-jwt-secret>` with a secret key for JWT encryption.

4. Start the development server:

```
cd ../client
npm start
cd ../server
npm start
```

## Usage

Visit the application in your browser at [http://localhost:3000](http://localhost:3000) to register, login, and use the login functionality.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README to include any additional information about your project or specific setup instructions.
