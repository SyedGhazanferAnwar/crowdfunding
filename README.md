# Koii Fundraiser Web Application

<div align="center">
  <img src="https://raw.githubusercontent.com/koii-network/koii.X/main/.github/images/koii_logo.svg" width="224px" alt="Koii Network Logo"/><br/>
  <p>Create Koii Fundraise: A Decentralized Crowdfunding Platform</p>

  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white" alt="typescript" />
  <a href="https://discord.gg/koii" target="_blank">
    <img src="https://img.shields.io/badge/Discord-7289DA?style=flat&logo=discord&logoColor=white" alt="Discord" />
  </a>
  <a href="http://koii.network/" target="_blank">
    <img src="https://img.shields.io/badge/made%20by-koii-blue" alt="made-by-koii" />
  </a>
</div>

## 📝 Project Overview

The Koii Fundraiser is a decentralized web application designed to help creators and projects raise funds through a user-friendly, blockchain-powered crowdfunding platform. Built on the Koii Network, this application provides a transparent and secure way to manage fundraising campaigns.

### Key Features
- Customizable fundraising portal
- Support for multiple cryptocurrency payment types (Arweave, Ethereum)
- Responsive and modern UI
- Social media integration
- Fully configurable project details
- Decentralized deployment on Arweave

## 🚀 Getting Started

### Prerequisites
- Node.js (v16.13.1 LTS recommended)
- Yarn package manager

### Installation Steps
1. Clone the repository
```bash
git clone https://github.com/your-repo/koii-fundraiser.git
cd koii-fundraiser
```

2. Install dependencies
```bash
yarn install
```

3. Start the development server
```bash
yarn start
```

### Environment Configuration
Create a `.env` file in the project root for any required environment variables. Currently, no specific environment variables are required.

## 🛠 Project Structure
```
koii-fundraiser/
├── public/           # Static assets and HTML template
├── src/
│   ├── api/          # API service configurations
│   ├── components/   # Reusable React components
│   ├── config/       # Application and fundraiser configurations
│   ├── hooks/        # Custom React hooks
│   ├── pages/        # Top-level page components
│   └── routes/       # Application routing
```

## 🔧 Technologies Used
- React 17
- TypeScript
- Chakra UI
- React Router
- Axios
- Web3
- Arweave SDK
- React Query

## 🌟 Feature Highlights
- Dynamic fundraising portal configuration
- Multi-cryptocurrency support
- Responsive design
- Customizable project details
- Social media links integration
- FAQ section
- Wallet integration

## 🚢 Deployment

### Deploying to Arweave
1. Install arkb globally
```bash
npm install -g arkb
```

2. Place your Arweave wallet keyfile as `wallet.json` in the project root

3. Deploy to Arweave
```bash
yarn deploy
```

### Other Deployment Options
- Vercel
- Netlify
- GitHub Pages

## 🔧 Customization

### Fundraiser Configuration
Edit `src/config/funding-config.tsx` to customize:
- Project title and description
- Funding goal
- Images
- Social links
- Payment type
- About section
- FAQs

### App Configuration
Modify `src/config/app-config.ts` to adjust:
- Language
- Website metadata
- Canonical URL
- Company details

## 📄 License
This project is open-source. Specific licensing details to be added.

## 🤝 Contributing
Contributions are welcome! Please check out the Koii Network's contribution guidelines.

## 📞 Support
- Discord: [Koii Network Discord](https://discord.gg/koii)
- Website: [Koii Network](https://koii.network)