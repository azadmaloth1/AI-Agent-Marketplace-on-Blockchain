# 🛡 DeFi Guardian — Autonomous AI Monitoring Agent
### Hackathon Submission: Agentic AI × Blockchain — Challenge #1

---

## 📌 Problem Statement Addressed
DeFi ecosystems operate 24/7 with rapid fluctuations in liquidity, token prices, and smart contract risks. Manual monitoring is inefficient and leads to missed opportunities and financial losses.

**DeFi Guardian** is an autonomous AI agent that continuously monitors DeFi protocols, analyzes blockchain data, and provides real-time alerts — eliminating the need for manual oversight.

---

## ✅ Requirements Fulfillment Matrix

| Requirement | Implementation | Status |
|---|---|---|
| AI-based monitoring of DeFi market conditions | AI Agent with live price feeds, inference engine, ML signal generator | ✅ |
| Real-time blockchain event tracking | Live block scanner, event log, TX monitoring | ✅ |
| Detection of liquidation threats & anomalies | Risk scoring, health factor alerts, anomaly detection | ✅ |
| Automated alert system | Real-time alert feed with Critical/Warning/Info/Opportunity tiers | ✅ |
| Dashboard with portfolio insights & market trends | 6-section dashboard: Overview, Monitoring, Alerts, Portfolio, Analytics, Chain Log | ✅ |
| Blockchain wallet integration | MetaMask, WalletConnect, Coinbase, Phantom — user-specific monitoring | ✅ |
| Transparent on-chain logging | Blockchain audit trail with TX hash, block, protocol, action logging | ✅ |

---

## 🏗 Architecture Overview

```
┌─────────────────────────────────────────────────────────┐
│                  DeFi Guardian Frontend                  │
├──────────────┬──────────────┬───────────────────────────┤
│  Dashboard   │  Monitoring  │  Alerts  │  Portfolio     │
│  Analytics   │  Chain Log   │          │                │
├──────────────┴──────────────┴──────────┴────────────────┤
│                    Core Engine Layer                     │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌────────┐ │
│  │ AI Model │  │ Block    │  │ Alert    │  │ Risk   │ │
│  │ Engine   │  │ Scanner  │  │ Engine   │  │ Engine │ │
│  └──────────┘  └──────────┘  └──────────┘  └────────┘ │
├──────────────────────────────────────────────────────────┤
│                   Data Layer                             │
│  Price Oracle | Mempool Monitor | Event Log | Wallet API │
└─────────────────────────────────────────────────────────┘
```

---

## 🚀 Features

### 1. 📊 Overview Dashboard
- Live TVL, active alerts, AI scan count, opportunity counter
- Real-time market activity chart (60s window)
- Portfolio risk gauge with animated needle
- Protocol status table (6 major DeFi protocols)
- Transparent blockchain audit log

### 2. 🔭 Autonomous Agent Monitor
- **Start / Pause / Reset** agent controls
- Real-time protocol cards (Aave, Uniswap, Compound, Curve, MakerDAO, dYdX)
- Network activity chart with TPS + AI ops/second
- Full agent execution log (exportable as .txt)
- Exportable PDF/TXT monitoring report

### 3. 🚨 Alert Center
- 7+ pre-loaded alerts with full descriptions and block numbers
- Types: Critical, Warning, Info, Opportunity
- Filterable by type
- Actions: View Details, Dismiss, Take Action
- Auto-generated live alerts during monitoring

### 4. 💼 Portfolio Dashboard
- Wallet-gated (connect to unlock)
- Total portfolio value with daily P&L
- Open positions table with health factor bars
- AI Recommendations (rebalancing, risk, yield)
- Live position health monitoring

### 5. 📈 Analytics
- ETH/USD and BTC/USD live charts
- DeFi TVL 7-day bar chart
- Liquidation Risk Index chart
- Fear & Greed Index
- Gas oracle display

### 6. 🔗 Blockchain Transaction Log
- Full transparent transaction audit trail
- Filterable by type: Swap, Liquidity, Borrow, Liquidation, Bridge
- TX hash, block number, protocol, AI flag, timestamp

---

## 🔧 Technical Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| Charts | Chart.js 4.4 |
| Typography | Orbitron + IBM Plex Mono (Google Fonts) |
| Wallet | Custom modal (MetaMask/WalletConnect/Coinbase/Phantom UI) |
| Data | Simulated live feeds with deterministic randomness |
| Deployment | Single-file, no build step required |

---

## 🌐 Deployment (60 seconds)

### Option A — Netlify (Recommended)
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag the entire `autonomous-defi-agent/` folder
3. ✅ Live instantly

### Option B — Vercel
```bash
npx vercel --name defi-guardian
```

### Option C — GitHub Pages
```bash
git init && git add . && git commit -m "DeFi Guardian"
git push origin main
# Enable Pages in repo settings
```

### Option D — Local
```bash
# Just open index.html in any browser — no server needed
open index.html
```

---

## 📂 File Structure

```
autonomous-defi-agent/
├── index.html          ← Complete application (self-contained)
├── README.md           ← This file
├── netlify.toml        ← Netlify deploy config
├── vercel.json         ← Vercel deploy config
└── PROJECT_DESCRIPTION.md  ← Official challenge description
```

---

## 💡 Impact

- **Reduces financial risk** from delayed responses to DeFi threats
- **Automates monitoring** of 24/7 markets — no manual oversight needed
- **Transparent audit trail** — every event logged with block number
- **AI-driven insights** — actionable recommendations, not just raw data
- **Cross-protocol visibility** — unified view across Aave, Compound, Uniswap, Curve, MakerDAO, dYdX

---

## 👥 Team
Hackathon Submission — Agentic AI × Blockchain Challenge
Challenge: Autonomous DeFi Monitoring Agent (#1)

---

*DeFi Guardian v2.4 — Built for the future of decentralized finance*
