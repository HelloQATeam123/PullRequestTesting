# PullRequestTesting

![PullRequestTesting](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

## Overview

PullRequestTesting is a modern e-commerce web application featuring comprehensive product management with customization options. Built with React, this application provides a seamless shopping experience with dynamic product attributes, cart management, and multi-currency support.

## Key Features

### 🛒 Cart Management
- **Add/Remove Products**: Intuitive product addition and removal with real-time cart updates
- **Quantity Control**: Flexible quantity adjustment for all cart items with ChangeCartItemQuantity component
- **Cart Overlay**: Quick cart preview without leaving the current page
- **Success Notifications**: User feedback through SuccessMessage component

### 🔍 Product Discovery
- **Category Filtering**: Efficient product browsing by category
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Selection**: Dynamic product attributes with comprehensive selection options
- **Single Product Views**: Detailed product pages with full customization

### 💰 Currency Support
- **Multi-currency Overlay**: Dedicated currency selection interface
- **Global Accessibility**: Tailored shopping experience for international customers

### ✅ Secure Checkout
- **Multi-step Process**: Guided checkout flow with dedicated checkout route
- **Order Management**: Complete order processing and confirmation system
- **Form Validation**: Comprehensive input validation throughout the application

## Technical Implementation

### Architecture
- **Frontend**: React with component-based architecture
- **State Management**: Custom cart logic with attribute selection
- **Data Persistence**: Firebase Firestore integration
- **Routing**: React Router with dedicated routes for all major features

### Component Structure
- **Core Components**: AddToCartButton, ChangeCartItemQuantity, SuccessMessage
- **Specialized Modules**: Attributes, Cart Overlay, Currency Overlay, Header
- **Route Components**: All Products, Cart, Checkout, Landing, Single Product, Order, Not Found

## Getting Started

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

3. **Start development server**
   ```bash
   npm start
   ```

4. **Open application**
   Navigate to [http://localhost:3000](http://localhost:3000) in your browser

## Available Scripts

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
- Opens [http://localhost:3000](http://localhost:3000)
- Hot reload enabled
- Lint errors displayed in console

### Production Build
```bash
npm run build
```
- Optimized production build in `build/` folder
- Minified and hashed filenames
- Ready for deployment

## Project Structure

```
src/
├── components/          # Reusable UI components
├── routes/             # Page-level route components
├── core-ui/            # Styling and responsive design
├── data/               # Static data and product information
├── database/           # Firebase configuration
├── helpers/            # Utility functions
└── assets/             # Static assets and images
```

## Dependencies

### Core Dependencies
- **React** - Frontend framework
- **React Router** - Client-side routing
- **Firebase Firestore** - Cloud database solution

### Development Stack
- **Create React App** - Build toolchain
- **Firebase** - Backend services

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Database powered by [Firebase](https://firebase.google.com/)

---

**Project Status**: Active Development | **Last Updated**: 2024
