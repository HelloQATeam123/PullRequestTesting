![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience for women's fashion. Browse through 150+ products with customizable attributes, manage your cart with ease, and checkout in your preferred currency.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Overview

Shopping Time is a comprehensive e-commerce solution designed to provide users with an intuitive and efficient online shopping experience. The platform features a curated collection of women's clothing with multiple size and color options, a dynamic shopping cart, and multi-currency support.

**Live Demo:** [https://shopping-time.vercel.app/](https://shopping-time.vercel.app/)

## Key Features

### Cart Management
- **Add/Remove Products:** Seamlessly add items to your cart or remove them with a single click
- **Quantity Control:** Adjust product quantities directly from your cart
- **Cart Overlay:** Quick-access cart summary without leaving your current page
- **Detailed Product Information:** View selected attributes (size, color) for each cart item

### Enhanced Shopping Experience
- **Category Filtering:** Browse products by category for easier navigation
- **Flexible Shopping Flow:** Add products from both category pages and individual product pages
- **Attribute Validation:** Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options:** Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion:** Prices update dynamically based on selected currency

### Streamlined Checkout
- **Multi-Step Process:** Guided checkout flow for a smooth purchase experience
- **Form Validation:** Built-in validations ensure accurate order information and reduce errors

## Technology Stack

- **Frontend Framework:** React (Class Components refactored to Hooks)
- **Routing:** React Router
- **Backend/Database:** Firebase Firestore
- **UI Components:** React Simple Image Slider
- **Utilities:** UUID for unique identifiers

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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads when you make changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include hashes for cache busting. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Note:** This is a one-way operation. Once you eject, you cannot revert.

Ejects the application from Create React App, giving you full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). Only use this if you need custom configuration beyond what Create React App provides.

## Project Goals

This project was developed to achieve the following objectives:

- ✅ Master React Class Components and modern Hooks patterns
- ✅ Implement complex cart logic with attribute selection
- ✅ Integrate comprehensive form validation
- ✅ Utilize Firebase for external data persistence
- ✅ Create a production-ready e-commerce application

## Dependencies

- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel functionality
- [UUID](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firebase Firestore](https://firebase.google.com/docs/firestore) - Cloud database

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with Create React App** | [Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
