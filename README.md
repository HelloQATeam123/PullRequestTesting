![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

**Live Demo:** [View Application](https://pullrequesttesting.vercel.app/)

Shopping Time is a modern e-commerce web application featuring over 150 women's clothing products with customizable attributes including size and color variations. The platform provides a comprehensive shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Goals](#project-goals)
- [License](#license)

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them as needed
- **Quantity Adjustment**: Modify product quantities directly from the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item

### Product Discovery
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Currency Conversion**: Prices update dynamically based on selected currency

### Checkout Process
- **Multi-Step Checkout**: Intuitive, guided checkout experience
- **Form Validation**: Comprehensive validation to ensure accurate order information
- **Secure Processing**: User-friendly interface designed with security best practices

## Technology Stack

- **Frontend Framework**: React (Class components refactored to Hooks)
- **Routing**: React Router
- **Backend/Database**: Firebase Firestore
- **Additional Libraries**:
  - [React Router](https://www.npmjs.com/package/react-router-dom) - Navigation and routing
  - [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Product image galleries
  - [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation

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
Launches the test runner in interactive watch mode. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified, and filenames include hashes for cache busting. See the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
**Warning**: This is a one-way operation. Ejecting gives you full control over configuration files and dependencies but removes the abstraction layer provided by Create React App.

## Project Goals

This project was developed to achieve the following objectives:

- **React Proficiency**: Practice building with React Class components and refactoring to modern Hooks
- **Complex State Management**: Implement cart logic with attribute selection and validation
- **Form Handling**: Develop robust form validation for checkout process
- **External Data Integration**: Utilize Firebase Firestore for persistent data storage
- **Modern E-commerce Patterns**: Apply industry-standard patterns for online shopping experiences

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with Create React App** | [Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
