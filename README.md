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

Shopping Time is a production-ready e-commerce application that demonstrates modern React development practices. The platform features an extensive catalog of women's clothing with customizable product attributes, real-time cart management, and a streamlined checkout process.

**Live Demo:** [https://shopping-time.vercel.app/](https://shopping-time.vercel.app/)

## Key Features

### 🛒 Cart Management

- **Add/Remove Products**: Intuitive controls for managing cart items
- **Quantity Adjustment**: Real-time quantity updates with instant price recalculation
- **Cart Overlay**: Quick-access cart summary without page navigation
- **Product Attributes**: Detailed display of selected sizes, colors, and other product specifications
- **Persistent Storage**: Cart data saved using Firebase for cross-session continuity

### 🔍 Product Discovery

- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping**: Add items from both category pages and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy

### 💱 Multi-Currency Support

- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Real-time Conversion**: Automatic price updates based on selected currency
- **Localized Experience**: Shop in your preferred currency for transparent pricing

### ✅ Checkout Process

- **Multi-Step Flow**: Guided checkout process for improved user experience
- **Form Validation**: Comprehensive validation to ensure data accuracy and reduce errors
- **Secure Processing**: User-friendly interface with security best practices

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
   - Enable Firestore database

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   - Navigate to [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`

Runs the application in development mode with hot-reloading enabled.

- **URL**: [http://localhost:3000](http://localhost:3000)
- **Features**: Automatic reload on file changes, lint error reporting in console

### `npm test`

Launches the test runner in interactive watch mode.

- **Documentation**: [Running Tests](https://facebook.github.io/create-react-app/docs/running-tests)

### `npm run build`

Creates an optimized production build in the `build` folder.

- **Optimizations**: Minification, code splitting, hash-based filenames
- **Output**: Production-ready static files
- **Documentation**: [Deployment Guide](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run eject`

**⚠️ Warning: This is a one-way operation and cannot be reversed.**

Ejects from Create React App to gain full control over configuration files (webpack, Babel, ESLint, etc.). Only use if you need advanced customization beyond CRA's capabilities.

## Project Goals

This project was developed to achieve the following technical objectives:

- ✅ **React Proficiency**: Implement and refactor React Class Components to modern Hooks
- ✅ **State Management**: Build complex logic for product attributes and cart operations
- ✅ **Form Handling**: Implement comprehensive form validations for checkout process
- ✅ **External Integration**: Utilize Firebase Firestore for persistent data storage
- ✅ **User Experience**: Create an intuitive, responsive e-commerce interface

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

**Built with ❤️ using React and Firebase**
