![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shopping-time.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform built with React, featuring comprehensive shopping cart functionality, multi-currency support, and Firebase integration for data persistence.

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
- **React Components**: Modern component-based architecture
- **State Management**: Custom cart logic with attribute selection validation
- **Form Validation**: Client-side validation with user feedback
- **External Data Persistence**: Firebase integration for data storage
- **Responsive Design**: Mobile-first approach with CSS3

### Tech Stack
- **Frontend**: React with Create React App
- **Routing**: React Router DOM for client-side navigation
- **Database**: Firebase Firestore for data persistence
- **Styling**: CSS3 with responsive design patterns
- **Build Tool**: Webpack (via Create React App)

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

The application will be available at `http://localhost:3000`

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production deployment |
| `npm run eject` | Ejects from Create React App (⚠️ irreversible) |

### Development Mode
```bash
npm start
```
- Opens `http://localhost:3000` in your browser
- Hot reload enabled for real-time development
- Console displays lint errors and warnings

### Production Build
```bash
npm run build
```
- Creates optimized production build in `build/` folder
- Minified and optimized for best performance
- Ready for deployment to any static hosting service

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── AddToCartButton.js
│   ├── ChangeCartItemQuantity.js
│   ├── SuccessMessage.js
│   ├── attributes/      # Product attribute components
│   ├── cart-overlay/    # Cart overlay functionality
│   ├── currency-overlay/# Currency selection
│   └── header/          # Header components
├── routes/              # Page components
│   ├── all-products/    # Product listing page
│   ├── cart/            # Shopping cart page
│   ├── checkout/        # Checkout process
│   ├── landing/         # Home page
│   ├── not-found/       # 404 page
│   ├── order/           # Order confirmation
│   └── single-product/  # Product detail page
├── core-ui/             # Global styles
├── data/                # Static data files
├── database/            # Firebase configuration
└── helpers/             # Utility functions
```

## 📚 Key Dependencies

| Package | Purpose | Documentation |
|---------|---------|---------------|
| React Router DOM | Client-side routing | [Docs](https://reactrouter.com/) |
| Firebase | Backend services & database | [Docs](https://firebase.google.com/docs) |
| React Testing Library | Component testing | [Docs](https://testing-library.com/docs/react-testing-library/intro/) |

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

---

**[Report Bug](../../issues)** | **[Request Feature](../../issues)**
