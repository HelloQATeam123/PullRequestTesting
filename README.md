![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform built with React, featuring a comprehensive catalog of women's clothing with advanced shopping cart functionality and multi-currency support.

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
- **Product Management**: Intuitive add/remove functionality with real-time cart updates
- **Quantity Control**: Flexible quantity adjustment with inventory validation
- **Cart Overlay**: Non-intrusive cart preview without navigation disruption
- **Product Details**: Comprehensive attribute display including size, color, and specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Efficient product discovery through category-based navigation
- **Multi-page Shopping**: Seamless cart integration across category and product detail pages
- **Attribute Validation**: Mandatory attribute selection to ensure order accuracy
- **Responsive Design**: Optimized experience across all device types

### 💰 Multi-Currency Support
- **Global Accessibility**: Support for multiple currencies (EUR, GBP, AUD, JPY, USD)
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency-appropriate formatting and display

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

### Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Latest | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Latest | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Latest | Unique identifier generation |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Latest | Cloud database and storage |

## 🚀 Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
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

3. **Configure environment variables**
   ```bash
   # Create .env file and add your Firebase configuration
   cp .env.example .env
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

### Development

```bash
npm start
```
Launches the development server with hot reloading at `http://localhost:3000`

### Testing

```bash
npm test
```
Runs the test suite in interactive watch mode

### Production Build

```bash
npm run build
```
Creates an optimized production build in the `build` folder

### Advanced Configuration

```bash
npm run eject
```
**⚠️ Warning**: This is irreversible. Ejects from Create React App for full configuration control.

## 📁 Project Structure

```
PullRequestTesting/
├── public/
│   ├── index.html
│   ├── favicon.ico
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
├── LICENSE
└── README.md
```

## 🎯 Development Goals

This project was developed to demonstrate proficiency in:

- ✅ **React Architecture**: Implementation of both class components and functional components with hooks
- ✅ **State Management**: Complex cart logic with attribute selection and validation
- ✅ **Form Handling**: Comprehensive form validation and error handling
- ✅ **External Integration**: Firebase integration for data persistence
- ✅ **Responsive Design**: Mobile-first approach with cross-device compatibility
- ✅ **Performance Optimization**: Code splitting and lazy loading implementation

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Workflow

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

---

**Built with ❤️ using React and modern web technologies**
