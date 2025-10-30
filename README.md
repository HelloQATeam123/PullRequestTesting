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

Shopping Time is a production-ready e-commerce platform that demonstrates modern web development practices and provides a seamless shopping experience. The application features a comprehensive product catalog, dynamic cart management, and flexible currency options to accommodate a global user base.

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

### Currency Support
- **Multi-Currency**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Conversion**: Real-time currency conversion throughout the shopping experience

### Checkout Process
- **Multi-Step Checkout**: Streamlined, user-friendly checkout flow
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent errors
- **Secure Processing**: Built with security and user experience best practices

## Technology Stack

### Core Technologies
- **React** - Component-based UI framework
- **React Router** - Client-side routing
- **Firebase Firestore** - Cloud-based data persistence

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Declarative routing for React
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel component
- [UUID](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - NoSQL cloud database

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Available Scripts

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads when you make changes, and lint errors are displayed in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests](https://facebook.github.io/create-react-app/docs/running-tests) documentation for more information.

### `npm run build`
Builds the application for production to the `build` folder. The build is optimized for best performance, with minified files and hashed filenames ready for deployment. See the [deployment](https://facebook.github.io/create-react-app/docs/deployment) documentation for more information.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you cannot go back.**

This command removes the single build dependency and copies all configuration files (webpack, Babel, ESLint, etc.) into your project for full control. Only use this if you need to customize the build configuration beyond what Create React App provides.

## Project Goals

This project was developed to achieve the following technical objectives:

- ✅ Master React class components and functional components with hooks
- ✅ Implement complex state management for cart and product attributes
- ✅ Build comprehensive form validation logic
- ✅ Integrate Firebase for external data persistence
- ✅ Create a responsive, production-ready e-commerce application

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Note**: This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
