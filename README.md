![Shopping Time](https://raw.githubusercontent.com/HelloQATeam123/PullRequestTesting/main/src/assets/images/project-preview.webp)

# Shopping Time

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

A modern, responsive e-commerce platform featuring over 150 women's clothing products with comprehensive shopping cart functionality and multi-currency support.

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
- **Global Currency Options**: Support for EUR, GBP, AUD, JPY, and more
- **Real-time Conversion**: Dynamic price updates based on selected currency
- **Localized Experience**: Currency formatting appropriate to user selection

### 🔐 Secure Checkout Process
- **Multi-Step Workflow**: Guided checkout process for enhanced user experience
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **Error Prevention**: Client-side validation reduces checkout errors

## 🛠️ Technical Implementation

### Architecture & Development Goals
- **React Class Components**: Initial implementation using class-based components
- **Hooks Migration**: Refactored to modern React hooks for improved performance
- **State Management**: Custom cart logic with attribute selection validation
- **External Data Persistence**: Firebase integration for data storage
- **Form Validation**: Comprehensive client-side validation system

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- Modern web browser

## 🚀 Quick Start

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

4. **Open your browser**
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
- Hot reload enabled for real-time development
- Console displays lint errors and warnings

### Production Build
```bash
npm run build
```
- Creates optimized production build in `build/` folder
- Minified and optimized for best performance
- Ready for deployment

### Testing
```bash
npm test
```
- Interactive test runner with watch mode
- See [running tests documentation](https://facebook.github.io/create-react-app/docs/running-tests) for more information

## 🔧 Dependencies

| Package | Purpose | Documentation |
|---------|---------|---------------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing | [Docs](https://reactrouter.com/) |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image carousel | [NPM](https://www.npmjs.com/package/react-simple-image-slider) |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation | [NPM](https://www.npmjs.com/package/uuid) |
| [Firestore](https://firebase.google.com/docs/firestore) | Cloud database | [Firebase Docs](https://firebase.google.com/docs/firestore) |

## 🚀 Deployment

This project is optimized for deployment on:
- [Vercel](https://vercel.com/) (recommended)
- [Netlify](https://netlify.com/)
- [GitHub Pages](https://pages.github.com/)

For detailed deployment instructions, see the [Create React App deployment documentation](https://facebook.github.io/create-react-app/docs/deployment).

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 📞 Support

If you encounter any issues or have questions, please [open an issue](https://github.com/HelloQATeam123/PullRequestTesting/issues) on GitHub.

---

**Built with ❤️ using React and Firebase**
