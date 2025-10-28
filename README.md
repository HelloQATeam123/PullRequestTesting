![Shopping Time](https://raw.githubusercontent.com/catherineisonline/shopping-time/main/src/assets/images/project-preview.webp)

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

Shopping Time is a production-ready e-commerce application built with React, offering an intuitive shopping experience with advanced product customization, real-time cart management, and international currency support. The platform demonstrates modern web development practices and scalable architecture patterns.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add items to your cart or remove them with a single click
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.) for each cart item

### Product Discovery & Selection
- **Category Filtering**: Browse products by category for efficient navigation
- **Multi-Page Shopping**: Add products to cart from both category pages and individual product detail pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart, ensuring order accuracy

### International Commerce
- **Multi-Currency Support**: Shop in your preferred currency (EUR, GBP, AUD, JPY, and more)
- **Dynamic Currency Conversion**: Real-time price updates based on selected currency

### Checkout Experience
- **Multi-Step Checkout**: Guided checkout process for secure and streamlined purchases
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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for efficient caching. See [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you cannot revert.**

Ejects the application from Create React App, exposing all configuration files and dependencies (webpack, Babel, ESLint, etc.) for full customization. Only use this if you need complete control over the build configuration.

## Technology Stack

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Product image galleries
- **[uuid](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firestore](https://firebase.google.com/docs/firestore)** - Cloud database for data persistence

### Development Tools
- Create React App - Project bootstrapping and build tooling
- React Hooks - Modern state management
- Firebase - Backend services

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with React** | [Live Demo](https://shopping-time.vercel.app/)
