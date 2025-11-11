![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce web application built with React, featuring comprehensive product catalog with customization options, shopping cart functionality, and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technology Stack](#technology-stack)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce platform that demonstrates modern web development practices and provides a seamless shopping experience. The application offers extensive product customization, intuitive cart management, and a streamlined checkout process.

## Key Features

### Cart Management
- **Add/Remove Products**: Effortlessly manage items in your shopping cart with intuitive controls
- **Quantity Adjustment**: Modify product quantities directly from the cart interface using dedicated quantity controls
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.) for each cart item
- **Success Notifications**: Visual feedback when items are successfully added to cart

### Product Discovery
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping**: Add products to cart from both category pages and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart, ensuring order accuracy
- **Comprehensive Product Data**: Extensive product catalog with detailed information

### Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies with dedicated currency overlay interface
- **Dynamic Conversion**: Real-time currency switching for international customers

### Checkout Process
- **Multi-Step Checkout**: Guided checkout flow designed for optimal user experience
- **Order Management**: Complete order processing with confirmation pages
- **Form Validation**: Comprehensive validation to ensure accurate order information and reduce errors

## Technical Highlights

This project showcases several key development practices and technologies:

- **React Architecture**: Modern React application with component-based architecture
- **State Management**: Custom cart logic with attribute selection and validation
- **Form Handling**: Robust form validation implementation
- **Backend Integration**: Firebase/Firestore integration for data persistence
- **Responsive Design**: Mobile-first approach with dedicated responsive CSS
- **Routing**: Client-side routing with dedicated route components
- **UI Components**: Reusable component library with hover effects and styling

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

The build is optimized for best performance:
- React is bundled in production mode
- Build is minified
- Filenames include content hashes for cache optimization

See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: This is a one-way operation. Once you eject, you cannot go back.**

This command removes the single build dependency and copies all configuration files (webpack, Babel, ESLint, etc.) into your project for full control over the build process.

## Technology Stack

### Core Technologies
- **React** - UI library for building user interfaces
- **Create React App** - Build tooling and configuration

### Key Components
- **Cart Management** - AddToCartButton, ChangeCartItemQuantity components
- **UI Overlays** - Cart overlay, Currency overlay components
- **Routing** - Dedicated route components for all pages
- **Styling** - Custom CSS with responsive design and hover effects

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [Firebase Firestore](https://firebase.google.com/docs/firestore) - Cloud database for data persistence

## Project Structure

```
src/
├── components/          # Reusable UI components
├── routes/             # Page-level route components
├── core-ui/            # Styling and CSS files
├── data/               # Product data and configuration
├── database/           # Firebase configuration
└── helpers/            # Utility functions
```

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**[Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)** | **[Request Feature](https://github.com/HelloQATeam123/PullRequestTesting/issues)**
