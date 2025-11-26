![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options, shopping cart functionality, and multi-currency support.

## Overview

Shopping Time is a production-ready e-commerce application built with React, offering an intuitive shopping experience with advanced product filtering, cart management, and a streamlined checkout process. The platform supports multiple product attributes (size, color) and provides customers with flexible currency options for a truly global shopping experience.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add items to your cart or remove them with a single click
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View all selected attributes (size, color, etc.) before checkout

### Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product detail pages
- **Attribute Validation**: Required attributes must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Prices update dynamically based on selected currency

### Secure Checkout Process
- **Multi-Step Checkout**: Guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation ensures accurate order information
- **Error Prevention**: Built-in safeguards to minimize user errors during checkout

## Technical Highlights

- **React Architecture**: Modern React application with component-based architecture
- **State Management**: Custom cart logic with attribute selection and validation
- **Form Validation**: Robust client-side validation for checkout process
- **Firebase Integration**: External data persistence using Firestore

## Technology Stack

### Core Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Product image galleries
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - Cloud database

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
Launches the development server at [http://localhost:3000](http://localhost:3000) with hot-reloading enabled.

### `npm test`
Runs the test suite in interactive watch mode. See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified and includes hashed filenames for cache optimization.

### `npm run eject`
**Warning**: This is a one-way operation. Ejects from Create React App, giving you full control over configuration files and dependencies.

## Project Structure

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), providing a solid foundation with modern build tooling and best practices.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
