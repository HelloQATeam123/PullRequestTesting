![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce web application built with React, featuring over 150 women's clothing products with comprehensive customization options, shopping cart management, and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce platform that demonstrates modern web development practices and provides a seamless shopping experience. The application offers extensive product customization, intuitive cart management, and flexible currency options to accommodate a global user base.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add items to your cart or remove them with a single click
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color, etc.) for each cart item before checkout

### Product Discovery & Selection
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Prices update dynamically based on selected currency

### Checkout Experience
- **Multi-Step Checkout Process**: Guided checkout flow for a smooth transaction experience
- **Form Validation**: Comprehensive validation ensures accurate order information and reduces errors

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: [React Router](https://www.npmjs.com/package/react-router-dom)
- **Image Slider**: [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)
- **Unique Identifiers**: [uuid](https://www.npmjs.com/package/uuid)
- **Backend/Database**: [Firebase Firestore](https://firebase.google.com/docs/firestore)

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

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Available Scripts

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads when you make changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, filenames include hashes, and the app is ready for deployment. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you cannot go back.**

Ejects the app from Create React App, giving you full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). Only use this if you need custom configuration beyond what Create React App provides.

## Project Goals

This project was developed to achieve the following technical objectives:

- ✅ Master React Class Components and successfully refactor to modern Hooks
- ✅ Implement complex state management for product attributes and cart functionality
- ✅ Develop comprehensive form validation for checkout process
- ✅ Integrate Firebase Firestore for persistent data storage

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with Create React App** | [Documentation](https://github.com/facebook/create-react-app)
