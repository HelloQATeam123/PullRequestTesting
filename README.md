![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive e-commerce platform built with React, featuring comprehensive shopping cart functionality and multi-currency support for women's clothing products.

## 🚀 Live Demo

Visit the live application: [Shopping Time](https://pullrequesttesting.vercel.app/)

## ✨ Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality
- **Quantity Control**: Adjust product quantities directly from the cart using dedicated components
- **Cart Overlay**: Real-time cart preview without page navigation
- **Product Attributes**: Detailed product information including size, color, and specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories
- **Dual Shopping Interface**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Currency Overlay**: Intuitive currency selection interface

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided, user-friendly checkout flow
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Confirmation**: Complete order processing with success messaging

## 🛠️ Technology Stack

- **Frontend**: React 18.x with Hooks
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with responsive design modules
- **Build Tool**: Create React App
- **State Management**: React Context and Hooks
- **Testing**: Jest and React Testing Library

## 📋 Prerequisites

Before running this project, ensure you have:

- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
- Git

## 🚀 Getting Started

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
| `npm run eject` | **One-way operation** - Ejects from Create React App |

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── AddToCartButton.js
│   ├── ChangeCartItemQuantity.js
│   ├── SuccessMessage.js
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Shopping cart overlay
│   ├── currency-overlay/ # Currency selection
│   └── header/          # Navigation header
├── routes/              # Page components
│   ├── all-products/    # Product listing
│   ├── cart/           # Shopping cart page
│   ├── checkout/       # Checkout process
│   ├── landing/        # Home page
│   ├── order/          # Order confirmation
│   └── single-product/ # Product details
├── core-ui/            # Global styles
├── data/               # Static data
├── database/           # Firebase configuration
└── helpers/            # Utility functions
```

## 🎯 Project Goals & Achievements

This project demonstrates proficiency in:

- ✅ **Modern React Development**: Functional components with Hooks
- ✅ **Complex State Management**: Sophisticated cart logic with attribute selection
- ✅ **Form Validation**: Comprehensive validation system for checkout process
- ✅ **External Data Integration**: Firebase Firestore for data persistence
- ✅ **Responsive Design**: Mobile-first, cross-device compatible interface
- ✅ **Component Architecture**: Modular, reusable component structure
- ✅ **Performance Optimization**: Efficient rendering and state updates

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 📞 Support

If you have any questions or need support, please open an issue on GitHub.

---

**Built with ❤️ using React and Firebase**
