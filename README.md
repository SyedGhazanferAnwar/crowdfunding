# Koii Fundraiser Web Application

## 🌟 Project Overview

The Koii Fundraiser is a web application designed to facilitate crowdfunding and financial support for projects within the Koii Network ecosystem. This application provides a user-friendly interface for exploring, creating, and contributing to funding campaigns using blockchain technology.

### Key Features
- Browse ongoing funding campaigns
- View detailed campaign information
- Contribute funds to campaigns
- Wallet integration (Finnie wallet support)
- Responsive and modern user interface

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+ recommended)
- Yarn package manager
- Finnie wallet browser extension

### Installation Steps
1. Clone the repository:
```bash
git clone https://github.com/your-org/koii-fundraiser.git
cd koii-fundraiser
```

2. Install dependencies:
```bash
yarn install
```

3. Create a `.env` file with the following variables:
```
REACT_APP_ARWEAVE_WALLET=path/to/wallet.json
REACT_APP_NETWORK_URL=https://testnet.koii.live
```

4. Start the development server:
```bash
yarn start
```

The application will be available at `http://localhost:3000`

## 🌐 Deployment

### Production Build
```bash
yarn build
```

### Deployment to Arweave
```bash
yarn deploy:arkb
```
Note: Requires a valid Arweave wallet (`wallet.json`)

## 📂 Project Structure
```
src/
├── api/           # API integration and service calls
├── assets/        # Static assets and images
├── components/    # Reusable React components
│   ├── cards/
│   ├── common/
│   └── funding/
├── config/        # Application configuration
├── hooks/         # Custom React hooks
├── pages/         # Top-level page components
├── routes/        # Application routing
└── services/      # Utility services and helpers
```

## 🛠 Technologies Used
- React (v17)
- TypeScript
- Chakra UI
- React Router
- Web3.js
- Arweave
- Axios
- React Query

## ✨ Feature Highlights
- Wallet Connection: Integrate with Finnie wallet
- Campaign Browsing: Explore and filter funding campaigns
- Contribution Mechanism: Direct fund pledging
- Real-time Exchange Rates
- Responsive Design

## 🔧 Configuration
- Environment Variables
  - `REACT_APP_ARWEAVE_WALLET`: Path to Arweave wallet
  - `REACT_APP_NETWORK_URL`: Koii network endpoint

## Available Scripts
- `yarn start`: Start development server
- `yarn build`: Create production build
- `yarn test`: Run test suite
- `yarn lint`: Run code linting

## 📄 License
This project is currently unlicensed. Please contact the Koii Network team for licensing details.

## 🤝 Contributing
Contributions are welcome! Please check out our contribution guidelines.

## 💬 Support
For support, please open an issue in the GitHub repository or join the Koii Network Discord.