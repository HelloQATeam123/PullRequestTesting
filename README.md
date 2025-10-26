# Shopping Time - E-Commerce Platform

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/HelloQATeam123/PullRequestTesting)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)

A modern, full-featured e-commerce platform built with React and Firebase, offering a seamless shopping experience with advanced cart management, multi-currency support, and secure checkout functionality.

## 📋 Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

### 🛒 Cart Management
- **Add/Remove Products**: Seamlessly add and remove items from your shopping cart
- **Quantity Control**: Adjust product quantities with intuitive controls
- **Cart Overlay**: Quick cart preview without leaving the current page
- **Product Attributes**: Detailed product information including size, color, and specifications
- **Persistent Cart**: Cart state maintained across browser sessions

### 🛍️ Shopping Experience
- **Category Filtering**: Browse products by categories for easy navigation
- **Product Search**: Advanced search functionality to find specific items
- **Attribute Selection**: Required attribute selection (size, color) before adding to cart
- **Product Gallery**: High-quality product images with zoom functionality
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, USD, and more
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Pricing**: Currency-appropriate formatting and symbols

### 🔒 Secure Checkout
- **Multi-Step Process**: Guided checkout flow for better user experience
- **Form Validation**: Comprehensive validation for all user inputs
- **Order Management**: Complete order tracking and management system
- **Firebase Integration**: Secure data storage and user authentication

## 🚀 Technology Stack

- **Frontend**: React 18.x with Hooks and Context API
- **Backend**: Firebase (Firestore Database, Authentication)
- **Routing**: React Router DOM
- **Styling**: CSS3 with responsive design
- **State Management**: React Context API
- **Build Tool**: Create React App
- **Deployment**: Vercel

### Dependencies

- `react` - UI library
- `react-router-dom` - Client-side routing
- `react-simple-image-slider` - Image carousel component
- `firebase` - Backend services
- `uuid` - Unique identifier generation

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Firebase configuration**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Firestore Database and Authentication
   - Copy your Firebase config and update the configuration file

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🎯 Usage

### For Users
1. Browse products by category or use the search functionality
2. Select product attributes (size, color) before adding to cart
3. Manage your cart using the cart overlay or dedicated cart page
4. Choose your preferred currency from the currency selector
5. Proceed through the multi-step checkout process
6. Complete your purchase with form validation ensuring accuracy

### For Developers
1. Follow the installation steps above
2. Explore the component structure in `/src/components`
3. Review the routing configuration in `/src/App.js`
4. Understand the state management through Context providers
5. Customize styling in the respective CSS files

## 📁 Project Structure

```
src/
├── components/
│   ├── cart/
│   │   ├── AddToCartButton/
│   │   ├── cart-overlay/
│   │   └── CartItem/
│   ├── checkout/
│   ├── product/
│   └── navigation/
├── pages/
│   ├── Category/
│   ├── Product/
│   └── Checkout/
├── context/
│   ├── CartContext.js
│   └── CurrencyContext.js
├── services/
│   └── firebase.js
├── utils/
└── assets/
    ├── images/
    └── styles/
```

## 📜 Available Scripts

### `npm start`
Runs the app in development mode at [http://localhost:3000](http://localhost:3000)

### `npm test`
Launches the test runner in interactive watch mode

### `npm run build`
Builds the app for production to the `build` folder with optimized performance

### `npm run eject`
**Note**: This is a one-way operation. Ejects from Create React App for full configuration control

## 🤝 Contributing

We welcome contributions to improve Shopping Time! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit your changes**
   ```bash
   git commit -m "Add your feature description"
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow React best practices and hooks patterns
- Maintain consistent code formatting
- Add appropriate comments for complex logic
- Test your changes thoroughly
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with ❤️ using React and Firebase**

For questions or support, please open an issue in the GitHub repository.
