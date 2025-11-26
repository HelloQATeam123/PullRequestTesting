# E-Commerce React Application

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/HelloQATeam123/PullRequestTesting)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Live Demo](https://img.shields.io/badge/demo-live-blue)](https://hellloqateam123.github.io/PullRequestTesting)

A modern, responsive e-commerce web application built with React.js, featuring a complete shopping cart system, product catalog, and checkout functionality.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Overview

This e-commerce platform provides a comprehensive online shopping experience with modern UI/UX design principles. The application features dynamic product management, shopping cart functionality, and a streamlined checkout process, all built with React.js and Firebase integration.

## Features

### Core Functionality
- **Product Catalog**: Browse and search through product listings
- **Shopping Cart**: Add, remove, and modify item quantities
- **Checkout System**: Complete purchase workflow
- **Order Management**: Track and manage customer orders
- **Responsive Design**: Optimized for desktop and mobile devices

### Technical Features
- **Firebase Integration**: Real-time database and authentication
- **Component-Based Architecture**: Modular and reusable React components
- **State Management**: Efficient cart and product state handling
- **Routing**: Single-page application with React Router
- **Testing Suite**: Comprehensive unit and integration tests

## Architecture

The application follows a component-based architecture with the following key layers:

- **Presentation Layer**: React components for UI rendering
- **Business Logic**: Custom hooks and helper functions
- **Data Layer**: Firebase integration for data persistence
- **Routing**: React Router for navigation management

## Prerequisites

Before running this application, ensure you have the following installed:

- **Node.js** (version 14.0 or higher)
- **npm** (version 6.0 or higher)
- **Git** for version control

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Firebase**
   - Set up your Firebase project
   - Update the configuration in `src/database/firebase.js`

4. **Start the development server**
   ```bash
   npm start
   ```

The application will be available at `http://localhost:3000`

## Available Scripts

| Script | Description |
|--------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | **Note: this is a one-way operation. Once you eject, you can't go back!** |

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Shopping cart overlay components
│   ├── currency-overlay/ # Currency selection components
│   └── header/         # Header navigation components
├── routes/             # Page-level components
│   ├── all-products/   # Product listing page
│   ├── cart/          # Shopping cart page
│   ├── checkout/      # Checkout process
│   └── single-product/ # Product detail page
├── core-ui/           # Global styles and CSS
├── data/              # Static data and configurations
├── database/          # Firebase configuration
└── helpers/           # Utility functions and helpers
```

## Technologies Used

- **Frontend**: React.js, HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Firebase (Database, Authentication)
- **Testing**: Jest, React Testing Library
- **Build Tools**: Create React App, npm
- **Version Control**: Git

## Contributing

We welcome contributions to improve this project. Please follow these guidelines:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Development Guidelines
- Follow existing code style and conventions
- Write tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with ❤️ by the HelloQATeam123**
