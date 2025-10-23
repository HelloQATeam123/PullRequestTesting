![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://shopping-time.vercel.app/)

A modern, full-featured e-commerce platform built with React, offering an extensive catalog of over 150 women's clothing products with customizable attributes including size and color variations. The application provides a comprehensive shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [Dependencies](#dependencies)
- [License](#license)

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add items to your shopping cart or remove them with intuitive controls
- **Quantity Adjustment**: Modify product quantities directly within the cart interface
- **Cart Overlay**: Quick-access cart summary overlay for efficient shopping without page navigation
- **Product Attributes**: Detailed display of selected product attributes (size, color, etc.) for informed purchasing decisions

### Product Discovery & Selection
- **Category Filtering**: Browse products by category for efficient product discovery
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product detail pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy

### Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Currency Conversion**: Real-time price updates based on selected currency

### Checkout Experience
- **Multi-Step Checkout**: Guided checkout process designed for security and ease of use
- **Form Validation**: Comprehensive input validation to ensure data accuracy and prevent errors

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: React Router
- **Backend/Database**: Firebase Firestore
- **Build Tool**: Create React App
- **Additional Libraries**: React Simple Image Slider, UUID

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

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, filenames include hashes, and the app is ready for deployment. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation. Once you eject, you cannot revert.**

Ejects the app from Create React App, copying all configuration files and dependencies into your project for full customization control. Only use this if you need advanced configuration options.

## Project Goals

This project was developed to achieve the following technical objectives:

- **React Proficiency**: Practice with React Class Components and modern Hooks patterns
- **State Management**: Implement complex cart logic with attribute selection and validation
- **Form Handling**: Develop robust form validation for checkout processes
- **External Data Persistence**: Integrate Firebase Firestore for data storage and retrieval
- **User Experience**: Create an intuitive, responsive e-commerce interface

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and backend services |

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details. You are free to use, modify, and distribute this project in accordance with the MIT License terms.

---

**Live Demo**: [shopping-time.vercel.app](https://shopping-time.vercel.app/)
