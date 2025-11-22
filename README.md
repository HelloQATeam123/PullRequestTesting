![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience with over 150 women's clothing products featuring multiple size and color options.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce application that demonstrates modern React development practices and provides a complete online shopping experience. The platform features an extensive catalog of women's clothing with advanced filtering, cart management, and multi-currency support.

**Live Demo:** [https://shopping-time.vercel.app/](https://shopping-time.vercel.app/)

## Key Features

### 🛒 Advanced Cart Management
- **Add/Remove Products:** Intuitive interface for managing cart items
- **Quantity Adjustment:** Real-time quantity updates with instant price recalculation
- **Cart Overlay:** Quick-access cart summary without page navigation
- **Detailed Product Attributes:** Complete visibility of selected sizes, colors, and specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering:** Efficient product discovery through organized categories
- **Flexible Shopping Paths:** Add products from both category and individual product pages
- **Attribute Validation:** Required attribute selection (size, color) before cart addition to ensure order accuracy

### 💱 Multi-Currency Support
- **Global Currency Options:** Support for EUR, GBP, AUD, JPY, and additional currencies
- **Real-time Conversion:** Seamless currency switching throughout the shopping experience

### ✅ Secure Checkout Process
- **Multi-Step Workflow:** Guided checkout process for improved user experience
- **Form Validation:** Comprehensive validation to ensure data accuracy and prevent errors
- **Firebase Integration:** Secure external data persistence

## Technology Stack

- **Frontend Framework:** React (Class Components refactored to Hooks)
- **Routing:** React Router DOM
- **UI Components:** React Simple Image Slider
- **Utilities:** UUID for unique identifiers
- **Backend/Database:** Firebase Firestore
- **Build Tool:** Create React App

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

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Add your Firebase configuration to the project

4. **Start the development server**
   ```bash
   npm start
   ```

The application will open at [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`
Launches the development server with hot-reload functionality.
- Opens at [http://localhost:3000](http://localhost:3000)
- Automatically reloads on code changes
- Displays lint errors in the console

### `npm test`
Runs the test suite in interactive watch mode.
See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder.
- Minifies code for optimal performance
- Includes content hashes in filenames for cache busting
- Ready for deployment

See [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**⚠️ Warning: This is a one-way operation and cannot be reversed.**

Ejects from Create React App, providing full control over configuration files and dependencies. Only use if you need complete customization beyond CRA's capabilities.

## Project Goals

This project was developed to achieve the following technical objectives:

- ✅ Master React Class Components and modern Hooks patterns
- ✅ Implement complex state management for product attributes and cart functionality
- ✅ Develop comprehensive form validation system
- ✅ Integrate Firebase for scalable data persistence
- ✅ Create a production-ready, user-friendly e-commerce platform

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and data persistence |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with ❤️ using React and Firebase**
