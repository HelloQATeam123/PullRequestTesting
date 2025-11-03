# PullRequestTesting

![PullRequestTesting](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

## Overview

PullRequestTesting is a modern e-commerce platform featuring over 150 women's clothing products with comprehensive customization options. The application provides a seamless shopping experience with dynamic product attributes, real-time cart management, and multi-currency support.

## Key Features

### Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items with dedicated AddToCartButton component
- **Quantity Adjustment**: Real-time quantity updates using ChangeCartItemQuantity component
- **Cart Overlay**: Quick-access summary view without leaving the current page
- **Success Notifications**: User feedback through SuccessMessage component

### Product Discovery
- **Category Filtering**: Efficient navigation through organized product categories
- **Flexible Shopping Flow**: Add products from both category listings and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy

### Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies with dedicated currency overlay
- **Real-time Conversion**: Seamless price updates based on selected currency

### Checkout Process
- **Multi-Step Workflow**: Guided checkout experience for improved user flow
- **Order Management**: Complete order processing and confirmation system
- **Form Validation**: Comprehensive input validation to ensure data accuracy

## Technical Implementation

### Architecture
- Built with React using modern component architecture
- Firebase/Firestore integration for data persistence
- Client-side routing with React Router
- Modular component structure with dedicated UI components

### Component Structure
- **Core Components**: AddToCartButton, ChangeCartItemQuantity, SuccessMessage
- **Overlay Systems**: Cart overlay and currency selection overlays
- **Route-Based Pages**: Landing, product catalog, single product, cart, checkout, and order pages
- **Responsive Design**: Mobile-first approach with dedicated responsive CSS

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
Launches the development server at [http://localhost:3000](http://localhost:3000) with hot-reload enabled.

### `npm test`
Runs the test suite in interactive watch mode.

### `npm run build`
Creates an optimized production build in the `build` folder with minification and hashing.

### `npm run eject`
**Warning**: This is a one-way operation. Ejects from Create React App to expose configuration files for advanced customization.

## Technology Stack

### Core Dependencies
- **React**: UI framework with modern hooks-based components
- **React Router**: Client-side routing for SPA navigation
- **Firebase Firestore**: Cloud database and data persistence
- **Create React App**: Development toolchain and build system

### Project Structure
```
src/
├── components/          # Reusable UI components
├── routes/             # Page-level route components
├── core-ui/            # Global styles and responsive design
├── data/               # Static data and product information
├── database/           # Firebase configuration
└── helpers/            # Utility functions and helpers
```

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for complete terms and conditions.

---

**Note**: This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). For deployment instructions and additional configuration options, refer to the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
