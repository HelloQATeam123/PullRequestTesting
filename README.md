# Shopping Time

![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

**Live Demo:** [View Application](https://pullrequesttesting.vercel.app/)

## Overview

Shopping Time is a modern e-commerce web application featuring over 150 women's clothing products with comprehensive customization options. Built with React, this application provides a seamless shopping experience with dynamic product attributes, cart management, and multi-currency support.

## Key Features

### 🛒 Cart Management
- **Add/Remove Products**: Intuitive product addition and removal with real-time cart updates
- **Quantity Control**: Flexible quantity adjustment for all cart items
- **Cart Overlay**: Quick cart preview without leaving the current page
- **Product Details**: Complete attribute information (size, color, etc.) displayed in cart

### 🔍 Product Discovery
- **Category Filtering**: Efficient product browsing by category
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents incomplete orders

### 💰 Currency Support
- **Multi-currency**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Global Accessibility**: Tailored shopping experience for international customers

### ✅ Secure Checkout
- **Multi-step Process**: Guided checkout flow for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Error Prevention**: Proactive validation to minimize checkout issues

## Technical Implementation

### Architecture
- **Frontend**: React with both Class Components and Hooks implementation
- **State Management**: Custom cart logic with attribute selection
- **Data Persistence**: Firebase Firestore integration
- **Validation**: Client-side form validation throughout the application

### Development Goals Achieved
- ✅ React Class Components implementation and Hooks refactoring
- ✅ Complex cart logic with product attribute management
- ✅ Comprehensive form validation system
- ✅ External data persistence with Firebase

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
| `npm run eject` | Ejects from Create React App (irreversible) |

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

## Dependencies

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Image carousel functionality
- **[UUID](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - Cloud database solution

### Development Stack
- **React** - Frontend framework
- **Create React App** - Build toolchain
- **Firebase** - Backend services

## Project Structure

```
PullRequestTesting/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── assets/
│   │   └── images/
│   ├── components/
│   │   ├── attributes/
│   │   ├── cart-overlay/
│   │   ├── currency-overlay/
│   │   └── header/
│   ├── core-ui/
│   ├── data/
│   ├── database/
│   ├── helpers/
│   └── routes/
│       ├── all-products/
│       ├── cart/
│       ├── checkout/
│       ├── landing/
│       ├── not-found/
│       ├── order/
│       └── single-product/
├── package.json
└── README.md
```

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

**Note**: This project was created for educational purposes to demonstrate React development skills and e-commerce functionality implementation.
