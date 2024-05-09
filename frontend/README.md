# Chatter Box - Frontend

## Overview

This repository contains the frontend codebase for Chatter Box, a real-time chat application developed using ReactJS, Apollo Client, Zustand, and the UI library Mantine. The frontend is designed to provide users with an intuitive and responsive interface for engaging in real-time conversations, managing profiles, and creating chatrooms.

## Features

- **Real-time Chat**: Utilizes GraphQL subscriptions to display messages in real-time and show typing indicators.
- **User Authentication**: Provides a secure authentication flow with JWT Tokens stored as HttpOnly cookies.
- **Profile Management**: Allows users to update their names and profile avatars.
- **Responsive Design**: Built with Mantine to ensure responsiveness across various devices and screen sizes.

## Technologies Used

- **ReactJS**: A JavaScript library for building user interfaces.
- **Apollo Client**: A comprehensive state management library for managing GraphQL data in React applications.
- **Zustand**: A lightweight state management library for React applications, used for managing local UI state.
- **Mantine**: A React component library providing accessible and customizable UI components.
- **Docker**: Used for containerization and deployment.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the frontend directory:

   ```bash
   cd real-time-chat-app/frontend
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the frontend development server:

   ```bash
   npm start
   ```

5. Open your browser and visit `http://localhost:3000` to view the application.

## Additional Notes

- Ensure that the backend server is running and accessible for full functionality.
- For production deployment, follow the necessary steps to build and deploy the frontend application.