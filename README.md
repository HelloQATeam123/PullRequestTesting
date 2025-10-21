![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive e-commerce platform built with React, featuring comprehensive shopping cart functionality and multi-currency support for women's clothing products.

## 🚀 Live Demo

Visit the live application: [Shopping Time](https://pullrequesttesting.vercel.app/)

## ✨ Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality
- **Quantity Control**: Adjust product quantities directly from the cart using ChangeCartItemQuantity component
- **Cart Overlay**: Real-time cart preview without page navigation
- **Product Attributes**: Detailed product information including size, color, and specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories
- **Dual Shopping Interface**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Success Notifications**: User feedback through SuccessMessage component

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies with currency overlay
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Tailored shopping experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided, user-friendly checkout flow
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🛠️ Technology Stack

- **Frontend**: React 18.x with Hooks
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with responsive design and custom UI components
- **Build Tool**: Create React App
- **Testing**: Jest and React Testing Library

## 📋 Prerequisites

Before running this project, ensure you have:

- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
- Git

## 🚀 Getting Started

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
- Enables hot reloading for development
- Displays lint errors in the console

### Production Build
```bash
npm run build
```
- Creates optimized production build in `build/` folder
- Minifies code and includes content hashes
- Ready for deployment

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── AddToCartButton.js
│   ├── ChangeCartItemQuantity.js
│   ├── SuccessMessage.js
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Cart overlay functionality
│   ├── currency-overlay/ # Currency selection
│   └── header/          # Header components
├── routes/              # Page components
│   ├── all-products/    # Product listing page
│   ├── cart/           # Shopping cart page
│   ├── checkout/       # Checkout process
│   ├── landing/        # Home page
│   ├── single-product/ # Product detail page
│   └── order/          # Order confirmation
├── core-ui/            # Global styles
├── data/               # Static data
├── database/           # Firebase configuration
└── helpers/            # Utility functions
```

## 🎯 Project Goals & Achievements

- ✅ **React Mastery**: Implemented modern React patterns with Hooks
- ✅ **Component Architecture**: Modular, reusable component structure
- ✅ **State Management**: Complex cart logic with attribute selection
- ✅ **Form Validation**: Comprehensive input validation system
- ✅ **External Data**: Firebase integration for persistent data storage
- ✅ **Responsive Design**: Mobile-first, cross-device compatibility
- ✅ **Performance**: Optimized build with code splitting

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 📞 Support

If you have any questions or need help with the project, please open an issue on GitHub.

---

**Made with ❤️ by the Development Team**
