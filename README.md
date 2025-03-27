# Koii Fundraiser Web Application

## 🌟 Project Overview

The Koii Fundraiser is a decentralized web application designed to facilitate community-driven funding and support for various projects using blockchain technology. This platform enables users to create, explore, and contribute to funding initiatives with transparency and efficiency.

Key features include:
- Decentralized fundraising platform
- Blockchain-powered transactions
- User-friendly funding pledge mechanism
- Integration with Finnie wallet
- Responsive and modern web interface

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or later)
- Yarn package manager
- Modern web browser
- Finnie wallet browser extension (recommended)

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
Create a `.env` file in the project root with the following configuration:
```bash
REACT_APP_BUNDLER_API_URL=https://mainnet.koii.live
REACT_APP_API_URL=https://koi.rocks:8888/api/v1
REACT_APP_NODE_URL=https://mainnet.koii.live
REACT_APP_INFURA_URL=https://mainnet.infura.io/v3/YOUR_INFURA_PROJECT_ID
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
The project includes a custom deployment script for Arweave:
```bash
yarn deploy:arkb
```
Note: Requires a valid `wallet.json` for Arweave deployment.

## 📂 Project Structure

- `src/`
  - `App/`: Main application configuration
  - `api/`: API service integrations
  - `components/`: Reusable React components
  - `config/`: Application and feature configurations
  - `hooks/`: Custom React hooks
  - `pages/`: Top-level page components
  - `routes/`: Application routing logic
  - `services/`: Utility services and helpers

## 🛠 Technologies Used

- **Frontend**:
  - React 17
  - TypeScript
  - React Router
  - Chakra UI
  - Framer Motion

- **Blockchain & Web3**:
  - Arweave
  - Web3.js
  - Koii SDK
  - Finnie Wallet

- **State Management**:
  - React Query
  - React Hook Form

- **Styling**:
  - Node SASS
  - Styled Components

## ✨ Feature Highlights

- Decentralized fundraising platform
- Wallet integration (Finnie)
- Funding pledge mechanism
- Real-time exchange rate tracking
- Responsive design
- Secure blockchain transactions

## 🔧 Configuration Options

Configurable settings are managed via environment variables:
- Blockchain node URL
- API endpoints
- Infura provider configuration

## 📄 License

This project is currently unlicensed. Refer to the project maintainers for usage permissions.

## 🤝 Contributing

Contributions are welcome! Please check the issues page and follow the project's contribution guidelines.

---

**Built with ❤️ by the Koii Network Team**