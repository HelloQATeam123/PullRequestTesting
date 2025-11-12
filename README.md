![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

Shopping Time is a modern e-commerce web application featuring over 150 women's clothing products with customizable attributes including size and color variations. The platform provides a comprehensive shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Dependencies](#dependencies)
- [License](#license)

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them as needed
- **Quantity Adjustment**: Modify product quantities directly from the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item

### Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for easier navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Prices update dynamically based on selected currency

### Secure Checkout Process
- **Multi-Step Checkout**: Intuitive, guided checkout flow for a smooth purchase experience
- **Form Validation**: Comprehensive validation ensures accurate order information and reduces errors

## Technology Stack

- **Frontend Framework**: React (Class Components refactored to Hooks)
- **Backend/Database**: Firebase Firestore
- **Routing**: React Router
- **State Management**: React Hooks
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
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads when you make changes, and lint errors are displayed in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [Create React App testing documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include hashes for cache busting. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning**: This is a one-way operation that cannot be reversed.

Ejects the Create React App configuration, giving you full control over webpack, Babel, ESLint, and other build tools. Only use this if you need custom configuration beyond what Create React App provides.

## Dependencies

| Package | Purpose |
|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries |
| [uuid](https://www.npmjs.com/package/uuid) | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database and data persistence |

## Development Highlights

- Implemented React Class Components and successfully refactored to modern Hooks
- Developed custom logic for product attribute selection and cart management
- Integrated comprehensive form validation throughout the checkout process
- Utilized Firebase Firestore for external data persistence and real-time updates

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with ❤️ using React and Firebase**
