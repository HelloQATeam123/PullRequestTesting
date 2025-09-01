![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://pullrequesttesting.vercel.app/)
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
- **Form Validation**: Comprehensive client-side validation for data integrity
- **Error Prevention**: Robust validation prevents incomplete or incorrect orders

## 🛠️ Technical Implementation

### Architecture & Development Goals
- **Component Evolution**: Initially built with React Class components, refactored to modern Hooks
- **State Management**: Custom cart logic with attribute selection and validation
- **Data Persistence**: Firebase integration for external data storage
- **Form Handling**: Advanced form validation and error handling

### Built With
- **Frontend**: React 18.x with modern Hooks
- **Routing**: React Router for seamless navigation
- **Database**: Firebase Firestore for data persistence
- **Styling**: Responsive CSS with mobile-first approach
- **Build Tool**: Create React App

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
| `npm run eject` | **⚠️ One-way operation** - Ejects from Create React App |

### Development Mode
```bash
npm start
```
- Opens `http://localhost:3000` in your browser
- Enables hot reloading for development
- Displays lint errors in the console

### Production Build
```bash
npm run build
```
- Creates optimized production build in `build/` folder
- Minifies code and includes content hashes
- Ready for deployment to any static hosting service

## 🔧 Dependencies

### Core Dependencies
- **[React Router](https://www.npmjs.com/package/react-router-dom)** - Client-side routing
- **[React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider)** - Product image galleries
- **[UUID](https://www.npmjs.com/package/uuid)** - Unique identifier generation
- **[Firebase Firestore](https://firebase.google.com/docs/firestore)** - Cloud database and storage

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Workflow
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

The MIT License permits unrestricted use, modification, and distribution of this software, provided the original copyright notice and license terms are included.

## 🔗 Links

- **[Live Demo](https://pullrequesttesting.vercel.app/)** - Experience the application
- **[Repository](https://github.com/HelloQATeam123/PullRequestTesting)** - Source code
- **[Issues](https://github.com/HelloQATeam123/PullRequestTesting/issues)** - Report bugs or request features

---

*Built with ❤️ using React and modern web technologies*
