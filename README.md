<div align="center">

![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

**A Modern E-Commerce Platform for Women's Fashion**

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

[Live Demo](https://shopping-time.vercel.app/) • [Report Bug](../../issues) • [Request Feature](../../issues)

</div>

---

## Overview

Shopping Time is a full-featured e-commerce web application specializing in women's fashion, offering over 150 products with customizable attributes including size and color variations. The platform provides a seamless shopping experience with real-time cart management, multi-currency support, and a secure checkout process.

## Key Features

### 🛒 Cart Management
- **Dynamic Cart Operations**: Add, remove, and update product quantities in real-time
- **Cart Overlay**: Quick access to cart summary without leaving the current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item
- **Persistent Storage**: Cart data maintained across sessions using Firebase

### 🔍 Product Discovery
- **Category Filtering**: Browse products by organized categories
- **Flexible Shopping Flow**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding to cart
- **Comprehensive Product Details**: High-quality images and detailed specifications

### 💱 Multi-Currency Support
- Support for multiple currencies: EUR, GBP, AUD, JPY, and more
- Real-time currency conversion
- Localized pricing display

### ✅ Secure Checkout
- **Multi-Step Process**: Guided checkout flow for enhanced user experience
- **Form Validation**: Client-side validation ensuring data accuracy
- **Error Prevention**: Comprehensive validation to minimize checkout errors

## Technical Implementation

### Architecture
- Built with **React** (Class components refactored to Hooks)
- **Firebase Firestore** for data persistence
- **React Router** for navigation
- Responsive design for all device sizes

### Development Highlights
- Implemented complex state management for cart and product attributes
- Custom form validation logic
- Integration with external APIs for currency conversion
- Optimized performance with React best practices

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

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000)

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode at [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | Ejects from Create React App (⚠️ one-way operation) |

## Technology Stack

### Core Technologies
- **React** - UI library
- **React Router** - Client-side routing
- **Firebase Firestore** - Cloud database

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Declarative routing for React
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel component
- [UUID](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - NoSQL cloud database

## Project Structure

```
PullRequestTesting/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── assets/
│   │   └── images/
│   ├── components/
│   │   ├── AddToCartButton.js
│   │   ├── ChangeCartItemQuantity.js
│   │   ├── SuccessMessage.js
│   │   ├── attributes/
│   │   ├── cart-overlay/
│   │   ├── currency-overlay/
│   │   └── header/
│   ├── core-ui/
│   │   ├── hovers.css
│   │   ├── responsive.css
│   │   └── styles.css
│   ├── data/
│   │   └── all-products.js
│   ├── database/
│   │   └── firebase.js
│   ├── helpers/
│   │   └── ResetLocation.js
│   ├── routes/
│   │   ├── all-products/
│   │   ├── cart/
│   │   ├── checkout/
│   │   ├── landing/
│   │   ├── not-found/
│   │   ├── order/
│   │   └── single-product/
│   └── App.js
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Product images and data sourced from various fashion retailers
- Inspired by modern e-commerce best practices

---

<div align="center">

**[⬆ back to top](#shopping-time)**

Made with ❤️ by [HelloQATeam123](https://github.com/HelloQATeam123)

</div>
