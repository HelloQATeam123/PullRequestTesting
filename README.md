![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE)

A modern, full-featured e-commerce platform built with React, offering a comprehensive shopping experience with over 150 women's clothing products. The application provides advanced product customization, cart management, and multi-currency support.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [Dependencies](#dependencies)
- [License](#license)

## Features

### Cart Management

- **Add/Remove Products**: Seamlessly add products to your cart or remove them with intuitive controls
- **Quantity Adjustment**: Modify product quantities directly from the cart interface
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Attributes**: View detailed product information including selected size, color, and other attributes

### Product Discovery

- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products to cart from both category pages and individual product pages
- **Attribute Selection**: Required attribute selection (size, color) before adding to cart to ensure order accuracy

### Multi-Currency Support

Support for multiple international currencies including:
- EUR (Euro)
- GBP (British Pound)
- AUD (Australian Dollar)
- JPY (Japanese Yen)
- And more

### Checkout Process

- **Multi-Step Checkout**: Guided checkout process for a smooth transaction experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Secure Processing**: User-friendly and secure checkout flow

## Technology Stack

- **Frontend**: React (Class Components refactored to Hooks)
- **Routing**: React Router
- **Backend/Database**: Firebase Firestore
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

Runs the application in development mode at [http://localhost:3000](http://localhost:3000).

The page will automatically reload when you make changes. Lint errors will be displayed in the console.

### `npm test`

Launches the test runner in interactive watch mode.

See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the application for production to the `build` folder.

The build is optimized for best performance:
- React is bundled in production mode
- Build is minified
- Filenames include hashes for cache optimization

See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: This is a one-way operation. Once you eject, you cannot go back.**

This command removes the single build dependency and copies all configuration files (webpack, Babel, ESLint, etc.) into your project for full control.

The curated feature set is suitable for most small and medium deployments. Only use `eject` if you need complete customization control.

## Project Goals

This project was developed to achieve the following objectives:

- ✅ Practice React Class Components and refactor to modern Hooks
- ✅ Implement complex product attribute selection logic
- ✅ Build a fully functional shopping cart system
- ✅ Integrate comprehensive form validations
- ✅ Utilize Firebase for external data persistence

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [uuid](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and data persistence |

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with ❤️ using React and Firebase**
