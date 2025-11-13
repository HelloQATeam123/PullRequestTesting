![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://shopping-time.vercel.app/)
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

Shopping Time is a production-ready e-commerce platform that demonstrates modern web development practices and provides a seamless shopping experience. The application includes advanced cart management, product filtering, attribute selection, and a secure multi-step checkout process.

## Key Features

### 🛒 Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items
- **Quantity Adjustment**: Flexible quantity controls for each product
- **Cart Overlay**: Quick access to cart summary without page navigation
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.)

### 🔍 Product Discovery
- **Category Filtering**: Browse products by category for efficient navigation
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection before adding to cart to ensure order accuracy

### 💱 Currency Support
- **Multi-currency**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Dynamic Conversion**: Real-time currency switching for international customers

### ✅ Checkout Process
- **Multi-step Workflow**: Guided checkout process for improved user experience
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent errors
- **Secure Processing**: User-friendly and secure transaction flow

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
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

3. Start the development server:
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
**Note: This is a one-way operation. Once you eject, you cannot revert.**

Ejects the application from Create React App, providing full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). This is not required for most projects.

## Project Goals

This project was developed to achieve the following technical objectives:

- ✅ Master React Class Components and modern Hooks patterns
- ✅ Implement complex state management for cart and product attributes
- ✅ Develop comprehensive form validation logic
- ✅ Integrate Firebase for persistent data storage
- ✅ Create a production-ready e-commerce application

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database |

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with ❤️ using React and Firebase**
