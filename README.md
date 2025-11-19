![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

**Live Demo:** [shopping-time.vercel.app](https://shopping-time.vercel.app/)

Shopping Time is a modern, full-featured e-commerce web application specializing in women's fashion. The platform offers an extensive catalog of over 150 products with customizable attributes including size and color variations. Built with React, the application provides a seamless shopping experience with real-time cart management and multi-currency support.

## Table of Contents
- [Key Features](#key-features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technology Stack](#technology-stack)
- [License](#license)

## Key Features

### Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items with real-time updates
- **Quantity Adjustment**: Flexible quantity controls for each product in the cart
- **Cart Overlay**: Quick-access cart summary without leaving the current page
- **Detailed Product Information**: Complete attribute display including selected size, color, and other specifications

### Enhanced Shopping Experience
- **Category Filtering**: Efficient product discovery through organized category navigation
- **Multi-Page Shopping**: Add products to cart from both category listings and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy
- **Responsive Design**: Optimized experience across all device sizes

### Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Seamless currency switching throughout the shopping experience

### Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process designed for clarity and ease of use
- **Form Validation**: Comprehensive input validation to ensure data accuracy and prevent errors
- **User-Friendly Interface**: Intuitive design focused on conversion optimization

## Technical Highlights

This project demonstrates proficiency in:
- React class components with subsequent refactoring to modern hooks
- Complex state management for cart and product attributes
- Form validation and error handling
- Firebase/Firestore integration for data persistence
- Responsive design principles
- Component-based architecture

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
Launches the development server with hot-reload functionality.
- Opens at [http://localhost:3000](http://localhost:3000)
- Automatically reloads on code changes
- Displays lint errors in the console

### `npm test`
Executes the test suite in interactive watch mode.
See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder.
- Minifies code for optimal performance
- Includes content hashes in filenames for cache busting
- Ready for deployment

See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation and cannot be reversed.**

Ejects from Create React App, providing full control over configuration files and dependencies. Only use if you need complete customization of the build tooling.

## Technology Stack

### Core Technologies
- **React** - Frontend framework
- **Create React App** - Build tooling and configuration
- **Firebase/Firestore** - Backend database and data persistence

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Product image galleries
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - Cloud database

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note:** This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
