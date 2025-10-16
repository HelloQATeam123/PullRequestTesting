# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.0+-blue.svg)](https://reactjs.org/)

## Overview

Shopping Time is a modern, responsive e-commerce platform built with React, featuring comprehensive product management with advanced cart functionality, multi-currency support, and secure checkout workflow.

## ✨ Key Features

### 🛒 Advanced Cart Management
- **Dynamic Product Management**: Add, remove, and modify product quantities with real-time updates
- **Interactive Cart Overlay**: Quick access to cart summary without page navigation
- **Attribute Tracking**: Detailed product information including size, color, and other specifications
- **Persistent Storage**: Cart data maintained across browser sessions

### 🛍️ Enhanced Shopping Experience
- **Category Filtering**: Intuitive product categorization for streamlined browsing
- **Flexible Shopping Flow**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔒 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🎯 Technical Achievements

- **React Architecture**: Implemented using modern React patterns and hooks
- **State Management**: Complex cart logic with attribute selection and validation
- **Form Validation**: Robust client-side validation with user feedback
- **External Data Persistence**: Firebase integration for data storage and retrieval
- **Performance Optimization**: Component-based architecture for improved performance

## 🚀 Getting Started

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
- **React** - Frontend framework
- **React Router** - Client-side routing
- **Create React App** - Build toolchain

### Services
- **Firebase** - Backend services and data storage

## 🏗️ Project Structure

```
PullRequestTesting/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── cart-overlay/
│   │   ├── currency-overlay/
│   │   ├── header/
│   │   └── attributes/
│   ├── routes/
│   │   ├── all-products/
│   │   ├── cart/
│   │   ├── checkout/
│   │   ├── landing/
│   │   ├── order/
│   │   └── single-product/
│   ├── assets/
│   ├── data/
│   ├── database/
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

## 🙏 Acknowledgments

- Create React App team for the excellent build toolchain
- Firebase team for reliable backend services
- React community for continuous inspiration and support

---

**Built with ❤️ using React**
