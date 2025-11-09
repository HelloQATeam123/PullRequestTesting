# 🛍️ Shopping Time - E-Commerce Platform

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive e-commerce platform built with React, featuring a comprehensive shopping cart system, multi-currency support, and Firebase integration. This application provides a seamless shopping experience with over 150 women's clothing products.

## ✨ Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Intuitive product management with one-click add/remove functionality
- **Quantity Control**: Flexible quantity adjustment for all cart items
- **Cart Overlay**: Real-time cart preview without page navigation
- **Product Attributes**: Detailed product information including size, color, and specifications
- **Persistent Cart**: Cart state maintained across browser sessions

### 🎯 Product Catalog
- **Category Filtering**: Advanced filtering system for easy product discovery
- **Product Pages**: Detailed individual product views with image galleries
- **Attribute Selection**: Required attribute selection (size, color) before cart addition
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Search Functionality**: Quick product search and filtering capabilities

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, USD, and more
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Pricing**: Currency-appropriate formatting and display

### 🔒 Secure Checkout Process
- **Multi-Step Checkout**: Guided checkout process with progress indicators
- **Form Validation**: Comprehensive client-side validation for all user inputs
- **Order Management**: Complete order processing and confirmation system
- **Firebase Integration**: Secure data storage and retrieval

## 🚀 Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn package manager
- Firebase account (for backend services)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Add your Firebase configuration to the project
   - Enable Firestore database

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## 📜 Available Scripts

### `npm start`
Runs the app in development mode with hot reloading enabled.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Builds the app for production to the `build` folder with optimized performance.

### `npm run eject`
**⚠️ Note: This is a one-way operation!**
Ejects from Create React App for full configuration control.

## 🛠️ Built With

### Core Technologies
- **React** - Frontend framework with hooks and context API
- **React Router** - Client-side routing and navigation
- **Firebase/Firestore** - Backend database and authentication
- **Create React App** - Build toolchain and development environment

### Key Dependencies
- **react-router-dom** - Declarative routing for React
- **react-simple-image-slider** - Image carousel component
- **uuid** - Unique identifier generation
- **Firebase SDK** - Backend services integration

### Development Tools
- **ESLint** - Code linting and formatting
- **Webpack** - Module bundling (via CRA)
- **Babel** - JavaScript transpilation (via CRA)

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Page-level components
├── context/            # React context providers
├── hooks/              # Custom React hooks
├── utils/              # Utility functions
├── styles/             # CSS and styling files
├── assets/             # Images and static assets
└── firebase/           # Firebase configuration
```

## 🤝 Contributing

We welcome contributions to improve Shopping Time! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow existing code style and conventions
- Add tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting PR

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact & Support

- **Project Repository**: [GitHub](https://github.com/HelloQATeam123/PullRequestTesting)
- **Live Demo**: [Shopping Time](https://shopping-time.vercel.app/)
- **Issues**: [Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)

---

⭐ **Star this repository if you found it helpful!**
