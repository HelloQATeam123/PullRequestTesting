![PullRequestTesting](https://img.shields.io/badge/Project-PullRequestTesting-blue)

# PullRequestTesting

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern e-commerce web application built with React, featuring comprehensive product management, shopping cart functionality, and multi-currency support for an enhanced user experience.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [License](#license)

## Overview

PullRequestTesting is a full-featured e-commerce platform that demonstrates modern React development practices. The application provides a complete shopping experience with product browsing, cart management, checkout process, and order handling capabilities.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add items to your cart or remove them with intuitive controls
- **Quantity Adjustment**: Modify product quantities directly from the cart interface using dedicated quantity change components
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Success Notifications**: Visual feedback for cart actions through success message components

### Product Discovery & Selection
- **Product Catalog**: Browse through comprehensive product listings with detailed information
- **Category Navigation**: Efficient product filtering and navigation system
- **Single Product Views**: Detailed product pages with complete specifications
- **Attribute Selection**: Product customization with various attributes and options

### Multi-Currency Support
- **Currency Overlay**: Dedicated currency selection interface
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Price Updates**: Dynamic price conversion based on selected currency

### Checkout & Order Management
- **Multi-Step Checkout**: Comprehensive checkout process with form validation
- **Order Processing**: Complete order management system
- **Responsive Design**: Mobile-friendly interface with dedicated responsive styling

## Technology Stack

- **Frontend Framework**: React with modern Hooks
- **Routing**: React Router for navigation
- **Database**: Firebase Firestore integration
- **Styling**: Custom CSS with responsive design and hover effects
- **Testing**: Jest testing framework
- **Build Tool**: Create React App

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm package manager

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
Creates an optimized production build in the `build` folder. The build is minified, filenames include hashes, and the app is ready for deployment.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you cannot go back.**

Ejects the app from Create React App, giving you full control over configuration files and dependencies.

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Cart overlay functionality
│   ├── currency-overlay/# Currency selection components
│   └── header/          # Header navigation components
├── core-ui/            # Global styling and responsive design
├── data/               # Static data and product information
├── database/           # Firebase configuration and setup
├── helpers/            # Utility functions and helpers
└── routes/             # Page components and routing
    ├── all-products/   # Product listing pages
    ├── cart/           # Shopping cart pages
    ├── checkout/       # Checkout process
    ├── landing/        # Landing page
    ├── order/          # Order management
    └── single-product/ # Individual product pages
```

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with Create React App** | [Documentation](https://facebook.github.io/create-react-app)
