# Shopping Time - E-Commerce React Application

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/HelloQATeam123/PullRequestTesting)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)

A modern, full-featured e-commerce web application built with React and Firebase, offering a seamless shopping experience with over 150 women's clothing products, dynamic cart management, and multi-currency support.

## 📋 Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

### 🛒 Shopping Cart Management
- ✅ **Add/Remove Products**: Seamlessly add and remove items from your shopping cart
- ✅ **Quantity Control**: Adjust product quantities with intuitive controls
- ✅ **Cart Overlay**: Real-time cart summary without page navigation
- ✅ **Product Attributes**: Detailed product information including size, color, and specifications
- ✅ **Persistent Cart**: Cart state maintained across sessions using Firebase

### 🛍️ Product Catalog
- ✅ **Category Filtering**: Browse products by categories for easy navigation
- ✅ **Product Details**: Comprehensive product pages with multiple images and descriptions
- ✅ **Attribute Selection**: Required attribute selection (size, color) before adding to cart
- ✅ **Search Functionality**: Find products quickly with built-in search
- ✅ **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- ✅ **Currency Conversion**: Support for EUR, GBP, AUD, JPY, USD and more
- ✅ **Real-time Rates**: Dynamic currency conversion with live exchange rates
- ✅ **Localized Pricing**: Currency-appropriate formatting and display

### 🔒 Secure Checkout Process
- ✅ **Multi-Step Checkout**: Guided checkout process with progress indicators
- ✅ **Form Validation**: Comprehensive client-side validation for all forms
- ✅ **Order Management**: Complete order processing and confirmation system
- ✅ **Firebase Integration**: Secure data storage and user management

## 🚀 Technology Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| **React** | Frontend Framework | 18.x |
| **Firebase** | Backend & Database | 9.x |
| **React Router** | Client-side Routing | Latest |
| **CSS3** | Styling & Animations | - |
| **JavaScript ES6+** | Programming Language | - |
| **Firestore** | NoSQL Database | - |
| **Vercel** | Deployment Platform | - |

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager
- Firebase account for backend services

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Firebase Configuration**
   ```bash
   # Create a .env file in the root directory
   touch .env
   ```
   
   Add your Firebase configuration:
   ```env
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🎯 Usage

### For Customers
1. **Browse Products**: Navigate through categories or use search functionality
2. **Select Attributes**: Choose size, color, and other product attributes
3. **Add to Cart**: Add selected items to your shopping cart
4. **Manage Cart**: View, edit, or remove items from cart overlay
5. **Checkout**: Complete purchase through the multi-step checkout process

### For Developers
```bash
# Run tests
npm test

# Build for production
npm run build

# Deploy to Vercel
vercel --prod
```

## 📁 Project Structure

```
src/
├── components/           # Reusable UI components
│   ├── Cart/            # Shopping cart components
│   ├── Product/         # Product display components
│   └── Checkout/        # Checkout process components
├── routes/              # Application routing
├── database/            # Firebase configuration and utilities
├── assets/              # Static assets (images, icons)
├── styles/              # CSS stylesheets
└── utils/               # Helper functions and utilities
```

## 🛠️ Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode on [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | **One-way operation** - Ejects from Create React App |

## 📚 Dependencies

### Core Dependencies
| Package | Version | Purpose |
|---------|---------|---------|
| `react` | ^18.x | Core React library |
| `react-dom` | ^18.x | React DOM rendering |
| `react-router-dom` | ^6.x | Client-side routing |
| `firebase` | ^9.x | Backend services |

### UI & Utilities
| Package | Version | Purpose |
|---------|---------|---------|
| `react-simple-image-slider` | Latest | Product image carousel |
| `uuid` | Latest | Unique identifier generation |

### Development Dependencies
| Package | Version | Purpose |
|---------|---------|---------|
| `@testing-library/react` | Latest | React component testing |
| `@testing-library/jest-dom` | Latest | Jest DOM matchers |

## 🤝 Contributing

We welcome contributions to improve Shopping Time! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow React best practices and hooks patterns
- Maintain consistent code formatting
- Add tests for new features
- Update documentation as needed
- Ensure Firebase security rules are properly configured

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

---

**Built with ❤️ using React and Firebase**

For questions or support, please open an issue in the GitHub repository.
