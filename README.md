![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive e-commerce platform built with React, featuring comprehensive shopping cart functionality and multi-currency support for women's clothing products.

## 🚀 Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality via AddToCartButton component
- **Quantity Control**: Adjust product quantities directly from the cart using ChangeCartItemQuantity component
- **Cart Overlay**: Real-time cart preview without leaving the current page
- **Success Notifications**: Visual feedback through SuccessMessage component for user actions

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories for targeted shopping
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding to cart to ensure order accuracy
- **Product Catalog**: Comprehensive product data management through all-products.js

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies with dedicated currency overlay interface
- **Real-time Currency Conversion**: Seamless shopping experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided, user-friendly checkout flow with dedicated checkout route
- **Order Management**: Complete order processing and confirmation system
- **Form Validation**: Comprehensive input validation to ensure data accuracy

## 🎯 Technical Achievements

- **React Architecture**: Modern React implementation with component-based architecture
- **State Management**: Complex cart logic with attribute selection and validation
- **Routing**: Multi-page application with React Router (landing, products, cart, checkout, orders)
- **External Data Persistence**: Firebase integration for data storage and retrieval
- **Responsive Design**: Mobile-first approach with dedicated responsive CSS

## 🛠️ Technology Stack

- **Frontend**: React.js
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with modular styling (core-ui directory)
- **Build Tool**: Create React App
- **Testing**: Jest with React Testing Library

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
| `npm run build` | Builds the app for production with optimized performance |
| `npm run eject` | **⚠️ One-way operation** - Ejects from Create React App configuration |

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Cart preview functionality
│   ├── currency-overlay/ # Currency selection
│   ├── header/         # Navigation header
│   └── attributes/     # Product attribute selection
├── routes/             # Page-level components
│   ├── landing/        # Home page
│   ├── all-products/   # Product catalog
│   ├── single-product/ # Product details
│   ├── cart/           # Shopping cart
│   ├── checkout/       # Checkout process
│   └── order/          # Order confirmation
├── core-ui/            # Global styles and responsive design
├── data/               # Static product data
├── database/           # Firebase configuration
└── helpers/            # Utility functions
```

## 📚 Dependencies

### Core Dependencies
- **React Router DOM** - Client-side routing for multi-page navigation
- **Firebase Firestore** - Cloud database solution for data persistence
- **React Testing Library** - Component testing utilities

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 🔗 Links

- **Repository**: [https://github.com/HelloQATeam123/PullRequestTesting](https://github.com/HelloQATeam123/PullRequestTesting)

---

<div align="center">
  <p>Built with ❤️ using React</p>
</div>
