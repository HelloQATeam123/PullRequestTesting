![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce web application built with React, featuring over 150 women's clothing products with customizable attributes including size and color options. The platform provides a comprehensive shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Features

### Cart Management

- **Add/Remove Products**: Seamlessly add products to your shopping cart or remove items as needed
- **Quantity Adjustment**: Modify product quantities directly within the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.) for each cart item

### Product Browsing

- **Category Filtering**: Efficiently navigate through product categories to find desired items
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart ensures order accuracy

### Multi-Currency Support

- **Global Currency Options**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Currency Conversion**: Real-time price updates based on selected currency

### Checkout Process

- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation to ensure accurate order information and reduce errors

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: [React Router](https://www.npmjs.com/package/react-router-dom)
- **UI Components**: [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)
- **Utilities**: [uuid](https://www.npmjs.com/package/uuid)
- **Backend/Database**: [Firebase Firestore](https://firebase.google.com/docs/firestore)

## Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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

### Available Scripts

#### `npm start`

Runs the application in development mode.  
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will automatically reload when you make changes. Lint errors will be displayed in the console.

#### `npm test`

Launches the test runner in interactive watch mode.  
See the [running tests](https://facebook.github.io/create-react-app/docs/running-tests) documentation for more information.

#### `npm run build`

Builds the application for production to the `build` folder.  
The build is optimized for best performance, with minified files and hashed filenames.

See the [deployment](https://facebook.github.io/create-react-app/docs/deployment) documentation for more information.

#### `npm run eject`

**Note: This is a one-way operation. Once you eject, you cannot revert.**

This command removes the single build dependency and copies all configuration files (webpack, Babel, ESLint, etc.) into your project for full customization control.

## Project Goals

This project was developed to achieve the following objectives:

- ✅ Practice and master React Class Components, then refactor to modern Hooks
- ✅ Implement complex cart logic with attribute selection and management
- ✅ Develop comprehensive form validation for checkout process
- ✅ Integrate Firebase for external data persistence and management

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**[Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)** | **[Request Feature](https://github.com/HelloQATeam123/PullRequestTesting/issues)**
