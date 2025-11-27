![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience with over 150 women's clothing products, dynamic product attributes, and multi-currency support.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technology Stack](#technology-stack)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce application that demonstrates modern React development practices and provides a comprehensive online shopping experience. The platform features an extensive catalog of women's clothing with customizable attributes including size and color variations, intelligent cart management, and support for multiple international currencies.

## Key Features

### 🛒 Advanced Cart Management
- **Dynamic Product Management**: Add, remove, and modify product quantities with real-time updates
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) and specifications for each cart item
- **Persistent Cart State**: Cart data is maintained across sessions using Firebase

### 🔍 Enhanced Shopping Experience
- **Category-Based Navigation**: Intuitive filtering system to browse products by category
- **Flexible Shopping Flow**: Add products from both category listings and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💱 Multi-Currency Support
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and additional international currencies
- **Real-Time Conversion**: Prices automatically update based on selected currency
- **Localized Shopping**: Enhanced experience for international customers

### ✅ Secure Checkout Process
- **Multi-Step Checkout Flow**: Guided checkout process with clear progress indicators
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent errors
- **User-Friendly Interface**: Intuitive design focused on conversion optimization

## Technical Highlights

This project showcases several key development achievements:

- **React Architecture**: Modern React implementation with hooks and functional components
- **State Management**: Custom cart logic with complex attribute selection and validation
- **Form Handling**: Robust form validation implementation for checkout process
- **Backend Integration**: Firebase/Firestore integration for data persistence
- **Code Quality**: Clean, maintainable code following React best practices

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Firebase** (if applicable)
   - Create a Firebase project
   - Add your Firebase configuration to the project
   - Enable Firestore database

4. **Start the development server**
   ```bash
   npm start
   ```

The application will open at [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`
Runs the application in development mode with hot-reloading enabled.
- Opens automatically at [http://localhost:3000](http://localhost:3000)
- Live reload on code changes
- Console displays lint errors and warnings

### `npm test`
Launches the test runner in interactive watch mode.
- See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information

### `npm run build`
Creates an optimized production build in the `build` folder.
- Minified and optimized for best performance
- Filenames include content hashes for cache busting
- Ready for deployment to production

See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**⚠️ Warning: This is a one-way operation!**

Ejects from Create React App, giving you full control over configuration files. Only use if you need custom webpack, Babel, or ESLint configurations.

## Technology Stack

### Core Technologies
- **React** - Frontend framework
- **Create React App** - Build tooling and configuration
- **Firebase/Firestore** - Backend and database services

### Key Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Product image galleries
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - Cloud database

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with ❤️ using React**
