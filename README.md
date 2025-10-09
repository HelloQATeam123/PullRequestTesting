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
- **Success Notifications**: User feedback through SuccessMessage component

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories for targeted shopping
- **Flexible Shopping Flow**: Add products from both category pages and individual product pages
- **Attribute Selection**: Comprehensive product attributes management through dedicated attribute components

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple currencies with dedicated currency overlay interface
- **Real-time Currency Conversion**: Seamless shopping experience for international customers

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided checkout flow with dedicated checkout route
- **Order Management**: Complete order processing with dedicated order confirmation pages
- **Form Validation**: Comprehensive input validation to ensure data accuracy

## 🎯 Technical Achievements

- **React Architecture**: Modern React implementation with component-based architecture
- **State Management**: Complex cart logic with attribute selection and validation
- **Routing**: Multi-page application with React Router implementation
- **External Data Integration**: Firebase integration for data persistence
- **Responsive Design**: Mobile-first responsive design approach

## 🛠️ Technology Stack

- **Frontend**: React.js
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with modular styling approach (core-ui directory)
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
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Shopping cart overlay
│   ├── currency-overlay/# Currency selection
│   └── header/          # Navigation header
├── routes/              # Page-level components
│   ├── all-products/    # Product catalog
│   ├── cart/            # Shopping cart page
│   ├── checkout/        # Checkout process
│   ├── landing/         # Homepage
│   ├── order/           # Order confirmation
│   └── single-product/  # Product details
├── core-ui/             # Global styles and responsive design
├── data/                # Static data and product information
├── database/            # Firebase configuration
└── helpers/             # Utility functions
```

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
