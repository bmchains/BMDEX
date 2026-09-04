# MemeFlow DEX

A non-custodial multichain DEX starter project with a frontend and backend.

## Included
- Frontend: Vite + React + TypeScript
- Backend: Express + TypeScript
- Wallet connection interface
- Token swap interface
- Portfolio and transaction API endpoints
- Network configuration for Ethereum, BSC, Polygon, Tron, and Solana
- Safety-first architecture: no private keys, seed phrases, fake balances, or admin withdrawal backdoors

## Run
```bash
npm install
npm run dev
```

Frontend: http://localhost:5173
Backend: http://localhost:4000

This is a production-oriented starter, not a deployed exchange. Before mainnet use, add audited router integrations, RPC providers, persistent storage, monitoring, rate limits, KYC/AML controls where legally required, and independent security audits.
