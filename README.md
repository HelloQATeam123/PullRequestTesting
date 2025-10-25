![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

**Live Demo:** [shopping-time.vercel.app](https://shopping-time.vercel.app/)

Shopping Time is a modern e-commerce web application featuring over 150 women's clothing products with customizable attributes including size and color variations. The platform provides a comprehensive shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Features

### Cart Management
- **Add/Remove Products:** Seamlessly add products to your cart or remove them as needed
- **Quantity Adjustment:** Modify product quantities directly within the cart
- **Cart Overlay:** Quick-access cart summary without leaving your current page
- **Product Details:** View selected attributes (size, color) for each cart item

### Product Discovery
- **Category Filtering:** Browse products by category for efficient navigation
- **Flexible Shopping:** Add products from both category pages and individual product pages
- **Attribute Validation:** Required attributes must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- Support for multiple currencies including EUR, GBP, AUD, JPY, and more
- Seamless currency switching for international customers

### Checkout Process
- **Multi-Step Workflow:** Intuitive, guided checkout experience
- **Form Validation:** Built-in validation to ensure accurate order information

## Technical Highlights

- Built with React (Class components refactored to Hooks)
- Custom cart logic with attribute selection
- Form validation implementation
- Firebase/Firestore integration for data persistence

## Getting Started

### Prerequisites
- Node.js and npm installed on your system

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

The application will open at [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`
Runs the application in development mode with hot reloading enabled.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Creates an optimized production build in the `build` folder.

### `npm run eject`
**Warning:** This is a one-way operation. Ejects from Create React App, giving you full control over configuration files.

## Technology Stack

- **Framework:** React (Create React App)
- **Routing:** [React Router](https://www.npmjs.com/package/react-router-dom)
- **Image Slider:** [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)
- **Utilities:** [uuid](https://www.npmjs.com/package/uuid)
- **Database:** [Firebase Firestore](https://firebase.google.com/docs/firestore)

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.
