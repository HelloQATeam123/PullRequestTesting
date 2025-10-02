# PullRequestTesting

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

PullRequestTesting is a modern, responsive e-commerce platform featuring comprehensive shopping functionality with advanced cart management, multi-currency support, and secure checkout capabilities. Built with React, this application provides a seamless shopping experience with real-time updates and persistent data storage.

## Key Features

### 🛒 Advanced Cart Management
- **Dynamic Product Management**: Add, remove, and modify product quantities with real-time updates
- **Interactive Cart Overlay**: Quick access to cart summary without page navigation
- **Attribute Tracking**: Detailed product information including size, color, and other specifications
- **Persistent Storage**: Cart data maintained across browser sessions

### 🔍 Enhanced Shopping Experience
- **Product Catalog**: Comprehensive product browsing with detailed information
- **Flexible Shopping Flow**: Add products from both category and individual product pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💰 Multi-Currency Support
- **Global Accessibility**: Support for multiple currencies with real-time conversion
- **Dynamic Price Updates**: Automatic price recalculation based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔐 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Success Messaging**: Clear confirmation and feedback system

## Technical Implementation

### Architecture
- **Frontend Framework**: React with modern hooks implementation
- **State Management**: Context API for global state handling
- **Routing**: React Router for seamless navigation
- **Data Persistence**: Firebase Firestore for external data storage

### Development Approach
- Component-based architecture for maintainability and reusability
- Custom validation logic for form handling and user input
- Responsive CSS with mobile-first design principles

## Installation & Setup

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

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production deployment |
| `npm run eject` | Ejects from Create React App (irreversible) |

## Project Structure

```
src/
├── components/          # Reusable UI components
├── routes/             # Page-level components
├── core-ui/            # Global styles and CSS
├── data/               # Static data files
├── database/           # Firebase configuration
├── helpers/            # Utility functions
└── assets/             # Static assets and images
```

## Key Components

- **Cart Management**: Advanced shopping cart with quantity controls and attribute tracking
- **Currency System**: Multi-currency support with real-time conversion
- **Checkout Flow**: Secure, multi-step checkout process
- **Product Display**: Comprehensive product catalog with detailed views
- **Responsive UI**: Mobile-optimized interface with hover effects

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you find this project helpful, please consider giving it a ⭐ on GitHub!

---

**Built with ❤️ using React and modern web technologies**
