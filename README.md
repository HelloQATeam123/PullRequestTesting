![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://pullrequesttesting.vercel.app/)
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

Shopping Time is a production-ready e-commerce platform that demonstrates modern web development practices and provides a seamless shopping experience. The application features a comprehensive product catalog with customizable attributes, intelligent cart management, and a streamlined checkout process.

## Key Features

### Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items with real-time updates
- **Quantity Adjustment**: Flexible quantity controls for each product in the cart
- **Cart Overlay**: Quick-access cart summary without leaving the current page
- **Product Attributes**: Detailed display of selected attributes (size, color) for each cart item

### Product Browsing
- **Category Filtering**: Efficient product discovery through category-based navigation
- **Multi-page Shopping**: Add products to cart from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart to ensure order accuracy

### Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Conversion**: Real-time currency conversion for international customers

### Checkout Process
- **Multi-Step Workflow**: Guided checkout process designed for optimal user experience
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent errors
- **Secure Processing**: User-friendly interface with security best practices

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: [React Router](https://www.npmjs.com/package/react-router-dom)
- **Image Slider**: [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)
- **Unique Identifiers**: [UUID](https://www.npmjs.com/package/uuid)
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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors are displayed in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for efficient caching. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning**: This is a one-way operation that cannot be reversed.

Ejects the application from Create React App, providing full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). Only use this if you need complete customization beyond what Create React App provides.

## Project Goals

This project was developed to achieve the following technical objectives:

- ✅ Master React Class Components and modern Hooks patterns
- ✅ Implement complex state management for cart and product attributes
- ✅ Build comprehensive form validation system
- ✅ Integrate external data persistence with Firebase Firestore
- ✅ Create a production-ready, scalable e-commerce application

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Note**: This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
