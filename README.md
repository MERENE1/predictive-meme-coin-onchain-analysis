# Predictive On-Chain Analysis of Meme Coins  
### Behavioral Lead–Lag Comparison (PEPE vs WIF)

This project applies a behavioral on-chain framework to compare two Ethereum meme coins and evaluate whether **early behavioral signals can distinguish strong performers from weaker ones**.

Rather than explaining price action after the fact, the goal is to identify **predictive signals** observable *before* major trading expansions.

---

## 📌 Objective

To determine whether differences in:
- wallet onboarding,
- trade intent,
- and capital quality

can be used to **screen meme coins with higher probability of future momentum**.

---

## 🪙 Assets Analyzed

| Token | Symbol | Role |
|-----|-------|-----|
| PEPE | PEPE | Benchmark (strong performer) |
| Dogwifhat (ETH) | WIF | Comparison asset |

Both assets trade actively on Ethereum DEXs and share similar retail-driven dynamics.

---

## 🧱 Data Source

- **DEX Trades:** `dex.trades`
- **Blockchain:** Ethereum
- **Tooling:** Dune Analytics
- **Granularity:** Daily

---

## 🧠 Methodology

The same behavioral framework is applied identically to both tokens to ensure comparability.

### 1. Trade Extraction
- All buys and sells normalized to daily data
- Wallet-level participation tracked

### 2. Wallet Classification
- First-seen date calculated per wallet
- Wallets classified as:
  - New
  - Returning

### 3. Behavioral Metrics
Daily metrics include:
- Active wallets
- New wallets
- Buy vs sell trade counts
- Buy ratio
- Median trade size
- USD trading volume

---

## 🔮 Predictive Signals Evaluated

### New Wallet Growth
Measures fresh capital entering the ecosystem.

### Buy-Side Dominance
Captures directional conviction prior to attention phases.

### Trade Size Dynamics
Acts as a proxy for capital quality and early whale participation.

### Volume Timing
Used as a confirmation metric rather than a predictor.

---

## 📊 Comparative Findings

### PEPE
- Sustained growth in new wallets prior to major volume expansions
- Rising buy ratios ahead of runs
- Increasing median trade size before peak activity

### WIF
- Weaker or inconsistent new wallet onboarding
- Buy pressure less persistent
- Trade size expansion occurred closer to volume peaks

---

## 🧠 Key Insight

> Strong meme coin performers exhibit **coordinated behavioral shifts** before volume and price expansion, while weaker assets show delayed or fragmented signals.

This suggests that **on-chain behavior can be used as a screening mechanism**, not just a descriptive tool.

---

## 🚀 Why This Matters

This framework can be used to:
- Compare early-stage meme coins
- Filter out noise-driven pumps
- Support data-backed trade thesis formation

The PEPE vs WIF comparison demonstrates how **behavioral divergence emerges before market consensus**.

---

## 🛠 Skills Demonstrated

- On-chain behavioral analysis
- Comparative asset research
- SQL (Dune / Trino)
- Data storytelling and documentation

---

## dashboard (https://dune.com/akp_m/behavioral-comparison-of-meme-coins-ethereum?utm_source=share&utm_medium=copy&utm_campaign=dashboard)

This dashboard compares on-chain behavioral signals for two Ethereum meme coins (PEPE and WIF) to identify early indicators of trading momentum.

The visualizations track daily new wallet onboarding, buy-side versus sell-side activity, median trade size, and USD trading volume. By aligning these metrics over time, the dashboard highlights how coordinated increases in new wallets, buy pressure, and trade size tend to precede volume expansions in stronger-performing meme coins.

The comparison illustrates that PEPE exhibits earlier and more sustained behavioral shifts relative to WIF, suggesting that on-chain behavior can be used as a leading signal to screen meme coins before broader market attention emerges.

