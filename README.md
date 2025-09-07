# PullRequestTesting

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

PullRequestTesting is a modern, responsive e-commerce platform specializing in women's fashion. Built with React, this application features a comprehensive catalog of clothing products with dynamic attribute selection, multi-currency support, and a seamless shopping experience.

## ✨ Key Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Intuitive product management with one-click add/remove functionality
- **Quantity Control**: Dynamic quantity adjustment with real-time price updates
- **Cart Overlay**: Quick cart preview without leaving the current page
- **Product Attributes**: Detailed product information including size, color, and specifications

### 🔍 Product Discovery
- **Category Filtering**: Browse products by category for targeted shopping
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Product Variants**: Multiple size and color options for each product

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies with real-time conversion
- **Dynamic Price Updates**: Automatic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔐 Secure Checkout Process
- **Multi-step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Success Messaging**: Clear confirmation and feedback throughout the process

## 🛠 Technical Implementation

### Architecture
- **Frontend Framework**: React with modern hooks patterns
- **State Management**: React Context API and local state
- **Routing**: React Router for single-page application navigation
- **Data Persistence**: Firebase Firestore for external data storage

### Key Components
- **AddToCartButton**: Streamlined product addition functionality
- **ChangeCartItemQuantity**: Dynamic quantity management
- **SuccessMessage**: User feedback and confirmation system
- **Attribute Management**: Size, color, and product variant selection
- **Currency & Cart Overlays**: Non-intrusive user interface elements

## 🚀 Getting Started

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

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production |
| `npm run eject` | Ejects from Create React App (⚠️ irreversible) |

### Development Mode
```bash
npm start
```
- Opens [http://localhost:3000](http://localhost:3000) in your browser
- Hot reloading enabled for real-time development
- Console displays lint errors and warnings

### Production Build
```bash
npm run build
```
- Creates optimized production build in `build/` folder
- Minified and optimized for best performance
- Ready for deployment to any static hosting service

## 📦 Dependencies & Technologies

### Core Dependencies
- **React Router** - Client-side routing and navigation
- **Firebase Firestore** - Cloud database for data persistence
- **UUID** - Unique identifier generation for cart items

### Development Stack
- **React 18** - Frontend framework with hooks
- **Create React App** - Build toolchain and development server
- **CSS3** - Custom styling with responsive design
- **JavaScript ES6+** - Modern JavaScript features

## 🏗 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── attributes/      # Product attribute selection
│   ├── cart-overlay/    # Shopping cart preview
│   ├── currency-overlay/# Currency selection
│   └── header/          # Navigation header
├── routes/              # Page-level components
│   ├── all-products/    # Product catalog
│   ├── cart/            # Shopping cart page
│   ├── checkout/        # Checkout process
│   ├── landing/         # Home page
│   ├── single-product/  # Product detail page
│   └── order/           # Order confirmation
├── core-ui/             # Global styles and responsive design
├── data/                # Static product data
├── database/            # Firebase configuration
└── helpers/             # Utility functions
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Workflow
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The MIT License allows you to:
- ✅ Use the project commercially
- ✅ Modify and distribute
- ✅ Use privately
- ✅ Include in larger works

---

**Built for testing and development purposes**
