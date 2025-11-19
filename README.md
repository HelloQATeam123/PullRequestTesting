![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options including size and color selection, shopping cart management, and multi-currency support.

## Table of Contents
- [Features](#features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technology Stack](#technology-stack)
- [License](#license)

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them with intuitive controls
- **Quantity Adjustment**: Modify product quantities directly from the cart interface using the ChangeCartItemQuantity component
- **Cart Overlay**: Quick-access cart summary overlay for efficient shopping without page navigation
- **Detailed Product Attributes**: View selected sizes, colors, and other product specifications within the cart

### Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for streamlined product discovery
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product detail pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy
- **Success Notifications**: Real-time feedback when products are successfully added to cart

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Seamless price updates across the platform via currency overlay

### Secure Checkout Process
- **Multi-Step Checkout**: Guided checkout flow designed for optimal user experience
- **Form Validation**: Comprehensive validation to ensure accurate order information and reduce errors
- **Order Confirmation**: Complete order processing with confirmation pages

## Technical Highlights

This project demonstrates proficiency in:
- React class components with subsequent refactoring to modern React Hooks
- Complex state management for cart functionality and product attributes
- Form validation implementation
- Firebase/Firestore integration for external data persistence
- Responsive design principles with dedicated CSS modules
- Component-based architecture with reusable UI elements

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
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder with minified files and hashed filenames ready for deployment. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning**: This is a one-way operation that cannot be reversed.

Ejects the project from Create React App, providing full control over configuration files and dependencies. Only use this if you need complete customization of the build configuration.

## Technology Stack

### Core Technologies
- **React** - UI framework
- **Create React App** - Build tooling and configuration

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel functionality
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firebase Firestore](https://firebase.google.com/docs/firestore) - Cloud database and data persistence

### Project Structure
- **Components**: Modular React components for cart management, currency handling, and UI elements
- **Routes**: Page-level components for different application views
- **Core UI**: Centralized styling with responsive design and hover effects
- **Data**: Product information and application data management
- **Helpers**: Utility functions and location management

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note**: This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
