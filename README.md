![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options, dynamic cart management, and multi-currency support.

## Overview

Shopping Time is a production-ready e-commerce application built with React, offering an intuitive shopping experience with advanced product filtering, real-time cart management, and seamless checkout functionality. The platform supports multiple product attributes (size, color) and provides customers with flexible currency options for international shopping.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add items to your cart or remove them with a single click
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Attribute Display**: View selected product attributes (size, color) at checkout for order accuracy

### Product Discovery
- **Category Filtering**: Browse products by category for streamlined navigation
- **Multi-Page Shopping**: Add products to cart from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding to cart to ensure order accuracy

### International Support
- **Multi-Currency**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Dynamic Conversion**: Real-time currency conversion for global customers

### Checkout Experience
- **Multi-Step Process**: Guided checkout flow for improved user experience
- **Form Validation**: Client-side validation to ensure data accuracy and reduce errors
- **Secure Processing**: Built with security best practices

## Technical Highlights

- **React Architecture**: Initially built with class components, refactored to modern React Hooks
- **State Management**: Custom cart logic with attribute selection and validation
- **Form Handling**: Comprehensive validation for checkout process
- **Backend Integration**: Firebase/Firestore for data persistence

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Available Scripts

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page auto-reloads on changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified and includes hashed filenames for cache optimization. See [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you cannot revert.**

Ejects from Create React App, exposing all configuration files and dependencies (webpack, Babel, ESLint, etc.) for full customization. Only use if necessary for advanced configuration needs.

## Tech Stack

### Core Dependencies
- **React** - Frontend framework
- **React Router** - Client-side routing
- **React Simple Image Slider** - Product image galleries
- **uuid** - Unique identifier generation
- **Firebase/Firestore** - Cloud database for data persistence

### Build Tools
- Create React App - Project bootstrapping and build configuration

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
