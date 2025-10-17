# PullRequestTesting

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

## Overview

PullRequestTesting is a modern, responsive e-commerce platform built with React, featuring comprehensive shopping cart functionality, multi-currency support, and secure checkout processes. The application demonstrates advanced React patterns and state management techniques for building scalable e-commerce solutions.

## ✨ Key Features

### 🛒 Advanced Cart Management
- **Dynamic Product Management**: Add, remove, and modify product quantities with real-time updates
- **Interactive Cart Overlay**: Quick access to cart summary without page navigation
- **Attribute Tracking**: Comprehensive display of selected product attributes (size, color, etc.)
- **Persistent Storage**: Cart state maintained across browser sessions

### 🛍️ Enhanced Shopping Experience
- **Category-Based Filtering**: Intuitive product discovery through organized categories
- **Flexible Shopping Flow**: Add products from both category and individual product pages
- **Mandatory Attribute Selection**: Prevents cart errors by requiring size/color selection
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Tailored shopping experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process for enhanced user experience
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
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production |
| `npm run eject` | Ejects from Create React App (⚠️ irreversible) |

## 🛠️ Technology Stack

### Core Technologies
- **React 18.x** - Modern React with hooks and functional components
- **React Router** - Client-side routing and navigation
- **Firebase Firestore** - Cloud-based NoSQL database for data persistence

### Project Structure
```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Cart management components
│   ├── currency-overlay/ # Currency selection components
│   └── header/         # Navigation components
├── routes/             # Page-level components
│   ├── all-products/   # Product listing page
│   ├── cart/          # Shopping cart page
│   ├── checkout/      # Checkout process
│   └── single-product/ # Product detail page
├── core-ui/           # Global styles and CSS
├── data/              # Static data and product information
├── database/          # Firebase configuration
└── helpers/           # Utility functions
```

## 🎯 Development Goals Achieved

- ✅ **React Architecture**: Successfully implemented modern React patterns with hooks
- ✅ **Complex State Management**: Built sophisticated logic for attribute selection and cart management
- ✅ **Form Validation**: Implemented comprehensive form validation throughout the application
- ✅ **External Data Integration**: Integrated Firebase for persistent data storage and retrieval
- ✅ **Responsive Design**: Created a mobile-first, responsive user interface
- ✅ **Performance Optimization**: Optimized bundle size and loading performance

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Firebase for backend services
- Icons and assets from various open-source contributors

---

<div align="center">
  <p>Made with ❤️ for testing and development purposes</p>
</div>
