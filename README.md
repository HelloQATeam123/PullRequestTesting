![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive e-commerce platform built with React, featuring comprehensive shopping cart functionality, multi-currency support, and a complete checkout process.

## 🚀 Live Demo

Visit the live application: [pullrequesttesting.vercel.app](https://pullrequesttesting.vercel.app/)

## ✨ Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality
- **Quantity Control**: Adjust product quantities directly from cart or overlay
- **Cart Overlay**: Real-time cart summary without page navigation
- **Product Attributes**: Detailed product information including size, color, and specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories
- **Dual Shopping Interface**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Tailored shopping experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided, user-friendly checkout flow
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Confirmation**: Complete order processing with success messaging

## 🛠️ Technical Stack

- **Frontend**: React 18.x with Hooks and Class Components
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with responsive design modules
- **Build Tool**: Create React App
- **Deployment**: Vercel

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

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

3. **Configure Firebase**
   - Create a Firebase project
   - Add your Firebase configuration to `src/database/firebase.js`
   - Enable Firestore database

4. **Start development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production |
| `npm run eject` | Ejects from Create React App (⚠️ irreversible) |

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Shopping cart overlay
│   ├── currency-overlay/ # Currency selection
│   └── header/         # Navigation header
├── routes/             # Page components
│   ├── all-products/   # Product catalog
│   ├── cart/          # Shopping cart page
│   ├── checkout/      # Checkout process
│   └── single-product/ # Product details
├── core-ui/           # Global styles and responsive design
├── data/              # Product data management
├── database/          # Firebase configuration
└── helpers/           # Utility functions
```

## 🎯 Development Goals Achieved

- ✅ **React Mastery**: Implemented both Class components and Hooks patterns
- ✅ **State Management**: Complex cart logic with attribute selection
- ✅ **Form Validation**: Comprehensive input validation system
- ✅ **External Data**: Firebase integration for persistent data storage
- ✅ **Responsive Design**: Mobile-first approach with cross-device compatibility
- ✅ **Performance**: Optimized build with modular CSS architecture

## 📚 Key Components

| Component | Purpose |
|-----------|---------|
| `AddToCartButton` | Handles product addition to cart |
| `ChangeCartItemQuantity` | Manages cart item quantities |
| `SuccessMessage` | Displays order confirmation |
| `cart-overlay` | Real-time cart preview |
| `currency-overlay` | Multi-currency selection |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 👨‍💻 Development Team

**HelloQATeam123**
- GitHub: [@HelloQATeam123](https://github.com/HelloQATeam123)

## 🙏 Acknowledgments

- Create React App team for the excellent boilerplate
- Firebase team for the robust backend services
- React community for continuous inspiration and support

---

⭐ If you found this project helpful, please consider giving it a star!
