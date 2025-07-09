# Copilot Instructions for LaughFactory Ticket Scanning App

<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

## Project Overview

This is a React Native Expo application for ticket scanning with the following features:

- User authentication (Login, Forgot Password, Update Password)
- Dashboard with stats
- Events listing
- QR code scanning for tickets
- User profile management

## Architecture Guidelines

- Use functional components with React hooks
- Implement modular API service with baseURL configuration
- Use environment variables for API endpoints
- Follow React Native best practices for iOS optimization
- Maintain clean separation of concerns with separate folders for components, screens, services, and utilities

## API Integration

- All API calls should go through the centralized API service
- Use dummy/mock APIs during development
- Implement proper error handling and loading states
- Store authentication tokens securely using expo-secure-store

## Navigation

- Use React Navigation v6 with stack and tab navigators
- Implement proper authentication flow

## Code Style

- Use ES6+ features
- Implement proper PropTypes or TypeScript-style JSDoc comments
- Follow consistent naming conventions (camelCase for variables, PascalCase for components)
- Use async/await for asynchronous operations
