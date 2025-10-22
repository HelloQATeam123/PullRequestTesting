![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://shopping-time.vercel.app/)

A modern, full-featured e-commerce platform built with React, offering a comprehensive shopping experience with over 150 women's clothing products featuring customizable attributes such as size and color variations.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technology Stack](#technology-stack)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce application that demonstrates modern web development practices and provides users with an intuitive shopping experience. The platform supports multiple currencies, dynamic product filtering, and a seamless checkout process.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them with a single click
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.) for each cart item

### Product Discovery
- **Category Filtering**: Browse products by category for efficient navigation
- **Multi-Page Shopping**: Add products to cart from both category pages and individual product detail pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart to ensure order accuracy

### Internationalization
- **Multi-Currency Support**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Dynamic Currency Conversion**: Real-time price updates based on selected currency

### Checkout Process
- **Multi-Step Checkout**: Guided checkout flow for a smooth purchasing experience
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent submission errors
- **User-Friendly Interface**: Intuitive design focused on conversion optimization

## Technical Highlights

This project showcases several modern development practices:

- **React Architecture**: Component-based architecture with functional components and hooks
- **State Management**: Custom cart logic with attribute selection and validation
- **Form Handling**: Robust form validation implementation
- **External Data Persistence**: Firebase/Firestore integration for data storage
- **Responsive Design**: Mobile-first approach ensuring compatibility across devices
- **Routing**: Client-side routing with React Router for seamless navigation

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
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for cache optimization. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation and cannot be reversed.**

Ejects the application from Create React App, providing full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). Only use this if you need custom configuration beyond what Create React App provides.

## Technology Stack

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Product image galleries
- **[uuid](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firestore](https://firebase.google.com/docs/firestore)** - Cloud-based NoSQL database

### Development Tools
- Create React App - Project bootstrapping and build configuration
- React Hooks - Modern state management
- Firebase - Backend services and data persistence

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Live Demo**: [shopping-time.vercel.app](https://shopping-time.vercel.app/)
