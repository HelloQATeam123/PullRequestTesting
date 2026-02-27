# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

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
- **Category Filtering**: Intuitive product categorization for efficient browsing
- **Flexible Shopping Flow**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Accessibility**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔒 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Error Handling**: User-friendly error messages and recovery options

## 🎯 Technical Achievements

- **React Architecture**: Successfully implemented both class components and modern hooks
- **State Management**: Complex cart logic with attribute selection and validation
- **Form Handling**: Robust validation system with user feedback
- **External Integration**: Firebase integration for data persistence
- **Performance Optimization**: Efficient rendering and state updates

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
| `npm start` | Runs the app in development mode on [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production with optimizations |
| `npm run eject` | **⚠️ One-way operation** - Ejects from Create React App |

## 🛠️ Technology Stack

### Core Technologies
- **React** - Frontend framework with hooks and class components
- **React Router** - Client-side routing and navigation
- **JavaScript (ES6+)** - Modern JavaScript features and syntax

### Dependencies
- **[React Router DOM](https://www.npmjs.com/package/react-router-dom)** - Declarative routing for React applications
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Lightweight image carousel component
- **[UUID](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - NoSQL cloud database for data persistence

### Development Tools
- **Create React App** - Build toolchain and development environment
- **ESLint** - Code linting and style enforcement
- **Webpack** - Module bundling and asset optimization

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
│   ├── assets/
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

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Deployed on [Vercel](https://vercel.com/)
- Icons and images from various open-source contributors

---

**Made with ❤️ by the Development Team**
