# Koii Fundraise Portal 💰🐠

## Project Overview

Koii Fundraise is a customizable web application for creating decentralized crowdfunding portals built on the Koii Network. The platform allows project creators to set up funding campaigns with detailed configurations, social integrations, and blockchain-based fundraising capabilities.

Key features include:
- Fully customizable fundraising portal
- Support for Ethereum and Arweave payment types
- Flexible configuration of project details
- Integrated social media links
- Responsive design with modern UI components

## Getting Started

### Prerequisites
- Node.js (v16.13.1 LTS recommended)
- Yarn package manager

### Installation
1. Create a new fundraising portal:
```bash
npx create-koii-fundraise
```

2. Navigate to the project directory:
```bash
cd your-fundraise-project
```

3. Install dependencies:
```bash
yarn install
```

4. Start the development server:
```bash
yarn start
```

> Note: If `yarn start` doesn't work, try:
> ```bash
> react-scripts --openssl-legacy-provider start
> ```

### Environment Configuration
Create a `.env` file in the project root for any environment-specific variables if needed.

## Project Structure
```
├── public/                 # Static assets and HTML template
├── src/
│   ├── api/                # API service integrations
│   ├── components/         # Reusable React components
│   ├── config/             # Application and funding configurations
│   ├── hooks/              # Custom React hooks
│   ├── pages/              # Top-level page components
│   ├── routes/             # Application routing
│   └── services/           # Utility services and helpers
```

## Technologies Used
- React (v17)
- TypeScript
- React Router
- Chakra UI
- Arweave & Web3 Integration
- SASS for styling
- React Query for data fetching
- Axios for HTTP requests

## Fundraiser Customization

### Project Configuration
Customize your fundraiser in `src/config/funding-config.tsx`:
- Set project title and description
- Configure funding goal
- Add slider images
- Define social media links
- Create FAQ sections

### Deployment Customization
Modify `src/config/app-config.ts` to update:
- Language settings
- Metadata
- Canonical URL
- Company information

## Deployment to Arweave

1. Install arkb globally:
```bash
npm install -g arkb
```

2. Add your Arweave wallet as `wallet.json` in the project root

3. Deploy to Arweave:
```bash
yarn deploy
```

## Available Scripts
- `yarn start`: Start development server
- `yarn build`: Create production build
- `yarn test`: Run test suite
- `yarn deploy`: Build and deploy to Arweave
- `yarn lint`: Run code formatting checks

## Contributing
Contributions are welcome! Please check out the [Koii Network Discord](https://discord.gg/koii) for community support.

## License
This project is open-source. Check the LICENSE file for details.

## Powered by Koii Network
[![Koii Network](https://img.shields.io/badge/powered%20by-Koii%20Network-blue)](https://koii.network)