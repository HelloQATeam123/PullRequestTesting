# React E-Commerce Shopping Cart Application

A comprehensive React-based e-commerce shopping cart application featuring product browsing, cart management, and checkout functionality. This application provides a complete shopping experience with product catalog, cart operations, quantity management, and secure checkout process.

## Features

- **Product Catalog**: Browse through a comprehensive collection of products with detailed information
- **Shopping Cart**: Add, remove, and manage items in your shopping cart
- **Quantity Management**: Easily adjust product quantities in your cart
- **Checkout Process**: Multi-step checkout with form validation
- **Currency Selection**: Support for multiple currencies (EUR, GBP, AUD, JPY, and more)
- **Firebase Integration**: External data storage and management
- **Responsive Design**: Optimized for various screen sizes and devices

## Functionality Overview
Below is a comprehensive overview of the functionalities that the website offers:

### Managing Your Cart
- Add and Remove Products: The website allows you to easily add products to your shopping cart with just a few clicks. You can also remove items from your cart when you change your mind or no longer wish to purchase them.

- Adjust Quantity: In addition to adding and removing items, you have the flexibility to change the quantity of products in your cart. Whether you want one more of your favorite item or need to reduce the quantity, it's a breeze.

- Cart Overlay: There is a convenient cart overlay that displays a summary of the items currently in your cart. This allows you to keep track of your selected items without navigating away from your shopping experience.

- Product Attributes: When reviewing your cart or cart overlay, you'll find detailed information about each product, including selected size and other relevant attributes. This ensures you have a clear understanding of your choices before proceeding to checkout.

### Streamlined Shopping
- Category Filtering: The website makes it easy to find products within your preferred categories. You can filter products by various categories, making it simple to locate exactly what you're looking for.

- Category and Product Page Shopping: Whether you prefer browsing by category or exploring individual product pages, you can add products to your cart from both locations. The website offers a seamless shopping experience to cater to your preferences.

- Attribute Selection: To maintain accuracy and prevent errors, you won't be able to add products to your cart until you've selected necessary attributes like size or color. This ensures that the items you receive are exactly what you expect.

### Flexible Currency Options
- Currency Selection: The customers come from diverse locations around the world. That's why the website offers the flexibility to change the store currency to various options such as EUR, GBP, AUD, JPY, and more. Shop in the currency that suits you best.

### Secure and User-Friendly Checkout
- Multi-Step Checkout: The website features a multi-step checkout process to guide you through the purchase smoothly and securely. Each step is designed with user experience in mind.

- Form Validations: To prevent errors and ensure accurate order information, the checkout page includes form validations. This guarantees that the necessary details are correctly entered, helping to streamline shopping experience.

## Installation

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

## Project Structure

- `src/components/` - React components for the application
- `src/routes/` - Page routing and navigation
- `src/data/` - Product data and configurations
- `src/database/` - Firebase configuration and database operations

## Usage

1. **Browse Products**: Navigate through the product catalog to explore available items
2. **Add to Cart**: Select product attributes (size, color) and add items to your shopping cart
3. **Manage Cart**: View cart contents, adjust quantities, or remove items as needed
4. **Checkout**: Complete your purchase through the multi-step checkout process with form validation
5. **Currency Selection**: Choose your preferred currency for pricing display

## Technologies Used

- **React** - Frontend framework for building user interfaces
- **Firebase** - Backend services for data storage and management
- **CSS** - Styling and responsive design
- **JavaScript** - Core programming language

## Goals I achieved
- Practice React Class components and then refactor to hooks
- Build logic to choose attributes and add items to the cart
- Add form validations
- Use Firebase to save data externally

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts <a id="scripts"></a>

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Dependencies | APIs | Services 

- [React Router](https://www.npmjs.com/package/react-router-dom)
- [React Slider](https://www.npmjs.com/package/react-simple-image-slider)
- [uuid](https://www.npmjs.com/package/uuid)
- [Firestore](https://firebase.google.com/docs/firestore)

## Contributing

We welcome contributions to improve this React e-commerce application! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch for your changes
3. Make your modifications and test thoroughly
4. Submit a pull request with a clear description of your changes
5. Ensure your code follows the existing style and conventions

Please refer to the [LICENSE](LICENSE) file for terms and conditions.

## License  <a id="license"></a>
This project is released under the MIT [LICENSE](LICENSE). You can find the specific terms and conditions outlined in the LICENSE file. This means you're free to utilize, modify, and distribute the project according to the terms of the MIT License.
