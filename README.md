# Secret Whisper App

Secret Whisper is a web application that allows users to share secrets anonymously. It provides a secure and user-friendly platform for sharing personal thoughts and experiences without revealing the user's identity.

![image](https://user-images.githubusercontent.com/99763743/197290151-e7ddad1b-98bf-4e15-b9c1-cdb02fbf13ef.png)

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)

## Features

- User Registration: Users can create accounts to access the app's features.
- Anonymous Secret Sharing: Users can share their secrets without revealing their identities.
- OAuth 2.0 Authentication: Multiple authentication options, including Google, GitHub, Spotify, and Facebook.
- Secure Environment: Sensitive information like API keys is protected using environment variables.

![image](https://user-images.githubusercontent.com/99763743/197290193-545f407e-e171-4bf8-8708-78fb39099bfc.png)

## Tech Stack

- Node.js and Express.js for server-side logic, routing, and web server creation.
- MongoDB for database storage of user information and secrets.
- Passport.js for robust authentication and user session management.
- EJS as the template engine for rendering dynamic web pages.
- OAuth 2.0 strategies for secure third-party authentication (Google, GitHub, Spotify, Facebook).
- Environment variables for safeguarding sensitive data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/secret-whisper.git
   ```
2. Navigate to the project directory:
   ```bash
   cd secret-whisper
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables by creating a .env file with the following content:
   ```bash
   CLIENT_GOOGLE_ID=your_google_client_id and other ...
   ```
