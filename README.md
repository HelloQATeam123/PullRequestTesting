# PullRequestTesting

[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## Overview

PullRequestTesting is a modern, responsive e-commerce platform specializing in women's fashion. Built with React and Firebase, it features a comprehensive product catalog with dynamic attribute selection, multi-currency support, and an intuitive shopping cart experience.

## ✨ Key Features

### 🛒 Cart Management
- **Add/Remove Products**: Seamless product management with intuitive controls
- **Quantity Adjustment**: Real-time quantity updates with instant price calculations
- **Cart Overlay**: Quick cart preview without leaving the current page
- **Product Details**: Complete attribute information (size, color, etc.) displayed in cart

### 🛍️ Shopping Experience
- **Category Filtering**: Advanced filtering system for easy product discovery
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies with real-time conversion
- **Dynamic Price Updates**: Instant price calculations based on selected currency
- **Localized Experience**: Currency formatting appropriate to user's selection

### 🔒 Secure Checkout
- **Multi-step Process**: Guided checkout flow for enhanced user experience
- **Form Validation**: Comprehensive validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🎯 Technical Achievements

- **React Architecture**: Modern React hooks implementation with component-based design
- **State Management**: Comprehensive cart logic with attribute selection and validation
- **Form Handling**: Robust form validation throughout the application
- **External Data Persistence**: Firebase integration for reliable data storage
- **Responsive Design**: Mobile-first, cross-platform compatible interface

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

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

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

> This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode on [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | **⚠️ One-way operation** - Ejects from Create React App |

### Development
```bash
npm start
```
Starts the development server with hot reloading and lint error reporting.

### Testing
```bash
npm test
```
Runs the test suite. See the [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### Production Build
```bash
npm run build
```
Creates an optimized production build with minified files and hashed filenames. Ready for deployment!

> **Note**: Only use `npm run eject` if you need full control over the build configuration. This is irreversible.

## 🛠️ Tech Stack

### Core Technologies
- **React** - Frontend framework with hooks
- **JavaScript (ES6+)** - Modern JavaScript features
- **CSS3** - Responsive styling and animations
- **HTML5** - Semantic markup

### Backend Services
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - NoSQL database for product data and user sessions

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Cart overlay functionality
│   ├── currency-overlay/ # Currency selection
│   ├── header/         # Navigation header
│   └── attributes/     # Product attributes
├── routes/             # Page components
│   ├── all-products/   # Product catalog
│   ├── single-product/ # Product details
│   ├── cart/          # Shopping cart
│   ├── checkout/      # Checkout process
│   └── order/         # Order confirmation
├── core-ui/           # Global styles
├── data/              # Static data
├── database/          # Firebase configuration
└── helpers/           # Utility functions
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **Repository**: [https://github.com/HelloQATeam123/PullRequestTesting](https://github.com/HelloQATeam123/PullRequestTesting)

---

<div align="center">
  <p>Built with ❤️ using React and Firebase</p>
</div>
