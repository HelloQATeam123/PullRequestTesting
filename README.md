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
- **Product Management**: Seamlessly add, remove, and modify products in your shopping cart
- **Quantity Control**: Flexible quantity adjustment with real-time price calculations
- **Cart Overlay**: Quick access cart summary without page navigation
- **Product Attributes**: Detailed product information including size, color, and specifications
- **Persistent Storage**: Cart data preserved across browser sessions

### 🛍️ Enhanced Shopping Experience
- **Category Filtering**: Intuitive product categorization and filtering system
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Search Functionality**: Quick product discovery capabilities

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Pricing**: Currency-appropriate formatting and display

### 🔒 Secure Checkout Process
- **Multi-step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Error Handling**: User-friendly error messages and recovery options
- **Order Confirmation**: Detailed order summaries and confirmation

## 🛠️ Technology Stack

- **Frontend Framework**: React 18.x
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with responsive design
- **Build Tool**: Create React App
- **Deployment**: Vercel
- **Package Management**: npm

### Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Latest | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Latest | Product image galleries |
| [UUID](https://www.npmjs.com/package/uuid) | Latest | Unique identifier generation |
| [Firebase](https://firebase.google.com/docs/firestore) | Latest | Backend services and database |

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
Launches the development server with hot reloading enabled. The application will automatically open in your default browser at `http://localhost:3000`.

### Testing

```bash
npm test
```
Runs the test suite in interactive watch mode. See the [Create React App testing documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### Production Build

```bash
npm run build
```
Creates an optimized production build in the `build` folder. The build is minified and includes hashed filenames for optimal caching.

### Advanced Configuration

```bash
npm run eject
```
**⚠️ Warning**: This is a one-way operation. Ejecting will give you full control over the build configuration but cannot be reversed.

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
│   ├── assets/
│   │   └── images/
│   ├── core-ui/
│   ├── data/
│   ├── database/
│   ├── helpers/
│   └── App.js
├── package.json
├── LICENSE
└── README.md
```

## 🎯 Development Goals

This project was developed to demonstrate proficiency in:

- **React Architecture**: Implementation of both class components and functional components with hooks
- **State Management**: Complex state handling for cart functionality and user interactions
- **Form Validation**: Comprehensive client-side validation with user-friendly error handling
- **External API Integration**: Firebase integration for data persistence and real-time updates
- **Responsive Design**: Mobile-first approach with cross-device compatibility
- **Performance Optimization**: Code splitting and lazy loading implementation

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

The MIT License permits unrestricted use, modification, and distribution of this software, provided that the original copyright notice and license terms are included in all copies or substantial portions of the software.

---

**Built with ❤️ using React and modern web technologies**
