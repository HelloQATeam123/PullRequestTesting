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
- **Quantity Control**: Adjust product quantities directly from the cart using ChangeCartItemQuantity component
- **Cart Overlay**: Real-time cart preview without page navigation
- **Success Notifications**: Visual feedback with SuccessMessage component

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Selection**: Comprehensive product attributes with validation
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Currency Overlay**: Easy currency switching with dedicated overlay component

### 🔐 Secure Checkout Process
- **Multi-step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🛠️ Technical Stack

- **Frontend**: React 18.x with modern Hooks and functional components
- **Routing**: React Router DOM for seamless navigation
- **Database**: Firebase Firestore for data persistence
- **Styling**: CSS3 with modular responsive design
- **Build Tool**: Create React App
- **Testing**: Jest and React Testing Library

## 📋 Prerequisites

Before running this project, ensure you have the following installed:

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

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Firestore Database
   - Update your Firebase configuration in `src/database/firebase.js`

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
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
PullRequestTesting/
├── public/
│   ├── index.html
│   ├── manifest.json
│   └── favicon.ico
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
│   │   ├── single-product/
│   │   └── order/
│   ├── core-ui/
│   │   ├── styles.css
│   │   ├── responsive.css
│   │   └── hovers.css
│   ├── data/
│   │   └── all-products.js
│   ├── database/
│   │   └── firebase.js
│   ├── helpers/
│   │   └── ResetLocation.js
│   └── App.js
├── package.json
└── README.md
```

## 🔧 Key Components

### Core Components
- **AddToCartButton** - Handles product addition to shopping cart
- **ChangeCartItemQuantity** - Manages cart item quantity updates
- **SuccessMessage** - Provides user feedback for successful actions
- **Cart Overlay** - Real-time cart preview functionality
- **Currency Overlay** - Multi-currency selection interface

### Routing Structure
- **Landing Page** - Homepage with featured products
- **All Products** - Complete product catalog with filtering
- **Single Product** - Detailed product view with attributes
- **Cart** - Shopping cart management interface
- **Checkout** - Secure checkout process
- **Order** - Order confirmation and management

## 🎯 Development Goals Achieved

- ✅ **Modern React Patterns**: Implemented with functional components and Hooks
- ✅ **Component Architecture**: Modular, reusable component structure
- ✅ **State Management**: Complex cart logic with real-time updates
- ✅ **Firebase Integration**: Persistent data storage and retrieval
- ✅ **Responsive Design**: Mobile-first approach with cross-device compatibility
- ✅ **User Experience**: Intuitive navigation and feedback systems

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 📞 Support

If you have any questions or need help with setup, please open an issue in the GitHub repository.

---

**Built with ❤️ using React and Firebase**
