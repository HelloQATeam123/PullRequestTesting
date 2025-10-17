![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

**Live Demo:** [View Application](https://pullrequesttesting.vercel.app/)

A modern, responsive e-commerce platform built with React, featuring over 150 women's clothing products with comprehensive shopping cart functionality and multi-currency support.

## 🚀 Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality
- **Quantity Control**: Adjust product quantities directly from the cart
- **Cart Overlay**: Real-time cart preview without leaving the current page
- **Product Attributes**: View detailed product information including size, color, and other specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories for targeted shopping
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection (size, color) before adding to cart
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Shopping**: Enhanced experience for international customers

### 🔐 Secure Checkout Process
- **Multi-step Checkout**: Guided, user-friendly checkout flow
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Error Prevention**: Built-in safeguards to minimize checkout errors

## 🎯 Technical Objectives

This project demonstrates proficiency in:
- **React Development**: Implementation of both class components and modern hooks
- **State Management**: Complex cart logic and attribute selection handling
- **Form Validation**: Client-side validation with user feedback
- **External Data Integration**: Firebase integration for data persistence
- **Responsive Design**: Mobile-first approach with cross-device compatibility

## 🛠️ Technology Stack

### Frontend
- **React** - Component-based UI library
- **React Router** - Client-side routing
- **React Hooks** - Modern state management
- **CSS3** - Responsive styling

### Backend & Services
- **Firebase Firestore** - NoSQL database for product and user data
- **Vercel** - Deployment and hosting platform

### Development Tools
- **Create React App** - Project bootstrapping and build tools
- **npm** - Package management

## 🚀 Getting Started

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

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode on [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | **One-way operation** - Ejects from Create React App configuration |

> **Note:** Only use `npm run eject` if you need full control over the build configuration. This action cannot be undone.

## 📦 Dependencies

| Package | Purpose | Documentation |
|---------|---------|---------------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing | [Docs](https://reactrouter.com/) |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image carousel | [NPM](https://www.npmjs.com/package/react-simple-image-slider) |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation | [NPM](https://www.npmjs.com/package/uuid) |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | NoSQL database | [Docs](https://firebase.google.com/docs/firestore) |

## 🏗️ Project Structure

```
PullRequestTesting/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── AddToCartButton.js
│   │   ├── ChangeCartItemQuantity.js
│   │   ├── SuccessMessage.js
│   │   ├── attributes/
│   │   ├── cart-overlay/
│   │   ├── currency-overlay/
│   │   └── header/
│   ├── routes/
│   │   ├── all-products/
│   │   ├── cart/
│   │   ├── checkout/
│   │   ├── landing/
│   │   ├── not-found/
│   │   ├── order/
│   │   └── single-product/
│   ├── assets/
│   ├── core-ui/
│   ├── data/
│   ├── database/
│   ├── helpers/
│   └── App.js
├── package.json
└── README.md
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 🔗 Links

- **Repository**: [GitHub](https://github.com/HelloQATeam123/PullRequestTesting)
- **Issues**: [Report a Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)

---

**Built with ❤️ using React and Firebase**
