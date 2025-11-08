![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://pullrequesttesting.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience for women's fashion with over 150 products, dynamic cart management, and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Overview

Shopping Time is a comprehensive e-commerce web application designed to provide users with an intuitive and efficient online shopping experience. The platform features a curated collection of women's clothing with customizable product attributes, real-time cart management, and support for multiple international currencies.

**Live Demo:** [https://pullrequesttesting.vercel.app/](https://pullrequesttesting.vercel.app/)

## Key Features

### Cart Management
- **Add/Remove Products:** Seamlessly add items to your cart or remove them with a single click
- **Quantity Adjustment:** Modify product quantities directly from the cart interface
- **Cart Overlay:** Quick-access cart summary without leaving your current page
- **Detailed Product Information:** View selected attributes (size, color) for each cart item before checkout

### Enhanced Shopping Experience
- **Category Filtering:** Browse products by category for efficient navigation
- **Flexible Shopping Flow:** Add products to cart from both category pages and individual product pages
- **Attribute Validation:** Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy
- **Product Customization:** Choose from multiple sizes and color options for each product

### Multi-Currency Support
- **Global Currency Options:** Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion:** Prices automatically update based on selected currency

### Secure Checkout Process
- **Multi-Step Checkout:** Guided checkout flow for a smooth purchasing experience
- **Form Validation:** Comprehensive validation to ensure accurate order information
- **Error Prevention:** Built-in checks to minimize user errors during checkout

## Technology Stack

- **Frontend Framework:** React (Class Components refactored to Hooks)
- **Routing:** React Router
- **Database:** Firebase Firestore
- **UI Components:** React Simple Image Slider
- **Utilities:** UUID for unique identifiers
- **Build Tool:** Create React App

### Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database for product data |

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
   
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application

## Available Scripts

### `npm start`

Runs the application in development mode with hot-reloading enabled.

- **URL:** [http://localhost:3000](http://localhost:3000)
- **Features:** Automatic page reload on changes, lint error reporting in console

### `npm test`

Launches the test runner in interactive watch mode.

See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Creates an optimized production build in the `build` folder.

- Bundles React in production mode
- Optimizes build for best performance
- Minifies files and includes content hashes in filenames
- Ready for deployment

See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**⚠️ Warning: This is a one-way operation. Once you eject, you cannot go back!**

Ejects the application from Create React App, giving you full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). Only use this if you need custom configuration beyond what Create React App provides.

## Project Goals

This project was developed to achieve the following technical objectives:

- ✅ **React Proficiency:** Practice building with React Class Components and refactoring to modern Hooks
- ✅ **Complex State Management:** Implement sophisticated cart logic with attribute selection and validation
- ✅ **Form Handling:** Develop comprehensive form validation for checkout process
- ✅ **External Data Integration:** Utilize Firebase Firestore for persistent data storage
- ✅ **User Experience:** Create an intuitive, error-free shopping experience with real-time feedback

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

You are free to use, modify, and distribute this project in accordance with the MIT License terms.

---

**Built with ❤️ using React and Firebase**
