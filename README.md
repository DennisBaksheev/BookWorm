# Bookworm Web App

## Introduction
Bookworm is a web application designed for book enthusiasts. It allows users to search for books, maintain a reading list, and utilize Google OAuth for secure sign-ins.

## Features
- **Book Search**: Users can search for books using Google Books API.
- **Reading List**: Users can add books to their personal reading list.
- **User Authentication**: Secure login and registration system with Google OAuth integration.

## Technologies Used
- Node.js
- Express.js
- MongoDB & Mongoose
- EJS (Embedded JavaScript templates)
- Passport.js for authentication
- Axios for API requests

## Installation and Setup
1. Clone the repository or download the source code.
2. Install Node.js and npm if not already installed.
3. Navigate to the project directory and install dependencies:
4. Create a `.env` file in the root directory and add the following variables:
SESSION_SECRET=your_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
MONGO_ATLAS_PASSKEY=your_mongodb_uri
API_KEY=your_google_books_api_key
5. Start the application:
npm start
6. Access the application through `http://localhost:3000` in your browser.

## Usage
- **Home Page**: Start by exploring the app's features.
- **Sign Up/Login**: Use Google OAuth to sign up or log in.
- **Book Search**: Search for books and view results.
- **Reading List**: Add books to your reading list and manage them.

## Live Demo
Check out the live demo of the application [here](https://reflective-voracious-provelone.glitch.me/).

## Contributing
Contributions to the Bookworm project are welcome.
