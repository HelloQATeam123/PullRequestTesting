![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://hellqateam123.github.io/PullRequestTesting/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience with over 150 women's clothing products. The application features dynamic product attributes, real-time cart management, and multi-currency support.

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
- **Dynamic Product Addition/Removal**: Seamlessly add or remove products from your shopping cart
- **Quantity Adjustment**: Modify product quantities directly within the cart
- **Cart Overlay**: Quick-access cart summary without leaving the current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item

### Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories for easier navigation
- **Flexible Product Selection**: Add items to cart from both category and product detail pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency (EUR, GBP, AUD, JPY, and more)
- **Real-time Currency Conversion**: Prices update dynamically based on selected currency

### Secure Checkout Process
- **Multi-Step Checkout Flow**: Intuitive, guided checkout experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Error Prevention**: Built-in safeguards to minimize user errors during checkout

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: React Router
- **Backend/Database**: Firebase Firestore
- **UI Components**: React Simple Image Slider
- **Utilities**: UUID for unique identifiers

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure Firebase:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Add your Firebase configuration to the project
   - Enable Firestore database

4. Start the development server:
   ```bash
   npm start
   ```

### Available Scripts

#### `npm start`
Launches the development server at [http://localhost:3000](http://localhost:3000). The application will automatically reload when you make changes, and lint errors will be displayed in the console.

#### `npm test`
Runs the test suite in interactive watch mode. See the [Create React App testing documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for optimal caching. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject`
**Warning**: This is a one-way operation that cannot be reversed.

Ejects the project from Create React App, giving you full control over the build configuration. This copies all configuration files and dependencies into your project. Only use this if you need complete control over the build setup.

## Project Architecture

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and follows modern React best practices:

- **Component Architecture**: Initially built with React Class Components, later refactored to functional components with Hooks
- **State Management**: Efficient state handling for cart operations and product attributes
- **Form Validation**: Robust client-side validation for checkout process
- **External Data Persistence**: Firebase Firestore integration for data storage

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

**Live Demo**: [https://hellqateam123.github.io/PullRequestTesting/](https://hellqateam123.github.io/PullRequestTesting/)
