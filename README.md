![Shopping Time](https://raw.githubusercontent.com/catherineisonline/shopping-time/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://shopping-time.vercel.app/)

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options including size and color selection, shopping cart management, and multi-currency support.

## Overview

Shopping Time is a production-ready e-commerce application built with React, demonstrating best practices in modern web development. The platform provides a seamless shopping experience with intuitive navigation, real-time cart management, and secure checkout processes.

## Key Features

### Cart Management
- **Add/Remove Products**: Effortlessly manage your shopping cart with intuitive controls
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item

### Product Discovery
- **Category Filtering**: Browse products by category for streamlined navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product detail pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Seamless price updates across the platform

### Checkout Experience
- **Multi-Step Process**: Guided checkout flow for enhanced user experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Secure Processing**: Built with security and data integrity in mind

## Technical Highlights

- **React Architecture**: Initially built with class components, refactored to modern React Hooks
- **State Management**: Custom cart logic with attribute selection and validation
- **Form Validation**: Robust client-side validation for checkout process
- **Firebase Integration**: External data persistence using Firestore

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

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Available Scripts

### `npm start`
Runs the application in development mode with hot-reloading enabled.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Creates an optimized production build in the `build` folder.

### `npm run eject`
**Warning**: This is a one-way operation. Ejects from Create React App, giving you full control over configuration files.

## Technology Stack

- **Framework**: React (Create React App)
- **Routing**: React Router
- **UI Components**: React Simple Image Slider
- **Utilities**: uuid
- **Backend**: Firebase Firestore

## Dependencies

- [React Router](https://www.npmjs.com/package/react-router-dom) - Declarative routing for React
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel component
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - Cloud-hosted NoSQL database

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
