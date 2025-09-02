# PullRequestTesting

## Overview

PullRequestTesting is a modern e-commerce web application built with React, featuring comprehensive product management, cart functionality, and checkout processes. The platform provides a seamless shopping experience with dynamic product attributes, cart management, and multi-currency support.

## Key Features

### 🛒 Cart Management
- **Add/Remove Products**: Intuitive product addition and removal with real-time cart updates
- **Quantity Control**: Flexible quantity adjustment for all cart items
- **Cart Overlay**: Quick cart preview without leaving the current page
- **Product Details**: Complete attribute information (size, color, etc.) displayed in cart

### 🔍 Product Discovery
- **Category Filtering**: Efficient product browsing by category
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents incomplete orders

### 💰 Currency Support
- **Multi-currency**: Support for multiple currencies with real-time conversion
- **Global Accessibility**: Localized pricing for international customers

### ✅ Secure Checkout
- **Multi-step Process**: Guided checkout flow for optimal user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## Technical Implementation

### Architecture
- **Frontend**: React with modern hooks architecture
- **State Management**: Custom cart logic with attribute handling
- **Data Persistence**: Firebase Firestore integration
- **Routing**: React Router for seamless navigation
- **Validation**: Custom form validation system

### Project Structure
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
│   │   ├── order/
│   │   └── single-product/
│   ├── core-ui/
│   ├── data/
│   ├── database/
│   └── helpers/
├── package.json
└── README.md
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

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

3. **Start development server**
   ```bash
   npm start
   ```

4. **Open application**
   Navigate to [http://localhost:3000](http://localhost:3000) in your browser

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production |
| `npm run eject` | Ejects from Create React App (irreversible) |

### Development Mode
```bash
npm start
```
- Opens [http://localhost:3000](http://localhost:3000)
- Hot reload enabled
- Lint errors displayed in console

### Production Build
```bash
npm run build
```
- Optimized production bundle
- Minified files with hash names
- Ready for deployment

## Core Components

### Cart Management
- **AddToCartButton.js** - Handles product addition to cart
- **ChangeCartItemQuantity.js** - Manages item quantity updates
- **cart-overlay/** - Cart preview functionality

### Product Display
- **all-products/** - Product listing and filtering
- **single-product/** - Individual product details
- **attributes/** - Product attribute selection

### User Experience
- **currency-overlay/** - Multi-currency selection
- **checkout/** - Secure checkout process
- **order/** - Order confirmation and management

## Development Stack

- **React 18+** - Frontend framework
- **Create React App** - Build toolchain
- **Firebase** - Backend services
- **React Router** - Client-side routing

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Database powered by [Firebase](https://firebase.google.com)

---

**QA Testing Repository**
