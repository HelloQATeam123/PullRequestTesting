![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce web application built with React, featuring over 150 women's clothing products with comprehensive customization options, shopping cart functionality, and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce platform that provides a seamless online shopping experience. The application offers an extensive catalog of women's clothing with advanced filtering, customizable product attributes, and a robust shopping cart system with multi-currency support.

## Key Features

### Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items with real-time updates
- **Quantity Adjustment**: Flexible quantity controls for each product in the cart
- **Cart Overlay**: Quick-access cart summary without leaving the current page
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.) for each cart item

### Shopping Experience
- **Category Filtering**: Browse products by category for efficient navigation
- **Multi-Page Shopping**: Add products to cart from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart to ensure order accuracy

### Currency Support
- **Multi-Currency**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Conversion**: Real-time currency conversion for international customers

### Checkout Process
- **Multi-Step Checkout**: Streamlined, user-friendly checkout flow
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent errors
- **Secure Processing**: Built with security best practices in mind

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: React Router
- **Backend/Database**: Firebase Firestore
- **UI Components**: React Simple Image Slider
- **Utilities**: UUID for unique identifiers
- **Build Tool**: Create React App

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

4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Available Scripts

### `npm start`

Runs the application in development mode at [http://localhost:3000](http://localhost:3000).

- Hot reload enabled for instant updates
- Lint errors displayed in console

### `npm test`

Launches the test runner in interactive watch mode.

See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Creates an optimized production build in the `build` folder.

- Minified and optimized for best performance
- Filenames include content hashes for cache busting
- Ready for deployment

See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Warning: This is a one-way operation. Once you eject, you cannot go back.**

Ejects the application from Create React App, giving you full control over the build configuration. Only use this if you need to customize webpack, Babel, ESLint, or other build tools.

## Project Goals

This project was developed to achieve the following technical objectives:

- ✅ Master React Class Components and modern Hooks patterns
- ✅ Implement complex state management for product attributes and cart functionality
- ✅ Develop comprehensive form validation logic
- ✅ Integrate Firebase for persistent data storage and real-time updates

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and backend services |

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**[Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)** | **[Request Feature](https://github.com/HelloQATeam123/PullRequestTesting/issues)**
