![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience for women's fashion with 150+ products, dynamic cart management, and multi-currency support.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Overview

Shopping Time is a production-ready e-commerce application that demonstrates modern React development practices. The platform features an extensive catalog of women's clothing with customizable product attributes, real-time cart management, and a streamlined checkout process.

**Live Demo:** [https://shopping-time.vercel.app/](https://shopping-time.vercel.app/)

## Key Features

### 🛒 Cart Management

- **Add/Remove Products**: Intuitive controls for managing cart items
- **Quantity Adjustment**: Real-time quantity updates with instant price recalculation
- **Cart Overlay**: Quick-access cart summary without page navigation
- **Product Attributes**: Detailed display of selected sizes, colors, and other product specifications
- **Persistent Storage**: Cart data saved using Firebase for cross-session continuity

### 🔍 Product Discovery

- **Category Filtering**: Browse products by organized categories
- **Flexible Shopping Flow**: Add items from both category pages and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy

### 💱 Multi-Currency Support

- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Automatic price updates based on selected currency
- **Localized Shopping Experience**: Shop in your preferred currency

### ✅ Secure Checkout

- **Multi-Step Process**: Guided checkout flow for improved user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Error Prevention**: Client-side validation to minimize order errors

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Routing**: React Router DOM
- **Backend/Database**: Firebase Firestore
- **UI Components**: React Simple Image Slider
- **Utilities**: UUID for unique identifiers
- **Deployment**: Vercel

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

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

3. **Configure Firebase** (if applicable)
   - Create a Firebase project
   - Add your Firebase configuration to the project
   - Enable Firestore database

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   - Navigate to [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`

Runs the application in development mode at [http://localhost:3000](http://localhost:3000).

- Hot-reloading enabled for instant updates
- Console displays lint errors and warnings

### `npm test`

Launches the test runner in interactive watch mode.

See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Creates an optimized production build in the `build` folder.

- Minified and optimized for best performance
- Filenames include content hashes for cache busting
- Ready for deployment

See [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**⚠️ Warning: This is a one-way operation!**

Ejects from Create React App, giving you full control over configuration files. Only use if you need custom webpack, Babel, or ESLint configurations.

## Project Goals

This project was developed to demonstrate proficiency in:

- ✅ React Class Components and modern Hooks patterns
- ✅ Complex state management for cart and product attributes
- ✅ Form validation and error handling
- ✅ Firebase integration for data persistence
- ✅ Responsive design and user experience optimization
- ✅ Production-ready code architecture

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and data persistence |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with ❤️ using React** | [Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues) | [Request Feature](https://github.com/HelloQATeam123/PullRequestTesting/issues)
