# Koii Fundraiser Portal

<p align="center">
  <img src="https://raw.githubusercontent.com/koii-network/koii.X/main/.github/images/koii_logo.svg" width="224px"/><br/>
  Create Decentralized Fundraising Portals 🐠💰
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white" alt="typescript" />&nbsp;
  <a href="https://discord.gg/koii" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=flat&logo=discord&logoColor=white" alt="discord" /></a>&nbsp;
  <a href="http://koii.network/" target="_blank"><img src="https://img.shields.io/badge/made%20by-koii-blue" alt="made-by-koii" /></a>
</p>

## 📝 Project Overview

Koii Fundraiser is a decentralized web application that enables organizations and individuals to create custom crowdfunding portals with blockchain-powered funding mechanisms. Built on the Koii Network, this platform allows seamless fundraising using Arweave or Ethereum cryptocurrencies.

### Key Features
- Customizable fundraising portal with configurable goals and settings
- Support for multiple cryptocurrencies (Arweave, Ethereum)
- Responsive and modern user interface
- Easy deployment to decentralized storage
- Comprehensive social media and project information integration

## 🚀 Getting Started

### Prerequisites
- Node.js (v16.13.1 LTS recommended)
- Yarn package manager
- Arweave wallet (for deployment)

### Installation
1. Create a new fundraiser portal:
```bash
npx create-koii-fundraise
```

2. Navigate to your project directory:
```bash
cd your-fundraiser-portal
```

3. Install dependencies:
```bash
yarn install
```

4. Start the development server:
```bash
yarn start
# Alternative: react-scripts --openssl-legacy-provider start
```

### Environment Configuration
Create a `.env` file in the project root for any required environment variables. Currently, no mandatory environment variables are specified.

## 🛠 Project Structure

```
koii-fundraiser/
├── public/               # Static assets and HTML template
├── src/
│   ├── api/              # API service integrations
│   ├── assets/           # Images and static files
│   ├── components/       # Reusable React components
│   ├── config/           # Application and fundraiser configurations
│   ├── hooks/            # Custom React hooks
│   ├── pages/            # Top-level page components
│   └── routes/           # Application routing
```

## 🔧 Technologies Used

- **Frontend**: React 17, TypeScript
- **Styling**: Chakra UI, Emotion, SASS
- **State Management**: React Query
- **Routing**: React Router
- **Form Handling**: React Hook Form
- **Blockchain**: Web3, Arweave SDK
- **Deployment**: Arweave (arkb)

## 🎨 Customization

### Fundraiser Configuration
Modify `src/config/funding-config.tsx` to customize:
- Project title and description
- Funding goal
- Images
- Social media links
- Payment type (Arweave/Ethereum)
- FAQ content

### App Configuration
Edit `src/config/app-config.ts` to adjust:
- Language
- Locale
- Website metadata
- SEO settings

## 🌐 Deployment

### Arweave Deployment
1. Install arkb globally:
```bash
npm install -g arkb
```

2. Add your Arweave wallet as `wallet.json` in the project root

3. Deploy to Arweave:
```bash
yarn deploy
```

## 📜 License

Currently no license specified. Please contact Koii Network for licensing information.

## 🤝 Community & Support

- [Koii Discord](https://discord.gg/koii)
- [Koii Website](https://koii.network)
- [GitHub Repository](https://github.com/koii-network)

## 📋 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.