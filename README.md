![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A modern, full-featured e-commerce platform built with React, offering a seamless shopping experience with over 150 women's clothing products. The application features dynamic product attributes, real-time cart management, and multi-currency support.

## 🌟 Key Features

### Cart Management
- **Dynamic Product Management**: Add, remove, and update product quantities in real-time
- **Cart Overlay**: Quick-access cart summary without leaving your current page
- **Detailed Product Information**: View selected attributes (size, color) for each cart item
- **Persistent Cart State**: Cart data maintained throughout your shopping session

### Shopping Experience
- **Category Filtering**: Browse products by category for efficient navigation
- **Flexible Shopping Flow**: Add products from both category and individual product pages
- **Attribute Validation**: Required attributes (size, color) must be selected before adding to cart
- **Intuitive Interface**: User-friendly design optimized for conversion

### Multi-Currency Support
Support for multiple international currencies including:
- EUR (Euro)
- GBP (British Pound)
- AUD (Australian Dollar)
- JPY (Japanese Yen)
- And more

### Secure Checkout
- **Multi-Step Process**: Guided checkout flow for improved user experience
- **Form Validation**: Comprehensive validation to ensure data accuracy
- **Error Prevention**: Real-time feedback to minimize user errors

## 🎯 Technical Achievements

- Implemented React Class components with subsequent refactoring to modern Hooks
- Developed complex state management for product attributes and cart functionality
- Integrated comprehensive form validation system
- Utilized Firebase/Firestore for external data persistence
- Responsive design optimized for all device sizes

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher recommended)
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

## 📜 Available Scripts

### `npm start`
Launches the development server at [http://localhost:3000](http://localhost:3000) with hot-reloading enabled.

### `npm test`
Runs the test suite in interactive watch mode. See [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Creates an optimized production build in the `build` folder. The build is minified and includes hashed filenames for cache optimization.

### `npm run eject`
**⚠️ Warning: This is a one-way operation!**

Ejects from Create React App, giving you full control over configuration files. Only use if you need custom configuration beyond what Create React App provides.

## 🛠️ Technology Stack

### Core Technologies
- **React** - Frontend framework
- **React Router** - Client-side routing
- **Firebase/Firestore** - Backend and database services

### Dependencies
- [React Router](https://www.npmjs.com/package/react-router-dom) - Declarative routing for React
- [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) - Image carousel component
- [uuid](https://www.npmjs.com/package/uuid) - Unique identifier generation
- [Firestore](https://firebase.google.com/docs/firestore) - Cloud-hosted NoSQL database

## 📁 Project Structure

```
PullRequestTesting/
├── src/
│   ├── assets/
│   │   └── images/         # Project images and static assets
│   ├── components/         # Reusable React components
│   │   ├── attributes/     # Product attribute components
│   │   ├── cart-overlay/   # Cart overlay functionality
│   │   ├── currency-overlay/ # Currency selection components
│   │   └── header/         # Header navigation components
│   ├── core-ui/           # Global styles and responsive design
│   ├── data/              # Static product data
│   ├── database/          # Firebase configuration
│   ├── helpers/           # Utility helper functions
│   └── routes/            # Page components and routing
│       ├── all-products/  # Product listing pages
│       ├── cart/          # Shopping cart page
│       ├── checkout/      # Checkout process
│       ├── landing/       # Home page
│       ├── not-found/     # 404 error page
│       ├── order/         # Order confirmation
│       └── single-product/ # Individual product pages
├── public/                # Public assets and HTML template
└── package.json          # Project dependencies and scripts
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **Live Demo**: [https://shopping-time.vercel.app/](https://shopping-time.vercel.app/)
- **Repository**: [https://github.com/HelloQATeam123/PullRequestTesting](https://github.com/HelloQATeam123/PullRequestTesting)

---

**Built with Create React App** - This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
