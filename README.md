![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience with over 150 women's clothing products. The application features dynamic product attributes, real-time cart management, multi-currency support, and a secure checkout process.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Available Scripts](#available-scripts)
- [Project Architecture](#project-architecture)
- [License](#license)

## Features

### Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items
- **Quantity Adjustment**: Real-time quantity updates with instant price recalculation
- **Cart Overlay**: Quick-access cart summary without page navigation
- **Detailed Product Information**: Complete attribute display including size, color, and specifications

### Product Discovery
- **Category Filtering**: Efficient product browsing by category
- **Multi-Page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy

### Multi-Currency Support
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Real-Time Conversion**: Automatic price updates based on selected currency

### Checkout Process
- **Multi-Step Workflow**: Streamlined, user-friendly checkout experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Secure Processing**: Built with security best practices

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: React Router DOM
- **Backend/Database**: Firebase Firestore
- **UI Components**: React Simple Image Slider
- **Utilities**: UUID for unique identifiers

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn package manager
- Firebase account (for backend services)

### Installation

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
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Add your Firebase configuration to the project
   - Enable Firestore database

4. **Start the development server**
   ```bash
   npm start
   ```

### Available Scripts

#### `npm start`
Launches the development server at [http://localhost:3000](http://localhost:3000). The application will automatically reload when you make changes, and lint errors will be displayed in the console.

#### `npm test`
Runs the test suite in interactive watch mode. See the [Create React App testing documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for efficient caching. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for deployment instructions.

#### `npm run eject`
**Warning**: This is a one-way operation that cannot be reversed.

Ejects the project from Create React App, giving you full control over the build configuration. This copies all configuration files and dependencies into your project. Only use this if you need custom configuration beyond what Create React App provides.

## Project Architecture

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and follows modern React development practices:

- **Component Architecture**: Modular, reusable components organized in logical directories
- **State Management**: React Hooks for efficient state handling
- **Data Persistence**: Firebase Firestore for external data storage
- **Form Handling**: Custom validation logic for checkout process
- **Routing**: Multi-page application with dedicated routes for landing, products, cart, checkout, and order pages

### Project Structure

```
src/
├── components/          # Reusable UI components
├── routes/             # Page-level components
├── core-ui/            # Global styles and CSS
├── data/               # Static product data
├── database/           # Firebase configuration
└── helpers/            # Utility functions
```

### Development Goals Achieved

- ✅ Implemented React Class Components and successfully refactored to Hooks
- ✅ Built comprehensive product attribute selection logic
- ✅ Developed dynamic cart management system
- ✅ Integrated form validation throughout the application
- ✅ Implemented Firebase for persistent data storage

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and backend services |

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details. You are free to use, modify, and distribute this project in accordance with the MIT License terms.

---

**Built with ❤️ using React and Firebase**
