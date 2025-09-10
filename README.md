# PullRequestTesting

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

PullRequestTesting is a modern, responsive e-commerce platform built with React, featuring comprehensive product management and shopping cart functionality. The application provides a seamless shopping experience with dynamic product filtering, cart management, and multi-currency support.

## Key Features

### 🛒 Cart Management
- **Dynamic Cart Operations**: Add, remove, and modify product quantities with real-time updates
- **Cart Overlay**: Quick access to cart summary without page navigation
- **Product Attributes**: Detailed product information including size, color, and other specifications
- **Persistent Storage**: Cart data maintained across browser sessions

### 🔍 Product Discovery
- **Category Filtering**: Intuitive product categorization for enhanced browsing
- **Attribute Selection**: Required attribute selection (size, color) before cart addition
- **Dual Shopping Interface**: Add products from both category and individual product pages
- **Product Validation**: Prevents incomplete product selections

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies with real-time conversion
- **Dynamic Price Updates**: Automatic price updates based on selected currency
- **Localized Shopping**: Enhanced user experience for international customers

### 🔐 Secure Checkout
- **Multi-Step Process**: Guided checkout flow for optimal user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## Technical Implementation

### Architecture
- **Frontend Framework**: React with modern component architecture
- **State Management**: Context API for global state management
- **Routing**: React Router for seamless navigation
- **Data Persistence**: Firebase Firestore for external data storage

### Development Features
- ✅ Comprehensive cart logic with attribute selection
- ✅ Integrated form validation throughout the application
- ✅ Firebase integration for data persistence
- ✅ Responsive design for all device types

## Getting Started

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
   Navigate to [http://localhost:3000](http://localhost:3000)

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production |
| `npm run eject` | Ejects from Create React App (⚠️ irreversible) |

## Dependencies

### Core Dependencies
- **React Router** - Client-side routing
- **Firebase Firestore** - Cloud database service
- **UUID** - Unique identifier generation

## Project Structure

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
│   │   ├── not-found/
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

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Database powered by [Firebase](https://firebase.google.com/)

---

**Professional E-commerce Solution**
