![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive e-commerce platform built with React, featuring comprehensive shopping cart functionality and multi-currency support for women's clothing products.

## 🚀 Live Demo

Visit the live application: [pullrequesttesting.vercel.app](https://pullrequesttesting.vercel.app/)

## ✨ Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality
- **Quantity Control**: Adjust product quantities directly from the cart using ChangeCartItemQuantity component
- **Cart Overlay**: Real-time cart preview without page navigation
- **Success Notifications**: Visual feedback with SuccessMessage component

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Selection**: Comprehensive product attributes with validation
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Currency Overlay**: Easy currency switching with dedicated overlay component

### 🔐 Secure Checkout Process
- **Multi-step Checkout**: Guided, user-friendly checkout flow
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🛠️ Technical Stack

- **Frontend**: React 18.x with modern component architecture
- **Routing**: React Router DOM for single-page application navigation
- **Database**: Firebase Firestore for real-time data storage
- **Styling**: CSS3 with modular styling approach (core-ui directory)
- **Build Tool**: Create React App
- **State Management**: React Hooks and component-based state

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/HelloQATeam123/PullRequestTesting.git
   cd PullRequestTesting
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Firebase**
   - Create a Firebase project
   - Add your Firebase configuration to `src/database/firebase.js`
   - Enable Firestore database

4. **Start development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production |
| `npm run eject` | Ejects from Create React App (⚠️ irreversible) |

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── AddToCartButton.js
│   ├── ChangeCartItemQuantity.js
│   ├── SuccessMessage.js
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Shopping cart overlay
│   ├── currency-overlay/ # Currency selection overlay
│   └── header/          # Navigation header
├── core-ui/            # Global styles and responsive design
├── data/               # Static product data
├── database/           # Firebase configuration
├── helpers/            # Utility functions
└── routes/             # Page components and routing
    ├── all-products/
    ├── cart/
    ├── checkout/
    ├── landing/
    ├── single-product/
    └── order/
```

## 🎯 Development Goals Achieved

- ✅ **Component Architecture**: Modular component structure with reusable elements
- ✅ **State Management**: Complex cart logic with quantity management
- ✅ **Form Validation**: Comprehensive checkout and attribute validation
- ✅ **External Data**: Firebase integration for persistent data storage
- ✅ **Responsive Design**: Mobile-first approach with dedicated responsive CSS
- ✅ **User Experience**: Overlay components for seamless interactions

## 📚 Key Components

### Core Components
- **AddToCartButton**: Handles product addition to shopping cart
- **ChangeCartItemQuantity**: Manages cart item quantity updates
- **SuccessMessage**: Provides user feedback for successful actions

### Overlay Systems
- **Cart Overlay**: Real-time cart management without page refresh
- **Currency Overlay**: Multi-currency selection interface
- **Header**: Navigation and user interface elements

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Workflow
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Database powered by [Firebase](https://firebase.google.com/)
- Responsive design with custom CSS architecture

---

**E-commerce Platform Testing Repository**
