# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.0+-blue.svg)](https://reactjs.org/)

![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

## Overview

Shopping Time is a modern, responsive e-commerce platform built with React, featuring over 150 women's clothing products with comprehensive customization options. The application provides a seamless shopping experience with advanced cart management, multi-currency support, and secure checkout functionality.

**🔗 [Live Demo](https://shopping-time.vercel.app/)**

## ✨ Key Features

### 🛒 Advanced Cart Management
- **Dynamic Product Management**: Add, remove, and modify product quantities with real-time updates
- **Interactive Cart Overlay**: Quick access to cart summary without page navigation
- **Attribute Tracking**: Detailed product information including size, color, and other specifications
- **Persistent Storage**: Cart data maintained across browser sessions

### 🛍️ Enhanced Shopping Experience
- **Category Filtering**: Intuitive product categorization for streamlined browsing
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Accessibility**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔒 Secure Checkout Process
- **Multi-step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Error Handling**: User-friendly error messages and recovery options

## 🎯 Project Objectives

This project demonstrates proficiency in:
- **React Development**: Implementation using both class components and modern hooks
- **State Management**: Complex cart logic and attribute selection handling
- **Form Validation**: Robust client-side validation implementation
- **External Integration**: Firebase integration for data persistence
- **Modern Web Standards**: Responsive design and accessibility best practices

## 🚀 Quick Start

### Prerequisites
- Node.js (v14.0 or higher)
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

3. **Start development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the development server on port 3000 |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Creates an optimized production build |
| `npm run eject` | Ejects from Create React App (⚠️ irreversible) |

### Development Mode
```bash
npm start
```
- Hot reloading enabled
- Lint errors displayed in console
- Accessible at [http://localhost:3000](http://localhost:3000)

### Production Build
```bash
npm run build
```
- Optimized bundle creation
- Minified files with hash names
- Ready for deployment

## 🛠️ Technology Stack

### Core Technologies
- **[React](https://reactjs.org/)** - Frontend framework
- **[React Router](https://reactrouter.com/)** - Client-side routing
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - Database and backend services

### Additional Libraries
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Image carousel functionality
- **[UUID](https://www.npmjs.com/package/uuid)** - Unique identifier generation

### Development Tools
- **Create React App** - Project bootstrapping and build tools
- **ESLint** - Code linting and formatting
- **Webpack** - Module bundling (via CRA)

## 📁 Project Structure

```
PullRequestTesting/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   ├── manifest.json
│   └── ...
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
│   ├── assets/
│   │   └── images/
│   ├── core-ui/
│   ├── data/
│   ├── database/
│   ├── helpers/
│   ├── App.js
│   └── index.js
├── package.json
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 🔗 Links

- **Live Demo**: [https://shopping-time.vercel.app/](https://shopping-time.vercel.app/)
- **Repository**: [https://github.com/HelloQATeam123/PullRequestTesting](https://github.com/HelloQATeam123/PullRequestTesting)

---

<div align="center">
  <p>Built with ❤️ using React</p>
</div>
