![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options including size and color selection, shopping cart management, and multi-currency support.

## Table of Contents
- [Features](#features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#scripts)
- [Technologies & Dependencies](#dependencies)
- [License](#license)

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them with intuitive controls
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary overlay for efficient shopping without page navigation
- **Detailed Product Attributes**: View selected size, color, and other product specifications within the cart

### Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for streamlined product discovery
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product detail pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Seamless price updates across the platform

### Secure Checkout Process
- **Multi-Step Checkout**: Guided checkout flow designed for optimal user experience
- **Form Validation**: Comprehensive validation to ensure accurate order information and reduce errors

## Technical Highlights

This project demonstrates proficiency in:
- React class components with subsequent refactoring to modern React Hooks
- Complex state management for cart and product attribute selection
- Form validation implementation
- Firebase/Firestore integration for external data persistence
- Responsive design principles

## Getting Started

### Prerequisites
- Node.js (v14 or higher recommended)
- npm or yarn package manager

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

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts <a id="scripts"></a>

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000).
- Hot reload enabled for real-time updates
- Lint errors displayed in console

### `npm test`
Launches the test runner in interactive watch mode.
See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder.
- Minified and optimized for best performance
- Filenames include hashes for cache busting
- Ready for deployment

See [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation and cannot be reversed.**

Ejects the application from Create React App, providing full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). Only use if customization beyond CRA's capabilities is required.

## Technologies & Dependencies <a id="dependencies"></a>

- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Image carousel functionality
- **[uuid](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - Cloud-based NoSQL database

## License <a id="license"></a>

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
