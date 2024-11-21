# Shopping Time E-commerce Platform

[![Project Preview](https://raw.githubusercontent.com/catherineisonline/shopping-time/main/src/assets/images/project-preview.webp)](https://shopping-time.vercel.app/)

[Live Demo](https://shopping-time.vercel.app/)

## Overview
Shopping Time is a comprehensive e-commerce platform specializing in women's fashion. Featuring over 150 carefully curated clothing products, the platform offers a seamless shopping experience with advanced product customization, multi-currency support, and intuitive cart management.

## Features

### Product Management
- Extensive catalog with 150+ women's fashion items
- Advanced product customization (sizes, colors)
- Category-based organization and filtering
- Attribute validation for accurate product selection

### Shopping Experience
- Intuitive cart management
  - Add/remove items
  - Quantity adjustments
  - Real-time cart overlay
  - Detailed product attributes display
- Multi-currency support (EUR, GBP, AUD, JPY)
- Secure checkout process
  - Multi-step verification
  - Form validation
  - Order confirmation

## Technical Implementation
Built with modern web technologies:
- React.js for dynamic UI
- Firebase/Firestore for data management
- Responsive design principles
- Component-based architecture

## Development Setup

### Prerequisites
- Node.js (v14 or higher)
- npm/yarn package manager
- Firebase account (for backend services)

### Installation
```bash
# Clone repository
git clone https://github.com/catherineisonline/shopping-time.git

# Install dependencies
cd shopping-time
npm install

# Configure environment
cp .env.example .env
# Add your Firebase credentials

# Start development server
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

## Dependencies
- React Router DOM - Navigation
- React Simple Image Slider - Product galleries
- UUID - Unique identifiers
- Firebase/Firestore - Backend services
- React Testing Library - Unit testing

## Contributing
This project serves as a portfolio piece demonstrating full-stack development capabilities. While direct contributions are not accepted, you're welcome to:
- Submit suggestions via [GitHub Discussions](https://github.com/catherineisonline/shopping-time/discussions)
- Fork the project for personal use
- Report bugs through issues

## License
Copyright (c) 2023 Shopping Time. Released under the [MIT License](https://github.com/catherineisonline/shopping-time/blob/main/LICENSE).
