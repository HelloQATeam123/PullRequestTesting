![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://pullrequesttesting.vercel.app/)

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
- **Quantity Adjustment**: Modify product quantities directly from the cart with dedicated quantity controls
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item
- **Success Notifications**: Visual feedback when items are successfully added to cart

### Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy
- **Product Gallery**: Interactive image slider for detailed product viewing

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Prices update dynamically based on selected currency
- **Currency Overlay**: Easy currency selection interface

### Secure Checkout Process
- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation ensures accurate order information and reduces errors
- **Order Confirmation**: Complete order processing with confirmation page

## Technical Highlights

This project demonstrates proficiency in:
- React class components with subsequent refactoring to modern hooks
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
   ```

2. Navigate to the project directory
   ```bash
   cd PullRequestTesting
   ```

3. Install dependencies
   ```bash
   npm install
   ```

4. Start the development server
   ```bash
   npm start
   ```

## Available Scripts

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000).

The page will hot-reload on changes, and lint errors will appear in the console.

### `npm test`
Launches the test runner in interactive watch mode.

See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder.

The build is minified, and filenames include hashes for cache optimization. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation and cannot be reversed.**

Ejects the application from Create React App, providing full control over configuration files and dependencies. Only use this if you need complete customization control.

## Technologies & Dependencies

### Core Technologies
- **React** - UI library
- **Create React App** - Build tooling and configuration
- **Firebase Firestore** - Cloud database for data persistence

### Key Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel functionality
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation

### Project Structure
- **Components**: Modular React components for cart management, product attributes, and UI elements
- **Routes**: Page-level components for different application views
- **Core UI**: Centralized styling with responsive design and hover effects
- **Database**: Firebase integration for data management
- **Helpers**: Utility functions for enhanced user experience

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Live Demo**: [pullrequesttesting.vercel.app](https://pullrequesttesting.vercel.app/)
