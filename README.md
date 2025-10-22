![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://pullrequesttesting.vercel.app/)

A modern, full-featured e-commerce platform built with React, offering a comprehensive shopping experience with over 150 women's clothing products featuring customizable attributes, dynamic cart management, and multi-currency support.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technology Stack](#technology-stack)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce application that demonstrates modern web development practices and provides users with an intuitive shopping experience. The platform features a diverse catalog of women's clothing with customizable product attributes, real-time cart management, and flexible currency options to accommodate a global customer base.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add items to your cart or remove them with a single click
- **Quantity Adjustment**: Modify product quantities directly from the cart interface using dedicated quantity controls
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color, etc.) for each cart item before checkout
- **Success Notifications**: Visual feedback when items are successfully added to cart

### Shopping Experience
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy
- **Responsive Design**: Optimized for desktop and mobile devices
- **Product Gallery**: Interactive image sliders for detailed product viewing

### Currency Support
- **Multi-Currency**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Conversion**: Real-time currency conversion for international customers
- **Currency Overlay**: Easy currency selection interface

### Checkout Process
- **Multi-Step Checkout**: Guided checkout process for a smooth transaction experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Order Confirmation**: Complete order processing with confirmation pages
- **Secure Processing**: Built with security best practices in mind

## Technical Highlights

This project showcases several key development achievements:

- **React Architecture**: Modern React application with component-based architecture
- **State Management**: Complex cart logic with attribute selection and quantity management
- **Form Validation**: Client-side validation for enhanced user experience
- **Firebase Integration**: External data persistence using Firestore database
- **Responsive Design**: Mobile-first approach with cross-device compatibility
- **Routing**: Client-side routing with React Router for seamless navigation
- **Component Organization**: Well-structured component hierarchy with reusable UI elements

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
Builds the application for production to the `build` folder. The build is optimized for best performance, with minified files and hashed filenames ready for deployment. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you cannot go back.**

This command removes the single build dependency and copies all configuration files (webpack, Babel, ESLint, etc.) into your project for full customization control. Only use this if you need advanced configuration options.

## Technology Stack

### Core Technologies
- **React** - Frontend framework
- **Create React App** - Build tooling and configuration

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel functionality
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - Cloud database for data persistence

### Project Structure
- **Components**: Modular React components including cart management, currency selection, and UI elements
- **Routes**: Page-level components for different application views
- **Core UI**: Centralized styling with responsive design and hover effects
- **Database**: Firebase integration for data persistence
- **Helpers**: Utility functions and location management

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Repository**: [github.com/HelloQATeam123/PullRequestTesting](https://github.com/HelloQATeam123/PullRequestTesting)
