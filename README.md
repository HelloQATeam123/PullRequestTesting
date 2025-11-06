![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://pullrequesttesting.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce web application built with React, featuring over 150 women's clothing products with comprehensive customization options, shopping cart management, and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce platform that demonstrates modern web development practices and provides a seamless shopping experience. The application offers extensive product customization, intuitive cart management, and flexible currency options to accommodate a global user base.

## Key Features

### 🛒 Cart Management

- **Add/Remove Products**: Effortlessly manage your shopping cart with intuitive controls
- **Quantity Adjustment**: Modify product quantities directly from the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View all selected attributes (size, color, etc.) before checkout

### 🔍 Product Discovery

- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add items to cart from both category and product detail pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding to cart, ensuring order accuracy

### 💱 Multi-Currency Support

- **Global Currency Options**: Shop in your preferred currency (EUR, GBP, AUD, JPY, and more)
- **Real-time Currency Conversion**: Seamless price updates across the application

### ✅ Checkout Process

- **Multi-Step Checkout**: Guided, user-friendly checkout flow
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Secure Processing**: Built with security and user experience in mind

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: React Router
- **Backend/Database**: Firebase Firestore
- **UI Components**: React Simple Image Slider
- **Utilities**: UUID for unique identifiers

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

- Hot reload enabled for instant feedback
- Lint errors displayed in console

### `npm test`

Launches the test runner in interactive watch mode.

See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Creates an optimized production build in the `build` folder.

- Minified and optimized for best performance
- Filenames include content hashes for effective caching
- Ready for deployment

See [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**⚠️ Warning: This is a one-way operation. Once you eject, you cannot revert!**

Ejects from Create React App, giving you full control over configuration files and dependencies. Only use if you need custom configuration beyond what Create React App provides.

## Project Goals

This project was developed to achieve the following objectives:

- ✅ Master React Class Components and modern Hooks patterns
- ✅ Implement complex state management for cart and product attributes
- ✅ Build comprehensive form validation system
- ✅ Integrate Firebase for persistent data storage
- ✅ Create a production-ready, scalable e-commerce solution

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

**Built with Create React App** | [Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
