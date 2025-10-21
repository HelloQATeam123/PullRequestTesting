![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://pullrequesttesting.vercel.app/)
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

Shopping Time is a production-ready e-commerce platform that demonstrates modern web development practices and provides a seamless shopping experience. The application features an extensive product catalog with dynamic attribute selection, real-time cart management, and international currency support.

## Key Features

### Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items with instant feedback
- **Quantity Adjustment**: Flexible quantity controls for each product in the cart
- **Cart Overlay**: Quick-access cart summary without leaving the current page
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.) for each cart item

### Product Browsing
- **Category Filtering**: Efficient navigation through organized product categories
- **Multi-Page Shopping**: Add products to cart from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart to ensure order accuracy

### International Support
- **Multi-Currency**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Currency Conversion**: Real-time price updates based on selected currency

### Checkout Process
- **Multi-Step Checkout**: Streamlined, user-friendly checkout flow
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent errors
- **Secure Processing**: Built with security best practices in mind

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: [React Router](https://www.npmjs.com/package/react-router-dom)
- **UI Components**: [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)
- **Utilities**: [uuid](https://www.npmjs.com/package/uuid)
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

The page automatically reloads when you make changes, and lint errors are displayed in the console.

### `npm test`

Launches the test runner in interactive watch mode.

See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the application for production to the `build` folder.

The build is optimized for best performance:
- React is bundled in production mode
- Build is minified
- Filenames include content hashes for cache optimization

See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Warning: This is a one-way operation. Once you eject, you cannot go back.**

This command removes the single build dependency and copies all configuration files (webpack, Babel, ESLint, etc.) into your project for full control. Only use this if you need custom configuration beyond what Create React App provides.

## Project Goals

This project was developed to achieve the following objectives:

- ✅ Master React Class Components and modern Hooks patterns
- ✅ Implement complex state management for cart and product attributes
- ✅ Build comprehensive form validation system
- ✅ Integrate external data persistence with Firebase
- ✅ Create a production-ready, scalable e-commerce solution

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

You are free to use, modify, and distribute this project in accordance with the MIT License terms.

---

**Built with ❤️ using React and Firebase**
