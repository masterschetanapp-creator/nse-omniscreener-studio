# NSE OmniScreener Studio

**NSE OmniScreener Studio** is a unified, zero-cost Indian equity research terminal combining the most powerful analytical models across **Screener.in**, **Tickertape**, **Trendlyne**, **Tijori Finance**, **Chartink**, **TradingView**, and **StockEdge**.

Deployed directly via **Streamlit** for universal 24/7 web access across desktops, tablets, and smartphones.

---

## 🚀 Key Features

1. **Universal NSE Coverage:** All 2,620 active equities listed on the National Stock Exchange of India (NSE).
2. **Institutional Financial Health Scoring:**
   - **Piotroski F-Score (0–9):** Complete 9-point fundamental accounting quality test.
   - **Altman Z-Score:** Solvency and bankruptcy risk classifier (Safe, Grey, Distress zones).
   - **Forward PEG Ratio:** Growth-adjusted forward valuation multiple.
3. **Intrinsic Value Calculators:**
   - **Interactive 2-Stage DCF Model:** Free Cash Flow discounting with dynamic sliders for Cost of Capital (WACC), Explicit 5-Year Growth, and Terminal Growth Rate.
   - **Benjamin Graham Fair Value:** Classic formula $\sqrt{22.5 \times \text{EPS} \times \text{BVPS}}$ with Margin of Safety (MOS) %.
4. **Interactive Multi-Platform Analytics:**
   - **Tickertape:** Market Mood Index (MMI) sentiment speedometer.
   - **Trendlyne:** Durability, Valuation, Momentum (DVM) scorecards and Superstar portfolios (Rekha Jhunjhunwala, Ashish Kacholia, Vijay Kedia, etc.).
   - **Tijori Finance:** Product and segmental revenue breakdowns.
   - **Chartink:** Moving average crossovers (Golden Cross, Death Cross), RSI oversold/overbought, 52-week high breakout scanners.
   - **TradingView:** Interactive candlestick charts with 20, 50, and 200 DMAs.
   - **StockEdge:** High delivery volume percentages and institutional bulk/block deals.
5. **Auto-Updating Data Cache:**
   - Built-in `@st.cache_data(ttl=3600)` with automatic 1-hour updates from official NSE market data feeds and on-demand refresh.

---

## 📦 Local Installation & Execution

```bash
git clone https://github.com/masterschetanapp-creator/nse-omniscreener-studio.git
cd nse-omniscreener-studio
pip install -r requirements.txt
streamlit run app.py
```
