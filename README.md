![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

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

Shopping Time is a production-ready e-commerce application that demonstrates modern React development practices and provides a comprehensive online shopping experience. The platform features an extensive catalog of women's clothing with customizable product attributes, intelligent cart management, and a streamlined checkout process.

**Live Demo:** [https://shopping-time.vercel.app/](https://shopping-time.vercel.app/)

## Key Features

### 🛒 Advanced Cart Management

- **Dynamic Product Management**: Add, remove, and update product quantities with real-time cart synchronization
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) and product details directly in the cart
- **Persistent Storage**: Cart data is maintained across sessions using Firebase

### 🔍 Enhanced Shopping Experience

- **Category Filtering**: Efficiently browse products by category
- **Flexible Product Selection**: Add items to cart from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy
- **Responsive Design**: Optimized for all device sizes

### 💱 Multi-Currency Support

- **Global Currency Options**: Shop in your preferred currency (USD, EUR, GBP, AUD, JPY, and more)
- **Real-time Conversion**: Prices automatically update based on selected currency

### ✅ Secure Checkout Process

- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Error Prevention**: Client-side validation reduces errors and improves data quality

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: React Router DOM
- **Backend/Database**: Firebase Firestore
- **UI Components**: React Simple Image Slider
- **Utilities**: UUID for unique identifiers
- **Build Tool**: Create React App

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

3. **Configure Firebase** (if applicable)
   - Create a Firebase project
   - Add your Firebase configuration to the project

4. **Start the development server**
   ```bash
   npm start
   ```

The application will open at [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`

Runs the application in development mode with hot-reloading enabled.  
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`

Launches the test runner in interactive watch mode.  
See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Creates an optimized production build in the `build` folder.  
The build is minified, and filenames include content hashes for optimal caching.  
See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Warning**: This is a one-way operation that cannot be reversed.

Ejects the Create React App configuration, giving you full control over webpack, Babel, ESLint, and other build tools. Only use this if you need custom configuration beyond what Create React App provides.

## Project Goals

This project was developed to achieve the following objectives:

- ✅ Master React Class Components and modern Hooks patterns
- ✅ Implement complex state management for cart and product attributes
- ✅ Build robust form validation for checkout processes
- ✅ Integrate external data persistence with Firebase Firestore
- ✅ Create a production-ready, scalable e-commerce application

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing and navigation |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and data persistence |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Developed by** [HelloQATeam123](https://github.com/HelloQATeam123)
