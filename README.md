![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform built with React, featuring comprehensive shopping cart functionality and multi-currency support for women's clothing products.

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
- **Localized Experience**: Tailored shopping experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided, user-friendly checkout flow
- **Form Validation**: Comprehensive input validation for data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🛠️ Technical Implementation

### Architecture & Development
- **Component-Based Architecture**: Modular React components for maintainability
- **State Management**: Custom cart logic with attribute selection and validation
- **Data Persistence**: Firebase integration for external data storage
- **Form Handling**: Robust validation system for checkout process

### Built With
- **Frontend**: React with modern Hooks and functional components
- **Routing**: React Router for seamless navigation
- **Database**: Firebase Firestore for data persistence
- **Styling**: Responsive CSS with mobile-first approach
- **Build Tool**: Create React App for development and production builds

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
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | **One-way operation** - Ejects from Create React App |

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
- Optimized production build in `build` folder
- Minified files with hash names
- Ready for deployment

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Cart overlay functionality
│   ├── currency-overlay/ # Currency selection
│   ├── header/         # Navigation header
│   └── attributes/     # Product attribute components
├── routes/             # Page components
│   ├── all-products/   # Product listing page
│   ├── single-product/ # Product detail page
│   ├── cart/          # Shopping cart page
│   ├── checkout/      # Checkout process
│   └── order/         # Order confirmation
├── core-ui/           # Global styles and CSS
├── data/              # Static product data
├── database/          # Firebase configuration
└── helpers/           # Utility functions
```

## 🔧 Dependencies

### Core Dependencies
- **React Router** - Client-side routing and navigation
- **Firebase Firestore** - Cloud database for data persistence
- **UUID** - Unique identifier generation for cart items

### Development Dependencies
- Create React App toolchain
- ESLint for code quality
- Testing utilities

## 🚀 Deployment

For deployment:
1. Run `npm run build`
2. Deploy the `build` folder to your hosting service
3. Configure environment variables for Firebase

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
