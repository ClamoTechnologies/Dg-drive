# DGDrive 3.0

A decentralized file storage and sharing platform built on blockchain technology.

## Project Structure

- `contracts/` - Smart contracts written in Solidity
- `client/` - React frontend application
- `scripts/` - Deployment and utility scripts
- `hardhat.config.js` - Hardhat configuration file

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- MetaMask or similar Web3 wallet

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Dgdrive3.0-main
```

2. Install dependencies:
```bash
npm install
```

3. Install client dependencies:
```bash
cd client
npm install
```

## Development

### Smart Contract Development

1. Start the local Hardhat network:
```bash
npx hardhat node
```

2. In a new terminal, deploy the contracts:
```bash
npx hardhat run scripts/deploy.js --network localhost
```

### Frontend Development

1. Start the React development server:
```bash
cd client
npm start
```

The application will be available at `http://localhost:3000`

## Configuration

1. Make sure your MetaMask is connected to the local Hardhat network:
   - Network Name: Hardhat
   - RPC URL: http://127.0.0.1:8545
   - Chain ID: 1337
   - Currency Symbol: ETH

2. Import one of the test accounts from the Hardhat node output into MetaMask

## Features

- Decentralized file storage
- Secure file sharing
- Blockchain-based access control
- User authentication and authorization

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue in the repository or contact the development team.
