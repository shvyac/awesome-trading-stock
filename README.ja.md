# Awesome Trading Stock（日本語）

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English README](README.md)

**株式／マーケット／トレーディング**向けの有用なリソースの厳選リストです。マーケットデータ API、チャート、バックテスト、ブローカー資料、開示情報、クオンツツール、そして日本（JPX／EDINET／J-Quants）を中心にまとめています。できるだけ公式／プロジェクトの耐久性のある URL を優先しています。

**発見・学習用のリストです。** 投資助言・売買推奨ではなく、ブローカーや戦略のランキングでもありません。

## 目次

- [マーケットデータ・API](#マーケットデータapi)
- [チャート・ターミナル](#チャートターミナル)
- [バックテスト・リサーチ](#バックテストリサーチ)
- [ブローカー・執行 API](#ブローカー執行-api)
- [テクニカル分析](#テクニカル分析)
- [クオンツ／ML プラットフォーム](#クオンツml-プラットフォーム)
- [開示・ファンダメンタルズ](#開示ファンダメンタルズ)
- [日本市場](#日本市場)
- [学習・論文](#学習論文)
- [関連リスト](#関連リスト)
- [コントリビューション](#コントリビューション)

---

## マーケットデータ・API

リサーチやアプリ向けのヒストリカル／ストリーミング市場データ。

- [OpenBB（英語）](https://openbb.co/) - アナリスト・クオンツ・AI エージェント向けのオープンデータ基盤。（[GitHub](https://github.com/OpenBB-finance/OpenBB)）
- [yfinance（英語）](https://ranaroussi.github.io/yfinance/) - Yahoo Finance 系マーケットデータへの Python アクセス（コミュニティ維持）。（[GitHub](https://github.com/ranaroussi/yfinance)）
- [Polygon.io（英語）](https://polygon.io/) - 株式・オプション・FX・暗号資産の REST／WebSocket マーケットデータ。
- [Tiingo（英語）](https://www.tiingo.com/) - 終値および IEX 系株式データ API。
- [Alpha Vantage（英語）](https://www.alphavantage.co/) - 株式・FX・暗号資産 API（無料開発者枠あり）。
- [Nasdaq Data Link（Quandl）（英語）](https://data.nasdaq.com/) - 経済・オルタナティブデータセットのマーケットプレイス。
- [AKShare（英語／中国語）](https://akshare.akfamily.xyz/) - 中国市場に強い Python 金融データインタフェース。（[GitHub](https://github.com/akfamily/akshare)）
- [ccxt（英語）](https://github.com/ccxt/ccxt) - 多数の暗号資産取引所を横断する統一取引／マーケットデータ API。

---

## チャート・ターミナル

可視化とインタラクティブ分析。

- [TradingView（英語）](https://www.tradingview.com/) - チャート、スクリーナー、アイデア共有。カスタム指標は Pine Script。
- [Pine Script v6 リファレンス（英語）](https://www.tradingview.com/pine-script-reference/v6/) - 公式 Pine 言語リファレンス。
- [Lightweight Charts（英語）](https://www.tradingview.com/lightweight-charts/) - TradingView のオープンソース HTML5 金融チャート。（[GitHub](https://github.com/tradingview/lightweight-charts)）
- [Fincept Terminal（英語）](https://github.com/Fincept-Corporation/FinceptTerminal) - オープンソースのファイナンスターミナル／分析 UI。
- [mplfinance（英語）](https://github.com/matplotlib/mplfinance) - pandas 向け Matplotlib ローソク足／OHLC 描画。

---

## バックテスト・リサーチ

戦略研究向けのイベント駆動／ベクトル化エンジン（まず紙上／シミュレーション）。

- [QuantConnect Lean（英語）](https://www.lean.io/) - オープンソースのアルゴ取引エンジン（Python／C#）。クラウドとローカル両対応。（[GitHub](https://github.com/QuantConnect/Lean)）
- [NautilusTrader（英語）](https://nautilustrader.io/) - 高性能イベント駆動トレーディング基盤（Rust コア、Python）。（[GitHub](https://github.com/nautechsystems/nautilus_trader)）
- [backtrader（英語）](https://www.backtrader.com/) - 定番の Python バックテストライブラリ。（[GitHub](https://github.com/mementum/backtrader)）
- [vectorbt（英語）](https://vectorbt.dev/) - 高速なベクトル化バックテストとポートフォリオ分析。（[GitHub](https://github.com/polakowo/vectorbt)）
- [backtesting.py（英語）](https://kernc.github.io/backtesting.py/) - 軽量な Python バックテスター。（[GitHub](https://github.com/kernc/backtesting.py)）
- [Zipline Reloaded（英語）](https://github.com/stefan-jansen/zipline-reloaded) - Quantopian Zipline のメンテ継続フォーク。
- [StockSharp（英語）](https://stocksharp.com/) - 株式・FX・暗号・オプション向けフル取引プラットフォーム（C#）。（[GitHub](https://github.com/stocksharp/stocksharp)）
- [Jesse（英語）](https://jesse.trade/) - 暗号資産向け Python 取引／バックテストフレームワーク。（[GitHub](https://github.com/jesse-ai/jesse)）
- [freqtrade（英語）](https://www.freqtrade.io/) - バックテストとハイパーパラメータ探索付きのオープンソース暗号取引ボット。（[GitHub](https://github.com/freqtrade/freqtrade)）

---

## ブローカー・執行 API

公式または広く使われるブローカー／ゲートウェイ資料（各国の規制と口座適格性を確認してください）。

- [Alpaca Docs（英語）](https://docs.alpaca.markets/) - 米国株／暗号の API。ペーパートレードあり。（[alpaca-py](https://github.com/alpacahq/alpaca-py)）
- [Interactive Brokers — TWS API（英語）](https://www.interactivebrokers.com/campus/ibkr-api-page/twsapi-doc/) - TWS／IB Gateway 経由のマルチアセット API。
- [ib_insync（英語）](https://ib-insync.readthedocs.io/) - IB TWS API 向けの扱いやすい Python ラッパー。
- [Tradier Docs（英語）](https://documentation.tradier.com/) - オプションに強いブローカー REST API。
- [kabuステーション API](https://kabucom.github.io/kabusapi/ptal/) - 国内株式／派生商品向け API（三菱UFJ eスマート証券）。（[GitHub](https://github.com/kabucom/kabusapi)）

---

## テクニカル分析

指標・シグナル用ヘルパー。

- [TA-Lib（英語）](https://ta-lib.org/) - 広く使われるテクニカル分析 C ライブラリ（Python バインディングあり）。
- [pandas-ta（英語）](https://www.pandas-ta.dev/) - pandas DataFrame 拡張としてのテクニカル指標。
- [ta（英語）](https://github.com/bukosabino/ta) - pandas／NumPy ベースのテクニカル指標。
- [Kand（英語）](https://github.com/kand-ta/kand) - 高速テクニカル分析（Rust／Python／WASM）。

---

## クオンツ／ML プラットフォーム

ファクターモデル、ML ワークフロー、ポートフォリオ分析向けリサーチスタック。

- [Microsoft Qlib（英語）](https://qlib.readthedocs.io/) - AI 志向の定量投資プラットフォーム。（[GitHub](https://github.com/microsoft/qlib)）
- [gs-quant（英語）](https://developer.gs.com/docs/gsquant/) - Goldman Sachs の定量ツールキット（Python）。（[GitHub](https://github.com/goldmansachs/gs-quant)）
- [QuantStats（英語）](https://github.com/ranaroussi/quantstats) - ポートフォリオ実績分析と tear sheet。
- [FinGPT（英語）](https://github.com/AI4Finance-Foundation/FinGPT) - オープンソースの金融 LLM リソース（AI4Finance）。
- [FinRobot（英語）](https://github.com/AI4Finance-Foundation/FinRobot) - 金融アプリ向けオープンソース AI エージェント基盤。
- [TradingAgents（英語）](https://github.com/TauricResearch/TradingAgents) - マルチエージェント LLM トレーディング研究フレームワーク。
- [TradeMaster（英語）](https://github.com/TradeMaster-NTU/TradeMaster) - 強化学習志向の定量取引プラットフォーム（NTU）。

---

## 開示・ファンダメンタルズ

規制開示ポータルと構造化ファンダメンタルズ。

- [SEC EDGAR（英語）](https://www.sec.gov/edgar) - 米国企業の開示検索。
- [SEC EDGAR APIs（英語）](https://www.sec.gov/search-filings/edgar-application-programming-interfaces) - 提出履歴・XBRL JSON の公式 API（`data.sec.gov`）。
- [EDINET](https://disclosure2.edinet-fsa.go.jp/) - 金融庁の電子開示システム（有価証券報告書など）。
- [EDINET API 操作ガイド等](https://disclosure2dl.edinet-fsa.go.jp/guide/static/disclosure/WEEK0060.html) - 公式 API／タクソノミ文書。
- [FRED（英語）](https://fred.stlouisfed.org/) - 米連邦準備の経済データ（マクロ時系列＋API）。

---

## 日本市場

取引所、公式データ、国内向けツール。

- [日本取引所グループ（JPX）](https://www.jpx.co.jp/) - 東証／大証などを含む取引所グループ（[English](https://www.jpx.co.jp/english/)）。
- [JPX マーケット情報・統計（英語）](https://www.jpx.co.jp/english/markets/index.html) - 公式の市場サマリーと統計。
- [J-Quants API](https://jpx-jquants.com/) - 個人向けのヒストリカル株価・財務など。（[JPX 概要](https://www.jpx.co.jp/markets/other-data-services/j-quants-api/index.html)）。
- [TDnet](https://www.release.tdnet.info/) - 適時開示情報伝達システム。
- [金融庁](https://www.fsa.go.jp/) - 政策・開示関連情報。
- [kabuステーション API](https://kabucom.github.io/kabusapi/ptal/) - 国内市場向け PC ベース取引 API。
- [python-kabusapi（英語）](https://github.com/shirasublue/python-kabusapi) - kabuステーション API のコミュニティ Python バインディング。

---

## 学習・論文

学習教材と論文コレクション（これも助言ではありません）。

- [Machine Learning for Trading（英語）](https://github.com/stefan-jansen/machine-learning-for-trading) - Jansen 著 ML for Trading のコード／ノートブック。
- [Quantopian Lectures（アーカイブ）（英語）](https://github.com/quantopian/research_public) - ファクターやパイプラインの古典的な講義ノート。
- [Awesome LLM Quantitative Trading Papers（英語）](https://github.com/Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers) - LLM ベース定量取引の論文集。
- [SSRN（英語）](https://www.ssrn.com/) - ファイナンス・経済学のワーキングペーパー。

---

## 関連リスト

- [wilsonfreitas/awesome-quant（英語）](https://github.com/wilsonfreitas/awesome-quant) - 広範なクオンツライブラリ／リソース。
- [paperswithbacktest/awesome-systematic-trading（英語）](https://github.com/paperswithbacktest/awesome-systematic-trading) - システマティック取引の Awesome リスト。
- [wangzhe3224/awesome-systematic-trading（英語）](https://github.com/wangzhe3224/awesome-systematic-trading) - 大規模なシステマティック取引リスト。
- [georgezouq/awesome-ai-in-finance（英語）](https://github.com/georgezouq/awesome-ai-in-finance) - ファイナンスにおける AI／深層学習。
- [AI4Finance-Foundation/Awesome_AI4Finance（英語）](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance) - AI4Finance の厳選リソース。
- [merovinh/best-of-algorithmic-trading（英語）](https://github.com/merovinh/best-of-algorithmic-trading) - アルゴ取引プロジェクトのランキング系リスト。
- [tradingview/awesome-tradingview（英語）](https://github.com/tradingview/awesome-tradingview) - TradingView 生態系リソース。
- [sindresorhus/awesome（英語）](https://github.com/sindresorhus/awesome) - Awesome のメタリスト。

---

## コントリビューション

コントリビューション歓迎です。リソース追加、リンク切れ修正、カテゴリ提案はプルリクエストでどうぞ。

**公式／ドキュメントの耐久性のある URL**、短い説明、継続的にメンテナンスされているプロジェクトを優先してください。製品名・団体名はそのまま。言語や地域が分かるように書くと親切です。本リストは**発見用のみ**（投資助言の体裁にしない）。可能なら `README.md` と `README.ja.md` の両方を更新してください。
