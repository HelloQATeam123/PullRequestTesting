![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

Shopping Time is a full-featured e-commerce platform specializing in women's fashion, offering over 150 products with customizable attributes including size and color variations. The application provides a comprehensive shopping experience with cart management, multi-currency support, and a streamlined checkout process.

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add products to your cart or remove them as needed
- **Quantity Adjustment**: Modify product quantities directly within the cart
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Product Details**: View selected attributes (size, color, etc.) for each cart item

### Product Discovery
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attributes must be selected before adding items to cart, ensuring order accuracy

### Multi-Currency Support
- **Global Currency Options**: Shop in your preferred currency including EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Prices automatically update based on selected currency

### Checkout Process
- **Multi-Step Workflow**: Intuitive, guided checkout experience
- **Form Validation**: Built-in validation ensures accurate order information
- **Secure Processing**: User-friendly interface with security best practices

## Technical Highlights

- Implemented using React class components, later refactored to modern hooks
- Custom cart logic with attribute selection and validation
- Form validation throughout the checkout process
- Firebase integration for persistent data storage

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

The application will open at [http://localhost:3000](http://localhost:3000)

## Available Scripts

### `npm start`
Runs the application in development mode with hot reloading enabled.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified and includes hashed filenames for cache optimization.

### `npm run eject`
**Warning**: This is a one-way operation. Ejects from Create React App, giving you full control over configuration files.

## Technology Stack

- **Framework**: React (Create React App)
- **Routing**: React Router
- **UI Components**: React Simple Image Slider
- **Utilities**: uuid
- **Backend**: Firebase Firestore

## Dependencies

- [React Router](https://www.npmjs.com/package/react-router-dom) - Client-side routing
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel functionality
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firebase Firestore](https://firebase.google.com/docs/firestore) - Cloud database

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
