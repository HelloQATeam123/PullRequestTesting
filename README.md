![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

A modern, full-featured e-commerce platform built with React, offering a comprehensive shopping experience with over 150 women's clothing products featuring multiple size and color options.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technology Stack](#technology-stack)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce application that demonstrates modern web development practices and provides a seamless shopping experience. The platform includes advanced cart management, multi-currency support, and a streamlined checkout process with comprehensive form validation.

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
- **Secure Processing**: User-friendly and secure transaction flow

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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors are displayed in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for optimal caching. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you cannot revert.**

Ejects the application from Create React App, providing full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). This is only recommended for advanced users who require custom configuration.

## Technology Stack

### Core Dependencies
- **React Router** - Client-side routing for seamless navigation
- **React Simple Image Slider** - Product image galleries and carousels
- **uuid** - Unique identifier generation for cart items and orders
- **Firebase/Firestore** - Cloud-based data storage and real-time synchronization

### Framework
- **Create React App** - Build tooling and development environment setup

### Architecture
- **Component-based Design** - Modular components for cart, currency, header, and product management
- **Route-based Organization** - Structured routing for landing, products, cart, checkout, and order pages
- **Responsive CSS** - Mobile-first design with dedicated responsive stylesheets

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details. You are free to use, modify, and distribute this project in accordance with the MIT License terms.
