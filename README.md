![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

A modern, full-featured e-commerce platform built with React, offering a comprehensive shopping experience with over 150 women's clothing products, dynamic product attributes, and multi-currency support.

## Overview

Shopping Time is a production-ready e-commerce application that demonstrates modern web development practices and provides users with an intuitive shopping experience. The platform features extensive product customization options, real-time cart management, and a streamlined checkout process.

## Key Features

### Cart Management
- **Dynamic Product Management**: Add, remove, and update product quantities with real-time cart synchronization
- **Cart Overlay**: Quick-access cart summary for seamless shopping without page navigation
- **Detailed Product Information**: View selected attributes (size, color) and product details directly in the cart
- **Persistent Cart State**: Cart data is maintained across sessions using Firebase integration

### Product Browsing & Selection
- **Category Filtering**: Efficiently browse products by category with intuitive navigation
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product detail pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy
- **Comprehensive Product Details**: Each product includes multiple images, detailed descriptions, and available variations

### Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Prices automatically update based on selected currency
- **Localized Shopping Experience**: Shop in your preferred currency for transparent pricing

### Checkout Process
- **Multi-Step Checkout**: Guided checkout flow with clear progress indicators
- **Form Validation**: Comprehensive validation ensures accurate order information and reduces errors
- **Secure Data Handling**: User information is processed securely with proper validation and error handling

## Technical Highlights

- **React Architecture**: Initially built with class components, refactored to modern React Hooks for improved performance and maintainability
- **State Management**: Efficient state management for cart, products, and user preferences
- **Firebase Integration**: External data persistence using Firestore for reliable data storage
- **Responsive Design**: Fully responsive interface optimized for desktop, tablet, and mobile devices
- **Form Validation**: Robust client-side validation for enhanced user experience and data integrity

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

4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Available Scripts

### `npm start`
Runs the application in development mode with hot-reloading enabled. The page will automatically reload when you make changes, and lint errors will be displayed in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for efficient caching. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you cannot revert.**

Ejects the application from Create React App, giving you full control over the build configuration. This copies all configuration files and dependencies into your project. Only use this if you need custom configuration beyond what Create React App provides.

## Technology Stack

### Core Technologies
- **React**: Frontend framework with Hooks-based architecture
- **React Router**: Client-side routing and navigation
- **Firebase Firestore**: Cloud-based NoSQL database for data persistence

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Declarative routing for React applications
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Lightweight image carousel component
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation for cart items and orders
- [Firestore](https://firebase.google.com/docs/firestore) - Cloud database for storing product and order data

## Project Structure

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), providing a solid foundation with modern build tooling and best practices.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details. You are free to use, modify, and distribute this project in accordance with the MIT License terms.

## Acknowledgments

Built with Create React App and deployed on Vercel for optimal performance and reliability.
