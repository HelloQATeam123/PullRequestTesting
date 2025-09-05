![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue)](https://pullrequesttesting.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform featuring over 150 women's clothing products with comprehensive shopping cart functionality and multi-currency support.

## 🚀 Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality
- **Quantity Control**: Adjust product quantities directly from cart or overlay
- **Cart Overlay**: Real-time cart summary without page navigation
- **Product Attributes**: Detailed product information including size, color, and specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by category for targeted shopping
- **Flexible Shopping Flow**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive validation to ensure data accuracy
- **Error Prevention**: Client-side validation reduces checkout errors

## 🛠️ Technical Implementation

### Architecture & Development Goals
- **React Class Components**: Initial implementation using class-based components
- **Hooks Refactoring**: Migration to modern React hooks for improved performance
- **State Management**: Custom cart logic with attribute selection validation
- **External Data Persistence**: Firebase integration for data storage
- **Form Validation**: Comprehensive client-side validation system

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
| `npm start` | Runs the app in development mode with hot reloading |
| `npm test` | Launches the interactive test runner |
| `npm run build` | Builds optimized production bundle |
| `npm run eject` | Ejects from CRA configuration (⚠️ irreversible) |

## 🔧 Dependencies

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Product image carousel
- **[UUID](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - Cloud database

### Development Stack
- **React 18.x** - Frontend framework
- **Create React App** - Build toolchain
- **Firebase** - Backend services
- **CSS3** - Styling and responsive design

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
│   ├── assets/
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
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 🔗 Links

- **Live Demo**: [https://pullrequesttesting.vercel.app/](https://pullrequesttesting.vercel.app/)
- **Repository**: [https://github.com/HelloQATeam123/PullRequestTesting](https://github.com/HelloQATeam123/PullRequestTesting)

---

<div align="center">
  <p>Built with ❤️ using React</p>
</div>
