# Awesome Trading Stock

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[日本語版はこちら / Japanese](README.ja.md)

A curated list of useful **stock / markets / trading** resources — market-data APIs, charting, backtesting, broker docs, filings, quant tooling, and Japan (JPX / EDINET / J-Quants). Prefer durable official / project URLs. ⭐ badges show live GitHub star counts (via shields.io).

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
- [shvyac's awesome lists](#shvyacs-awesome-lists)

---

## Market data & APIs

Historical and streaming market data for research and apps.

- [OpenBB](https://openbb.co/) ![GitHub stars](https://img.shields.io/github/stars/openbq-org/OpenBB?style=flat&label=%E2%AD%90) - Open data platform for analysts, quants, and AI agents. The company wound down in Aug 2026 and open-sourced its full stack; the non-profit [OpenBQ](https://openbq.org/) now stewards the project ([announcement](https://openbb.co/blog/openbb-belongs-to-everyone)); the GitHub repo moved to the openbq-org organization. ([GitHub](https://github.com/openbq-org/OpenBB))
- [yfinance](https://ranaroussi.github.io/yfinance/) ![GitHub stars](https://img.shields.io/github/stars/ranaroussi/yfinance?style=flat&label=%E2%AD%90) - Pythonic access to Yahoo Finance market data (community-maintained). ([GitHub](https://github.com/ranaroussi/yfinance))
- [Massive (formerly Polygon.io)](https://massive.com/) - Stocks, options, indices, forex, and futures REST + WebSocket market data (rebranded from Polygon.io; old domain redirects). ([MCP server](https://github.com/massive-com/mcp_massive) ![GitHub stars](https://img.shields.io/github/stars/massive-com/mcp_massive?style=flat&label=%E2%AD%90))
- [Tiingo](https://www.tiingo.com/) - End-of-day and IEX-backed equities data API.
- [Alpha Vantage](https://www.alphavantage.co/) - Stock, forex, and crypto APIs with a free developer tier.
- [Nasdaq Data Link (Quandl)](https://data.nasdaq.com/) - Economic and alternative datasets marketplace.
- [AKShare](https://akshare.akfamily.xyz/) ![GitHub stars](https://img.shields.io/github/stars/akfamily/akshare?style=flat&label=%E2%AD%90) - Python financial-data interfaces with strong China-market coverage. ([GitHub](https://github.com/akfamily/akshare))
- [ccxt](https://github.com/ccxt/ccxt) ![GitHub stars](https://img.shields.io/github/stars/ccxt/ccxt?style=flat&label=%E2%AD%90) - Unified trading / market-data API across 100+ crypto exchanges and prediction markets (JS / TS, Python, C#, PHP, Go, Java, Rust).

---

## Charting & terminals

Visualization and interactive analysis.

- [TradingView](https://www.tradingview.com/) - Charts, screeners, and social ideas; Pine Script for custom indicators.
- [Pine Script v6 reference](https://www.tradingview.com/pine-script-reference/v6/) - Official Pine language reference.
- [Lightweight Charts](https://www.tradingview.com/lightweight-charts/) ![GitHub stars](https://img.shields.io/github/stars/tradingview/lightweight-charts?style=flat&label=%E2%AD%90) - TradingView’s open-source HTML5 financial charts. ([GitHub](https://github.com/tradingview/lightweight-charts))
- [Fincept Terminal](https://github.com/Fincept-Corporation/FinceptTerminal) ![GitHub stars](https://img.shields.io/github/stars/Fincept-Corporation/FinceptTerminal?style=flat&label=%E2%AD%90) - Open-source finance terminal (C++ / Qt) for market analytics, investment research, and economic data.
- [mplfinance](https://github.com/matplotlib/mplfinance) ![GitHub stars](https://img.shields.io/github/stars/matplotlib/mplfinance?style=flat&label=%E2%AD%90) - Matplotlib candlestick and OHLC plotting for pandas (no commits since Aug 2024).

---

## Backtesting & research

Event-driven and vectorized engines for strategy research (paper / sim first).

- [QuantConnect Lean](https://www.lean.io/) ![GitHub stars](https://img.shields.io/github/stars/QuantConnect/Lean?style=flat&label=%E2%AD%90) - Open-source algorithmic trading engine (Python / C#) with cloud and local workflows. ([GitHub](https://github.com/QuantConnect/Lean))
- [NautilusTrader](https://nautilustrader.io/) ![GitHub stars](https://img.shields.io/github/stars/nautechsystems/nautilus_trader?style=flat&label=%E2%AD%90) - High-performance event-driven trading platform (Rust core, Python). ([GitHub](https://github.com/nautechsystems/nautilus_trader))
- [backtrader](https://www.backtrader.com/) ![GitHub stars](https://img.shields.io/github/stars/mementum/backtrader?style=flat&label=%E2%AD%90) - Classic Python backtesting library (mature; little recent development). ([GitHub](https://github.com/mementum/backtrader))
- [vectorbt](https://vectorbt.dev/) ![GitHub stars](https://img.shields.io/github/stars/polakowo/vectorbt?style=flat&label=%E2%AD%90) - Fast vectorized backtesting and portfolio analysis. ([GitHub](https://github.com/polakowo/vectorbt))
- [backtesting.py](https://kernc.github.io/backtesting.py/) ![GitHub stars](https://img.shields.io/github/stars/kernc/backtesting.py?style=flat&label=%E2%AD%90) - Lightweight Python backtester. ([GitHub](https://github.com/kernc/backtesting.py))
- [Zipline Reloaded](https://github.com/stefan-jansen/zipline-reloaded) ![GitHub stars](https://img.shields.io/github/stars/stefan-jansen/zipline-reloaded?style=flat&label=%E2%AD%90) - Maintained fork of Quantopian’s Zipline pipeline.
- [hftbacktest](https://github.com/nkaz001/hftbacktest) ![GitHub stars](https://img.shields.io/github/stars/nkaz001/hftbacktest?style=flat&label=%E2%AD%90) - High-frequency / market-making backtester (Rust, Python) modeling queue position, latency, and L2/L3 order books.
- [StockSharp](https://stocksharp.com/) ![GitHub stars](https://img.shields.io/github/stars/StockSharp/StockSharp?style=flat&label=%E2%AD%90) - Full trading platform (C#) for equities, FX, crypto, and options. ([GitHub](https://github.com/StockSharp/StockSharp))
- [Jesse](https://jesse.trade/) ![GitHub stars](https://img.shields.io/github/stars/jesse-ai/jesse?style=flat&label=%E2%AD%90) - Crypto-focused Python trading / backtesting framework. ([GitHub](https://github.com/jesse-ai/jesse))
- [freqtrade](https://www.freqtrade.io/) ![GitHub stars](https://img.shields.io/github/stars/freqtrade/freqtrade?style=flat&label=%E2%AD%90) - Open-source crypto trading bot with backtesting and hyperopt. ([GitHub](https://github.com/freqtrade/freqtrade))
- [Hummingbot](https://hummingbot.org/) ![GitHub stars](https://img.shields.io/github/stars/hummingbot/hummingbot?style=flat&label=%E2%AD%90) - Open-source framework for building and running crypto market-making and arbitrage bots across CEX / DEX connectors. ([GitHub](https://github.com/hummingbot/hummingbot))

---

## Broker & execution APIs

Official or widely used broker / gateway documentation (check local regs and account eligibility).

- [Alpaca Docs](https://docs.alpaca.markets/) - Commission-free equities / options / crypto API with paper trading; docs are split by region (US, EU, UK, JP, etc.). ([alpaca-py](https://github.com/alpacahq/alpaca-py) ![GitHub stars](https://img.shields.io/github/stars/alpacahq/alpaca-py?style=flat&label=%E2%AD%90), [official MCP server](https://github.com/alpacahq/alpaca-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/alpacahq/alpaca-mcp-server?style=flat&label=%E2%AD%90))
- [Interactive Brokers — TWS API](https://www.interactivebrokers.com/campus/ibkr-api-page/twsapi-doc/) - Multi-asset broker API via TWS / IB Gateway (recent versions use Protobuf messaging; Python 3.11+).
- [ib_async](https://github.com/ib-api-reloaded/ib_async) ![GitHub stars](https://img.shields.io/github/stars/ib-api-reloaded/ib_async?style=flat&label=%E2%AD%90) - Community-maintained successor to ib_insync: friendly Python (asyncio) wrapper around the IB TWS API. (The original [ib_insync](https://github.com/erdewit/ib_insync) ![GitHub stars](https://img.shields.io/github/stars/erdewit/ib_insync?style=flat&label=%E2%AD%90) repo is archived.)
- [Tradier API](https://docs.tradier.com/) - Brokerage REST + streaming API for US equities and options (docs moved from documentation.tradier.com).
- [kabuステーション API](https://kabucom.github.io/kabusapi/ptal/) ![GitHub stars](https://img.shields.io/github/stars/kabucom/kabusapi?style=flat&label=%E2%AD%90) - Japanese equities / derivatives API (三菱UFJ eスマート証券). ([GitHub](https://github.com/kabucom/kabusapi))

---

## Technical analysis

Indicators and signal helpers.

- [TA-Lib](https://ta-lib.org/) - Widely used technical-analysis C library with Python bindings. ([Python wrapper](https://github.com/TA-Lib/ta-lib-python) ![GitHub stars](https://img.shields.io/github/stars/TA-Lib/ta-lib-python?style=flat&label=%E2%AD%90))
- [pandas-ta](https://pypi.org/project/pandas-ta/) - Technical indicators as a pandas DataFrame extension (original GitHub repo and pandas-ta.dev site no longer available; latest PyPI release is 0.4.71b0 beta from Sep 2025, Python 3.12+).
- [ta](https://github.com/bukosabino/ta) ![GitHub stars](https://img.shields.io/github/stars/bukosabino/ta?style=flat&label=%E2%AD%90) - Technical analysis indicators in pandas / NumPy.
- [Kand](https://github.com/kand-ta/kand) ![GitHub stars](https://img.shields.io/github/stars/kand-ta/kand?style=flat&label=%E2%AD%90) - Fast technical analysis (Rust / Python / WASM).

---

## Quant / ML platforms

Research stacks for factor models, ML workflows, and portfolio analytics.

- [Microsoft Qlib](https://qlib.readthedocs.io/) ![GitHub stars](https://img.shields.io/github/stars/microsoft/qlib?style=flat&label=%E2%AD%90) - AI-oriented quantitative investment platform. ([GitHub](https://github.com/microsoft/qlib))
- [gs-quant](https://developer.gs.com/docs/gsquant/) ![GitHub stars](https://img.shields.io/github/stars/goldmansachs/gs-quant?style=flat&label=%E2%AD%90) - Goldman Sachs quantitative toolkit (Python). ([GitHub](https://github.com/goldmansachs/gs-quant))
- [QuantStats](https://github.com/ranaroussi/quantstats) ![GitHub stars](https://img.shields.io/github/stars/ranaroussi/quantstats?style=flat&label=%E2%AD%90) - Portfolio performance analytics and tear sheets.
- [skfolio](https://skfolio.org/) ![GitHub stars](https://img.shields.io/github/stars/skfolio/skfolio?style=flat&label=%E2%AD%90) - Portfolio optimization and risk management built on scikit-learn. ([GitHub](https://github.com/skfolio/skfolio))
- [Riskfolio-Lib](https://riskfolio-lib.readthedocs.io/) ![GitHub stars](https://img.shields.io/github/stars/dcajasn/Riskfolio-Lib?style=flat&label=%E2%AD%90) - Portfolio optimization library (mean-risk, risk parity, CVaR, drawdown models). ([GitHub](https://github.com/dcajasn/Riskfolio-Lib))
- [QuantLib](https://www.quantlib.org/) ![GitHub stars](https://img.shields.io/github/stars/lballabio/QuantLib?style=flat&label=%E2%AD%90) - Free / open-source C++ library for derivatives pricing, fixed income, and risk modeling (Python bindings available). ([GitHub](https://github.com/lballabio/QuantLib))
- [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) ![GitHub stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat&label=%E2%AD%90) - Open-source financial LLM resources (AI4Finance).
- [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) ![GitHub stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat&label=%E2%AD%90) - Open-source AI agent platform for financial applications.
- [TradingAgents](https://github.com/TauricResearch/TradingAgents) ![GitHub stars](https://img.shields.io/github/stars/TauricResearch/TradingAgents?style=flat&label=%E2%AD%90) - Multi-agent LLM trading research framework.
- [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) ![GitHub stars](https://img.shields.io/github/stars/HKUDS/Vibe-Trading?style=flat&label=%E2%AD%90) - Open-source personal LLM trading agent (HKU Data Intelligence Lab): natural-language strategy research, backtesting, and MCP integration.
- [daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) ![GitHub stars](https://img.shields.io/github/stars/ZhuLinsen/daily_stock_analysis?style=flat&label=%E2%AD%90) - LLM-powered multi-market stock analysis system (strong China A-share focus): multi-source quotes, real-time news, decision dashboard, and automated notifications with free scheduled runs.
- [TradeMaster](https://github.com/TradeMaster-NTU/TradeMaster) ![GitHub stars](https://img.shields.io/github/stars/TradeMaster-NTU/TradeMaster?style=flat&label=%E2%AD%90) - RL-oriented quantitative trading platform (NTU).

---

## Filings & fundamentals

Regulatory disclosure portals and structured fundamentals.

- [SEC EDGAR — Search Filings](https://www.sec.gov/search-filings) - US company filings search ([Full-Text Search](https://www.sec.gov/edgar/search/)).
- [SEC EDGAR APIs](https://www.sec.gov/search-filings/edgar-application-programming-interfaces) - Official submissions and XBRL JSON APIs (`data.sec.gov`).
- [FinanceToolkit](https://github.com/JerBouma/FinanceToolkit) ![GitHub stars](https://img.shields.io/github/stars/JerBouma/FinanceToolkit?style=flat&label=%E2%AD%90) - Transparent Python toolkit for financial-statement analysis, ratios, valuation, and risk / performance metrics (includes an MCP server).
- [EDINET](https://disclosure2.edinet-fsa.go.jp/) - Japan FSA electronic disclosure system (有価証券報告書など).
- [EDINET API guides](https://disclosure2dl.edinet-fsa.go.jp/guide/static/disclosure/WEEK0060.html) - Official API / taxonomy documentation (Japanese).
- [FRED](https://fred.stlouisfed.org/) - Federal Reserve Economic Data (macro time series + API).

---

## Japan markets

Exchanges, official data products, and JP-oriented tooling.

- [Japan Exchange Group (JPX)](https://www.jpx.co.jp/english/) - Tokyo Stock Exchange / Osaka Exchange group home ([日本語](https://www.jpx.co.jp/)).
- [JPX Data & Statistics](https://www.jpx.co.jp/english/markets/index.html) - Official market summaries and published statistics.
- [J-Quants API](https://jpx-jquants.com/) - JPX historical prices, financials, and related datasets for individuals. V2 API (Dec 2025) uses API keys (V1 token login removed; accounts registered since 22 Dec 2025 are V2-only) and offers an official MCP server; bulk CSV and equity minute-bar / tick data added Jan 2026 (Light plan+). ([JPX overview](https://www.jpx.co.jp/markets/other-data-services/j-quants-api/index.html), [V1 → V2 migration](https://jpx-jquants.com/ja/spec/migration-v1-v2), [Python client](https://github.com/J-Quants/jquants-api-client-python) ![GitHub stars](https://img.shields.io/github/stars/J-Quants/jquants-api-client-python?style=flat&label=%E2%AD%90))
- [TDnet](https://www.release.tdnet.info/) - Timely Disclosure Network for TSE-listed company announcements.
- [金融庁 (FSA)](https://www.fsa.go.jp/) - Japan Financial Services Agency policy and disclosure information.
- [kabuステーション API](https://kabucom.github.io/kabusapi/ptal/) - Local PC-based trading API for Japanese markets.
- [python-kabusapi](https://github.com/shirasublue/python-kabusapi) ![GitHub stars](https://img.shields.io/github/stars/shirasublue/python-kabusapi?style=flat&label=%E2%AD%90) - Community Python bindings for kabu STATION API (not updated since 2021).

---

## Education & papers

Learning material and paper collections (still not advice).

- [Machine Learning for Trading](https://github.com/stefan-jansen/machine-learning-for-trading) ![GitHub stars](https://img.shields.io/github/stars/stefan-jansen/machine-learning-for-trading?style=flat&label=%E2%AD%90) - Code / notebooks companion to Jansen’s ML-for-trading book (3rd edition: from data sourcing to live execution). ([ml4trading.io](https://ml4trading.io))
- [Quantopian Lectures (archived)](https://github.com/quantopian/research_public) ![GitHub stars](https://img.shields.io/github/stars/quantopian/research_public?style=flat&label=%E2%AD%90) - Classic lecture notebooks on factors and pipelines.
- [Awesome LLM Quantitative Trading Papers](https://github.com/Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers) ![GitHub stars](https://img.shields.io/github/stars/Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers?style=flat&label=%E2%AD%90) - Papers on LLM-based quantitative trading.
- [SSRN](https://papers.ssrn.com/) - Working papers across finance and economics.

---

## Related lists

- [wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant) ![GitHub stars](https://img.shields.io/github/stars/wilsonfreitas/awesome-quant?style=flat&label=%E2%AD%90) - Broad quant libraries and resources.
- [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) ![GitHub stars](https://img.shields.io/github/stars/paperswithbacktest/awesome-systematic-trading?style=flat&label=%E2%AD%90) - Systematic trading awesome list.
- [wangzhe3224/awesome-systematic-trading](https://github.com/wangzhe3224/awesome-systematic-trading) ![GitHub stars](https://img.shields.io/github/stars/wangzhe3224/awesome-systematic-trading?style=flat&label=%E2%AD%90) - Large curated systematic trading list.
- [georgezouq/awesome-ai-in-finance](https://github.com/georgezouq/awesome-ai-in-finance) ![GitHub stars](https://img.shields.io/github/stars/georgezouq/awesome-ai-in-finance?style=flat&label=%E2%AD%90) - AI / deep learning in finance.
- [AI4Finance-Foundation/Awesome_AI4Finance](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance) ![GitHub stars](https://img.shields.io/github/stars/AI4Finance-Foundation/Awesome_AI4Finance?style=flat&label=%E2%AD%90) - AI4Finance curated resources.
- [merovinh/best-of-algorithmic-trading](https://github.com/merovinh/best-of-algorithmic-trading) ![GitHub stars](https://img.shields.io/github/stars/merovinh/best-of-algorithmic-trading?style=flat&label=%E2%AD%90) - Ranked algorithmic-trading projects.
- [tradingview/awesome-tradingview](https://github.com/tradingview/awesome-tradingview) ![GitHub stars](https://img.shields.io/github/stars/tradingview/awesome-tradingview?style=flat&label=%E2%AD%90) - TradingView ecosystem resources.
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ![GitHub stars](https://img.shields.io/github/stars/sindresorhus/awesome?style=flat&label=%E2%AD%90) - The Awesome meta-list.

---

## Contributing

Contributions welcome — open a pull request to add a resource, fix a broken link, or suggest a category.

Prefer **durable official / docs URLs**, short blurbs, and actively maintained projects. Keep product and organization names; mark language or region when helpful. This list is for **discovery only** (no financial advice framing). Update both `README.md` and `README.ja.md` when you can.

---

## shvyac's awesome lists

All curated lists maintained by [shvyac](https://github.com/shvyac):

- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-azure-ai-dynamics365-security](https://github.com/shvyac/awesome-azure-ai-dynamics365-security) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-azure-ai-dynamics365-security?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-hpc](https://github.com/shvyac/awesome-hpc) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hpc?style=flat&label=%E2%AD%90)
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
