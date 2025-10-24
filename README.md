![Shopping Time](https://raw.githubusercontent.com/catherineisonline/shopping-time/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://shopping-time.vercel.app/)

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
- **Multi-Page Shopping**: Add products to cart from both category pages and individual product detail pages
- **Required Attribute Selection**: Enforced attribute selection (size, color) before adding to cart to prevent ordering errors

### International Support
- **Multi-Currency**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Dynamic Currency Conversion**: Real-time price updates based on selected currency

### Checkout Experience
- **Multi-Step Process**: Guided checkout flow for improved user experience
- **Form Validation**: Client-side validation to ensure data accuracy and reduce errors
- **Secure Processing**: Built with security best practices in mind

## Technical Highlights

- Implemented using React class components, later refactored to modern React Hooks
- Custom cart logic with attribute selection and validation
- Firebase/Firestore integration for data persistence
- Comprehensive form validation system
- Responsive design for mobile and desktop experiences

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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page auto-reloads on code changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for cache busting. See [deployment](https://facebook.github.io/create-react-app/docs/deployment) for details.

### `npm run eject`
**Warning: This is a one-way operation!**

Ejects from Create React App, giving you full control over configuration files and dependencies. Only use if you need custom configuration beyond what Create React App provides.

## Technology Stack

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Product image galleries
- **[uuid](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firestore](https://firebase.google.com/docs/firestore)** - Cloud database for data persistence

### Development Tools
- Create React App - Project bootstrapping and build tooling
- ESLint - Code quality and consistency

## Project Structure

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), providing a modern build setup with no configuration required.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Built as a demonstration of modern React development practices and e-commerce functionality implementation.
