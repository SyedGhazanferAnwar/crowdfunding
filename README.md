# Koii Fundraiser Web Application

<div align="center">
  <img src=".github/images/koii_logo.svg" width="200px" alt="Koii Network Logo"/><br/>
  <p>A Decentralized Crowdfunding Platform Built with React and Arweave</p>

  <a href="https://github.com/koii-network">
    <img src="https://img.shields.io/badge/GitHub-Koii%20Network-blue?style=flat-square&logo=github" alt="GitHub"/>
  </a>
  <a href="https://discord.gg/koii">
    <img src="https://img.shields.io/badge/Discord-Join%20Community-7289DA?style=flat-square&logo=discord" alt="Discord"/>
  </a>
  <img src="https://img.shields.io/badge/TypeScript-✓-007ACC?style=flat-square&logo=typescript" alt="TypeScript"/>
</div>

## 📖 Project Overview

Koii Fundraiser is a decentralized web application that enables projects to create customizable crowdfunding portals using Arweave or Ethereum blockchain. This platform provides an intuitive interface for fundraising, allowing project creators to showcase their initiatives and accept cryptocurrency contributions.

### 🌟 Key Features
- Customizable fundraising portal configuration
- Multi-blockchain support (Arweave, Ethereum)
- Dynamic project description and media gallery
- Social media integration
- FAQ section
- Responsive design
- Secure blockchain-based transactions

## 🚀 Getting Started

### Prerequisites
- Node.js (v16.13.1 LTS recommended)
- Yarn package manager
- Arweave or Ethereum wallet

### Installation

1. Clone the repository
```bash
git clone https://github.com/koii-network/koii-fundraiser.git
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

Create a `.env` file in the project root for any custom environment variables. Currently, no specific environment variables are required.

## 🔧 Project Configuration

### Fundraiser Customization
Modify `src/config/funding-config.tsx` to customize your fundraising portal:
- Project title and description
- Funding goal
- Social media links
- Images and gallery
- FAQs
- Payment type (Arweave/Ethereum)

### App Settings
Update `src/config/app-config.ts` for global application settings:
- Language
- Locale
- Metadata
- Canonical URL

## 🌐 Deployment

### Deploy to Arweave
1. Install arkb globally:
```bash
npm install -g arkb
```

2. Add your Arweave wallet as `wallet.json` in the project root

3. Deploy to Arweave:
```bash
yarn deploy
```

### Alternative Deployment Options
- Vercel
- Netlify
- GitHub Pages

## 📂 Project Structure
```
koii-fundraiser/
├── public/              # Static assets
├── src/
│   ├── api/             # API integration
│   ├── assets/          # Images and media
│   ├── components/      # Reusable React components
│   ├── config/          # Application configurations
│   ├── hooks/           # Custom React hooks
│   ├── pages/           # Page components
│   └── services/        # Utility services
```

## 🛠 Technologies Used
- React (v17)
- TypeScript
- React Router
- Chakra UI
- Arweave SDK
- Web3.js
- SASS
- React Query
- Framer Motion

## 📄 License
This project is open-source. Specific licensing details are pending.

## 🤝 Contributing
Contributions are welcome! Please check our [Contributing Guidelines](CONTRIBUTING.md).

## 📬 Contact
- Website: [koii.network](https://koii.network)
- Discord: [Koii Network Discord](https://discord.gg/koii)
- Twitter: [@KoiiNetwork](https://twitter.com/KoiiNetwork)