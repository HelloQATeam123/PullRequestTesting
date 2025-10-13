![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive e-commerce platform built with React, featuring comprehensive shopping cart functionality, multi-currency support, and a complete checkout system.

## 🚀 Live Demo

Visit the live application: [Shopping Time](https://pullrequesttesting.vercel.app/)

## ✨ Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality
- **Quantity Control**: Adjust product quantities directly from the cart
- **Cart Overlay**: Real-time cart preview without page navigation
- **Product Attributes**: Detailed product information including size, color, and specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔐 Secure Checkout Process
- **Multi-step Checkout**: Guided, user-friendly purchase flow
- **Form Validation**: Comprehensive input validation for accurate order processing
- **Order Confirmation**: Complete order processing with success messaging

## 🛠️ Technical Stack

- **Frontend**: React 18.x with Hooks
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with responsive design
- **Build Tool**: Create React App
- **Deployment**: Vercel

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

### Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production |
| `npm run eject` | Ejects from Create React App (⚠️ irreversible) |

## 📦 Key Components

### Core Components
- **AddToCartButton** - Handles product addition to cart
- **ChangeCartItemQuantity** - Manages cart item quantity updates
- **SuccessMessage** - Displays order confirmation messages
- **Cart Overlay** - Real-time cart preview functionality
- **Currency Overlay** - Multi-currency selection interface
- **Header** - Navigation and cart access

### Route Structure
- **Landing Page** - Homepage with featured products
- **All Products** - Complete product catalog
- **Single Product** - Detailed product view
- **Cart** - Shopping cart management
- **Checkout** - Order processing flow
- **Order** - Order confirmation and tracking

## 🎯 Development Goals Achieved

- ✅ **React Architecture**: Implemented functional components with hooks
- ✅ **State Management**: Complex cart logic with attribute selection
- ✅ **Form Validation**: Comprehensive client-side validation
- ✅ **External Data Integration**: Firebase Firestore integration
- ✅ **Responsive Design**: Mobile-first approach with cross-device compatibility
- ✅ **Component Reusability**: Modular component architecture

## 🏗️ Project Structure

```
PullRequestTesting/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── attributes/
│   │   ├── cart-overlay/
│   │   ├── currency-overlay/
│   │   └── header/
│   ├── routes/
│   │   ├── all-products/
│   │   ├── cart/
│   │   ├── checkout/
│   │   ├── landing/
│   │   └── single-product/
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

## 📞 Support

If you have any questions or need help with the project, please open an issue on GitHub.

---

**Made with ❤️ by the Development Team**
