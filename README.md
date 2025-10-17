# PullRequestTesting

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

## Overview

PullRequestTesting is a modern, responsive e-commerce web application built with React. The platform features comprehensive product management with advanced cart functionality, multi-currency support, and secure checkout processes. The application provides a seamless shopping experience with real-time cart updates and persistent data storage.

## ✨ Key Features

### 🛒 Advanced Cart Management
- **Dynamic Product Management**: Add, remove, and modify product quantities with real-time updates
- **Interactive Cart Overlay**: Quick access to cart summary without page navigation
- **Attribute Tracking**: Detailed product information including selected sizes, colors, and specifications
- **Persistent Storage**: Cart data maintained across browser sessions using Firebase

### 🛍️ Enhanced Shopping Experience
- **Category-Based Filtering**: Intuitive product discovery through organized categories
- **Flexible Shopping Flow**: Add products from both category pages and individual product details
- **Mandatory Attribute Selection**: Prevents cart errors by requiring size/color selection before purchase
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Shopping**: Enhanced user experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process with clear progress indicators
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🚀 Getting Started

### Prerequisites
- Node.js (v14.0.0 or higher)
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

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode with hot reloading |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production with optimizations |
| `npm run eject` | Ejects from Create React App (⚠️ irreversible) |

## 🛠️ Technology Stack

### Core Technologies
- **React 18.x** - Modern React with hooks and functional components
- **React Router** - Client-side routing and navigation
- **Create React App** - Development environment and build tooling

### Dependencies & Services
- **React Router DOM** - Declarative routing for React applications
- **Firebase Firestore** - Cloud-based NoSQL database for data persistence
- **Custom CSS** - Responsive styling with hover effects and mobile optimization

## 🎯 Development Goals Achieved

- ✅ **React Architecture**: Successfully implemented modern React hooks and functional components
- ✅ **Complex State Management**: Built sophisticated logic for product attributes and cart management
- ✅ **Form Validation**: Implemented comprehensive client-side validation system
- ✅ **External Data Integration**: Integrated Firebase for persistent data storage and retrieval
- ✅ **Responsive Design**: Created mobile-first, responsive user interface
- ✅ **Performance Optimization**: Optimized bundle size and loading performance

## 📁 Project Structure

```
PullRequestTesting/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── AddToCartButton.js
│   │   ├── ChangeCartItemQuantity.js
│   │   ├── SuccessMessage.js
│   │   ├── attributes/
│   │   ├── cart-overlay/
│   │   ├── currency-overlay/
│   │   └── header/
│   ├── routes/
│   │   ├── all-products/
│   │   ├── cart/
│   │   ├── checkout/
│   │   ├── landing/
│   │   ├── order/
│   │   └── single-product/
│   ├── core-ui/
│   ├── data/
│   ├── database/
│   ├── helpers/
│   └── App.js
├── package.json
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **Repository**: [https://github.com/HelloQATeam123/PullRequestTesting](https://github.com/HelloQATeam123/PullRequestTesting)

---

<div align="center">
  <p>Built with ❤️ using React</p>
</div>
