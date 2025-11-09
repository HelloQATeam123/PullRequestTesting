# 🛍️ Shopping Time - E-Commerce Platform

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen.svg)](https://shopping-time.vercel.app/)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue.svg)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange.svg)](https://firebase.google.com/)

A modern, responsive e-commerce platform built with React and Firebase, featuring a comprehensive shopping cart system, multi-currency support, and seamless checkout experience.

## 🚀 Features

### 🛒 Shopping Cart Management
- **Dynamic Cart Operations**: Add, remove, and modify product quantities in real-time
- **Cart Persistence**: Shopping cart state maintained across browser sessions
- **Cart Overlay**: Quick access to cart contents without page navigation
- **Product Attributes**: Full support for size, color, and variant selection

### 🏪 Product Catalog
- **Extensive Inventory**: 150+ women's clothing products with multiple variants
- **Category Filtering**: Intuitive product categorization and filtering system
- **Product Details**: Comprehensive product pages with image galleries
- **Attribute Selection**: Required attribute selection before cart addition

### 💰 Multi-Currency Support
- **Global Commerce**: Support for EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Dynamic currency switching throughout the application
- **Localized Pricing**: Currency-appropriate formatting and display

### 🔒 Secure Checkout
- **Multi-Step Process**: Guided checkout flow with progress indicators
- **Form Validation**: Comprehensive client-side validation for all user inputs
- **Order Management**: Complete order processing and confirmation system

### 📱 Responsive Design
- **Mobile-First**: Optimized for all device sizes and screen resolutions
- **Cross-Browser**: Compatible with all modern web browsers
- **Performance**: Optimized loading times and smooth user interactions

## 🛠️ Built With

- **Frontend Framework**: React 18.x with Hooks
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Authentication**: Firebase Auth
- **Styling**: CSS3 with responsive design
- **Build Tool**: Create React App
- **Deployment**: Vercel

## 📦 Installation

### Prerequisites
- Node.js (v14.0.0 or higher)
- npm or yarn package manager
- Firebase account for backend services

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure Firebase**
   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Firestore Database and Authentication
   - Copy your Firebase configuration
   - Create a `.env` file in the root directory:
   ```env
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   ```

4. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## 📜 Available Scripts

### Development
```bash
npm start          # Start development server
npm test           # Run test suite in watch mode
npm run build      # Create production build
npm run eject      # Eject from Create React App (irreversible)
```

### Production
```bash
npm run build      # Build for production
npm run serve      # Serve production build locally
```

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart/           # Shopping cart components
│   ├── product/        # Product-related components
│   └── checkout/       # Checkout process components
├── pages/              # Main application pages
├── hooks/              # Custom React hooks
├── services/           # API and Firebase services
├── utils/              # Utility functions
├── styles/             # Global styles and themes
└── assets/             # Static assets (images, icons)
```

## 🔧 Key Dependencies

- **react**: ^18.2.0 - Core React library
- **react-router-dom**: ^6.x - Client-side routing
- **firebase**: ^9.x - Backend services
- **react-simple-image-slider**: Image carousel component
- **uuid**: Unique identifier generation

## 🤝 Contributing

We welcome contributions to improve Shopping Time! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow React best practices and hooks patterns
- Maintain consistent code formatting
- Add tests for new features
- Update documentation as needed
- Ensure responsive design compatibility

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- Built with Create React App for rapid development setup
- Firebase for providing robust backend infrastructure
- React community for excellent documentation and resources

## 📞 Contact & Support

- **Project Repository**: [GitHub](https://github.com/HelloQATeam123/PullRequestTesting)
- **Live Demo**: [Shopping Time](https://shopping-time.vercel.app/)
- **Issues**: Please report bugs and feature requests through GitHub Issues

---

⭐ **Star this repository if you find it helpful!**
