# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

## Overview

Shopping Time is a modern, responsive e-commerce web application built with React. The platform features over 150 women's clothing products with comprehensive customization options including size and color variations. The application provides a seamless shopping experience with advanced cart management, multi-currency support, and secure checkout functionality.

**🔗 [Live Demo](https://shopping-time.vercel.app/)**

## ✨ Key Features

### 🛒 Advanced Cart Management
- **Product Management**: Intuitive add/remove functionality with real-time cart updates
- **Quantity Control**: Flexible quantity adjustment with instant price calculations
- **Cart Overlay**: Non-intrusive cart preview without navigation disruption
- **Product Details**: Comprehensive attribute display including size, color, and specifications

### 🛍️ Enhanced Shopping Experience
- **Smart Filtering**: Category-based product filtering for efficient browsing
- **Dual Shopping Modes**: Add products from both category and individual product pages
- **Attribute Validation**: Mandatory attribute selection to ensure order accuracy
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Accessibility**: Support for multiple currencies (EUR, GBP, AUD, JPY, USD)
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting according to regional standards

### 🔒 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process with clear progress indicators
- **Form Validation**: Comprehensive client-side validation for data integrity
- **Error Handling**: User-friendly error messages and recovery options

## 🎯 Technical Achievements

- **React Architecture**: Successfully implemented and refactored from class components to modern React hooks
- **State Management**: Complex cart logic with persistent state management
- **Form Validation**: Robust client-side validation with user feedback
- **External Integration**: Firebase integration for data persistence and real-time updates
- **Performance Optimization**: Optimized rendering and state updates for smooth user experience

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
| `npm start` | Runs the app in development mode on [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | **⚠️ One-way operation** - Ejects from Create React App |

## 🛠️ Technology Stack

### Core Technologies
- **[React](https://reactjs.org/)** - Frontend framework
- **[React Router](https://reactrouter.com/)** - Client-side routing
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - Database and real-time data sync

### Additional Libraries
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Image carousel functionality
- **[UUID](https://www.npmjs.com/package/uuid)** - Unique identifier generation

## 📁 Project Structure

```
PullRequestTesting/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
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
│   ├── assets/
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
- Icons and images from various open-source contributors
- Inspiration from modern e-commerce platforms

---

**Made with ❤️ by the Development Team**
