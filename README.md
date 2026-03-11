# Gateway Wallet: Institutional Web3 Interface

Gateway Wallet is a high-fidelity, non-custodial blockchain interface designed for institutional-grade asset management. Built with a focus on immersive 3D aesthetics and secure decentralised interaction, it provides a seamless bridge to the Ethereum ecosystem.

## 💎 High-Fidelity Features

### 1. Immersive 3D/Neon UI
- **Dynamic 3D Environment**: Powered by Three.js and `@react-three/fiber`, featuring a floating particle system and interactive Ethereum assets.
- **Neon Design System**: A cohesive glassmorphic UI with vibrant neon accents (`#bc13fe`, `#08f7fe`) and smooth Framer Motion micro-interactions.
- **Interactive Cursor**: A magnetic, neon-responsive cursor that enhances the sense of tactile depth across the dashboard.
- **Responsive Architecture**: Fully optimized for mobile, tablet, and desktop viewports with fluid typography and adaptive grids.

### 2. Robust Blockchain Infrastructure
- **Ethers v6 Integration**: Real-time interaction with the Sepolia Testnet for account management and transaction broadcasting.
- **Wallet Intelligence**: Automatic network detection, Sepolia enforcement, and real-time balance synchronisation.
- **Transparent Ledger**: Persistent, IndexedDB-backed transaction history with direct links to Etherscan for auditability.
- **Gas Optimization**: Integrated gas estimation for efficient on-chain ETH transfers.

### 3. Institutional Vault Protocol
- **SimpleWallet Integration**: Direct interaction with the `SimpleWallet` smart contract for professional asset segregation.
- **Secure Custody**: Non-custodial vault for long-term ETH deposits and withdrawals, ensuring assets never leave your machine's local control until you authorise.

---

## 🛠️ Tech Stack

- **Core**: Vite, React 18, TypeScript
- **Blockchain**: Ethers v6, MetaMask API
- **Visuals**: Three.js, React Three Fiber, Framer Motion
- **Styling**: Tailwind CSS, Shadcn UI, Lucide Icons
- **State/Storage**: TanStack Query, LocalForage (IndexedDB)

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- npm / pnpm
- MetaMask Extension (Connected to Sepolia Testnet)

### Installation
```bash
# 1. Clone & Install
git clone <repository-url>
cd gateway-wallet
npm install

# 2. Configure Environment
# Create a .env file with:
# VITE_SEPOLIA_RPC_URL=your_rpc_url
# VITE_VAULT_ADDRESS=your_deployed_contract_address

# 3. Launch Development Server
npm run dev
```

---

## 🏛️ Academic Context (University Viva)

This project was developed as a comprehensive final-year blockchain implementation, scoring for 300-mark evaluation criteria.

**Key Evaluation Points:**
- **Security**: Zero-knowledge storage policy; private keys never touch the server-side.
- **UX/UI**: Modern 3D/Neon aesthetic implementation using industry-standard libraries.
- **Integration**: Successful Ethers v6 handshake and smart contract settlement.
- **Responsiveness**: Cross-device stability with performance-optimised rendering.

---
*Developed for excellence in Web3 Engineering.*
