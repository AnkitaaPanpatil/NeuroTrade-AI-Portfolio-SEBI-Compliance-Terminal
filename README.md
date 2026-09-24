<!-- STREAMING_CHUNK:Documenting project overview and mission statement -->
# 🧠 NeuroTrade — AI Portfolio & SEBI Compliance Terminal

> **Systematic AI Asset Allocation, Research Synthesis, and Anti-Emotional Execution Shield for Indian Capital Markets.**

**NeuroTrade** is an institutional-grade, web-based wealth management and systematic portfolio rebalancing terminal engineered specifically for retail and high-net-worth investors in the Indian capital markets (NSE & BSE). By synthesizing quantitative macro models, behavioral finance guardrails, and statutory adherence to Securities and Exchange Board of India (**SEBI**) regulations, NeuroTrade systematically solves the three classic causes of retail wealth destruction: **time constraints**, **inadequate research depth**, and **emotion-driven panic/FOMO trading**.

---

<!-- STREAMING_CHUNK:Detailing core problem space and system pillars -->
## 🚨 The Core Problems NeuroTrade Solves

| Traditional Retail Challenge | The Behavioral/Systemic Impact | NeuroTrade Systematic Solution |
| :--- | :--- | :--- |
| **Severe Time Constraints** | Working professionals lack 15+ hours weekly to parse quarterly earnings filings, conference call transcripts, and RBI macro releases. | **Instant 60-Second Deep-Dive**: AI synthesizes filings, valuation percentiles, and earnings health into a structured briefing in seconds. |
| **Inadequate Research** | Relying on unverified social media "hot tips", speculative momentum chases, and penny stocks subject to manipulation. | **SEBI-Screened Quality Universe**: Automatically screens out illiquid scrips, penny counters, and ASM/GSM surveillance list securities. |
| **Emotional Trading Bias** | Chasing parabolic green candles (FOMO) and panic-selling quality compounders at local drawdowns. | **NeuroShield Interception**: Monitors trade frequency, enforces mandatory 120s cooling delays, and intercepts impulse revenge orders. |
| **Concentration Risk** | Over-allocating 30–50% of net worth into a single speculative stock without proper multi-asset hedging. | **SEBI Concentration Guardrails**: Hardcoded 10% single-stock ceiling across all model mandates with automated drift rebalancing. |

---

<!-- STREAMING_CHUNK:Detailing feature modules -->
## 🌟 Core System Pillars

### 1. 🛡️ NeuroShield — Cognitive Bias Interceptor
- **FOMO Over-Extension Index**: Real-time heuristic tracking whether candidate orders chase parabolic green candles after 5+ consecutive up-days.
- **Revenge Trading & Churn Detector**: Detects rapid consecutive stop-loss triggers within 90 minutes and enforces mandatory cooling-off lockout intervals.
- **Sunk Cost & Loss Aversion Anchor**: Flags decaying fundamental investment theses that are held merely to avoid booking a paper loss.
- **Circuit Breakers & Delay Timers**: Enforces a 120-second rational delay timer on high-volatility market orders and a 2.5% daily portfolio risk circuit breaker.

### 2. 📊 Adaptive Multi-Asset Portfolio & Canvas Trajectory
- **Multi-Asset Diversification**: Spreads capital systematically across **Large-Cap Equities**, **Mid-Cap Compounders**, **Government Sovereign Debt (G-Sec 10-Yr)**, **Sovereign Gold Bonds (SGB)**, and **Liquid Cash Buffers**.
- **Drawdown Suppression Engine**: Responsive HTML5 Canvas engine contrasting the dynamic model against the benchmark **NIFTY 50**, exhibiting volatility mitigation and lower max drawdown during market stress periods.
- **Holdings Ledger**: Real-time valuation, unrealized P&L tracking, allocation weightings, and instantaneous compliance status badges.

### 3. ⚡ 60-Second AI Fundamental Research Hub (Powered by Gemini)
- **Institutional Synthesis**: Generates an exhaustive fundamental briefing for any NSE/BSE listed scrip (e.g., `HDFCBANK`, `RELIANCE`, `INFY`, `TCS`, `ITC`).
- **Structured 3-Pillar Breakdown**:
  - 🏛️ **Moat & Core Revenue Drivers** (Operating leverage, market franchise power, and margin health)
  - ⚠️ **Key Headwinds & Macro Risks** (Monetary policy, raw material inflation, regulatory hurdles)
  - 📈 **Quantitative Earnings Health** (ROE, ROIC, Gross NPA for banks, EPS CAGR, and debt coverage)
- **Historical Valuation Lowdown**: Calculates fair value estimates vs. 10-year Price-to-Book (P/B) and Price-to-Earnings (P/E) bands.
- **Offline Heuristic Resiliency**: Built-in algorithmic fallback generation ensures zero downtime even during connectivity interruptions.

### 4. ⚖️ SEBI Statutory Compliance & Audit Trail
- **Single-Stock Concentration Ceiling**: Strictly enforces that no individual equity position exceeds **10.0%** of net aggregate AUM (compliant with SEBI Investment Adviser Regulations).
- **Surveillance & ASM/GSM Filtering**: Prohibits exposure to micro-cap penny stocks, high-debt shell companies, and scrips under Additional Surveillance Measures (ASM) or Graded Surveillance Measures (GSM).
- **Mandate Risk Recalibrator**: Allows users to dynamically recalibrate their mandate (Horizon: 1–5+ years; Drawdown: 10–25%) and automatically computes the statutory Equity Cap, Debt Floor, and Gold Allocation bounds.
- **Exportable Audit Trail**: One-click CSV export of compliance verification logs for tax and regulatory recordkeeping.

