# touyan-expert-team

**投研星图团** · v1.0.0 · `team`

> Investment Star-map Team covering hotspot scanning, deep company research, K-line technical review, portfolio strategy and event interpretation, with built-in data-reliability guardrails against hallucination.


Part of the [WorkBuddy Experts](https://github.com/Lucewalk/WorkBuddy-Experts) collection — expert teams, agents and skills for the WorkBuddy AI assistant platform.


## What it does

- **hotspot-discovery** — 热点扫描与机会发现引擎。当用户不知道看什么、想了解市场有什么机会、或没有明确标的时调用。基于政策信号、资金信号、事件催化三重验证，输出 3-5 个值得深入研究的方向。
- **company-deep-analysis** — 公司深度研报生成引擎。当用户要求"深度研报""拉X年看""长期持有分析""系统性看透一家公司"时调用。覆盖8大分析维度：财务全景、资产解剖、变化复盘、分析师观点、未来展望、风险清单、事件日历、行业对标。
- **industry-theme-research** — 行业/主题研究引擎。当用户提到"某行业值不值得投""某概念/方向研究下""板块分析""产业链拆解"时调用。覆盖政策梳理、产业链拆解、资金验证、估值横比、催化剂识别5大模块，输出可操作的标的推荐。
- **compare-decide** — 对比决策引擎。当用户要在多只股票中做选择（"A还是B""选哪个""对比下"）时调用。提供多维对比表、差异化逻辑分析、分期限结论，帮用户在可比标的中做出有依据的选择。
- **portfolio-strategy** — 策略生成引擎。当用户给出资金量和风险偏好要求配置方案时调用。提供风险评估→行业配置→标的精选→买入节奏→风控红线的完整组合策略，帮用户从研究结论转化为可执行的投资计划。
- **claw-stock** — 个股分析师。当用户提到任何 A 股、港股、美股股票名称或代码，或说出"分析一下"、"看看这只"、"打个分"、"值得买吗"、"怎么看"等意图时，调用本 skill。
- **eastmoney-mx-skills-suite** — >
- **xiaodi-financial-analysis-team** — 金融分析师团队 - 股票分析、基金推荐、持仓复盘、投资决策
- **akshare-finance-data** — Retrieve structured A-share market data with AKShare, including leaderboard data, limit-up review data, and capital-flow data. Use this skil
- **mx-stocks-screener** — 基于东方财富数据库，支持通过自然语言输入筛选A港美股、基金、债券等多种资产，支持多元指标筛选，含技术面、消息面、基本面及市场情绪等，可用于全球资产速筛、跨市场监控、投资组合构建、策略回测等场景。返回结果包含数据说明及 csv 文件。Natural language screene
- **astock-report** — A股报告生成与推送技能。触发方式：晨报（cron 08:00）、晚报（cron 20:00）、收盘小结（cron 15:00）、盘中预警（cron 每5分钟）、财经周末要闻（cron 周五20:00）、IPO周报（cron 周六09:00）。内置两套系统：①投资者情绪打分（6维度
- **china-stock-analysis** — A 股、港股、中概股深度分析技能，支持多维度财务指标解读、行业对比和估值判断。提供客观、数据驱动的研究视角，不包含投资诱导。
- **claw-stock-watcher-pro** — Manage and monitor a personal A-share watchlist with support for adding, removing, listing stocks, and summarizing verified current performa
- **akshare-stock** — >
- **stock-monitor-skill** — 全功能智能股票监控预警系统。支持成本百分比、均线金叉死叉、RSI超买超卖、成交量异动、跳空缺口、动态止盈等7大预警规则。符合中国投资者习惯（红涨绿跌）。
- **kline-candlestick-reader** — 获取和标准化 A 股/ETF K 线数据，并为 K 线解读助手生成可审计的量价事实。用于用户请求东方财富 K 线数据、A 股或 ETF 技术复盘、多周期 K 线分析、双标的技术结构对比，或用户粘贴 CSV K 线数据并要求离线解读时。
- **us-market-data** — 获取美股实时报价与历史 K 线数据（东方财富公开接口，零 API Key），并为美股研究生成可审计的量价事实。用于用户请求美股行情、K 线、技术复盘、实时价格，或提供美股代码/名称（如 AAPL、苹果、特斯拉、英伟达）时。A 股/ETF 请改用 kline-market-data
- **strategy-backtest** — 对 K 线数据运行简单策略回测（纯标准库，零依赖）：双均线交叉、买入持有、定投分批；输出总收益/年化/夏普/最大回撤/胜率/交易明细与净值曲线尾部。用于用户要求回测策略、验证均线策略、对比参数组合，或评估某策略在 A 股/美股标的历史表现时。

## Agent roster

| Agent | Role |
|---|---|
| `hotspot` | 热点扫描官 - 投研星图团 · 热点扫描 |
| `kline` | K线技术复盘官 - 投研星图团 · K线技术复盘 |
| `stock` | 个股深研官 - 投研星图团 · 个股深研 |
| `touyan-expert-team-lead` | 投研总览官 - 裴览 |

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk/touyan-expert-team/releases) or clone this repo;
2. Unzip keeping the internal manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).

## Version

Current release: **v1.0.0** — see [CHANGELOG.md](CHANGELOG.md) if present, or the package manifest.

## License

MIT — see [LICENSE](LICENSE).
