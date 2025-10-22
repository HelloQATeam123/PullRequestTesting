![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

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
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color, etc.) for each cart item before checkout

### Shopping Experience
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy
- **Responsive Design**: Optimized for desktop and mobile devices

### Currency Support
- **Multi-Currency**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Conversion**: Real-time currency conversion for international customers

### Checkout Process
- **Multi-Step Checkout**: Guided checkout process for a smooth transaction experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Secure Processing**: Built with security best practices in mind

## Technical Highlights

This project showcases several key development achievements:

- **React Architecture**: Modern React implementation with hooks and functional components
- **State Management**: Complex cart logic with attribute selection and validation
- **Form Validation**: Robust client-side validation for checkout process
- **Firebase Integration**: External data persistence using Firestore
- **Responsive Design**: Mobile-first approach with cross-device compatibility

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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000).
- Hot reload enabled for instant feedback
- Console displays lint errors and warnings

### `npm test`
Launches the test runner in interactive watch mode.
See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder.
- Minified and optimized for best performance
- Filenames include content hashes for cache busting
- Ready for deployment

See [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**⚠️ Warning: This is a one-way operation. Once you eject, you cannot go back!**

Ejects the build configuration, giving you full control over webpack, Babel, ESLint, and other dependencies. Only use this if you need custom configuration beyond what Create React App provides.

## Technology Stack

### Core Dependencies
- **[React](https://reactjs.org/)** - UI library
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Image carousel component
- **[uuid](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - Cloud database for data persistence

### Development Tools
- **[Create React App](https://github.com/facebook/create-react-app)** - Build toolchain and development environment

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The MIT License permits commercial and private use, modification, and distribution of this software, provided that the original copyright notice and license terms are included in all copies or substantial portions of the software.

---

For questions, issues, or contributions, please open an issue on GitHub.
