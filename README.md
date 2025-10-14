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
- **Global Currency Options**: Support for multiple currencies with dedicated currency overlay
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Tailored shopping experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided, user-friendly checkout flow
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Order Management**: Complete order processing and confirmation system

## 🛠️ Technical Stack

- **Frontend**: React 18.x with modern component architecture
- **Routing**: React Router DOM for seamless navigation
- **Database**: Firebase Firestore for data persistence
- **Styling**: CSS3 with modular styling approach (core-ui directory)
- **Build Tool**: Create React App
- **State Management**: React Hooks and component-based state

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── AddToCartButton.js
│   ├── ChangeCartItemQuantity.js
│   ├── SuccessMessage.js
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Cart preview functionality
│   ├── currency-overlay/ # Currency selection
│   └── header/          # Navigation components
├── routes/              # Page-level components
│   ├── all-products/    # Product catalog
│   ├── cart/           # Shopping cart page
│   ├── checkout/       # Checkout process
│   ├── landing/        # Home page
│   ├── single-product/ # Product details
│   └── order/          # Order confirmation
├── core-ui/            # Global styles and responsive design
├── data/               # Static product data
├── database/           # Firebase configuration
└── helpers/            # Utility functions
```

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
| `npm start` | Runs the app in development mode on [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | **One-way operation** - Ejects from Create React App |

## 🎯 Development Goals Achieved

- ✅ **React Mastery**: Implemented modern React patterns with hooks and functional components
- ✅ **State Management**: Complex cart logic with attribute selection and quantity management
- ✅ **Form Validation**: Comprehensive input validation and error handling
- ✅ **External Data Persistence**: Firebase integration for data storage
- ✅ **Responsive Design**: Mobile-first approach with modular CSS architecture
- ✅ **Performance Optimization**: Efficient rendering and state updates
- ✅ **Component Architecture**: Well-organized, reusable component structure

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 📞 Support

If you have any questions or need help with setup, please open an issue in the GitHub repository.

---

**Built with ❤️ using React and Firebase**
