![PullRequestTesting](https://img.shields.io/badge/project-PullRequestTesting-blue)

# PullRequestTesting

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce web application built with React, featuring comprehensive shopping functionality with customizable product attributes including size and color options. The platform provides a complete shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [License](#license)

## Features

### Cart Management

- **Add/Remove Products**: Seamlessly add products to your shopping cart or remove items as needed
- **Quantity Adjustment**: Modify product quantities directly within the cart using dedicated quantity controls
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Attributes**: Detailed display of selected attributes (size, color, etc.) for each cart item

### Product Browsing

- **Category Filtering**: Efficiently navigate through product categories to find desired items
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart ensures order accuracy

### Multi-Currency Support

- **Global Currency Options**: Support for multiple currencies with dedicated currency overlay component
- **Dynamic Currency Conversion**: Real-time price updates based on selected currency

### Checkout Process

- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Order Management**: Complete order processing with success messaging and order confirmation
- **Form Validation**: Comprehensive validation to ensure accurate order information

## Technology Stack

- **Frontend Framework**: React with modern component architecture
- **Routing**: React Router for seamless navigation
- **Database**: Firebase integration for data persistence
- **Styling**: Custom CSS with responsive design and hover effects
- **Testing**: Jest testing framework with React Testing Library

## Getting Started

This project was bootstrapped with Create React App.

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

### Available Scripts

#### `npm start`

Runs the application in development mode.  
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will automatically reload when you make changes. Lint errors will be displayed in the console.

#### `npm test`

Launches the test runner in interactive watch mode.  
See the [running tests](https://facebook.github.io/create-react-app/docs/running-tests) documentation for more information.

#### `npm run build`

Builds the application for production to the `build` folder.  
The build is optimized for best performance, with minified files and hashed filenames.

#### `npm run eject`

**Note: This is a one-way operation. Once you eject, you cannot revert.**

This command removes the single build dependency and copies all configuration files into your project for full customization control.

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Cart overlay functionality
│   ├── currency-overlay/# Currency selection
│   └── header/          # Header components
├── routes/              # Page-level components
│   ├── all-products/    # Product listing page
│   ├── cart/            # Shopping cart page
│   ├── checkout/        # Checkout process
│   ├── landing/         # Home page
│   ├── order/           # Order confirmation
│   └── single-product/  # Product detail page
├── core-ui/             # Global styles and responsive design
├── data/                # Static product data
├── database/            # Firebase configuration
└── helpers/             # Utility functions
```

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**[Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)** | **[Request Feature](https://github.com/HelloQATeam123/PullRequestTesting/issues)**
