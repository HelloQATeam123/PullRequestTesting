![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options, dynamic cart management, and multi-currency support.

## Overview

Shopping Time is a production-ready e-commerce application built with React, featuring an extensive catalog of women's fashion items. The platform provides a seamless shopping experience with advanced product customization, real-time cart management, and flexible currency options to serve a global customer base.

## Key Features

### Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items with instant feedback
- **Quantity Adjustment**: Real-time quantity updates with automatic price recalculation
- **Cart Overlay**: Quick-access cart summary without navigation disruption
- **Product Attributes**: Detailed display of selected attributes (size, color) for informed purchasing decisions

### Shopping Experience
- **Category Filtering**: Efficient product discovery through organized category navigation
- **Multi-Page Shopping**: Add products to cart from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy

### Currency Support
- **Multi-Currency**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Dynamic Conversion**: Real-time price updates based on selected currency

### Checkout Process
- **Multi-Step Workflow**: Guided checkout process optimized for conversion
- **Form Validation**: Comprehensive input validation to ensure data accuracy and reduce errors

## Technical Highlights

- Implemented with React Class components, refactored to modern Hooks architecture
- Custom cart logic with attribute selection and validation
- Firebase/Firestore integration for persistent data storage
- Comprehensive form validation system
- Responsive design for cross-device compatibility

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
Runs the application in development mode with hot-reloading enabled.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Creates an optimized production build in the `build` folder with minification and hashing.

### `npm run eject`
**Warning**: This is a one-way operation. Ejects from Create React App to expose configuration files for advanced customization.

## Technology Stack

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Product image galleries
- **[uuid](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firestore](https://firebase.google.com/docs/firestore)** - Cloud database for data persistence

### Development Tools
- Create React App - Build tooling and configuration
- React Hooks - Modern state management
- Firebase SDK - Backend services integration

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Cart management components
│   ├── currency-overlay/ # Currency selection
│   └── header/         # Navigation components
├── routes/             # Page-level components
│   ├── all-products/   # Product catalog
│   ├── cart/           # Shopping cart
│   ├── checkout/       # Checkout process
│   └── single-product/ # Product details
├── data/               # Static product data
├── database/           # Firebase configuration
└── helpers/            # Utility functions
```

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
