![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

Shopping Time is a full-featured e-commerce platform showcasing over 150 women's clothing products with customizable attributes including size and color variations. The application provides a comprehensive shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them as needed
- **Quantity Adjustment**: Modify product quantities directly within the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Details**: View selected attributes (size, color) for each cart item before checkout

### Product Discovery
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping**: Add products to cart from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Prices automatically update based on selected currency

### Checkout Process
- **Multi-Step Workflow**: Intuitive, guided checkout experience
- **Form Validation**: Built-in validation ensures accurate order information and reduces errors

## Technical Implementation

### Key Achievements
- Implemented React Class components with subsequent refactoring to React Hooks
- Developed custom logic for attribute selection and cart management
- Integrated comprehensive form validation
- Utilized Firebase/Firestore for persistent data storage

### Technology Stack
- **Framework**: React (bootstrapped with Create React App)
- **Routing**: React Router
- **UI Components**: React Simple Image Slider
- **Utilities**: uuid
- **Backend**: Firebase Firestore

## Getting Started

### Prerequisites
- Node.js and npm installed on your system

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   ```

2. Navigate to the project directory
   ```bash
   cd PullRequestTesting
   ```

3. Install dependencies
   ```bash
   npm install
   ```

4. Start the development server
   ```bash
   npm start
   ```

## Available Scripts

### `npm start`
Runs the application in development mode at [http://localhost:3000](http://localhost:3000). The page automatically reloads on code changes, and lint errors appear in the console.

### `npm test`
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified and includes hashed filenames for optimal performance. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning**: This is a one-way operation that cannot be reversed.

Ejects the application from Create React App, providing full control over configuration files and dependencies (webpack, Babel, ESLint, etc.). Only use this if you need complete customization beyond what Create React App provides.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.
