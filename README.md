<div align="center">
  <h1>E-Commerce React Application</h1>
  
  [![Live Demo](https://img.shields.io/badge/demo-live-green.svg)](https://your-demo-link.com)
  [![React](https://img.shields.io/badge/React-17.0.2-blue.svg)](https://reactjs.org/)
  [![Firebase](https://img.shields.io/badge/Firebase-9.0.0-orange.svg)](https://firebase.google.com/)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
</div>

## 📑 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## ✨ Features
- Product catalog with categories
- Shopping cart functionality
- User authentication
- Order processing
- Responsive design

## 🛠 Tech Stack
- React 17.0.2
- Firebase 9.0.0
- CSS3 for styling
- Jest for testing

## 💻 Installation
```bash
git clone https://github.com/HelloQATeam123/PullRequestTesting.git
cd PullRequestTesting
npm install
npm start
```

## 📁 Project Structure
```
src/
  ├── components/     # Reusable components
  ├── core-ui/       # Core styling
  ├── data/          # Static data
  ├── database/      # Firebase configuration
  ├── routes/        # Application routes
  └── helpers/       # Utility functions
```

## ⚙️ Configuration
Configure Firebase in `src/database/firebase.js`:
```javascript
const firebaseConfig = {
  apiKey: process.env.REACT_APP_FIREBASE_API_KEY,
  authDomain: process.env.REACT_APP_FIREBASE_AUTH_DOMAIN,
  // Add other config values
};
```

## 🧪 Testing
```bash
npm test
npm run test:coverage
```

## 🚀 Deployment
```bash
npm run build
firebase deploy
```

## 👥 Contributing
1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

## 📄 License
MIT License - see [LICENSE](LICENSE)

## 💬 Support
- GitHub Issues
- Email: support@example.com

[🔝 Back to Top](#-table-of-contents)
