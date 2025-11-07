![PullRequestTesting](https://img.shields.io/badge/project-PullRequestTesting-blue)

# PullRequestTesting

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience. Browse through products with customizable attributes, manage your cart with ease, and checkout in your preferred currency.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)

## Features

### Cart Management

- **Add/Remove Products**: Seamlessly add products to your cart or remove them with a single click
- **Quantity Control**: Adjust product quantities directly from your cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item

### Enhanced Shopping Experience

- **Category Filtering**: Efficiently browse products by category
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support

- **Global Currency Options**: Shop in your preferred currency
- **Real-time Currency Conversion**: Prices update dynamically based on your selected currency

### Secure Checkout Process

- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation ensures accurate order information and reduces errors
- **Data Persistence**: Cart data saved externally using Firebase

## Technology Stack

- **Frontend**: React (Class Components refactored to Hooks)
- **Routing**: React Router
- **Backend/Database**: Firebase Firestore
- **Styling**: CSS3
- **Build Tool**: Create React App

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

Runs the application in development mode at [http://localhost:3000](http://localhost:3000).

The page will automatically reload when you make changes. Lint errors will be displayed in the console.

### `npm test`

Launches the test runner in interactive watch mode.

See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the application for production to the `build` folder.

The build is optimized for best performance, with minified files and hashed filenames. Your app is ready to be deployed.

### `npm run eject`

**Note: This is a one-way operation. Once you eject, you can't go back.**

This command removes the single build dependency and copies all configuration files into your project, giving you full control over the build configuration.

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Cart overlay functionality
│   ├── currency-overlay/# Currency selection
│   └── header/          # Header components
├── core-ui/            # Global styles and UI utilities
├── data/               # Static data and product information
├── database/           # Firebase configuration
├── helpers/            # Utility functions
└── routes/             # Page components and routing
    ├── all-products/   # Product listing page
    ├── cart/           # Shopping cart page
    ├── checkout/       # Checkout process
    ├── landing/        # Home page
    ├── not-found/      # 404 page
    ├── order/          # Order confirmation
    └── single-product/ # Product detail page
```

## Project Goals

This project was developed to achieve the following objectives:

- ✅ Practice and master React Class Components, then refactor to modern Hooks
- ✅ Implement complex cart logic with attribute selection and management
- ✅ Develop comprehensive form validation for checkout process
- ✅ Integrate Firebase for external data persistence and real-time updates

## Dependencies

### Core Dependencies

- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [Firebase Firestore](https://firebase.google.com/docs/firestore) - Cloud database and data persistence

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**[Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)** | **[Request Feature](https://github.com/HelloQATeam123/PullRequestTesting/issues)**
