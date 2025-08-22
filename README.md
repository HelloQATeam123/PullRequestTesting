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
- **Quantity Control**: Adjust product quantities with dedicated quantity controls
- **Cart Overlay**: Real-time cart summary without page navigation
- **Success Messages**: Visual feedback for cart operations

### 🔍 Enhanced Shopping Experience
- **Product Attributes**: Comprehensive attribute selection system
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Route-Based Navigation**: Dedicated pages for products, cart, and checkout
- **Error Handling**: 404 page for invalid routes

### 💰 Multi-Currency Support
- **Currency Overlay**: Interactive currency selection interface
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Global Support**: Multiple currency options for international customers

### 🔐 Complete Checkout Process
- **Multi-Step Checkout**: Guided checkout flow with validation
- **Order Confirmation**: Dedicated order success page
- **Form Validation**: Comprehensive input validation system

## 🛠️ Technical Stack

- **Frontend**: React 18.x with modern hooks and components
- **Routing**: React Router DOM for SPA navigation
- **Database**: Firebase Firestore for data persistence
- **Styling**: Modular CSS with responsive design and hover effects
- **Build Tool**: Create React App
- **Testing**: Jest and React Testing Library

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
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Shopping cart overlay
│   ├── currency-overlay/# Currency selection
│   └── header/          # Navigation header
├── routes/              # Page components
│   ├── all-products/    # Product listing page
│   ├── cart/           # Shopping cart page
│   ├── checkout/       # Checkout process
│   ├── landing/        # Home page
│   ├── order/          # Order confirmation
│   └── single-product/ # Product detail page
├── core-ui/            # Global styles and responsive design
├── data/               # Static product data
├── database/           # Firebase configuration
└── helpers/            # Utility functions
```

## 🎯 Key Components

- **AddToCartButton**: Handles product addition to cart
- **ChangeCartItemQuantity**: Manages cart item quantities
- **SuccessMessage**: Provides user feedback
- **ResetLocation**: Navigation helper utility

## 📚 Dependencies

### Core Dependencies
- React Router DOM - Client-side routing
- Firebase - Backend services and database
- UUID - Unique identifier generation

### Development Dependencies
- Create React App - Build toolchain
- Jest - Testing framework
- React Testing Library - Component testing utilities

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

## 🙏 Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Database powered by [Firebase](https://firebase.google.com/)
- Testing with [Jest](https://jestjs.io/) and [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

---

**Professional E-commerce Solution**
