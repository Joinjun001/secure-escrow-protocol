# Perp DEX

Ethereum 기반 하이브리드 DEX 프로젝트.

- 주문/매칭: Off-chain
- 자금 보관/정산: On-chain
- 네트워크: Ethereum Sepolia

## Tech Stack

- Solidity + Foundry
- TypeScript
- Next.js
- NestJS
- PostgreSQL
- Prisma
- Docker
- MetaMask / wagmi / viem

## Structure

```text
.
├── contracts/
├── backend/
├── frontend/
└── docker-compose.yml
```

## Initial Goal

```text
Deposit
→ Limit Order
→ Matching
→ Settlement
→ Withdraw
```

## Run

### Contracts

```bash
cd contracts
forge build
forge test
```

### Backend

```bash
cd backend
npm run start:dev
```

### Frontend

```bash
cd frontend
npm run dev
```

### Database

```bash
docker compose up -d
```
