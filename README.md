# Joke-Reviews Server

The server for the Joke-Reviews application is responsible for handling API requests, storing user accounts, and managing global chat history. It is built using **Express.js** and integrates with the **GitHub API** for data storage.

## Features

- **User Account Management**: Handles user account creation, updates, and retrieval.
- **Global Chat Storage**: Stores and retrieves global chat messages for real-time communication.
- **API Endpoints**: Provides RESTful endpoints for client-server communication.
- **GitHub Integration**: Stores user data and chat history in a GitHub repository for persistence.

## Project Structure

### Files

- **index.js**: Main server file that initializes the Express.js application and defines API endpoints.

### API Endpoints

- **`/JokeAccounts`**:
  - Handles user account creation and updates.
  - Supports operations like adding new users and retrieving user data.
- **`/GlobalChatHistory`**:
  - Manages global chat messages.
  - Allows storing and retrieving chat history for real-time communication.

## Installation

### Prerequisites

- Node.js and npm installed on your machine.

### Steps

1. Navigate to the `server` directory:

   ```bash
   cd server
   ```

2. Install dependencies:
   npm install

3. Start the server:
   npm start

## Technologies Used

- **Express.js**: Web framework for building the server.
- **GitHub API**: Used for storing user accounts and global chat history.
- **CORS**: Middleware for enabling cross-origin requests.

## License

This project is licensed under the MIT License.
