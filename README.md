[![Live Demo](https://img.shields.io/badge/demo-live-green)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

![Shopping Time](https://raw.githubusercontent.com/catherineisonline/shopping-time/main/src/assets/images/project-preview.webp)

# [Shopping Time](https://shopping-time.vercel.app/)
Shopping Time is an e-commerce website that has at least 150 women's clothing products with different sizes and color choices. You can choose various attributes like size and color. There is a cart where you can see added items and edit, add, or remove them. You can also set a currency of your choice.

## Features

### Core Functionality
Below is a comprehensive overview of the functionalities that the website offers:

### Shopping Experience
- Cart Management
  - Add/remove products with ease
  - Adjust quantities flexibly
  - Convenient cart overlay with product summaries
  - Detailed product attributes display
  
- Product Navigation
  - Intuitive category filtering
  - Seamless category and product page shopping
  - Smart attribute selection system
  
- Multi-Currency Support
  - Support for EUR, GBP, AUD, JPY and more
  - Real-time currency conversion
  
### Checkout Process
- Secure checkout flow with multiple steps
- Comprehensive form validations
- Order confirmation system

## Technical Stack
- Frontend: React.js
- State Management: React Hooks
- Routing: React Router
- Database: Firebase/Firestore

## Project Achievements
- Practice React Class components and then refactor to hooks
- Build logic to choose attributes and add items to the cart
- Add form validations
- Use Firebase to save data externally


## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation
1. Clone the repository
   ```bash
   git clone https://github.com/catherineisonline/shopping-time.git
   ```
2. Install dependencies
   ```bash
   npm install
   ```
3. Start development server
   ```bash
   npm start
   ```

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

## Development

### Code Structure
```
src/
├── components/    # Reusable UI components
├── pages/        # Page components
├── services/     # API and business logic
├── utils/        # Helper functions
└── assets/       # Static resources
```

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Routing
- [React Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image slider
- [uuid](https://www.npmjs.com/package/uuid) - Unique ID generation
- [Firestore](https://firebase.google.com/docs/firestore) - Database

## Contributing
While this project primarily serves as a personal portfolio piece, suggestions and ideas are welcome through [discussions](https://github.com/catherineisonline/shopping-time/discussions). Feel free to fork the project for your own use.

## License
Released under the [MIT License](LICENSE). See LICENSE file for details.
