# Koii Fundraiser Web Application

## 📖 Project Overview

The Koii Fundraiser is a web application designed to facilitate crowdfunding and financial contributions for Koii Network projects. This React-based platform provides an intuitive interface for users to explore, understand, and pledge support to various funding initiatives.

### 🌟 Key Features
- Funding project browsing and details
- Interactive funding pledge mechanism
- Responsive and modern user interface
- Blockchain-integrated wallet support
- Real-time exchange rate information

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+ recommended)
- Yarn package manager

### Installation Steps
1. Clone the repository
```bash
git clone https://github.com/your-org/koii-fundraiser.git
cd koii-fundraiser
```

2. Install dependencies
```bash
yarn install
```

3. Create a `.env` file in the project root with the following variables:
```
REACT_APP_API_ENDPOINT=your_api_endpoint
REACT_APP_WALLET_CONFIG=your_wallet_config
```

4. Start the development server
```bash
yarn start
```

The application will be available at `http://localhost:3000`

## 🌐 Deployment

### Production Build
```bash
yarn build
```

### Arweave Deployment
```bash
yarn deploy:arkb
```
Note: Requires a valid `wallet.json` for Arweave deployment.

## 📂 Project Structure
```
src/
├── api/            # API service integrations
├── assets/         # Static assets
├── components/     # Reusable React components
│   ├── cards/
│   ├── common/
│   └── funding/
├── config/         # Application configurations
├── hooks/          # Custom React hooks
├── pages/          # Top-level page components
└── routes/         # Application routing
```

## 🛠 Technologies Used
- React 17
- TypeScript
- React Router
- Chakra UI
- React Query
- SASS
- Web3.js
- Arweave SDK

## ✨ Feature Highlights
- Wallet Integration (Finnie Wallet)
- Dynamic Funding Progress Tracking
- Social Media Sharing
- Responsive Design
- Form Validation

## 🔧 Configuration
- Configurable via `.env` file
- Build settings in `tsconfig.json`
- ESLint and Prettier for code quality

## 📋 Scripts
- `yarn start`: Start development server
- `yarn build`: Create production build
- `yarn test`: Run test suite
- `yarn lint`: Run code style checks

## 📄 License
Currently no license specified. Please contact project administrators for usage permissions.

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact
For more information, visit [Koii Network](https://koii.network)