#  Betfin Poker Game

## Next-Generation Crypto Poker Platform

Betfin Poker is a blockchain-powered gaming platform that brings competitive poker into the Web3 ecosystem. 
Players can join poker tables, compete for rewards, and engage with a decentralized staking economy. 
Built on EVM-compatible chains, Betfin Poker combines skill-based gameplay, smart contract security, and community-driven incentives.

---

![](client/src/assets/game/First-background.jpg)

---

##  Features
- **Decentralized Poker Rooms**: Host, join, and spectate Texas Hold'em games
- **Play-to-Earn (P2E)**: Earn real crypto rewards
- **NFT Avatars**: Use unique NFT avatars at the table
- **On-Chain Game Logic**: Fair, transparent, and tamper-proof
- **Token Staking**: Stake tokens for rewards and in-game benefits
- **Modern UI/UX**: Responsive, mobile-friendly design
- **Secure & Regulated**: Built by a globally trusted financial group

---

## Project Structure

### Frontend & Player Dashboard

* React + Next.js – Responsive UI for game tables, player stats, and staking dashboards.
* Real-Time Interactions – WebSocket integration for instant game updates.
* Wallet-Connected Experience – Players interact directly with their crypto wallets for game actions and payouts.

### Admin & Game Operations Panel

* Admins can create and manage poker tables, set buy-in limits, and configure blind structures.
* Real-time tracking of active games, player activity, and transaction histories.
* Tools to detect collusion or cheating behaviors, ensuring a fair gaming environment.

### Backend (Microservices)

* Node.js + Express.js – Handles game matchmaking, session management, and player authentication.
* Golang Modules – For high-performance poker engine logic and concurrency handling.
* Blockchain Integration – Ethers.js and Web3.js for wallet connections and smart contract calls.
* Real-time data delivery for game states, betting actions, and chat features.

---

## Getting Started

### 1. Clone the repository
```bash
git clone <project repo url>
cd <project directory name>
```

### 2. Install and start backend dependencies
```bash
npm install
npm start
```

### 3. Install frontend dependencies
Open new terminal
```bash
cd client
npm install
cd ..
```

### 4. Run both with one command from the root:
```bash
npm start
```

---

## 🛡️ License

This project is licensed under the **ISC License**.
