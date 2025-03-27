# Koii Fundraiser Web Application

## 🌟 Project Overview

Koii Fundraiser is a web application built to facilitate fundraising and crowdfunding activities using blockchain technology. The application provides a seamless platform for users to create, view, and contribute to various funding campaigns with enhanced transparency and decentralized features.

### 🚀 Key Features
- Decentralized fundraising platform
- Wallet integration (Finnie wallet support)
- Real-time funding tracking
- Social sharing capabilities
- Secure blockchain-based transactions

## 🛠 Getting Started

### Prerequisites
- Node.js (v14 or later)
- Yarn package manager
- Finnie Wallet extension (recommended)

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

3. Set up environment variables
Create a `.env` file in the project root and add necessary configuration:
```
REACT_APP_API_ENDPOINT=https://your-api-endpoint.com
REACT_APP_WALLET_CONFIG=your_wallet_configuration
```

4. Start the development server
```bash
yarn start
```

The application will be available at `http://localhost:3000`

## 🚢 Deployment

### Production Build
```bash
yarn build
```

### Deployment Options
- Arweave Deployment (Built-in Support)
```bash
yarn deploy:arkb  # Deploys to Arweave using arkb
```

## 📂 Project Structure
```
src/
├── api/           # API interaction layers
├── assets/        # Static assets
├── components/    # Reusable React components
│   ├── cards/
│   ├── common/
│   └── funding/
├── config/        # Application configurations
├── hooks/         # Custom React hooks
├── pages/         # Top-level page components
├── routes/        # Application routing
└── services/      # Utility services and helpers
```

## 🔧 Technologies Used
- **Frontend**: React (TypeScript)
- **State Management**: React Query
- **UI Framework**: Chakra UI
- **Routing**: React Router
- **Form Handling**: React Hook Form
- **Blockchain**: Arweave, Web3
- **Styling**: SASS, Emotion
- **Testing**: Jest, React Testing Library

## ✨ Feature Highlights
- Wallet Connection via Finnie
- Detailed Funding Campaign Pages
- Pledge and Contribution Tracking
- Social Media Integration
- Responsive Design

## 🔒 Configuration
- Supports environment-based configuration
- Configurable API endpoints
- Customizable UI themes
- Extensible routing and state management

## 📜 Scripts
- `yarn start`: Start development server
- `yarn build`: Create production build
- `yarn test`: Run test suite
- `yarn lint`: Run code linting
- `yarn deploy`: Build and deploy to Arweave

## 📄 License
Currently Unlicensed. Please contact the project maintainers for licensing information.

## 🤝 Contributing
Contributions are welcome! Please check the issues page and feel free to submit pull requests.

## 🔗 Additional Resources
- [Koii Network Documentation](https://docs.koii.network)
- [Arweave Documentation](https://docs.arweave.org)

**Built with ❤️ by the Koii Network Team**