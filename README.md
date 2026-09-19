# Awesome Trading Stock

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[日本語版はこちら / Japanese](README.ja.md)

A curated list of useful **stock / markets / trading** resources — market-data APIs, charting, backtesting, broker docs, filings, quant tooling, and Japan (JPX / EDINET / J-Quants). Prefer durable official / project URLs.

**Discovery list only** — not investment advice, not a recommendation to trade, and not a ranking of brokers or strategies.

## Contents

- [Market data & APIs](#market-data--apis)
- [Charting & terminals](#charting--terminals)
- [Backtesting & research](#backtesting--research)
- [Broker & execution APIs](#broker--execution-apis)
- [Technical analysis](#technical-analysis)
- [Quant / ML platforms](#quant--ml-platforms)
- [Filings & fundamentals](#filings--fundamentals)
- [Japan markets](#japan-markets)
- [Education & papers](#education--papers)
- [Related lists](#related-lists)
- [Contributing](#contributing)

---

## Market data & APIs

Historical and streaming market data for research and apps.

- [OpenBB](https://openbb.co/) - Open data platform for analysts, quants, and AI agents. ([GitHub](https://github.com/OpenBB-finance/OpenBB))
- [yfinance](https://ranaroussi.github.io/yfinance/) - Pythonic access to Yahoo Finance market data (community-maintained). ([GitHub](https://github.com/ranaroussi/yfinance))
- [Polygon.io](https://polygon.io/) - Stocks, options, forex, and crypto REST + WebSocket market data.
- [Tiingo](https://www.tiingo.com/) - End-of-day and IEX-backed equities data API.
- [Alpha Vantage](https://www.alphavantage.co/) - Stock, forex, and crypto APIs with a free developer tier.
- [Nasdaq Data Link (Quandl)](https://data.nasdaq.com/) - Economic and alternative datasets marketplace.
- [AKShare](https://akshare.akfamily.xyz/) - Python financial-data interfaces with strong China-market coverage. ([GitHub](https://github.com/akfamily/akshare))
- [ccxt](https://github.com/ccxt/ccxt) - Unified trading / market-data API across many crypto exchanges.

---

## Charting & terminals

Visualization and interactive analysis.

- [TradingView](https://www.tradingview.com/) - Charts, screeners, and social ideas; Pine Script for custom indicators.
- [Pine Script v6 reference](https://www.tradingview.com/pine-script-reference/v6/) - Official Pine language reference.
- [Lightweight Charts](https://www.tradingview.com/lightweight-charts/) - TradingView’s open-source HTML5 financial charts. ([GitHub](https://github.com/tradingview/lightweight-charts))
- [Fincept Terminal](https://github.com/Fincept-Corporation/FinceptTerminal) - Open-source finance terminal / analytics UI.
- [mplfinance](https://github.com/matplotlib/mplfinance) - Matplotlib candlestick and OHLC plotting for pandas.

---

## Backtesting & research

Event-driven and vectorized engines for strategy research (paper / sim first).

- [QuantConnect Lean](https://www.lean.io/) - Open-source algorithmic trading engine (Python / C#) with cloud and local workflows. ([GitHub](https://github.com/QuantConnect/Lean))
- [NautilusTrader](https://nautilustrader.io/) - High-performance event-driven trading platform (Rust core, Python). ([GitHub](https://github.com/nautechsystems/nautilus_trader))
- [backtrader](https://www.backtrader.com/) - Classic Python backtesting library. ([GitHub](https://github.com/mementum/backtrader))
- [vectorbt](https://vectorbt.dev/) - Fast vectorized backtesting and portfolio analysis. ([GitHub](https://github.com/polakowo/vectorbt))
- [backtesting.py](https://kernc.github.io/backtesting.py/) - Lightweight Python backtester. ([GitHub](https://github.com/kernc/backtesting.py))
- [Zipline Reloaded](https://github.com/stefan-jansen/zipline-reloaded) - Maintained fork of Quantopian’s Zipline pipeline.
- [StockSharp](https://stocksharp.com/) - Full trading platform (C#) for equities, FX, crypto, and options. ([GitHub](https://github.com/stocksharp/stocksharp))
- [Jesse](https://jesse.trade/) - Crypto-focused Python trading / backtesting framework. ([GitHub](https://github.com/jesse-ai/jesse))
- [freqtrade](https://www.freqtrade.io/) - Open-source crypto trading bot with backtesting and hyperopt. ([GitHub](https://github.com/freqtrade/freqtrade))

---

## Broker & execution APIs

Official or widely used broker / gateway documentation (check local regs and account eligibility).

- [Alpaca Docs](https://docs.alpaca.markets/) - Commission-free US equities / crypto API; paper trading. ([alpaca-py](https://github.com/alpacahq/alpaca-py))
- [Interactive Brokers — TWS API](https://www.interactivebrokers.com/campus/ibkr-api-page/twsapi-doc/) - Multi-asset broker API via TWS / IB Gateway.
- [ib_insync](https://ib-insync.readthedocs.io/) - Friendly Python wrapper around the IB TWS API.
- [Tradier Docs](https://documentation.tradier.com/) - Brokerage REST API with strong options support.
- [kabuステーション API](https://kabucom.github.io/kabusapi/ptal/) - Japanese equities / derivatives API (三菱UFJ eスマート証券). ([GitHub](https://github.com/kabucom/kabusapi))

---

## Technical analysis

Indicators and signal helpers.

- [TA-Lib](https://ta-lib.org/) - Widely used technical-analysis C library with Python bindings.
- [pandas-ta](https://www.pandas-ta.dev/) - Technical indicators as a pandas DataFrame extension.
- [ta](https://github.com/bukosabino/ta) - Technical analysis indicators in pandas / NumPy.
- [Kand](https://github.com/kand-ta/kand) - Fast technical analysis (Rust / Python / WASM).

---

## Quant / ML platforms

Research stacks for factor models, ML workflows, and portfolio analytics.

- [Microsoft Qlib](https://qlib.readthedocs.io/) - AI-oriented quantitative investment platform. ([GitHub](https://github.com/microsoft/qlib))
- [gs-quant](https://developer.gs.com/docs/gsquant/) - Goldman Sachs quantitative toolkit (Python). ([GitHub](https://github.com/goldmansachs/gs-quant))
- [QuantStats](https://github.com/ranaroussi/quantstats) - Portfolio performance analytics and tear sheets.
- [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) - Open-source financial LLM resources (AI4Finance).
- [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) - Open-source AI agent platform for financial applications.
- [TradingAgents](https://github.com/TauricResearch/TradingAgents) - Multi-agent LLM trading research framework.
- [TradeMaster](https://github.com/TradeMaster-NTU/TradeMaster) - RL-oriented quantitative trading platform (NTU).

---

## Filings & fundamentals

Regulatory disclosure portals and structured fundamentals.

- [SEC EDGAR](https://www.sec.gov/edgar) - US company filings search.
- [SEC EDGAR APIs](https://www.sec.gov/search-filings/edgar-application-programming-interfaces) - Official submissions and XBRL JSON APIs (`data.sec.gov`).
- [EDINET](https://disclosure2.edinet-fsa.go.jp/) - Japan FSA electronic disclosure system (有価証券報告書など).
- [EDINET API guides](https://disclosure2dl.edinet-fsa.go.jp/guide/static/disclosure/WEEK0060.html) - Official API / taxonomy documentation (Japanese).
- [FRED](https://fred.stlouisfed.org/) - Federal Reserve Economic Data (macro time series + API).

---

## Japan markets

Exchanges, official data products, and JP-oriented tooling.

- [Japan Exchange Group (JPX)](https://www.jpx.co.jp/english/) - Tokyo Stock Exchange / Osaka Exchange group home ([日本語](https://www.jpx.co.jp/)).
- [JPX Data & Statistics](https://www.jpx.co.jp/english/markets/index.html) - Official market summaries and published statistics.
- [J-Quants API](https://jpx-jquants.com/) - JPX historical prices, financials, and related datasets for individuals. ([JPX overview](https://www.jpx.co.jp/markets/other-data-services/j-quants-api/index.html))
- [TDnet](https://www.release.tdnet.info/) - Timely Disclosure Network for TSE-listed company announcements.
- [金融庁 (FSA)](https://www.fsa.go.jp/) - Japan Financial Services Agency policy and disclosure information.
- [kabuステーション API](https://kabucom.github.io/kabusapi/ptal/) - Local PC-based trading API for Japanese markets.
- [python-kabusapi](https://github.com/shirasublue/python-kabusapi) - Community Python bindings for kabu STATION API.

---

## Education & papers

Learning material and paper collections (still not advice).

- [Machine Learning for Trading](https://github.com/stefan-jansen/machine-learning-for-trading) - Code / notebooks companion to Jansen’s ML-for-trading book.
- [Quantopian Lectures (archived)](https://github.com/quantopian/research_public) - Classic lecture notebooks on factors and pipelines.
- [Awesome LLM Quantitative Trading Papers](https://github.com/Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers) - Papers on LLM-based quantitative trading.
- [ssrn.com](https://www.ssrn.com/) - Working papers across finance and economics.

---

## Related lists

- [wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant) - Broad quant libraries and resources.
- [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) - Systematic trading awesome list.
- [wangzhe3224/awesome-systematic-trading](https://github.com/wangzhe3224/awesome-systematic-trading) - Large curated systematic trading list.
- [georgezouq/awesome-ai-in-finance](https://github.com/georgezouq/awesome-ai-in-finance) - AI / deep learning in finance.
- [AI4Finance-Foundation/Awesome_AI4Finance](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance) - AI4Finance curated resources.
- [merovinh/best-of-algorithmic-trading](https://github.com/merovinh/best-of-algorithmic-trading) - Ranked algorithmic-trading projects.
- [tradingview/awesome-tradingview](https://github.com/tradingview/awesome-tradingview) - TradingView ecosystem resources.
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) - The Awesome meta-list.

---

## Contributing

Contributions welcome — open a pull request to add a resource, fix a broken link, or suggest a category.

Prefer **durable official / docs URLs**, short blurbs, and actively maintained projects. Keep product and organization names; mark language or region when helpful. This list is for **discovery only** (no financial advice framing). Update both `README.md` and `README.ja.md` when you can.
