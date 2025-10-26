<div align="center">

![Shopping Time](https://raw.githubusercontent.com/catherineisonline/shopping-time/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/HelloQATeam123/PullRequestTesting)
[![React](https://img.shields.io/badge/React-18.x-61DAFB.svg)](https://reactjs.org/)

**A modern, responsive e-commerce platform built with React.js**

[🚀 Live Demo](https://shopping-time.vercel.app/) | [📖 Documentation](#table-of-contents) | [🐛 Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Setup](#environment-setup)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Development Goals](#development-goals)
- [Contributing](#contributing)
- [License](#license)
- [Quick Links](#quick-links)

---

## Overview

**Shopping Time** is a comprehensive e-commerce platform featuring over 150 women's clothing products with extensive customization options. Built with modern React.js and powered by Firebase, it delivers a seamless shopping experience with advanced cart management, multi-currency support, and responsive design.

### Key Highlights
- 🛍️ **150+ Products** - Extensive catalog of women's clothing
- 🎨 **Product Customization** - Multiple sizes and color options
- 💰 **Multi-Currency Support** - Shop in your preferred currency
- 🛒 **Advanced Cart Management** - Real-time cart updates and persistence
- 📱 **Responsive Design** - Optimized for all devices
- 🔒 **Secure Checkout** - Multi-step validation process

---

## Features

### 🛒 Shopping Cart Management
- **Add/Remove Products** - Intuitive cart operations with real-time updates
- **Quantity Adjustment** - Flexible quantity management for each item
- **Cart Overlay** - Quick cart preview without page navigation
- **Product Attributes** - Detailed product information with selected attributes
- **Cart Persistence** - Maintain cart state across sessions

### 🛍️ Enhanced Shopping Experience
- **Category Filtering** - Browse products by specific categories
- **Dual Shopping Interface** - Add products from category or product pages
- **Attribute Validation** - Mandatory attribute selection prevents ordering errors
- **Product Search** - Find products quickly and efficiently
- **Responsive Design** - Seamless experience across all devices

### 💱 Multi-Currency Support
- **Global Currency Options** - Support for EUR, GBP, AUD, JPY, and more
- **Real-time Conversion** - Dynamic price updates based on selected currency
- **Localized Pricing** - Currency-appropriate formatting and display

### 🔐 Secure Checkout Process
- **Multi-Step Checkout** - Guided purchase process for better user experience
- **Form Validation** - Comprehensive validation to ensure data accuracy
- **Order Confirmation** - Detailed order summaries and confirmations
- **Error Handling** - Robust error management and user feedback

---

## Technology Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| **React.js** | Frontend Framework | 18.x |
| **JavaScript ES6+** | Programming Language | Latest |
| **Firebase** | Backend & Database | Latest |
| **Firestore** | NoSQL Database | Latest |
| **CSS3** | Styling & Animations | Latest |
| **React Router** | Client-side Routing | 6.x |
| **Create React App** | Build Tool | Latest |

### Additional Libraries
- **React Simple Image Slider** - Product image galleries
- **UUID** - Unique identifier generation
- **React Hooks** - Modern React state management

---

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (version 14.0 or higher)
- **npm** (version 6.0 or higher) or **yarn**
- **Git** for version control

```bash
# Check your Node.js version
node --version

# Check your npm version
npm --version
```

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
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

### Environment Setup

#### Firebase Configuration

1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
2. Enable Firestore Database
3. Create a `.env` file in the root directory:

```env
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

---

## Available Scripts

In the project directory, you can run:

### `npm start`
```bash
npm start
```
Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser. The page will reload when you make changes.

### `npm test`
```bash
npm test
```
Launches the test runner in interactive watch mode. See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
```bash
npm run build
```
Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run eject`
```bash
npm run eject
```
**Note: This is a one-way operation. Once you `eject`, you can't go back!**

This command will remove the single build dependency from your project and copy all configuration files and transitive dependencies into your project.

---

## Project Structure

```
shopping-time/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   ├── utils/
│   ├── hooks/
│   └── App.js
├── package.json
└── README.md
```

---

## Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| [React Router DOM](https://www.npmjs.com/package/react-router-dom) | ^6.x | Client-side routing |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Latest | Image carousel functionality |
| [UUID](https://www.npmjs.com/package/uuid) | Latest | Unique identifier generation |
| [Firebase](https://firebase.google.com/docs/firestore) | Latest | Backend services and database |

### Development Dependencies
- Create React App
- React Scripts
- Web Vitals
- Testing Library

---

## Development Goals

This project was developed to achieve the following objectives:

- ✅ **React Mastery** - Practice React Class components and refactor to modern hooks
- ✅ **State Management** - Build complex logic for attribute selection and cart management
- ✅ **Form Validation** - Implement comprehensive form validations
- ✅ **External Data** - Integrate Firebase for data persistence
- ✅ **Responsive Design** - Create mobile-first, responsive user interfaces
- ✅ **E-commerce Logic** - Develop complete shopping cart and checkout functionality

---

## Contributing

We welcome contributions to Shopping Time! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/catherineisonline/shopping-time/blob/main/LICENSE) file for details.

```
MIT License - you are free to use, modify, and distribute this project
according to the terms of the MIT License.
```

---

## Quick Links

<div align="center">

| Resource | Link |
|----------|------|
| 🚀 **Live Demo** | [shopping-time.vercel.app](https://shopping-time.vercel.app/) |
| 📖 **Documentation** | [Table of Contents](#table-of-contents) |
| 🐛 **Issues** | [Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues) |
| 💡 **Features** | [Feature Requests](https://github.com/HelloQATeam123/PullRequestTesting/issues) |
| 📜 **License** | [MIT License](#license) |
| 🛠️ **Scripts** | [Available Scripts](#available-scripts) |

---

**Built with ❤️ using React.js and Firebase**

</div>
