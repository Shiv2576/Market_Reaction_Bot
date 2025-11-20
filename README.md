# MRT — Market Reaction Trading Bot

> Real-time whale-driven trading signals for Ethereum & Solana, delivered via Telegram

MRT is a self-hosted, privacy-first trading signal engine that monitors Bitcoin whale activity on **Mempool.Space** and predicts short-term price impact on **Ethereum** and **Solana**. Signals are delivered instantly to Telegram—no cloud dependencies, no KYC, no noise.

## ✨ Core Features

- 🤖 **Telegram-native alerts** – Structured signals with entry, target, stop-loss, and chain context  
- 🐋 **Whale transaction detection** – Real-time scraping of >100 BTC moves from Mempool.Space  
- 📊 **Cross-chain impact modeling** – Maps BTC whale behavior to ETH/SOL volatility using on-chain lags & DEX flows  
- 🎯 **Confidence scoring** – Dynamic signal reliability based on historical correlation and market regime  
- 🔌 **Modular engine** – Extend logic in **Go** or **TypeScript** (e.g., Uniswap V3 liquidity, Chainlink oracles)  
- 💾 **Offline-first & self-hosted** – Runs entirely on your infrastructure; state persisted via `better-sqlite3`  
- 🌙 **Dark-mode documentation** – Clean, minimal docs (black background, off-white text) powered by **Docus + Nuxt 4**

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start dev server (docs + signal formatting layer)
npm run dev
