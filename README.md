![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive e-commerce platform built with React, featuring a comprehensive women's clothing catalog with advanced shopping cart functionality and multi-currency support.

## 🚀 Live Demo

Visit the live application: [Shopping Time](https://pullrequesttesting.vercel.app/)

## 📋 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Development Goals](#development-goals)
- [Contributing](#contributing)
- [License](#license)

## 📖 Overview

Shopping Time is a full-featured e-commerce web application showcasing modern React development practices. The platform offers an extensive catalog of over 150 women's clothing items with comprehensive product customization options, advanced cart management, and seamless checkout experience.

## ✨ Key Features

### 🛒 Advanced Cart Management
- **Product Operations**: Seamlessly add, remove, and modify product quantities
- **Real-time Updates**: Dynamic cart overlay with instant item summary
- **Attribute Tracking**: Detailed product information including size, color, and specifications
- **Persistent Storage**: Cart state maintained across browser sessions

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Intuitive product categorization and filtering system
- **Flexible Navigation**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Accessibility**: Support for multiple currencies (EUR, GBP, AUD, JPY, USD)
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔐 Secure Checkout Process
- **Multi-step Workflow**: Guided checkout process with clear progress indicators
- **Form Validation**: Comprehensive client-side validation for data integrity
- **Error Handling**: User-friendly error messages and recovery options

## 🛠 Technology Stack

- **Frontend Framework**: React 18.x with Hooks
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with responsive design
- **Build Tool**: Create React App
- **Deployment**: Vercel

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14.0 or higher)
- npm or yarn package manager
- Git

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
   - Create a Firebase project
   - Add your Firebase configuration to the project
   - Enable Firestore database

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

### Development

- **`npm start`** - Runs the app in development mode with hot reloading
- **`npm test`** - Launches the test runner in interactive watch mode
- **`npm run build`** - Creates an optimized production build
- **`npm run eject`** - Ejects from Create React App (⚠️ irreversible)

### Production Deployment

The application is configured for deployment on Vercel with automatic builds from the main branch.

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

## 🎯 Development Goals

This project was developed to demonstrate proficiency in:

- **React Architecture**: Implementation of both class components and modern hooks
- **State Management**: Complex cart logic with attribute selection and validation
- **Form Handling**: Comprehensive form validation and error handling
- **External APIs**: Integration with Firebase for data persistence
- **Responsive Design**: Mobile-first approach with cross-device compatibility
- **Performance Optimization**: Code splitting and lazy loading implementation

## 📦 Dependencies

| Package | Purpose | Version |
|---------|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing | Latest |
| [React Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries | Latest |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation | Latest |
| [Firebase](https://firebase.google.com/docs/firestore) | Backend services and database | 9.x |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with ❤️ using React and Firebase**
