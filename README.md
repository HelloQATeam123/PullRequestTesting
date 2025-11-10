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
- **Add/Remove Products**: Seamlessly add products to your cart or remove them as needed
- **Quantity Adjustment**: Modify product quantities directly from the cart with dedicated quantity controls
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item
- **Success Notifications**: Visual confirmation when items are added to cart

### Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy
- **Responsive Design**: Optimized experience across desktop, tablet, and mobile devices

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency with dedicated currency overlay
- **Real-time Currency Conversion**: Prices update dynamically based on selected currency

### Secure Checkout Process
- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation ensures accurate order information and reduces errors
- **Order Confirmation**: Complete order processing with confirmation pages

## Technical Highlights

This project demonstrates proficiency in:
- React class components with modern hooks implementation
- Complex state management for cart and product attributes
- Form validation and error handling
- Firebase Firestore integration for external data persistence
- Responsive design and user experience optimization
- Component-based architecture with reusable UI elements
- Client-side routing with React Router

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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include hashes for cache busting. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation that cannot be reversed.**

Ejects the project from Create React App, providing full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). Only use this if you need complete customization control.

## Technology Stack

### Core Technologies
- **React** - UI framework
- **Create React App** - Project bootstrapping and build tooling

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel functionality
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firebase Firestore](https://firebase.google.com/docs/firestore) - Cloud database for data persistence

### Project Structure
- **Components**: Modular UI components including cart management, currency selection, and navigation
- **Routes**: Page-level components for different application views
- **Core UI**: Centralized styling with responsive design and hover effects
- **Database**: Firebase integration for data persistence
- **Helpers**: Utility functions and location management

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.
