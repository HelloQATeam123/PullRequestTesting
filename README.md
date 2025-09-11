![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform featuring comprehensive shopping cart functionality, multi-currency support, and seamless user experience.

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
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🛠️ Technical Implementation

### Architecture & Development
- **React Components**: Modern component-based architecture
- **State Management**: Custom cart logic with attribute selection validation
- **Firebase Integration**: Cloud database for data persistence
- **Responsive UI**: Mobile-first design approach
- **Form Validation**: Client-side validation system

### Key Components
- **AddToCartButton**: Handles product addition with attribute validation
- **ChangeCartItemQuantity**: Manages cart item quantity updates
- **Cart Overlay**: Real-time cart preview functionality
- **Currency Overlay**: Multi-currency selection interface

## 📋 Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn package manager
- Modern web browser with JavaScript enabled

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
| `npm run build` | Creates optimized production build in `/build` directory |
| `npm run eject` | **⚠️ One-way operation** - Exposes all configuration files |

## 🔧 Dependencies

### Core Dependencies
- **React Router** - Client-side routing and navigation
- **Firebase Firestore** - Cloud database solution
- **UUID** - Unique identifier generation

### Development Dependencies
- Create React App toolchain
- Jest testing framework
- ESLint code linting
- Babel transpilation

## 🏗️ Project Structure

```
PullRequestTesting/
├── public/
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
│   ├── helpers/
│   └── App.js
├── package.json
└── README.md
```

## 🌐 Deployment

The application can be deployed on various platforms including Vercel, Netlify, or traditional hosting services.

## 🧪 Testing

Run the test suite to ensure code quality:

```bash
npm test
```

Tests are located alongside components and use Jest testing framework.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 📞 Support

For support, please open an issue in the GitHub repository or contact the maintainer.

---

**Built with ❤️ using React and Firebase**
