![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience with over 150 women's clothing products. The application features dynamic product attributes, real-time cart management, and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Architecture](#project-architecture)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce application that demonstrates modern React development practices and provides a comprehensive online shopping experience. The platform supports extensive product customization, intelligent cart management, and a streamlined checkout process.

**Live Demo:** [https://shopping-time.vercel.app/](https://shopping-time.vercel.app/)

## Key Features

### Cart Management
- **Dynamic Product Addition/Removal**: Seamlessly add or remove products from your shopping cart
- **Quantity Adjustment**: Modify product quantities directly within the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving the current page
- **Attribute Tracking**: Comprehensive display of selected product attributes (size, color, etc.)
- **Real-time Updates**: Instant cart synchronization across all views

### Product Discovery
- **Category Filtering**: Intuitive navigation through product categories
- **Multi-page Shopping**: Add products from both category listings and individual product pages
- **Attribute Validation**: Required attribute selection before cart addition to ensure order accuracy
- **Detailed Product Information**: Complete specifications and multiple product images

### International Support
- **Multi-Currency**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Dynamic Currency Conversion**: Real-time price updates based on selected currency
- **Localized Shopping Experience**: Tailored for global customers

### Checkout Process
- **Multi-Step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive validation to ensure data accuracy
- **Secure Processing**: Built with security best practices in mind

## Technology Stack

### Core Technologies
- **React**: Component-based UI development
- **React Router**: Client-side routing and navigation
- **Firebase Firestore**: Cloud-based data persistence
- **Create React App**: Build tooling and development environment

### Key Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Declarative routing for React applications
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Product image galleries
- [UUID](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firebase Firestore](https://firebase.google.com/docs/firestore) - NoSQL cloud database

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

5. **Access the application**
   - Open [http://localhost:3000](http://localhost:3000) in your browser

## Available Scripts

### `npm start`
Launches the development server with hot-reloading enabled.
- **URL**: [http://localhost:3000](http://localhost:3000)
- **Features**: Automatic reloading on file changes, lint error reporting

### `npm test`
Executes the test suite in interactive watch mode.
- See [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information

### `npm run build`
Creates an optimized production build.
- **Output**: `build/` directory
- **Optimizations**: Minification, code splitting, hash-based filenames
- **Deployment Ready**: Optimized for best performance
- See [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information

### `npm run eject`
⚠️ **Warning**: This is a one-way operation and cannot be reversed.

Ejects from Create React App, providing full control over configuration files and build dependencies. Only use if you need complete customization of the build process.

## Project Architecture

### Development Approach
- **Component Evolution**: Initially developed with React Class components, subsequently refactored to modern React Hooks
- **State Management**: Centralized cart logic with context-based state management
- **Form Handling**: Custom validation logic for checkout and user input
- **External Data Persistence**: Firebase integration for scalable data storage

### Key Accomplishments
- ✅ Mastered React Class components and Hooks patterns
- ✅ Implemented complex cart logic with attribute selection
- ✅ Developed comprehensive form validation system
- ✅ Integrated Firebase for cloud-based data management
- ✅ Created responsive, mobile-friendly interface
- ✅ Implemented multi-currency support

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss proposed modifications.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for complete details.

The MIT License permits use, modification, and distribution of this software in accordance with the terms specified in the LICENSE file.

---

**Built with ❤️ using React** | [Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues) | [Request Feature](https://github.com/HelloQATeam123/PullRequestTesting/issues)
