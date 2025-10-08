![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive e-commerce platform built with React, featuring over 150 women's clothing products with comprehensive shopping cart functionality and multi-currency support.

## 🚀 Live Demo

Visit the live application: [Shopping Time](https://pullrequesttesting.vercel.app/)

## ✨ Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamlessly add items to cart with one-click functionality
- **Quantity Control**: Adjust product quantities directly from the cart
- **Cart Overlay**: Real-time cart preview without page navigation
- **Product Attributes**: Detailed product information including size, color, and specifications

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories
- **Multi-page Shopping**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔐 Secure Checkout Process
- **Multi-step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Error Handling**: User-friendly error messages and recovery options

## 🛠️ Technical Stack

- **Frontend**: React 18.x with Hooks and Class Components
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with responsive design
- **Build Tool**: Create React App
- **Deployment**: Vercel

## 📋 Prerequisites

Before running this project, ensure you have the following installed:

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

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Firestore Database
   - Add your Firebase configuration to the project

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode on [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | **One-way operation** - Ejects from Create React App |

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
│   │   └── images/
│   ├── core-ui/
│   ├── data/
│   ├── database/
│   ├── helpers/
│   └── App.js
├── package.json
└── README.md
```

## 🔧 Dependencies

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Declarative routing for React
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Lightweight image carousel component
- **[UUID](https://www.npmjs.com/package/uuid)** - RFC4122 UUID generator
- **[Firebase](https://firebase.google.com/docs/firestore)** - Backend-as-a-Service platform

## 🎯 Development Goals Achieved

- ✅ **React Mastery**: Implemented both Class Components and Hooks patterns
- ✅ **State Management**: Complex cart logic with attribute selection
- ✅ **Form Validation**: Comprehensive input validation and error handling
- ✅ **External Data Persistence**: Firebase integration for data storage
- ✅ **Responsive Design**: Mobile-first approach with cross-device compatibility
- ✅ **Performance Optimization**: Code splitting and lazy loading implementation

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

**Made with ❤️ by the Development Team**
