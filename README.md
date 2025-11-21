![Shopping Time](https://raw.githubusercontent.com/catherineisonline/shopping-time/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://shopping-time.vercel.app/)

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options including size and color selection, shopping cart management, and multi-currency support.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Dependencies](#dependencies)
- [License](#license)

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add or remove items from your shopping cart
- **Quantity Adjustment**: Modify product quantities directly within the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item

### Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Prices automatically update based on selected currency

### Secure Checkout Process
- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation ensures accurate order information and reduces errors

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Backend/Database**: Firebase Firestore
- **Routing**: React Router
- **State Management**: React Hooks
- **Build Tool**: Create React App

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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include hashes for cache busting. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning**: This is a one-way operation. Ejecting exposes all configuration files and dependencies, giving you full control but removing the abstraction layer provided by Create React App.

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [uuid](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and data persistence |

## Project Highlights

- ✅ Implemented with React Class Components, then refactored to modern Hooks
- ✅ Custom cart logic with attribute selection and validation
- ✅ Comprehensive form validation throughout checkout process
- ✅ Firebase integration for external data persistence
- ✅ Responsive design for optimal viewing across devices

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Live Demo**: [shopping-time.vercel.app](https://shopping-time.vercel.app/)
