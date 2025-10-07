![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue)](https://pullrequesttesting.vercel.app/)
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
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔐 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive validation to ensure data accuracy
- **Error Prevention**: Client-side validation reduces checkout errors

## 🛠️ Technical Implementation

### Architecture & Development
- **React Components**: Modular component architecture with reusable UI elements
- **State Management**: Custom cart logic with persistent storage
- **Form Validation**: Robust client-side validation system
- **Firebase Integration**: Cloud database for data persistence
- **Responsive CSS**: Custom styling with mobile-first approach

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- Modern web browser

## 🚀 Quick Start

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

### Production Build
The `npm run build` command creates an optimized production build in the `build` folder, ready for deployment.

## 🔧 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Cart overlay functionality
│   ├── currency-overlay/ # Currency selection
│   └── header/         # Navigation header
├── routes/             # Page components
│   ├── all-products/   # Product catalog
│   ├── cart/          # Shopping cart
│   ├── checkout/      # Checkout process
│   └── single-product/ # Product details
├── core-ui/           # Global styles and CSS
├── data/              # Product data
├── database/          # Firebase configuration
└── helpers/           # Utility functions
```

## 🚀 Deployment

This project is optimized for deployment on platforms like:
- Vercel (recommended)
- Netlify
- GitHub Pages
- Any static hosting service

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Database powered by [Firebase](https://firebase.google.com/)

---

**[Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)** | **[Request Feature](https://github.com/HelloQATeam123/PullRequestTesting/issues)**
