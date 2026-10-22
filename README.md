# 🌊 CarbonChain - Blue Carbon Registry Platform

<div align="center">

![CarbonChain Banner](https://img.shields.io/badge/CarbonChain-Blue%20Carbon%20Registry-0066cc?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBkPSJNMTIgMkM2LjQ4IDIgMiA2LjQ4IDIgMTJzNC40OCAxMCAxMCAxMCAxMC00LjQ4IDEwLTEwUzE3LjUyIDIgMTIgMnoiIGZpbGw9IiNmZmYiLz48L3N2Zz4=)

![React](https://img.shields.io/badge/React-18.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Aptos](https://img.shields.io/badge/Aptos-Blockchain-000000?style=for-the-badge)
![Binance](https://img.shields.io/badge/Binance-Live%20API-F0B90B?style=for-the-badge&logo=binance&logoColor=white)

**🌱 Revolutionizing Carbon Credit Management with Blockchain & Real-Time Market Integration 💹**

[🚀 Quick Start](#-quick-start) • [✨ Features](#-features) • [🏗️ Tech Stack](#️-tech-stack) • [📸 Screenshots](#-screenshots) • [📚 Documentation](#-documentation)

</div>

---

## 🎯 What is CarbonChain?

CarbonChain is a **full-stack blockchain platform** that transforms how blue carbon credits are registered, verified, and traded. Built for mangrove restoration projects, it combines cutting-edge technology to create a transparent, efficient, and real-time carbon credit marketplace.

### 🌟 Key Highlights

- 🌊 **Blue Carbon Focus** - Specialized for mangrove and coastal ecosystem restoration
- ⛓️ **Blockchain-Powered** - Immutable records on Aptos blockchain
- 💹 **Real-Time Pricing** - Live market data from Binance API (updates every second!)
- 🤖 **AI-Driven** - Automated satellite imagery analysis and carbon calculations
- 📊 **Impact Tracking** - Comprehensive environmental and community benefit monitoring
- 🔒 **Secure & Transparent** - Multi-stage verification with blockchain audit trail

---

## ✨ Features

### 🌱 Carbon Credit Management
- **Project Registration** - Complete onboarding workflow with site details
- **AI Image Analysis** - Automated satellite and site image processing
- **Carbon Calculation** - Precise CO₂ sequestration estimates
- **Multi-Stage Verification** - Internal → Third-Party → Legal compliance
- **Blockchain Deployment** - Immutable project records on Aptos

### ⛓️ Blockchain Integration
- **Smart Contracts** - Production-ready Aptos Move contracts
- **GeoNFT Minting** - Location-bound NFTs for verified sites
- **Token Management** - Fungible carbon credit tokens
- **Transfer & Retirement** - Complete lifecycle management
- **Event Emission** - Real-time blockchain event tracking

### 💹 Live Market Features
- **Real-Time Pricing** - Binance API integration with 1-second updates
- **Market Sentiment** - Bullish/Bearish indicators based on crypto markets
- **Dynamic Valuation** - Portfolio values update with live market data
- **Price Fluctuation** - Visual indicators for market movements
- **Crypto Correlation** - 20% correlation to BTC price movements

### 📊 Impact Dashboard
- **Environmental Metrics** - CO₂ sequestration, biodiversity, water quality
- **Community Benefits** - Jobs created, families supported, income generated
- **Progress Tracking** - Restoration progress, carbon sequestration rates
- **Real-Time Monitoring** - Live data updates and visualizations
- **Comprehensive Reports** - Detailed impact analysis

---

## 🏗️ Tech Stack

### Frontend
```
React 18.0          - Modern UI framework
TailwindCSS         - Utility-first styling
Aptos Wallet SDK    - Blockchain wallet integration
Binance Service     - Real-time market data
```

### Backend
```
Python 3.9+         - Core language
FastAPI 0.104       - High-performance API framework
SQLAlchemy          - ORM for database operations
Pydantic            - Data validation
Aptos SDK           - Blockchain integration
```

### Blockchain
```
Aptos Move          - Smart contract language
Carbon Registry     - Main contract module
GeoNFT System       - Location-bound NFTs
Token Management    - Fungible credit tokens
```

### External APIs
```
Binance API         - Real-time cryptocurrency prices
Satellite Imagery   - Environmental monitoring
AI/ML Services      - Image analysis & carbon calc
```

---

## 🚀 Quick Start

### Prerequisites
- Python 3.9 or higher
- Node.js 14 or higher
- npm or yarn

### Installation & Setup

#### 1. Clone the Repository
```bash
git clone https://github.com/Nishat2006/Carbonchain.git
cd Carbonchain
```

#### 2. Start Backend
```bash
cd backend
pip install -r requirements.txt
python main.py
```
Backend will run on `http://localhost:8000`

#### 3. Start Frontend
```bash
cd carbon-assessment
npm install
npm start
```
Frontend will run on `http://localhost:3000`

#### 4. Quick Start (Windows)
```bash
# Start both servers at once
START_ALL.bat
```

### 🎮 Using the Platform

1. **Open** `http://localhost:3000` in your browser
2. **Create** a new carbon credit project
3. **Upload** site images for AI analysis
4. **Complete** verification workflow
5. **Deploy** to blockchain
6. **Monitor** impact on dashboard
7. **Trade** on marketplace with live pricing

---

## 📸 Screenshots

### Initial Assessment
![WhatsApp Image 2025-10-04 at 23 27 24_056aeacf](https://github.com/user-attachments/assets/6115f055-61aa-41cc-9aa2-f75562706b03)


### Carbon Marketplace
![WhatsApp Image 2025-10-04 at 23 27 23_57bbe710](https://github.com/user-attachments/assets/8d891731-e438-4aae-a0a9-96b328419aa0)


### Impact Dashboard
![WhatsApp Image 2025-10-04 at 23 27 23_9bbff530](https://github.com/user-attachments/assets/4c267544-cf25-4b28-85ef-65e729a63cd2)


### Blockchain Registry
![WhatsApp Image 2025-10-04 at 23 27 23_cc277b6b](https://github.com/user-attachments/assets/3e1a9c1b-c955-4ae2-b91e-6e4968207087)


---

## 📁 Project Structure

```
Carbonchain/
├── backend/                    # Python FastAPI Backend
│   ├── main.py                # Main API application
│   ├── models.py              # Database models
│   ├── schemas.py             # Pydantic schemas
│   ├── database.py            # Database configuration
│   ├── requirements.txt       # Python dependencies
│   └── services/              # Business logic modules
│       ├── binance_price_service.py    # Real-time pricing
│       ├── aptos_integration.py        # Blockchain integration
│       ├── blockchain_service.py       # Smart contract interactions
│       ├── image_analysis.py           # AI image processing
│       ├── carbon_calculator.py        # CO₂ calculations
│       ├── verification_service.py     # Verification workflow
│       └── marketplace_service.py      # Trading functionality
│
├── carbon-assessment/         # React Frontend
│   ├── src/
│   │   ├── components/        # React components
│   │   │   ├── InitialAssessment.js
│   │   │   ├── BlockchainRegistry.js
│   │   │   ├── SmartContracts.js
│   │   │   ├── CarbonMarketplace.js
│   │   │   ├── ImpactDashboard.js
│   │   │   └── WalletConnect.js
│   │   ├── services/          # Frontend services
│   │   │   ├── binanceService.js      # Market data service
│   │   │   └── aptosWallet.js         # Wallet integration
│   │   └── App.js             # Main application
│   └── package.json           # Node dependencies
│
├── aptos-contracts/           # Aptos Move Smart Contracts
│   ├── sources/
│   │   ├── carbon_credit.move         # Main registry contract
│   │   └── carbon_registry.move       # Enhanced CRUD contract
│   ├── Move.toml              # Move package configuration
│   ├── deploy_registry.bat    # Windows deployment
│   └── deploy_registry.sh     # Linux/Mac deployment
│
├── START_ALL.bat              # Quick start script (Windows)
├── start_both.bat             # Alternative startup
├── start_backend.bat          # Backend only
├── start_frontend.bat         # Frontend only
├── QUICK_START.md             # Quick start guide
└── README.md                  # This file
```

---

## 🔧 Configuration

### Backend Configuration
Create `.env` file in `backend/` directory:
```env
DATABASE_URL=sqlite:///./carbon_registry.db
APTOS_NODE_URL=https://fullnode.testnet.aptoslabs.com/v1
APTOS_MODULE_ADDRESS=your_contract_address_here
```

### Frontend Configuration
Create `.env.local` file in `carbon-assessment/` directory:
```env
REACT_APP_API_URL=http://localhost:8000
REACT_APP_APTOS_NODE_URL=https://fullnode.testnet.aptoslabs.com/v1
REACT_APP_CONTRACT_ADDRESS=your_contract_address_here
```

---

## 🌐 API Endpoints

### Projects
```
POST   /api/projects              - Create new project
GET    /api/projects              - List all projects
GET    /api/projects/{id}         - Get project details
PUT    /api/projects/{id}         - Update project
DELETE /api/projects/{id}         - Delete project
```

### Blockchain
```
POST   /api/blockchain/deploy     - Deploy smart contract
POST   /api/blockchain/mint-nft   - Mint GeoNFT
POST   /api/blockchain/tokenize   - Create carbon tokens
```

### Marketplace
```
GET    /api/marketplace/listings           - Get all listings
GET    /api/marketplace/statistics         - Market statistics
GET    /api/marketplace/live-prices        - Real-time prices
GET    /api/marketplace/portfolio-value/{credits}  - Calculate value
```

### Verification
```
POST   /api/verification          - Create verification record
PUT    /api/verification/{id}     - Update verification status
```

Full API documentation available at `http://localhost:8000/docs`

---

## 💹 Real-Time Market Integration

### Binance API Integration
- **Update Frequency**: 1 second
- **Data Source**: Binance Public API
- **Crypto Tracked**: BTC, ETH, BNB, APT
- **Correlation**: 20% to BTC price movements
- **Features**:
  - Live price updates
  - 24h high/low tracking
  - Market sentiment analysis
  - Volume monitoring
  - Dynamic portfolio valuation

### Price Calculation
```
Carbon Price = Base Price × (1 + BTC Change % × 0.2)
Market Value = Carbon Credits × Current Price
```

---

## ⛓️ Blockchain Deployment

### Deploy Smart Contract (Optional)

#### Prerequisites
- Aptos CLI installed
- Testnet account with APT tokens

#### Deployment Steps
```bash
cd aptos-contracts

# Windows
deploy_registry.bat

# Linux/Mac
./deploy_registry.sh
```

#### Initialize Registry
```bash
aptos move run --function-id 'YOUR_ADDRESS::registry::initialize'
```

---

## 🧪 Testing

### Backend Tests
```bash
cd backend
pytest
```

### Frontend Tests
```bash
cd carbon-assessment
npm test
```

### API Testing
Visit `http://localhost:8000/docs` for interactive API documentation

---

## 📊 Features Breakdown

### ✅ Fully Implemented
- [x] Complete backend API (20+ endpoints)
- [x] React frontend with 6 components
- [x] Real-time Binance price integration
- [x] Aptos blockchain smart contracts
- [x] AI image analysis simulation
- [x] Carbon credit calculations
- [x] Multi-stage verification workflow
- [x] GeoNFT minting
- [x] Token management
- [x] Marketplace with live pricing
- [x] Impact dashboard
- [x] Database operations (CRUD)
- [x] File upload handling

### 🚧 Future Enhancements
- [ ] Real AI/ML model integration
- [ ] Advanced satellite imagery analysis
- [ ] Multi-chain support (Ethereum, Polygon)
- [ ] Mobile app (React Native)
- [ ] Advanced analytics dashboard
- [ ] Automated reporting
- [ ] Multi-language support
- [ ] Integration with carbon registries (Verra, Gold Standard)

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License 

---

## 👥 Team

**Developed by**: Manas , Nishat , Parth , Kunjan 

**Contact**: [GitHub](https://github.com/BigO-Debbuger)

---

## 🙏 Acknowledgments

- **Aptos Foundation** - For blockchain infrastructure
- **Binance** - For real-time market data API
- **FastAPI** - For excellent Python web framework
- **React Team** - For powerful frontend library
- **Open Source Community** - For amazing tools and libraries

---



---

<div align="center">


[🌊 CarbonChain](https://github.com/BigO-Debbuger) | [📖 Documentation](./QUICK_START.md) | [🐛 Report Bug](https://github.com/BigO-Debbuger/Carbonchain/issues) | [✨ Request Feature](https://github.com/BigO-Debbuger/Carbonchain/issues)

</div>

<!-- implementation-notes -->
## Implementation Notes

CarbonChain combines a FastAPI backend, a React interface, and Aptos Move smart contracts.

- **Image analysis:** The integration status document describes the current image-analysis service as simulated. Treat its results as prototype output unless validated against a production analysis pipeline.
- **Blockchain:** The repository contains both a mock blockchain service for testing and an Aptos integration. Configure the target network and credentials before attempting transactions.
- **Market data:** The backend includes a Binance price service. Cryptocurrency prices are market-data inputs, not independently verified carbon-credit valuations.
- **Verification:** Review the verification workflow and underlying calculation assumptions before using project results for real-world carbon-credit issuance.

See `INTEGRATION_STATUS.md`, `backend/README.md`, and `aptos-contracts/README.md` for implementation and setup details.
