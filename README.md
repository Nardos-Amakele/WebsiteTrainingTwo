# WebsiteTrainingTwo

A simple web application built using Express.js for the backend and Mongoose as a DB. This app allows users to sign up, log in, and access a protected profile page. It implements JWT for authentication and authorization, with token refresh functionality.

#Features
- User registration with username and password
- User login with JWT authentication
- Profile page accessible only to authenticated users
- JWT token refresh every 10 minutes
- 
#Technologies Used
- Node.js
- Express.js
- Mongoose (for MongoDB)
- JSON Web Tokens (JWT)
- HTML/CSS for the front end

#Installation
#1. **Clone the repository**:
   git clone https://github.com/Nardos-Amakele/WebsiteTrainingTwo.git
   cd WebsiteTrainingTwo
#2. Install the libraries:
     npm install
#3.Create a .env file in the root directory and add this file to connect it to your database:
    JWT_SECRET=your_secret_key
    MONGODB_URI=your_mongodb_connection_string
#4.Run the application:
  npx nodemon server.js or npm start

