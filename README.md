![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue)](https://pullrequesttesting.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform featuring comprehensive shopping cart functionality, multi-currency support, and seamless checkout experience.

## 🚀 Features

### 🛒 Shopping Cart Management
- **Add/Remove Products**: Seamless cart functionality with real-time updates
- **Quantity Control**: Adjust product quantities with dedicated controls
- **Cart Overlay**: Quick cart summary without page navigation
- **Product Attributes**: Comprehensive product information and selection

### 🔍 Enhanced Shopping Experience
- **Category Filtering**: Browse products by specific categories
- **Dual Shopping Interface**: Add products from category and product detail pages
- **Attribute Validation**: Required attribute selection prevents ordering errors
- **Responsive Design**: Optimized for desktop and mobile devices

### 💰 Multi-Currency Support
- **Global Currency Options**: Support for multiple international currencies
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Tailored shopping experience for global customers

### 🔐 Secure Checkout Process
- **Multi-Step Checkout**: Guided, user-friendly purchase flow
- **Form Validation**: Comprehensive input validation for accurate processing
- **Success Messaging**: Clear confirmation and feedback system

## 🛠️ Technical Implementation

### Architecture
- **Component Structure**: Modular React components with clear separation of concerns
- **State Management**: Efficient cart and currency state handling
- **Routing**: React Router implementation for seamless navigation
- **Data Persistence**: Firebase integration for reliable data storage

### Technology Stack
- **Frontend**: React 18.x with modern Hooks
- **Routing**: React Router DOM
- **Database**: Firebase Firestore
- **Styling**: CSS3 with responsive design principles
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

The application will open at [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production |
| `npm run eject` | **One-way operation** - Ejects from Create React App |

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

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── cart-overlay/   # Cart overlay functionality
│   ├── currency-overlay/ # Currency selection
│   ├── header/         # Navigation header
│   └── attributes/     # Product attribute components
├── routes/             # Page-level components
│   ├── all-products/   # Product catalog
│   ├── single-product/ # Product details
│   ├── cart/          # Shopping cart
│   ├── checkout/      # Checkout process
│   └── order/         # Order confirmation
├── core-ui/           # Global styles and responsive design
├── data/              # Static data and product information
├── database/          # Firebase configuration
└── helpers/           # Utility functions
```

## 🔧 Dependencies

### Core Dependencies
- **React Router DOM** - Client-side routing and navigation
- **Firebase Firestore** - Cloud database solution
- **UUID** - Unique identifier generation

### Development Dependencies
- Create React App toolchain
- ESLint for code quality
- Webpack for bundling
- Babel for JavaScript transpilation

## 🚀 Deployment

### Deploy Your Own
1. Fork this repository
2. Connect to your preferred hosting platform (Vercel, Netlify, etc.)
3. Configure environment variables if needed
4. Deploy automatically from your main branch

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Workflow
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

---

**Built with ❤️ using React and Firebase**
