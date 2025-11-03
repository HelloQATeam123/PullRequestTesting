# Shopping Time

![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

**Live Demo:** [shopping-time.vercel.app](https://shopping-time.vercel.app/)

## Overview

Shopping Time is a modern e-commerce platform featuring over 150 women's clothing products with customizable attributes including size and color variations. The application provides a comprehensive shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them as needed
- **Quantity Adjustment**: Modify product quantities directly from the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item

### Product Discovery
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attributes must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- Seamless currency switching for international customers

### Checkout Process
- **Multi-Step Workflow**: Intuitive, guided checkout experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Secure Processing**: User-friendly interface with security best practices

## Technical Implementation

### Development Achievements
- Implemented using React Class components, later refactored to React Hooks
- Custom cart logic with attribute selection and validation
- Form validation system for checkout process
- Firebase integration for external data persistence

## Getting Started

### Prerequisites
- Node.js and npm installed on your system

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

## Available Scripts

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors are displayed in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [Create React App testing documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified and includes hashed filenames for optimal performance. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation and cannot be reversed.**

Ejects the application from Create React App, providing full control over configuration files and dependencies. This is not recommended unless you require advanced customization.

## Technology Stack

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)**: Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)**: Image carousel functionality
- **[uuid](https://www.npmjs.com/package/uuid)**: Unique identifier generation
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)**: Cloud-based data storage

### Framework
Built with [Create React App](https://github.com/facebook/create-react-app)

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for complete terms and conditions.

---

**Note:** This project was created for educational and portfolio purposes.
