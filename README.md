# Koii Fundraiser Web Application

## Project Overview

Koii Fundraiser is a web application that facilitates fundraising and crowdfunding activities using blockchain technology. The application provides a user-friendly interface for creating, managing, and contributing to funding campaigns with a focus on decentralized finance and community support.

### Key Features
- Blockchain-powered fundraising platform
- Secure wallet integration
- Campaign creation and management
- Real-time funding tracking
- Social sharing capabilities

## Technologies Used

### Core Technologies
- **Frontend**: React (v17)
- **Language**: TypeScript
- **Styling**: Chakra UI, SASS
- **State Management**: React Query
- **Routing**: React Router
- **Form Handling**: React Hook Form

### Blockchain & Web3
- Arweave
- Web3.js
- Koii SDK (@_koi/sdk)

## Getting Started

### Prerequisites
- Node.js (v14 or later)
- Yarn package manager

### Installation Steps
1. Clone the repository
```bash
git clone https://github.com/your-organization/koii-fundraiser.git
cd koii-fundraiser
```

2. Install dependencies
```bash
yarn install
```

3. Create a `.env` file in the project root with the following variables:
```
REACT_APP_API_ENDPOINT=your_api_endpoint
REACT_APP_WALLET_CONFIG=path_to_wallet_config
```

4. Start the development server
```bash
yarn start
```

The application will be available at `http://localhost:3000`

## Project Structure
```
src/
├── api/           # API service configurations
├── assets/        # Static assets
├── components/    # Reusable React components
│   ├── cards/
│   ├── common/
│   └── funding/
├── config/        # Application configurations
├── hooks/         # Custom React hooks
├── pages/         # Page components
├── routes/        # Application routing
└── services/      # Utility services
```

## Deployment

### Build for Production
```bash
yarn build
```

### Deployment to Arweave
The project includes a custom deployment script for Arweave:
```bash
yarn deploy:arkb
```
Note: Requires a valid `wallet.json` for Arweave deployment.

## Available Scripts
- `yarn start`: Starts development server
- `yarn build`: Creates production build
- `yarn test`: Runs test suite
- `yarn lint`: Runs code linting and formatting

## Configuration

### Environment Variables
- `REACT_APP_API_ENDPOINT`: Backend API endpoint
- `REACT_APP_WALLET_CONFIG`: Wallet configuration path

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Supports latest versions of major browsers

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Currently no license specified. Please contact the project owners for licensing information.

## Contact
For any inquiries, please reach out to the Koii team.

---

*Powered by Koii Network* 🚀