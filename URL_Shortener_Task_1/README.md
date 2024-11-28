# URL Shortener Project

This is a simple URL shortener web application built using Express.js, EJS, and MongoDB. It allows users to shorten long URLs into more manageable, shortened versions. Users can also sign up for an account to manage their shortened URLs.

## Features

- Shorten long URLs into easy-to-share shortened URLs.
- User authentication system for signup and login.
- Users can view, edit, and delete their shortened URLs.
- MongoDB database integration for storing URL data and user information.
- Responsive design using EJS templates for a seamless user experience on both desktop and mobile devices.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/TejasKumar555/codealpha_tasks/URL-Shortener_Task_1.git
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Set up MongoDB:

   - Make sure you have MongoDB installed and running locally.
   - Update the MongoDB connection string in `connection.js` file.

4. Run the application:

   ```
   npm start
   ```

5. Access the application in your web browser:

   ```
   http://localhost:4000
   ```

## Usage

1. **Sign Up/Login**: Users can sign up for an account or log in if they already have one.

2. **Shorten URL**: After logging in, users can enter a long URL and generate a shortened URL.

3. **Manage URLs**: Users can view, and delete their shortened URLs from their dashboard.

## Dependencies

- Express.js: Web application framework for Node.js.
- EJS: Embedded JavaScript templating for dynamic HTML generation.
- MongoDB: Document-oriented NoSQL database for storing URL data and user information.
- Mongoose: MongoDB object modeling for Node.js.
- Other dependencies listed in `package.json`.
