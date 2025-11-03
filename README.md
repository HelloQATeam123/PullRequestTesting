# Shopping Time

![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

**Live Demo:** [View Application](https://pullrequesttesting.vercel.app/)

## Overview

Shopping Time is a modern e-commerce platform featuring over 150 women's clothing products with comprehensive customization options. The application provides a seamless shopping experience with dynamic product attributes, real-time cart management, and multi-currency support.

## Key Features

### Cart Management
- **Add/Remove Products**: Intuitive interface for managing cart items
- **Quantity Adjustment**: Real-time quantity updates for all cart items
- **Cart Overlay**: Quick-access summary view without leaving the current page
- **Detailed Product Information**: Complete attribute display including size, color, and specifications

### Product Discovery
- **Category Filtering**: Efficient navigation through organized product categories
- **Flexible Shopping Flow**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before cart addition to ensure order accuracy

### Multi-Currency Support
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Real-time Conversion**: Seamless price updates based on selected currency

### Checkout Process
- **Multi-Step Workflow**: Guided checkout experience for improved user flow
- **Form Validation**: Comprehensive input validation to ensure data accuracy and reduce errors

## Technical Implementation

### Architecture
- Built with React (Class components refactored to Hooks)
- Firebase/Firestore integration for data persistence
- Client-side routing with React Router
- Component-based architecture for maintainability

### Development Highlights
- Custom cart logic with attribute selection
- Form validation implementation
- External data management via Firebase
- Responsive design patterns

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
- **[React](https://reactjs.org/)**: UI framework
- **[React Router](https://www.npmjs.com/package/react-router-dom)**: Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)**: Image carousel functionality
- **[UUID](https://www.npmjs.com/package/uuid)**: Unique identifier generation
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)**: Cloud database and data persistence

### Development Tools
- Create React App
- ESLint
- Webpack (via CRA)

## Project Structure

```
PullRequestTesting/
├── src/
│   ├── components/     # React components
│   │   ├── attributes/
│   │   ├── cart-overlay/
│   │   ├── currency-overlay/
│   │   └── header/
│   ├── routes/         # Page components
│   │   ├── all-products/
│   │   ├── cart/
│   │   ├── checkout/
│   │   ├── landing/
│   │   ├── not-found/
│   │   ├── order/
│   │   └── single-product/
│   ├── core-ui/        # Styling
│   ├── assets/         # Images and static files
│   ├── data/           # Product data
│   ├── database/       # Firebase configuration
│   └── helpers/        # Utility functions
├── public/             # Public assets
└── package.json        # Project dependencies
```

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for complete terms and conditions.

---

**Note**: This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
