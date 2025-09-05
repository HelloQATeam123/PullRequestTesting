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
- **Localized Shopping**: Tailored experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided, user-friendly purchase flow
- **Form Validation**: Comprehensive input validation for data accuracy
- **Order Management**: Complete order processing and confirmation

## 🛠 Technical Stack

- **Frontend**: React 18.x with Hooks and Class Components
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with responsive design and hover effects
- **State Management**: React Context and Component State
- **Testing**: Jest and React Testing Library

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- Firebase account (for database functionality)

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

3. **Configure Firebase**
   - Create a Firebase project
   - Add your Firebase configuration to `src/database/firebase.js`
   - Enable Firestore database

4. **Start the development server**
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

## 🏗 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── AddToCartButton.js
│   ├── ChangeCartItemQuantity.js
│   ├── SuccessMessage.js
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Shopping cart overlay
│   ├── currency-overlay/ # Currency selection
│   └── header/          # Navigation header
├── routes/              # Page components
│   ├── all-products/    # Product catalog
│   ├── cart/           # Shopping cart page
│   ├── checkout/       # Checkout process
│   ├── landing/        # Home page
│   ├── order/          # Order confirmation
│   └── single-product/ # Product details
├── core-ui/            # Global styles
├── data/               # Static product data
├── database/           # Firebase configuration
└── helpers/            # Utility functions
```

## 🎯 Development Goals Achieved

- ✅ **React Architecture**: Implemented both class components and functional components with hooks
- ✅ **State Management**: Complex cart logic with attribute selection
- ✅ **Form Validation**: Comprehensive input validation and error handling
- ✅ **External Data Persistence**: Firebase integration for data storage
- ✅ **Responsive Design**: Mobile-first approach with cross-device compatibility
- ✅ **Component Reusability**: Modular component architecture
- ✅ **Route Management**: Multi-page application with React Router

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 📞 Contact

For questions or support, please open an issue on GitHub.

---

**Built with ❤️ using React and Firebase**
