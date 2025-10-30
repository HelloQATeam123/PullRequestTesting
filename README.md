![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://hellloqateam123.github.io/PullRequestTesting/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce web application built with React, featuring over 150 women's clothing products with comprehensive shopping cart functionality and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce platform that demonstrates modern web development practices and provides a seamless shopping experience. The application includes advanced features such as dynamic product attributes, real-time cart management, multi-currency support, and a secure checkout process.

## Key Features

### Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items with real-time updates
- **Quantity Adjustment**: Flexible quantity controls for each product in the cart
- **Cart Overlay**: Quick-access cart summary without leaving the current page
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.) for each cart item

### Product Browsing
- **Category Filtering**: Efficient product discovery through category-based navigation
- **Multi-page Shopping**: Add products to cart from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart to ensure order accuracy

### Currency Support
- **Multi-Currency**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Conversion**: Real-time price updates based on selected currency

### Checkout Process
- **Multi-Step Checkout**: Streamlined, user-friendly checkout flow
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent errors
- **Secure Processing**: Built with security best practices in mind

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: [React Router](https://www.npmjs.com/package/react-router-dom)
- **Image Slider**: [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)
- **Unique IDs**: [uuid](https://www.npmjs.com/package/uuid)
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

Runs the application in development mode at [http://localhost:3000](http://localhost:3000).

The page will automatically reload when you make changes. Lint errors will be displayed in the console.

### `npm test`

Launches the test runner in interactive watch mode.

See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the application for production to the `build` folder.

The build is optimized for best performance, with minified files and hashed filenames. The application is ready for deployment.

### `npm run eject`

**Note: This is a one-way operation. Once you eject, you cannot go back.**

This command removes the single build dependency and copies all configuration files (webpack, Babel, ESLint, etc.) into your project for full control over the build configuration.

## Project Goals

This project was developed to achieve the following technical objectives:

- ✅ Master React Class Components and successfully refactor to modern Hooks
- ✅ Implement complex state management for product attributes and cart functionality
- ✅ Develop comprehensive form validation for checkout process
- ✅ Integrate Firebase for external data persistence and real-time updates

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Note**: This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
