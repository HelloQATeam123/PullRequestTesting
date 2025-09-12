![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform featuring over 150 women's clothing products with comprehensive shopping cart functionality and multi-currency support.

## 🚀 Features

### 🛒 Shopping Cart Management
- **Product Management**: Seamlessly add, remove, and modify product quantities
- **Real-time Updates**: Dynamic cart overlay with instant item tracking
- **Attribute Validation**: Comprehensive product attribute selection (size, color, etc.)
- **Persistent Storage**: Cart data maintained across sessions using Firebase

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Intuitive product categorization and filtering system
- **Flexible Navigation**: Add products from both category and individual product pages
- **Attribute Requirements**: Mandatory attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop and mobile devices

### 💰 Multi-Currency Support
- **Global Accessibility**: Support for multiple currencies (EUR, GBP, AUD, JPY, USD)
- **Real-time Conversion**: Dynamic currency switching throughout the shopping experience
- **Localized Pricing**: Currency-appropriate formatting and display

### 🔐 Secure Checkout Process
- **Multi-step Workflow**: Guided checkout process with clear progress indicators
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Error Prevention**: Client-side validation reduces checkout errors

## 🛠️ Technical Implementation

### Architecture
- **Frontend Framework**: React 18.x with modern hooks implementation
- **State Management**: Context API for global state management
- **Routing**: React Router for seamless navigation
- **Data Persistence**: Firebase Firestore for real-time data storage

### Development Approach
- **Component Evolution**: Initially built with class components, refactored to functional components with hooks
- **Modular Design**: Reusable components for scalable architecture
- **Performance Optimization**: Lazy loading and code splitting implementation

## 📋 Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn package manager
- Firebase account (for data persistence)

## 🚀 Quick Start

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
   - Add your Firebase configuration to the project
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

### Development Mode
```bash
npm start
```
- Opens [http://localhost:3000](http://localhost:3000) in your browser
- Enables hot reloading for development
- Displays lint errors in the console

### Production Build
```bash
npm run build
```
- Creates optimized production build in `build/` folder
- Minifies code and includes content hashes
- Ready for deployment to any static hosting service

### Testing
```bash
npm test
```
- Runs tests in interactive watch mode
- See [Create React App testing documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information

## 🔧 Dependencies

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Declarative routing for React applications
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Lightweight image carousel component
- **[UUID](https://www.npmjs.com/package/uuid)** - RFC4122 UUID generator for unique identifiers
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - NoSQL document database for real-time data storage

### Development Tools
- **Create React App** - Zero-configuration React development environment
- **ESLint** - Code linting and formatting
- **Jest** - JavaScript testing framework

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

## 🙏 Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Icons and images from various open-source contributors

---

**[Report Bug](https://github.com/HelloQATeam123/PullRequestTesting/issues)** | **[Request Feature](https://github.com/HelloQATeam123/PullRequestTesting/issues)**
