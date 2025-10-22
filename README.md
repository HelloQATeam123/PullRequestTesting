![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

A modern, full-featured e-commerce platform showcasing 150+ women's clothing products with comprehensive customization options, dynamic cart management, and multi-currency support.

## Overview

Shopping Time is a production-ready e-commerce application built with React, demonstrating best practices in modern web development. The platform provides an intuitive shopping experience with advanced product filtering, real-time cart management, and a streamlined checkout process.

## Key Features

### Cart Management
- **Add/Remove Products**: Seamlessly add items to your cart or remove them with a single click
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Attributes**: Detailed display of selected attributes (size, color) for each cart item

### Product Discovery
- **Category Filtering**: Browse products by category for efficient navigation
- **Multi-page Shopping**: Add products to cart from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding items to cart, ensuring order accuracy

### Currency Support
- **Multi-currency**: Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- **Dynamic Conversion**: Real-time currency conversion for international customers

### Checkout Process
- **Multi-step Checkout**: Guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation to ensure data accuracy and prevent errors

## Technical Highlights

- **React Architecture**: Modern React with Hooks for optimal performance
- **State Management**: Custom cart logic with attribute selection and validation
- **Form Handling**: Client-side validation for enhanced user experience
- **Backend Integration**: Firebase/Firestore for data persistence

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page auto-reloads on changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified and includes hashed filenames for optimal caching. See [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Note: This is a one-way operation. Once you eject, you cannot revert.**

Ejects the Create React App configuration, giving you full control over webpack, Babel, ESLint, and other dependencies. Only use this if you need custom configuration beyond what Create React App provides.

## Tech Stack

### Core Dependencies
- **React** - Frontend framework
- **React Router** - Client-side routing
- **React Simple Image Slider** - Product image galleries
- **uuid** - Unique identifier generation
- **Firebase/Firestore** - Cloud database for data persistence

## Project Structure

```
src/
├── components/          # Reusable UI components
├── routes/             # Page components and routing
├── core-ui/            # Global styles and CSS
├── data/               # Static data and product information
├── database/           # Firebase configuration
├── helpers/            # Utility functions
└── assets/             # Images and static assets
```

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.
