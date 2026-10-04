# 🍯 MadhuChain
*Problem Statement: "Honey Chain" — SIH26021 | Team Spark Innovator | Team ID 141528*

### Decentralized Honey Traceability Ecosystem
**Smart India Hackathon 2026 | Problem Statement SIH26021**
**Ministry of MSME / KVIC | Software Category**

> **Note:** This repository contains the Phase 2 simulated prototype (HTML5, CSS3, JavaScript on GitHub Pages).
> Phase 3 (Grand Finale) will be built on the production stack shown below.
> Hive telemetry is simulated from weather-API data, and all numbers in the prototype are demo data.

---

## 🎯 Problem Statement

- **77%** of tested honey brands failed NMR purity test — 10 of 13 brands (CSE India, Dec 2020)
- Beekeepers earn **~₹85/kg** to middlemen vs **~₹400/kg** retail price — huge income gap
- **Zero** bottle-level traceability exists in current market
- Only **~14,859** beekeepers registered on Madhukranti portal (PIB, Oct 2025) — large gap
- Rural farmers exploited by middlemen with no direct market access

---

## 💡 Our Solution

A **₹0/month** decentralized ecosystem offering:

- ✅ Dual-Key Anti-Counterfeit — QR Code + Secret 6-Character Cap PIN
- ✅ Hyperledger Fabric v2.5 Blockchain Traceability
- ✅ Self-hosted AI Advisory (Ollama + Qwen 2.5) in Hindi/English/Hinglish via Telegram Bot
- ✅ Bee Credits → Direct DBT Subsidy to Farmers
- ✅ ₹20 Consumer Cashback per verified bottle (500g, MRP ₹300)
- ✅ 217 crore+ unique Cap PIN combinations — single-use, auto-disabled after first scan
- ✅ Weather-based hive risk alerts at 4:00 AM and 4:00 PM daily

---

## 🖥️ Live Prototype Demo

