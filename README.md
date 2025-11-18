![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options including size and color selection, shopping cart management, and multi-currency support.

## Table of Contents
- [Features](#features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technologies & Dependencies](#technologies--dependencies)
- [License](#license)

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them as needed
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item before checkout

### Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product detail pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Prices update dynamically based on selected currency

### Secure Checkout Process
- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation ensures accurate order information and reduces errors

## Technical Highlights

This project demonstrates proficiency in:
- React class components with subsequent refactoring to modern hooks
- Complex state management for cart and product attributes
- Form validation and error handling
- Firebase integration for external data persistence
- Responsive design and user experience optimization

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

The application will open at [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include hashes for cache busting. See [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation!**

Ejects the application from Create React App, providing full control over configuration files. Only use if you need custom configuration beyond what Create React App provides.

## Technologies & Dependencies

### Core Technologies
- **React** - UI framework
- **Create React App** - Build tooling and configuration
- **Firebase Firestore** - Cloud database for data persistence

### Key Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel functionality
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - NoSQL cloud database

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with Create React App** | [Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
