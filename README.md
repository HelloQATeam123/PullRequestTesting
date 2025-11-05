![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://shopping-time.vercel.app/)

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options, dynamic cart management, and multi-currency support.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technology Stack](#technology-stack)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce web application built with React, offering an intuitive shopping experience with advanced product customization, real-time cart management, and international currency support. The platform demonstrates modern web development practices and scalable architecture patterns.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add items to your shopping cart or remove them with a single click
- **Quantity Adjustment**: Modify product quantities directly within the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.) for each cart item

### Product Discovery
- **Category Filtering**: Browse products by category for streamlined navigation
- **Multi-Page Shopping**: Add products to cart from both category pages and individual product detail pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart, ensuring order accuracy

### International Support
- **Multi-Currency**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Currency Conversion**: Real-time price updates based on selected currency

### Checkout Process
- **Multi-Step Checkout**: Guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent submission errors

## Technical Highlights

This project demonstrates proficiency in:
- React class components with subsequent refactoring to modern hooks
- Complex state management for cart and product attributes
- Form validation and error handling
- Firebase/Firestore integration for data persistence
- Responsive design and user experience optimization

## Getting Started

### Prerequisites
- Node.js (v14 or higher recommended)
- npm or yarn package manager

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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for efficient caching. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation that cannot be reversed.**

Ejects the application from Create React App, providing full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). Only use this if you need complete customization beyond what Create React App provides.

## Technology Stack

### Core Dependencies
- **[React](https://reactjs.org/)** - UI framework
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Image carousel functionality
- **[uuid](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - Cloud database for data persistence

### Development Tools
- **[Create React App](https://github.com/facebook/create-react-app)** - Build toolchain and development environment

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

The MIT License permits use, modification, and distribution of this software for both commercial and non-commercial purposes, subject to the terms outlined in the LICENSE file.

---

**Live Demo**: [https://shopping-time.vercel.app/](https://shopping-time.vercel.app/)