### 5. 🤖 Autopilot Rebalancer & Valuation-Aware Smart SIP
- **Drift-Triggered Execution**: Calculates percentage deviations from target mandate allocations and initiates multi-leg batch realignment orders only when drift surpasses ±3%.
- **Valuation-Aware Smart SIP**: Modulates monthly systematic investment plans (SIP) using dynamic P/E valuation multipliers (allocates more aggressively on market corrections and trims into irrational euphoria).

---

<!-- STREAMING_CHUNK:Describing technical stack and architecture -->
## 🛠️ Technical Architecture

NeuroTrade is built as an ultra-fast, zero-dependency, single-file application (`neurotrade_app.html`) engineered for sub-second execution speeds and seamless responsiveness across desktop, tablet, and mobile screens.

| Layer | Technology | Purpose & Implementation Details |
| :--- | :--- | :--- |
| **User Interface** | HTML5 / Semantic DOM | Zero-dependency accessible layout structured into 5 tabbed workspaces |
| **Styling & Theme** | Tailwind CSS CDN | Custom dark palette (`neuro` cyan, `wealth` emerald, `amberAlpha`, `darkSurface` glassmorphism) |
| **Typography** | Google Fonts | `Plus Jakarta Sans` (interface clarity) & `JetBrains Mono` (financial data precision) |
| **Iconography** | FontAwesome 6.5.1 | Financial and compliance vector icons |
| **Chart Rendering** | HTML5 Canvas API | High-DPI responsive time-series trajectory comparing portfolio vs. NIFTY 50 |
| **Audio Feedback** | Web Audio API | Pure synthesized affirmative chimes, rebalance bells, and alert tones |
| **Generative AI** | Google Gemini API (`gemini-3-flash-preview`) | Structured JSON extraction for institutional research reports |
| **State Engine** | In-Memory State Model | Real-time holding evaluations, drift monitors, and behavioral logging |

---

<!-- STREAMING_CHUNK:Providing quick start and setup instructions -->
## 🚀 Quick Start & Installation

NeuroTrade requires **no Node.js build process, no npm dependencies, and no backend compilation**.

### Method 1: Direct Browser Launch
1. Download `neurotrade_app.html`.
2. Double-click the file to open it directly in Google Chrome, Brave, Mozilla Firefox, Microsoft Edge, or Safari.

### Method 2: Local HTTP Server (Recommended)
Running via a lightweight local server ensures optimal handling of cross-origin requests when communicating with external APIs:

```bash
# Using Python 3
python -m http.server 8080

# Or using Node.js (npx)
npx serve .
```

Open your browser and navigate to:
```text
http://localhost:8080/neurotrade_app.html
```

---

<!-- STREAMING_CHUNK:Documenting Gemini API setup and user workflow -->
## 🔑 Connecting the Gemini AI API Key

NeuroTrade comes pre-equipped with an offline quantitative heuristic generator that functions automatically. To enable real-time institutional deep-dives via Google Gemini:

1. Open `neurotrade_app.html` in your text editor.
2. Locate the `generateInstantResearchReport` function (around line 520):
   ```javascript
   const apiKey = "YOUR_GEMINI_API_KEY_HERE";
   ```
3. Obtain a free API key from [Google AI Studio](https://aistudio.google.com/).
4. Insert your key into the empty string, save the file, and refresh your browser.

---

## 🗺️ User Workflow & Experience

```text
  [Portfolio Overview] ─────────> [Inspect Asset] ───────────> [AI 60-Sec Deep Dive]
           │                                                            │
           ▼                                                            ▼
  [Drift Detected (±3%)] ───────> [Autopilot Rebalance] ────> [SEBI Mandate Alignment]
           │                                                            │
           ▼                                                            ▼
  [Emotional Buy/Sell Order] ───> [NeuroShield Guard] ───────> [120s Cooling Pause]
           │                                                            │
           ▼                                                            ▼
  [Monthly Smart SIP] ──────────> [Valuation Multiplier] ───> [Systematic Execution]
```

1. **Morning Inspection**: Check the **Systematic Portfolio** dashboard to review active asset distribution, benchmark alpha vs. NIFTY 50, and single-stock exposure limits.
2. **Instant Research**: Navigate to the **AI Research Hub**, enter any Indian ticker (e.g. `INFY`, `ICICIBANK`, `RELIANCE`), and review the synthesized moat, financial health, and fair value range.
3. **Behavioral Check**: Use **NeuroShield** to evaluate your FOMO index, check behavioral logs, or simulate how irrational sell orders are delayed by cooling-off timers.
4. **Compliance Rebalance**: Access the **Systematic Auto-Rebalancer** tab to view portfolio drift and execute a 1-click batch rebalance to return all asset classes to optimal SEBI mandate weights.

---

<!-- STREAMING_CHUNK:Finalizing legal disclaimer and licensing -->
## ⚖️ Statutory SEBI Compliance & Legal Disclaimer

- **Educational & Algorithmic Tooling**: NeuroTrade is an algorithmic asset allocation and portfolio modeling terminal designed to assist users in maintaining prudent diversification and discipline.
- **SEBI Regulation Reference**: Allocation caps and diversification boundaries are designed in reference to the *Securities and Exchange Board of India (Investment Advisers) Regulations, 2013*.
- **No Direct Investment Advice**: Automated outputs, AI research summaries, and simulations do not constitute personal financial advice or a guarantee of investment returns. Users should conduct their own due diligence or consult a SEBI-registered Investment Adviser (RIA) before committing capital.

---

## 📄 License

This software is released under the [MIT License](LICENSE) — free to utilize, customize, and extend for personal portfolio management, wealth-tech hackathons, and research initiatives.
