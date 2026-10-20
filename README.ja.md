# Awesome Trading Stock（日本語）

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English README](README.md)

**株式／マーケット／トレーディング**向けの有用なリソースの厳選リストです。マーケットデータ API、チャート、バックテスト、ブローカー資料、開示情報、クオンツツール、そして日本（JPX／EDINET／J-Quants）を中心にまとめています。できるだけ公式／プロジェクトの耐久性のある URL を優先しています。 ⭐ バッジは GitHub のスター数をリアルタイム表示します(shields.io)。

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
- [shvyac の awesome リスト](#shvyac-の-awesome-リスト)

---

## マーケットデータ・API

リサーチやアプリ向けのヒストリカル／ストリーミング市場データ。

- [OpenBB（英語）](https://openbb.co/) ![GitHub stars](https://img.shields.io/github/stars/openbq-org/OpenBB?style=flat&label=%E2%AD%90) - アナリスト・クオンツ・AI エージェント向けのオープンデータ基盤。運営会社は2026年8月に事業を終了し全製品をオープンソース化、現在は非営利団体 [OpenBQ](https://openbq.org/) がプロジェクトを継承（[告知](https://openbb.co/blog/openbb-belongs-to-everyone)）。GitHub リポジトリは openbq-org 組織へ移管。（[GitHub](https://github.com/openbq-org/OpenBB)）
- [yfinance（英語）](https://ranaroussi.github.io/yfinance/) ![GitHub stars](https://img.shields.io/github/stars/ranaroussi/yfinance?style=flat&label=%E2%AD%90) - Yahoo Finance 系マーケットデータへの Python アクセス（コミュニティ維持）。（[GitHub](https://github.com/ranaroussi/yfinance)）
- [Massive（旧 Polygon.io）（英語）](https://massive.com/) - 株式・オプション・指数・FX・先物の REST／WebSocket マーケットデータ（Polygon.io から改称。旧ドメインはリダイレクト）。（[MCP サーバー](https://github.com/massive-com/mcp_massive) ![GitHub stars](https://img.shields.io/github/stars/massive-com/mcp_massive?style=flat&label=%E2%AD%90)）
- [Tiingo（英語）](https://www.tiingo.com/) - 終値および IEX 系株式データ API。
- [Alpha Vantage（英語）](https://www.alphavantage.co/) - 株式・FX・暗号資産 API（無料開発者枠あり）。
- [Nasdaq Data Link（Quandl）（英語）](https://data.nasdaq.com/) - 経済・オルタナティブデータセットのマーケットプレイス。
- [AKShare（英語／中国語）](https://akshare.akfamily.xyz/) ![GitHub stars](https://img.shields.io/github/stars/akfamily/akshare?style=flat&label=%E2%AD%90) - 中国市場に強い Python 金融データインタフェース。（[GitHub](https://github.com/akfamily/akshare)）
- [ccxt（英語）](https://github.com/ccxt/ccxt) ![GitHub stars](https://img.shields.io/github/stars/ccxt/ccxt?style=flat&label=%E2%AD%90) - 100以上の暗号資産取引所と予測市場を横断する統一取引／マーケットデータ API（JS／TS、Python、C#、PHP、Go、Java、Rust）。

---

## チャート・ターミナル

可視化とインタラクティブ分析。

- [TradingView（英語）](https://www.tradingview.com/) - チャート、スクリーナー、アイデア共有。カスタム指標は Pine Script。
- [Pine Script v6 リファレンス（英語）](https://www.tradingview.com/pine-script-reference/v6/) - 公式 Pine 言語リファレンス。
- [Lightweight Charts（英語）](https://www.tradingview.com/lightweight-charts/) ![GitHub stars](https://img.shields.io/github/stars/tradingview/lightweight-charts?style=flat&label=%E2%AD%90) - TradingView のオープンソース HTML5 金融チャート。（[GitHub](https://github.com/tradingview/lightweight-charts)）
- [Fincept Terminal（英語）](https://github.com/Fincept-Corporation/FinceptTerminal) ![GitHub stars](https://img.shields.io/github/stars/Fincept-Corporation/FinceptTerminal?style=flat&label=%E2%AD%90) - 市場分析・投資リサーチ・経済データ向けのオープンソースのファイナンスターミナル（C++／Qt）。
- [mplfinance（英語）](https://github.com/matplotlib/mplfinance) ![GitHub stars](https://img.shields.io/github/stars/matplotlib/mplfinance?style=flat&label=%E2%AD%90) - pandas 向け Matplotlib ローソク足／OHLC 描画（2024年8月以降コミットなし）。

---

## バックテスト・リサーチ

戦略研究向けのイベント駆動／ベクトル化エンジン（まず紙上／シミュレーション）。

- [QuantConnect Lean（英語）](https://www.lean.io/) ![GitHub stars](https://img.shields.io/github/stars/QuantConnect/Lean?style=flat&label=%E2%AD%90) - オープンソースのアルゴ取引エンジン（Python／C#）。クラウドとローカル両対応。（[GitHub](https://github.com/QuantConnect/Lean)）
- [NautilusTrader（英語）](https://nautilustrader.io/) ![GitHub stars](https://img.shields.io/github/stars/nautechsystems/nautilus_trader?style=flat&label=%E2%AD%90) - 高性能イベント駆動トレーディング基盤（Rust コア、Python）。（[GitHub](https://github.com/nautechsystems/nautilus_trader)）
- [backtrader（英語）](https://www.backtrader.com/) ![GitHub stars](https://img.shields.io/github/stars/mementum/backtrader?style=flat&label=%E2%AD%90) - 定番の Python バックテストライブラリ（成熟済みで近年の開発は少なめ）。（[GitHub](https://github.com/mementum/backtrader)）
- [vectorbt（英語）](https://vectorbt.dev/) ![GitHub stars](https://img.shields.io/github/stars/polakowo/vectorbt?style=flat&label=%E2%AD%90) - 高速なベクトル化バックテストとポートフォリオ分析。（[GitHub](https://github.com/polakowo/vectorbt)）
- [backtesting.py（英語）](https://kernc.github.io/backtesting.py/) ![GitHub stars](https://img.shields.io/github/stars/kernc/backtesting.py?style=flat&label=%E2%AD%90) - 軽量な Python バックテスター。（[GitHub](https://github.com/kernc/backtesting.py)）
- [Zipline Reloaded（英語）](https://github.com/stefan-jansen/zipline-reloaded) ![GitHub stars](https://img.shields.io/github/stars/stefan-jansen/zipline-reloaded?style=flat&label=%E2%AD%90) - Quantopian Zipline のメンテ継続フォーク。
- [hftbacktest（英語）](https://github.com/nkaz001/hftbacktest) ![GitHub stars](https://img.shields.io/github/stars/nkaz001/hftbacktest?style=flat&label=%E2%AD%90) - 板の待ち行列位置・レイテンシ・L2/L3 板を考慮する高頻度／マーケットメイク向けバックテスター（Rust、Python）。
- [StockSharp（英語）](https://stocksharp.com/) ![GitHub stars](https://img.shields.io/github/stars/StockSharp/StockSharp?style=flat&label=%E2%AD%90) - 株式・FX・暗号・オプション向けフル取引プラットフォーム（C#）。（[GitHub](https://github.com/StockSharp/StockSharp)）
- [Jesse（英語）](https://jesse.trade/) ![GitHub stars](https://img.shields.io/github/stars/jesse-ai/jesse?style=flat&label=%E2%AD%90) - 暗号資産向け Python 取引／バックテストフレームワーク。（[GitHub](https://github.com/jesse-ai/jesse)）
- [freqtrade（英語）](https://www.freqtrade.io/) ![GitHub stars](https://img.shields.io/github/stars/freqtrade/freqtrade?style=flat&label=%E2%AD%90) - バックテストとハイパーパラメータ探索付きのオープンソース暗号取引ボット。（[GitHub](https://github.com/freqtrade/freqtrade)）
- [Hummingbot（英語）](https://hummingbot.org/) ![GitHub stars](https://img.shields.io/github/stars/hummingbot/hummingbot?style=flat&label=%E2%AD%90) - CEX／DEX コネクタ経由で暗号資産のマーケットメイク・裁定ボットを構築・運用するオープンソースフレームワーク。（[GitHub](https://github.com/hummingbot/hummingbot)）

---

## ブローカー・執行 API

公式または広く使われるブローカー／ゲートウェイ資料（各国の規制と口座適格性を確認してください）。

- [Alpaca Docs（英語）](https://docs.alpaca.markets/) - 株式／オプション／暗号の API。ペーパートレードあり。ドキュメントは地域別（US、EU、UK、JP など）に分割。（[alpaca-py](https://github.com/alpacahq/alpaca-py) ![GitHub stars](https://img.shields.io/github/stars/alpacahq/alpaca-py?style=flat&label=%E2%AD%90)、[公式 MCP サーバー](https://github.com/alpacahq/alpaca-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/alpacahq/alpaca-mcp-server?style=flat&label=%E2%AD%90)）
- [Interactive Brokers — TWS API（英語）](https://www.interactivebrokers.com/campus/ibkr-api-page/twsapi-doc/) - TWS／IB Gateway 経由のマルチアセット API（最近のバージョンは Protobuf メッセージング、Python 3.11 以上）。
- [ib_async（英語）](https://github.com/ib-api-reloaded/ib_async) ![GitHub stars](https://img.shields.io/github/stars/ib-api-reloaded/ib_async?style=flat&label=%E2%AD%90) - ib_insync のコミュニティ後継。IB TWS API 向けの扱いやすい Python（asyncio）ラッパー。（元の [ib_insync](https://github.com/erdewit/ib_insync) ![GitHub stars](https://img.shields.io/github/stars/erdewit/ib_insync?style=flat&label=%E2%AD%90) リポジトリはアーカイブ済み）
- [Tradier API（英語）](https://docs.tradier.com/) - 米国株・オプション向けのブローカー REST／ストリーミング API（documentation.tradier.com から移転）。
- [kabuステーション API](https://kabucom.github.io/kabusapi/ptal/) ![GitHub stars](https://img.shields.io/github/stars/kabucom/kabusapi?style=flat&label=%E2%AD%90) - 国内株式／派生商品向け API（三菱UFJ eスマート証券）。（[GitHub](https://github.com/kabucom/kabusapi)）

---

## テクニカル分析

指標・シグナル用ヘルパー。

- [TA-Lib（英語）](https://ta-lib.org/) - 広く使われるテクニカル分析 C ライブラリ（Python バインディングあり）。（[Python ラッパー](https://github.com/TA-Lib/ta-lib-python) ![GitHub stars](https://img.shields.io/github/stars/TA-Lib/ta-lib-python?style=flat&label=%E2%AD%90)）
- [pandas-ta（英語）](https://pypi.org/project/pandas-ta/) - pandas DataFrame 拡張としてのテクニカル指標（元の GitHub リポジトリと pandas-ta.dev サイトは閲覧不可。PyPI の最新は 2025年9月の 0.4.71b0 ベータ、Python 3.12 以上）。
- [ta（英語）](https://github.com/bukosabino/ta) ![GitHub stars](https://img.shields.io/github/stars/bukosabino/ta?style=flat&label=%E2%AD%90) - pandas／NumPy ベースのテクニカル指標。
- [Kand（英語）](https://github.com/kand-ta/kand) ![GitHub stars](https://img.shields.io/github/stars/kand-ta/kand?style=flat&label=%E2%AD%90) - 高速テクニカル分析（Rust／Python／WASM）。

---

## クオンツ／ML プラットフォーム

ファクターモデル、ML ワークフロー、ポートフォリオ分析向けリサーチスタック。

- [Microsoft Qlib（英語）](https://qlib.readthedocs.io/) ![GitHub stars](https://img.shields.io/github/stars/microsoft/qlib?style=flat&label=%E2%AD%90) - AI 志向の定量投資プラットフォーム。（[GitHub](https://github.com/microsoft/qlib)）
- [gs-quant（英語）](https://developer.gs.com/docs/gsquant/) ![GitHub stars](https://img.shields.io/github/stars/goldmansachs/gs-quant?style=flat&label=%E2%AD%90) - Goldman Sachs の定量ツールキット（Python）。（[GitHub](https://github.com/goldmansachs/gs-quant)）
- [QuantStats（英語）](https://github.com/ranaroussi/quantstats) ![GitHub stars](https://img.shields.io/github/stars/ranaroussi/quantstats?style=flat&label=%E2%AD%90) - ポートフォリオ実績分析と tear sheet。
- [skfolio（英語）](https://skfolio.org/) ![GitHub stars](https://img.shields.io/github/stars/skfolio/skfolio?style=flat&label=%E2%AD%90) - scikit-learn 上に構築されたポートフォリオ最適化・リスク管理ライブラリ。（[GitHub](https://github.com/skfolio/skfolio)）
- [Riskfolio-Lib（英語）](https://riskfolio-lib.readthedocs.io/) ![GitHub stars](https://img.shields.io/github/stars/dcajasn/Riskfolio-Lib?style=flat&label=%E2%AD%90) - ポートフォリオ最適化ライブラリ（平均リスク、リスクパリティ、CVaR、ドローダウンモデル等）。（[GitHub](https://github.com/dcajasn/Riskfolio-Lib)）
- [QuantLib（英語）](https://www.quantlib.org/) ![GitHub stars](https://img.shields.io/github/stars/lballabio/QuantLib?style=flat&label=%E2%AD%90) - デリバティブ価格評価・債券・リスクモデリング向けのフリー／オープンソース C++ ライブラリ（Python バインディングあり）。（[GitHub](https://github.com/lballabio/QuantLib)）
- [FinGPT（英語）](https://github.com/AI4Finance-Foundation/FinGPT) ![GitHub stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat&label=%E2%AD%90) - オープンソースの金融 LLM リソース（AI4Finance）。
- [FinRobot（英語）](https://github.com/AI4Finance-Foundation/FinRobot) ![GitHub stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat&label=%E2%AD%90) - 金融アプリ向けオープンソース AI エージェント基盤。
- [TradingAgents（英語）](https://github.com/TauricResearch/TradingAgents) ![GitHub stars](https://img.shields.io/github/stars/TauricResearch/TradingAgents?style=flat&label=%E2%AD%90) - マルチエージェント LLM トレーディング研究フレームワーク。
- [Vibe-Trading（英語）](https://github.com/HKUDS/Vibe-Trading) ![GitHub stars](https://img.shields.io/github/stars/HKUDS/Vibe-Trading?style=flat&label=%E2%AD%90) - オープンソースの個人向け LLM トレーディングエージェント（香港大学 Data Intelligence Lab）。自然言語での戦略リサーチ、バックテスト、MCP 連携。
- [daily_stock_analysis（中国語／英語）](https://github.com/ZhuLinsen/daily_stock_analysis) ![GitHub stars](https://img.shields.io/github/stars/ZhuLinsen/daily_stock_analysis?style=flat&label=%E2%AD%90) - LLM 駆動のマルチマーケット株式分析システム（中国 A 株中心）。複数ソースの相場・リアルタイムニュース・意思決定ダッシュボード・自動通知、無料の定期実行に対応。
- [TradeMaster（英語）](https://github.com/TradeMaster-NTU/TradeMaster) ![GitHub stars](https://img.shields.io/github/stars/TradeMaster-NTU/TradeMaster?style=flat&label=%E2%AD%90) - 強化学習志向の定量取引プラットフォーム（NTU）。

---

## 開示・ファンダメンタルズ

規制開示ポータルと構造化ファンダメンタルズ。

- [SEC EDGAR — Search Filings（英語）](https://www.sec.gov/search-filings) - 米国企業の開示検索（[全文検索](https://www.sec.gov/edgar/search/)）。
- [SEC EDGAR APIs（英語）](https://www.sec.gov/search-filings/edgar-application-programming-interfaces) - 提出履歴・XBRL JSON の公式 API（`data.sec.gov`）。
- [FinanceToolkit（英語）](https://github.com/JerBouma/FinanceToolkit) ![GitHub stars](https://img.shields.io/github/stars/JerBouma/FinanceToolkit?style=flat&label=%E2%AD%90) - 財務諸表分析・財務比率・バリュエーション・リスク／パフォーマンス指標を透明に計算する Python ツールキット（MCP サーバーあり）。
- [EDINET](https://disclosure2.edinet-fsa.go.jp/) - 金融庁の電子開示システム（有価証券報告書など）。
- [EDINET API 操作ガイド等](https://disclosure2dl.edinet-fsa.go.jp/guide/static/disclosure/WEEK0060.html) - 公式 API／タクソノミ文書。
- [FRED（英語）](https://fred.stlouisfed.org/) - 米連邦準備の経済データ（マクロ時系列＋API）。

---

## 日本市場

取引所、公式データ、国内向けツール。

- [日本取引所グループ（JPX）](https://www.jpx.co.jp/) - 東証／大証などを含む取引所グループ（[English](https://www.jpx.co.jp/english/)）。
- [JPX マーケット情報・統計（英語）](https://www.jpx.co.jp/english/markets/index.html) - 公式の市場サマリーと統計。
- [J-Quants API](https://jpx-jquants.com/) - 個人向けのヒストリカル株価・財務など。V2 API（2025年12月）で API キー認証（V1 のトークン認証は廃止、2025年12月22日以降の登録者は V2 のみ）・公式 MCP サーバーに対応。2026年1月に CSV 一括提供と株式の分足・Tick データを追加（ライトプラン以上）。（[JPX 概要](https://www.jpx.co.jp/markets/other-data-services/j-quants-api/index.html)、[V1→V2 移行](https://jpx-jquants.com/ja/spec/migration-v1-v2)、[Python クライアント](https://github.com/J-Quants/jquants-api-client-python) ![GitHub stars](https://img.shields.io/github/stars/J-Quants/jquants-api-client-python?style=flat&label=%E2%AD%90)）
- [TDnet](https://www.release.tdnet.info/) - 適時開示情報伝達システム。
- [金融庁](https://www.fsa.go.jp/) - 政策・開示関連情報。
- [kabuステーション API](https://kabucom.github.io/kabusapi/ptal/) - 国内市場向け PC ベース取引 API。
- [python-kabusapi（英語）](https://github.com/shirasublue/python-kabusapi) ![GitHub stars](https://img.shields.io/github/stars/shirasublue/python-kabusapi?style=flat&label=%E2%AD%90) - kabuステーション API のコミュニティ Python バインディング（2021年以降更新なし）。

---

## 学習・論文

学習教材と論文コレクション（これも助言ではありません）。

- [Machine Learning for Trading（英語）](https://github.com/stefan-jansen/machine-learning-for-trading) ![GitHub stars](https://img.shields.io/github/stars/stefan-jansen/machine-learning-for-trading?style=flat&label=%E2%AD%90) - Jansen 著 ML for Trading のコード／ノートブック（第3版：データ取得から実運用まで）。（[ml4trading.io](https://ml4trading.io)）
- [Quantopian Lectures（アーカイブ）（英語）](https://github.com/quantopian/research_public) ![GitHub stars](https://img.shields.io/github/stars/quantopian/research_public?style=flat&label=%E2%AD%90) - ファクターやパイプラインの古典的な講義ノート。
- [Awesome LLM Quantitative Trading Papers（英語）](https://github.com/Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers) ![GitHub stars](https://img.shields.io/github/stars/Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers?style=flat&label=%E2%AD%90) - LLM ベース定量取引の論文集。
- [SSRN（英語）](https://papers.ssrn.com/) - ファイナンス・経済学のワーキングペーパー。

---

## 関連リスト

- [wilsonfreitas/awesome-quant（英語）](https://github.com/wilsonfreitas/awesome-quant) ![GitHub stars](https://img.shields.io/github/stars/wilsonfreitas/awesome-quant?style=flat&label=%E2%AD%90) - 広範なクオンツライブラリ／リソース。
- [paperswithbacktest/awesome-systematic-trading（英語）](https://github.com/paperswithbacktest/awesome-systematic-trading) ![GitHub stars](https://img.shields.io/github/stars/paperswithbacktest/awesome-systematic-trading?style=flat&label=%E2%AD%90) - システマティック取引の Awesome リスト。
- [wangzhe3224/awesome-systematic-trading（英語）](https://github.com/wangzhe3224/awesome-systematic-trading) ![GitHub stars](https://img.shields.io/github/stars/wangzhe3224/awesome-systematic-trading?style=flat&label=%E2%AD%90) - 大規模なシステマティック取引リスト。
- [georgezouq/awesome-ai-in-finance（英語）](https://github.com/georgezouq/awesome-ai-in-finance) ![GitHub stars](https://img.shields.io/github/stars/georgezouq/awesome-ai-in-finance?style=flat&label=%E2%AD%90) - ファイナンスにおける AI／深層学習。
- [AI4Finance-Foundation/Awesome_AI4Finance（英語）](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance) ![GitHub stars](https://img.shields.io/github/stars/AI4Finance-Foundation/Awesome_AI4Finance?style=flat&label=%E2%AD%90) - AI4Finance の厳選リソース。
- [merovinh/best-of-algorithmic-trading（英語）](https://github.com/merovinh/best-of-algorithmic-trading) ![GitHub stars](https://img.shields.io/github/stars/merovinh/best-of-algorithmic-trading?style=flat&label=%E2%AD%90) - アルゴ取引プロジェクトのランキング系リスト。
- [tradingview/awesome-tradingview（英語）](https://github.com/tradingview/awesome-tradingview) ![GitHub stars](https://img.shields.io/github/stars/tradingview/awesome-tradingview?style=flat&label=%E2%AD%90) - TradingView 生態系リソース。
- [sindresorhus/awesome（英語）](https://github.com/sindresorhus/awesome) ![GitHub stars](https://img.shields.io/github/stars/sindresorhus/awesome?style=flat&label=%E2%AD%90) - Awesome のメタリスト。

---

## コントリビューション

コントリビューション歓迎です。リソース追加、リンク切れ修正、カテゴリ提案はプルリクエストでどうぞ。

**公式／ドキュメントの耐久性のある URL**、短い説明、継続的にメンテナンスされているプロジェクトを優先してください。製品名・団体名はそのまま。言語や地域が分かるように書くと親切です。本リストは**発見用のみ**（投資助言の体裁にしない）。可能なら `README.md` と `README.ja.md` の両方を更新してください。

---

## shvyac の awesome リスト

[shvyac](https://github.com/shvyac) が管理しているキュレーションリストの一覧:

- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