| Screen | Live Link |
|--------|-----------|
| 🏠 Home | [View Demo](https://jitendrakush404-debug.github.io/MaDhuChain/) |
| 👨‍🌾 Farmer Bot | [View Demo](https://jitendrakush404-debug.github.io/MaDhuChain/farmer-bot.html) |
| 📱 Customer App | [View Demo](https://jitendrakush404-debug.github.io/MaDhuChain/customer-app.html) |
| 🏛️ Admin Dashboard | [View Demo](https://jitendrakush404-debug.github.io/MaDhuChain/admin-dashboard.html) |

---

## 🎥 Demo Video

> *(Upload hone ke baad link yahan add karein)*
> `https://youtu.be/<your-video-id>`

---

## 📁 Prototype Files

- `index.html` — Landing page (problem, solution, 3 platforms, tech stack, impact)
- `farmer-bot.html` — Telegram bot simulation (AI chat, hive status, Bee Credits)
- `customer-app.html` — QR scan + 6-character Cap PIN verification + cashback
- `admin-dashboard.html` — KVIC admin portal (onboarding, QR generator, blockchain explorer, fraud alerts)

---

## 🏗️ Technical Stack

| Layer | Technology |
|-------|------------|
| Frontend | React.js + React Native / PWA |
| Backend | Node.js + Express.js + Socket.io + Node-cron |
| Blockchain | Hyperledger Fabric v2.5 |
| AI Engine | Ollama + Qwen 2.5 (3B) — Self-hosted, zero API cost |
| Database | PostgreSQL (Supabase) + MongoDB Atlas |
| Media Storage | Cloudinary |
| Weather / IoT Sim | OpenWeatherMap API (sensor-ready architecture) |
| Bot | Telegram Bot API |
| Hosting | Vercel / GitHub Pages + Oracle Cloud Free VM |

---

## 📊 3-Screen Architecture

┌─────────────────────────────────────────────────────────┐ │ MadhuChain Ecosystem │ ├──────────────────┬──────────────────┬───────────────────┤ │ Screen 1 │ Screen 2 │ Screen 3 │ │ Farmer Bot │ Customer App │ Admin Panel │ │ (Telegram) │ (PWA) │ (KVIC Dashboard) │ │ │ │ │ │ • 4 AM / 4 PM │ • QR Scan │ • Onboarding │ │ Hive Alerts │ • Cap PIN Input │ Queue │ │ • AI Advisory │ • ₹20 Cashback │ • QR + Cap Code │ │ Hindi/English │ • Farmer Story │ Generator │ │ /Hinglish │ • Blockchain │ • Blockchain │ │ • Bee Credits │ Proof │ Explorer │ │ Check │ • Health Tips │ • Fraud Alerts │ └──────────────────┴──────────────────┴───────────────────┘ │ │ │ └────────────────┴──────────────────┘ Hyperledger Fabric v2.5 PostgreSQL + Cloudinary Ollama + Qwen 2.5 (3B)


---

## 💰 Unit Economics

| Component | Amount |
|-----------|--------|
| Bottle Size | 500 g |
| Retail Price (MRP) | ₹300 |
| Built-in Guarantee Fund | ₹30 |
| Consumer Cashback | ₹20 |
| Farmer Bee Credits (DBT) | ₹5 |
| System Maintenance | ₹5 |
| **Monthly Operating Cost** | **₹0** |

> AI runs on self-hosted Oracle Cloud Free VM (Ollama + Qwen 2.5).
> No paid API. No monthly subscription. No gas fees (permissioned chain).

---

## 🔐 Security Model

| Threat | Our Defence |
|--------|-------------|
| QR Code Clone | 6-character Cap PIN required (inside bottle cap) |
| PIN Brute Force | 217 crore+ combinations + 5 attempts lock |
| Double Scan Fraud | City mismatch detection → auto-block in seconds |
| Data Tampering | Hyperledger Fabric immutable ledger |
| API Cost | Self-hosted AI — zero external dependency |

---

## 👨‍🌾 Target Beneficiaries

- **~14,859** beekeepers currently registered on Madhukranti (PIB, Oct 2025)
- Rural farmers on 2G networks — Telegram works smoothly on low bandwidth
- KVIC cooperative network across India
- Consumers paying ₹400–600/kg without purity guarantee

---

## 📈 Potential Impact at Scale

| Metric | Data |
|--------|------|
| Brands failing NMR purity test | 77% (CSE India, Dec 2020) |
| India honey export FY 2023-24 | ~1.07 lakh tonnes ($177.55M) |
| Beekeepers on Madhukranti | ~14,859 (PIB, Oct 2025) |
| Unique Cap PIN combinations | 217 crore+ (2.17 billion) |
| Monthly operating cost | ₹0 (system design) |
| Farmer income target | ₹85/kg → ₹250/kg via KVIC chain |

---

## 📚 References

| Reference | Source |
|-----------|--------|
| 77% NMR failure — 10 of 13 brands tested | [CSE India, Dec 2020](https://www.cseindia.org/content/downloadreports/10494) |
| India honey export ~1.07 lakh tonnes, $177.55M FY 2023-24 | [PIB — NBHM, Nov 2025](https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/nov/doc2025112682601.pdf) |
| 14,859 beekeepers on Madhukranti (Oct 2025) | Same PIB document above |
| FSSAI Honey Standards | [fssai.gov.in](https://www.fssai.gov.in) |
| Hyperledger Fabric v2.5 | [hyperledger-fabric.readthedocs.io](https://hyperledger-fabric.readthedocs.io) |
| Ollama + Qwen 2.5 (3B) | [ollama.com/library/qwen2.5](https://ollama.com/library/qwen2.5) |

---

## 🏆 Competition Details

| Field | Details |
|-------|---------|
| Competition | Smart India Hackathon 2026 |
| Problem Statement | SIH26021 — "Honey Chain" |
| Ministry | MSME (KVIC) |
| Theme | Agriculture, FoodTech & Rural Development |
| Category | Software |
| Team Name | Spark Innovator |
| Team ID | 141528 |

---

*Phase 2 simulated prototype built for SIH 2026. Not an official KVIC / MSME product.*

© 2026 MadhuChain — Team Spark Innovator