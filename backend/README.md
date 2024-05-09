# Chatter Box - Backend

## Overview

This repository contains the backend codebase for Chatter Box, a real-time chat application developed using NestJS, Prisma, GraphQL, Redis, and Postgres. The backend is responsible for handling user authentication, managing profiles, creating chatrooms, and facilitating real-time communication between users.

## Features

- **Authentication Flow**: Implements secure user authentication with JWT Tokens stored as HttpOnly cookies.
- **Profile Management**: Allows users to update their names and profile avatars.
- **Chatroom Creation**: Enables users to create chatrooms and add members for group conversations.
- **Real-time Features**: Utilizes GraphQL subscriptions over WebSockets for real-time message updates and typing indicators.
- **Online User Tracking with Redis**: Redis stores live users in chatrooms, updating the user list in real-time on the backend.

## Technologies Used

- **NestJS**: A progressive Node.js framework for building efficient, reliable, and scalable server-side applications.
- **Prisma**: A modern database toolkit for TypeScript and Node.js that simplifies database access with a type-safe and auto-generated query builder.
- **GraphQL**: A query language for APIs that enables clients to request only the data they need.
- **Redis**: An in-memory data structure store used as a caching layer and for real-time data synchronization.
- **Postgres**: A powerful, open-source relational database system.
- **Docker**: Used for containerization and deployment.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the backend directory:

   ```bash
   cd real-time-chat-app/backend
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up environment variables:

   - Create a `.env` file based on the provided `.env.example` file.
   - Configure environment variables such as database connection details, JWT secret, and Redis URL.

5. Start the backend server in development mode:

   ```bash
   npm run start:dev
   ```

6. Open your browser and visit the specified URL to access the GraphQL playground for testing the API.

## Additional Notes

- Ensure that the required services (Postgres, Redis) are running and accessible for full functionality.
- Customize and extend the backend according to specific project requirements.
- For production deployment, follow best practices for security, scalability, and performance optimization.