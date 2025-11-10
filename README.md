![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience for women's fashion with 150+ products, dynamic cart management, and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce application that demonstrates modern React development practices and provides a comprehensive online shopping experience. The platform features an extensive catalog of women's clothing with advanced filtering, cart management, and checkout functionality.

## Key Features

### 🛒 Advanced Cart Management

- **Dynamic Product Management**: Add, remove, and update product quantities in real-time
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item
- **Persistent Cart State**: Your cart items are saved across sessions

### 🔍 Enhanced Shopping Experience

- **Category-Based Navigation**: Intuitive filtering system to browse products by category
- **Flexible Shopping Flow**: Add products from both category pages and individual product detail pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💱 Multi-Currency Support

- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and more
- **Real-Time Conversion**: Prices automatically update based on selected currency
- **Localized Shopping**: Shop in your preferred currency for a personalized experience

### ✅ Secure Checkout Process

- **Multi-Step Checkout**: Guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Error Prevention**: Client-side validation prevents common input errors

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: React Router DOM
- **Backend/Database**: Firebase Firestore
- **UI Components**: React Simple Image Slider
- **Utilities**: UUID for unique identifiers
- **Build Tool**: Create React App

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

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application

## Available Scripts

### `npm start`

Runs the application in development mode with hot-reloading enabled.

- **URL**: [http://localhost:3000](http://localhost:3000)
- **Features**: Automatic reload on file changes, lint error reporting in console

### `npm test`

Launches the test runner in interactive watch mode.

See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Creates an optimized production build in the `build` folder.

- Bundles React in production mode
- Optimizes for best performance
- Minifies code and includes content hashes in filenames
- Ready for deployment

See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**⚠️ Warning: This is a one-way operation. Once you eject, you cannot go back.**

Ejects the Create React App configuration, giving you full control over webpack, Babel, ESLint, and other build tools. Only use this if you need custom configuration beyond what Create React App provides.

## Project Goals

This project was developed to achieve the following objectives:

- ✅ **Master React Patterns**: Practice with React Class Components and successfully refactor to modern Hooks
- ✅ **Complex State Management**: Implement sophisticated cart logic with attribute selection and validation
- ✅ **Form Handling**: Build robust form validation for checkout process
- ✅ **External Data Integration**: Utilize Firebase Firestore for persistent data storage
- ✅ **Production-Ready Code**: Create a fully functional, deployable e-commerce application

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing and navigation |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and data persistence |

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with ❤️ using React** | [Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)
