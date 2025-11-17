![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

**Live Demo:** [shopping-time.vercel.app](https://shopping-time.vercel.app/)

Shopping Time is a full-featured e-commerce web application showcasing over 150 women's clothing products with customizable attributes including size and color variations. The platform provides a complete shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Table of Contents
- [Features](#features)
- [Technical Highlights](#technical-highlights)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technology Stack](#technology-stack)
- [License](#license)

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them as needed
- **Quantity Adjustment**: Modify product quantities directly within the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item

### Product Discovery
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product detail pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Prices update dynamically based on selected currency

### Checkout Process
- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation ensures accurate order information and reduces errors

## Technical Highlights

This project demonstrates proficiency in:
- React class components with subsequent refactoring to modern React Hooks
- Complex state management for cart and product attributes
- Form validation and error handling
- Firebase/Firestore integration for external data persistence
- Responsive design and user experience optimization

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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads when you make changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [Create React App testing documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include content hashes for efficient caching. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning: This is a one-way operation that cannot be reversed.**

Ejects the Create React App configuration, giving you full control over webpack, Babel, ESLint, and other build tools. Only use this if you need custom configuration beyond what Create React App provides.

## Technology Stack

### Core Technologies
- **React** - UI library with hooks-based architecture
- **React Router** - Client-side routing
- **Firebase/Firestore** - Backend database and data persistence

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Declarative routing for React
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel component
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - Cloud-hosted NoSQL database

### Development Tools
- Create React App - Project bootstrapping and build configuration

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with Create React App** | [Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
