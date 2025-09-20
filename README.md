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
- **Global Accessibility**: Support for EUR, GBP, AUD, JPY, and additional currencies
- **Real-time Conversion**: Dynamic currency switching throughout the shopping experience

### 🔐 Secure Checkout Process
- **Multi-step Workflow**: Guided checkout process with clear progression indicators
- **Form Validation**: Comprehensive input validation to ensure data accuracy
- **User-friendly Interface**: Intuitive design focused on conversion optimization

## 🛠️ Technical Implementation

### Architecture & Development Goals
- **Component Evolution**: Implemented using React Class components, later refactored to modern Hooks
- **State Management**: Custom cart logic with attribute selection and validation
- **Data Persistence**: Firebase integration for external data storage
- **Form Handling**: Robust validation system for checkout processes

### Built With
- **Frontend**: React 18.x with Create React App
- **Routing**: React Router for navigation
- **UI Components**: React Simple Image Slider for product galleries
- **Utilities**: UUID for unique identifier generation
- **Backend**: Firebase Firestore for data persistence

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
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production |
| `npm run eject` | **One-way operation** - Ejects from Create React App |

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
- Creates optimized production build in the `build` folder
- Minifies files and includes content hashes
- Ready for deployment

## 📦 Dependencies

| Package | Purpose | Documentation |
|---------|---------|---------------|
| [React Router](https://www.npmjs.com/package/react-router-dom) | Client-side routing | [Docs](https://reactrouter.com/) |
| [React Simple Image Slider](https://www.npmjs.com/package/react-simple-image-slider) | Product image galleries | [NPM](https://www.npmjs.com/package/react-simple-image-slider) |
| [UUID](https://www.npmjs.com/package/uuid) | Unique identifier generation | [NPM](https://www.npmjs.com/package/uuid) |
| [Firebase Firestore](https://firebase.google.com/docs/firestore) | Cloud database | [Docs](https://firebase.google.com/docs/firestore) |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/HelloQATeam123/PullRequestTesting/blob/main/LICENSE) file for details.

## 🔗 Links

- **Live Demo**: [https://pullrequesttesting.vercel.app/](https://pullrequesttesting.vercel.app/)
- **Repository**: [https://github.com/HelloQATeam123/PullRequestTesting](https://github.com/HelloQATeam123/PullRequestTesting)

---

<div align="center">
  <p>Built with ❤️ using React and Firebase</p>
</div>
