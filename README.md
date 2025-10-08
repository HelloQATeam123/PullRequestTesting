![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform featuring comprehensive shopping cart functionality and multi-currency support for women's clothing products.

## 🚀 Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality
- **Quantity Control**: Adjust product quantities directly from cart or overlay
- **Cart Overlay**: Real-time cart summary without page navigation
- **Product Attributes**: Detailed product information including size, color, and specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for targeted shopping
- **Dual Shopping Interface**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔐 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🛠️ Technical Implementation

### Architecture & Development
- **React Components**: Modern component-based architecture
- **State Management**: Custom cart logic with persistent storage
- **Form Validation**: Robust client-side validation system
- **Firebase Integration**: Cloud database for data persistence
- **Responsive Design**: Mobile-first approach with CSS3

### Built With
- **Frontend**: React, React Router
- **Styling**: CSS3, Responsive Design
- **Backend**: Firebase/Firestore
- **Build Tools**: Create React App

## 📦 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Quick Start
```bash
# Clone the repository
git clone https://github.com/HelloQATeam123/PullRequestTesting.git

# Navigate to project directory
cd PullRequestTesting

# Install dependencies
npm install

# Start development server
npm start
```

The application will open at [http://localhost:3000](http://localhost:3000)

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
- Opens [http://localhost:3000](http://localhost:3000)
- Hot reload enabled
- Lint errors displayed in console

### Production Build
```bash
npm run build
```
- Optimized production build in `build/` folder
- Minified and hashed filenames
- Ready for deployment

## 🔧 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Cart overlay functionality
│   ├── currency-overlay/ # Currency selection
│   └── header/         # Navigation header
├── routes/             # Page components
│   ├── all-products/   # Product listing
│   ├── cart/          # Shopping cart
│   ├── checkout/      # Checkout process
│   └── single-product/ # Product details
├── core-ui/           # Global styles
├── data/              # Product data
├── database/          # Firebase configuration
└── helpers/           # Utility functions
```

## 🔧 Dependencies

### Core Dependencies
- **React Router** - Client-side routing
- **UUID** - Unique identifier generation
- **Firebase/Firestore** - Cloud database solution

### Development Dependencies
- Create React App toolchain
- ESLint for code quality
- Testing utilities

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

## 📞 Support

For support, please open an issue on GitHub or contact the maintainer.

---

**[⬆ Back to Top](#shopping-time)**
