# ⚡ StarkYield — One-Tap Crypto Yield on Starknet

> Connect your wallet. Pick a pool. Earn yield. Zero gas fees.

![StarkYield Banner](https://img.shields.io/badge/Built%20with-Starkzap%20SDK-00f5a0?style=for-the-badge)
![Starknet](https://img.shields.io/badge/Network-Starknet-00c8ff?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-white?style=for-the-badge)

---

## 🎯 What is StarkYield?

StarkYield is a **one-tap crypto yield dashboard** built on Starknet. It removes all the complexity from DeFi yield farming — users simply connect their wallet, browse available yield pools, enter an amount, and stake in a single click. All transactions are **completely gasless** thanks to the Starkzap Paymaster.

---

## ✨ Features

- 🔌 **Wallet Connect** — Supports ArgentX, Braavos, OKX via Starkzap Wallets module
- ⚡ **Zero Gas Fees** — Every transaction routed through Starkzap Paymaster
- 📈 **Live Yield Pools** — STRK, BTC, and USDC pools with real-time APY
- 💰 **Yield Calculator** — Instant preview of daily/monthly/yearly earnings
- 📊 **Position Dashboard** — Track all your active staking positions
- 📱 **Mobile-First UI** — Fully responsive across all devices

---

## 🛠️ Starkzap Modules Used

| Module | Usage |
|--------|-------|
| **Wallets** | Wallet connection (ArgentX, Braavos, OKX) |
| **Paymaster (Gasless)** | All stake/unstake transactions are gasless |
| **Staking** | Pool staking, yield tracking, position management |

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- A Starknet wallet (ArgentX or Braavos recommended)

### Installation

```bash
git clone https://github.com/YOUR_USERNAME/starkyield
cd starkyield
npm install
npm run dev
```

### Or open directly
Just open `index.html` in your browser — no build step required for the demo!

---

## 🏗️ How It Works

```
User Opens App
      ↓
Connect Wallet (Starkzap Wallets SDK)
      ↓
Browse Yield Pools (STRK / BTC / USDC)
      ↓
Enter Amount → See Yield Preview
      ↓
Click "Stake Now"
      ↓
Starkzap Paymaster handles gas
      ↓
Transaction submitted to Starknet
      ↓
Position tracked in dashboard ✅
```

---

## 📊 Yield Pools

| Pool | APY | Token | Risk |
|------|-----|-------|------|
| STRK Staking Pool | 12.4% | STRK | Low |
| BTC Yield Vault | 8.7% | BTC | Medium |
| USDC Stable Pool | 6.1% | USDC | Low |

---

## 🔗 Links

- **Live App**: [https://starkyield.vercel.app](https://starkyield.vercel.app)
- **GitHub**: [https://github.com/YOUR_USERNAME/starkyield](https://github.com/YOUR_USERNAME/starkyield)
- **Starkzap SDK**: [https://github.com/keep-starknet-strange/starkzap](https://github.com/keep-starknet-strange/starkzap)

---

## 🏆 Starkzap Developer Challenge

This project was built for the **Starkzap Developer Challenge** (Feb 24 – Mar 17, 2025).

**Why StarkYield should win:**
- Uses **all 3 Starkzap modules** (Wallets + Paymaster + Staking)
- Solves a real problem: DeFi yield is too complex for most users
- Clean, production-grade UI that any user can understand
- Fully functional with real wallet integration flow

---

## 📄 License

MIT © 2025 StarkYield
