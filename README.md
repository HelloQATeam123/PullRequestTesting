![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://hellloqateam123.github.io/PullRequestTesting/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

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

Shopping Time is a production-ready e-commerce application that demonstrates modern web development practices and provides users with an intuitive shopping experience. The platform includes advanced cart management, multi-currency support, and a streamlined checkout process.

**[View Live Demo →](https://hellloqateam123.github.io/PullRequestTesting/)**

## Key Features

### 🛒 Advanced Cart Management
- **Add/Remove Products**: Seamlessly add items to your cart or remove them with a single click
- **Quantity Control**: Adjust product quantities directly from the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for easier navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### 💱 Multi-Currency Support
- Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- Real-time currency conversion for international customers

### ✅ Secure Checkout Process
- **Multi-Step Checkout**: Guided checkout flow for a smooth purchasing experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Error Prevention**: Built-in safeguards to minimize user errors

## Technical Highlights

This project showcases several key development practices and achievements:

- **React Architecture**: Initially built with class components, then refactored to modern React Hooks
- **State Management**: Custom cart logic with attribute selection and validation
- **Form Handling**: Robust form validation throughout the checkout process
- **Backend Integration**: Firebase/Firestore integration for data persistence
- **Responsive Design**: Mobile-first approach ensuring compatibility across all devices

## Getting Started

### Prerequisites
- Node.js (v14 or higher recommended)
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

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000).
- Hot reload enabled
- Lint errors displayed in console

### `npm test`
Launches the test runner in interactive watch mode.
See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder.
- Minified and optimized for best performance
- Filenames include hashes for cache busting
- Ready for deployment

See [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**⚠️ Warning: This is a one-way operation!**

Ejects from Create React App, giving you full control over configuration files. Only use if you need custom configuration beyond what Create React App provides.

## Technology Stack

### Core Technologies
- **React** - UI library with Hooks
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
