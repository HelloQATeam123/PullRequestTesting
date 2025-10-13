# PullRequestTesting

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

## Overview

PullRequestTesting is a modern, responsive e-commerce platform specializing in women's fashion. Built with React, the application features a comprehensive catalog of clothing products with dynamic attribute selection, multi-currency support, and a seamless shopping experience.

## ✨ Key Features

### 🛒 Shopping Cart Management
- **Dynamic Cart Operations**: Add, remove, and modify product quantities with real-time updates
- **Cart Overlay**: Quick access to cart summary without navigation interruption
- **Attribute Tracking**: Detailed product information including size, color, and other selected attributes
- **Persistent Storage**: Cart state maintained across browser sessions

### 🛍️ Enhanced Shopping Experience
- **Category Filtering**: Intuitive product categorization for streamlined browsing
- **Flexible Shopping Flow**: Add products from both category and individual product pages
- **Mandatory Attribute Selection**: Prevents cart errors by requiring size/color selection before purchase
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies with real-time conversion
- **Dynamic Price Updates**: Automatic price recalculation based on selected currency
- **Localized Experience**: Tailored shopping experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process with clear progress indicators
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

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
- **React 18.x** - Frontend framework
- **React Router** - Client-side routing
- **Create React App** - Build toolchain

### Dependencies
- **Firebase Firestore** - Cloud database for data persistence
- **Custom Components** - Modular component architecture for cart, currency, and product management

## 🎯 Development Goals Achieved

- ✅ **React Architecture**: Implemented both class components and functional components with hooks
- ✅ **State Management**: Complex cart logic with attribute selection and quantity management
- ✅ **Form Validation**: Comprehensive input validation across checkout process
- ✅ **External Data Persistence**: Firebase integration for data storage
- ✅ **Responsive Design**: Mobile-first approach with cross-device compatibility
- ✅ **Component Modularity**: Reusable components for scalable development

## 🏗️ Project Structure

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

## 📞 Support

If you have any questions or need support, please open an issue on GitHub.

---

**Made with ❤️ by the HelloQATeam123**
