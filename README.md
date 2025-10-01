![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue)](https://pullrequesttesting.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform featuring comprehensive shopping cart functionality, multi-currency support, and a complete checkout process.

## 🚀 Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamless cart functionality with quantity controls
- **Cart Overlay**: Real-time cart summary without page navigation
- **Quantity Management**: Dedicated component for cart item quantity adjustments
- **Success Notifications**: User feedback for cart operations

### 🔍 Enhanced Shopping Experience
- **Product Attributes**: Comprehensive attribute selection system
- **Category Navigation**: Browse products by category
- **Responsive Design**: Optimized for all device sizes
- **Single Product Views**: Detailed product pages with full specifications

### 💰 Multi-Currency Support
- **Currency Overlay**: Interactive currency selection interface
- **Real-time Conversion**: Dynamic price updates
- **Global Support**: Multiple currency options

### 🔐 Complete Checkout Process
- **Multi-Step Workflow**: Guided checkout experience
- **Order Management**: Complete order processing system
- **Form Validation**: Comprehensive input validation

## 🛠️ Technical Implementation

### Architecture
- **React Components**: Modular component architecture
- **Firebase Integration**: Cloud database for data persistence
- **Responsive CSS**: Custom styling with mobile-first approach
- **Route Management**: Complete routing system for all pages

### Component Structure
- **Core UI**: Centralized styling system
- **Reusable Components**: Modular cart and UI components
- **Route-Based Organization**: Dedicated components for each page
- **Helper Utilities**: Location reset and utility functions

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- Modern web browser

## 🚀 Quick Start

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

### Development
```bash
npm start          # Start development server
npm test           # Run test suite in watch mode
npm run build      # Create production build
npm run eject      # Eject from Create React App (irreversible)
```

### Script Details

| Command | Description |
|---------|-------------|
| `npm start` | Launches development server on port 3000 with hot reload |
| `npm test` | Runs Jest test runner in interactive watch mode |
| `npm run build` | Creates optimized production build in `/build` folder |
| `npm run eject` | **⚠️ One-way operation** - Exposes all configuration files |

## 🔧 Dependencies

### Core Dependencies
- **React** - Frontend framework
- **React Router** - Client-side routing
- **Firebase** - Backend services and database
- **UUID** - Unique identifier generation

### Development Tools
- Create React App - Build toolchain and development environment
- Jest - Testing framework
- Web Vitals - Performance monitoring

## 🏗️ Project Structure

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
│   │   ├── not-found/
│   │   ├── order/
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

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
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

## 🔗 Links

- **Repository**: [GitHub](https://github.com/HelloQATeam123/PullRequestTesting)
- **Issues**: [Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)

---

**Built with ❤️ using React and Firebase**
