![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce web application built with React, featuring comprehensive product catalog with customization options, shopping cart management, and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce platform that demonstrates modern web development practices and provides a seamless shopping experience. The application offers extensive product customization, intuitive cart management, and flexible currency options to accommodate a global user base.

## Key Features

### 🛒 Cart Management

- **Add/Remove Products**: Effortlessly manage your shopping cart with intuitive controls
- **Quantity Adjustment**: Modify product quantities directly from the cart using dedicated components
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Success Notifications**: Visual feedback for cart operations

### 🔍 Product Discovery

- **Category Filtering**: Browse products by category for efficient navigation
- **Single Product Views**: Detailed product pages with comprehensive information
- **Flexible Shopping Flow**: Add items to cart from both category and product detail pages
- **Attribute Selection**: Comprehensive product customization options

### 💱 Multi-Currency Support

- **Global Currency Options**: Shop in your preferred currency with dedicated currency overlay
- **Real-time Currency Conversion**: Seamless price updates across the application

### ✅ Checkout Process

- **Multi-Step Checkout**: Guided, user-friendly checkout flow
- **Order Management**: Complete order processing and confirmation
- **Responsive Design**: Optimized for all device sizes

## Technology Stack

- **Frontend Framework**: React with modern component architecture
- **Routing**: React Router for seamless navigation
- **Backend/Database**: Firebase integration for data persistence
- **Styling**: Custom CSS with responsive design and hover effects
- **Testing**: Jest and React Testing Library

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`

Runs the application in development mode at [http://localhost:3000](http://localhost:3000).

- Hot reload enabled for instant feedback
- Lint errors displayed in console

### `npm test`

Launches the test runner in interactive watch mode.

See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Creates an optimized production build in the `build` folder.

- Minified and optimized for best performance
- Filenames include hashes for cache busting
- Ready for deployment

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Shopping cart overlay
│   ├── currency-overlay/# Currency selection
│   └── header/          # Navigation header
├── routes/              # Page components
│   ├── all-products/    # Product catalog
│   ├── cart/            # Shopping cart page
│   ├── checkout/        # Checkout process
│   ├── landing/         # Home page
│   ├── single-product/  # Product detail page
│   └── order/           # Order confirmation
├── core-ui/             # Global styles and responsive design
├── data/                # Static product data
├── database/            # Firebase configuration
└── helpers/             # Utility functions
```

## Key Components

| Component | Purpose |
|-----------|---------|
| `AddToCartButton` | Handles adding products to shopping cart |
| `ChangeCartItemQuantity` | Manages cart item quantity updates |
| `SuccessMessage` | Displays user feedback notifications |
| `ResetLocation` | Navigation helper utility |

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with ❤️ using React and Firebase**
