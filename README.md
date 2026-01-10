![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://pullrequesttesting.vercel.app/)
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

Shopping Time is a production-ready e-commerce application that demonstrates modern React development practices and provides a comprehensive online shopping experience. The platform features an extensive catalog of women's clothing with customizable product attributes, intelligent cart management, and a streamlined checkout process.

## Key Features

### 🛒 Advanced Cart Management

- **Dynamic Product Management**: Add, remove, and update product quantities with real-time cart synchronization
- **Cart Overlay**: Quick-access cart summary for seamless shopping without page navigation
- **Detailed Product Information**: View selected attributes (size, color) and product details directly in the cart
- **Persistent Cart State**: Cart data is maintained across sessions using Firebase

### 🔍 Enhanced Shopping Experience

- **Category-Based Navigation**: Intuitive filtering system to browse products by category
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product detail pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart to ensure order accuracy
- **Responsive Design**: Optimized for desktop and mobile devices

### 💱 Multi-Currency Support

- **Global Currency Options**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Real-Time Currency Conversion**: Prices automatically update based on selected currency
- **Localized Shopping Experience**: Shop in your preferred currency for transparent pricing

### ✅ Secure Checkout Process

- **Multi-Step Checkout Flow**: Guided checkout process with clear progress indicators
- **Form Validation**: Comprehensive client-side validation to ensure data accuracy
- **User-Friendly Interface**: Intuitive design that minimizes friction during purchase completion

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

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Add your Firebase configuration to the project
   - Enable Firestore database

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application

## Available Scripts

### `npm start`

Runs the application in development mode with hot-reloading enabled.

**Access**: [http://localhost:3000](http://localhost:3000)

### `npm test`

Launches the test runner in interactive watch mode for continuous testing during development.

### `npm run build`

Creates an optimized production build in the `build` folder with:
- Minified and bundled code
- Optimized assets
- Hashed filenames for cache busting

The build is ready for deployment to any static hosting service.

### `npm run eject`

**⚠️ Warning**: This is a one-way operation and cannot be reversed.

Ejects from Create React App to gain full control over configuration files (webpack, Babel, ESLint). Only use if you need custom configuration beyond what Create React App provides.

## Project Goals

This project was developed to demonstrate proficiency in:

- ✅ **React Architecture**: Implementation using both Class Components and modern Hooks
- ✅ **State Management**: Complex cart logic with attribute selection and validation
- ✅ **Form Handling**: Comprehensive form validation for checkout process
- ✅ **External Data Integration**: Firebase Firestore for persistent data storage
- ✅ **User Experience**: Intuitive UI/UX design patterns for e-commerce applications

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing and navigation |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database for data persistence |

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Live Demo**: [https://pullrequesttesting.vercel.app/](https://pullrequesttesting.vercel.app/)

For questions or feedback, please open an issue on GitHub.
