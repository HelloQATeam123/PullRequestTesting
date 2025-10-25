![Shopping Time](https://raw.githubusercontent.com/catherineisonline/shopping-time/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://shopping-time.vercel.app/)
A modern e-commerce platform featuring over 150 women's clothing products with customizable attributes including size and color options. The application provides a comprehensive shopping cart system with full CRUD operations and multi-currency support.

## Features

### Cart Management
- **Add/Remove Products**: Seamlessly add or remove items from your shopping cart
- **Quantity Adjustment**: Modify product quantities directly within the cart
- **Cart Overlay**: Real-time cart summary accessible without navigation interruption
- **Product Attributes**: Detailed product information display including size, color, and other selected attributes

### Shopping Experience
- **Category Filtering**: Advanced filtering system for efficient product discovery
- **Multi-Page Cart Integration**: Add products to cart from both category and individual product pages
- **Required Attribute Selection**: Validation system ensuring all necessary product attributes are selected before adding to cart

### Currency Support
- **Multi-Currency**: Support for multiple international currencies including EUR, GBP, AUD, JPY, and more

### Checkout Process
- **Multi-Step Workflow**: Guided checkout process with intuitive user experience design
- **Form Validation**: Comprehensive validation system ensuring data accuracy and completeness

## Technical Objectives
- Implement React Class components and refactor to functional components with hooks
- Develop attribute selection logic and cart management functionality
- Integrate comprehensive form validation systems
- Utilize Firebase for external data persistence


## Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

To get started you need to:

1. Clone the project
2. ```npm install```
3. Install listed dependencies
4. Use available scripts, like ```npm start```

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


## License  <a id="license"></a>
This project is released under the MIT [LICENSE](https://github.com/catherineisonline/shopping-time/blob/main/LICENSE). You can find the specific terms and conditions outlined in the LICENSE file. This means you're free to utilize, modify, and distribute the project according to the terms of the MIT License.
