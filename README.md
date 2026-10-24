# touyan-expert-team

**投研星图团** · v1.0.0 · `team`

> Investment-research expert team — multi-role analysis pipeline


Part of the [Lucewalk Lumen](https://github.com/Lucewalk-Lumen/about-me) collection.


## What it does

- **Stock / kline / hotspot leads** — three desks covering single-stock analysis, candlestick reading and hotspot discovery
- **18 research skills** — from akshare-based market data (A-share & US) and the eastmoney information suite to industry-theme research, company deep-dives, portfolio strategy, strategy backtesting and stock monitoring
- **xiaodi-financial-analysis-team** — an embedded financial-analysis sub-team

## How it works

- Lead routes between the stock, kline and hotspot desks; each desk pulls from a dedicated skill set
- A compare-decide skill structures cross-option decisions; claw-stock and its watcher variant handle persistent tracking
- ⚠ Investment content is informational, not financial advice

## Agent roster

| Agent | Role |
|---|---|
| `hotspot` | 热点扫描官 - 投研星图团 · 热点扫描 |
| `kline` | K线技术复盘官 - 投研星图团 · K线技术复盘 |
| `stock` | 个股深研官 - 投研星图团 · 个股深研 |
| `touyan-expert-team-lead` | 投研总览官 - 裴览 |

## Skills

`akshare-finance-data` · `akshare-stock` · `astock-report` · `china-stock-analysis` · `claw-stock` · `claw-stock-watcher-pro` · `company-deep-analysis` · `compare-decide` · `eastmoney-mx-skills-suite` · `hotspot-discovery` · `industry-theme-research` · `kline-candlestick-reader` · `mx-stocks-screener` · `portfolio-strategy` · `stock-monitor-skill` · `strategy-backtest` · `us-market-data` · `xiaodi-financial-analysis-team`

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk-Lumen/touyan-expert-team/releases) or clone this repo;
2. Unzip keeping the `.codebuddy-plugin/` manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).


## Version

Current release: **v1.0.0**. See the package manifest for details.


## License

MIT — see [LICENSE](LICENSE).


---

## How to use / 如何使用

This is an **expert package / skill for the WorkBuddy AI assistant**.

**Prerequisites · 前置条件**
- WorkBuddy installed and signed in (latest version recommended).
- Prepare your own materials first (e.g. your literature library / course outline) — the agent works under a "stay faithful to the source, cite the page" rule.

**Import / enable · 导入 / 启用**
1. Download the package zip from this repo's **Releases**, or clone the repo; keep the `.codebuddy-plugin/` manifest intact.
2. In WorkBuddy, *custom connector → trust & enable*, or import the expert / enable the skill from the skill center.
3. Run one minimal example below to confirm the output matches your standards.

**Minimal example · 最小示例**
> 对这只 A 股做个个股深研,并提示非投资建议。


**Portability · 可移植性** — Delivered for WorkBuddy; won't run as-is elsewhere, but the methodology is documented in plain text and can be re-implemented on another platform. Knowledge is portable even if the runtime isn't.

**More · 更多**
Full onboarding & per-line guidance: portal [Lucewalk Lumen · 沐光行客](https://github.com/Lucewalk-Lumen/about-me) → "How to use". Issues: open one on this repo.

<details>
<summary><strong>📖 中文说明(Chinese README)</strong></summary>

# 投研星图团

**投研星图团:个股、K线、热点三席 × 18 项投研技能**

- 版本:v1.0.0 · 类型:team
- 版本真源:包内 `.codebuddy-plugin/plugin.json` 的 `version` 字段
- 所属合集:[Lucewalk Experts 门户](https://github.com/Lucewalk-Lumen/about-me)(全部产品目录与品牌说明)

## 安装

1. 从本仓库 [Releases](https://github.com/Lucewalk-Lumen/touyan-expert-team/releases) 页下载该包 zip(或直接克隆仓库);
2. 解压后**保持内部清单结构不变**(`.codebuddy-plugin/` 目录);
3. 在 WorkBuddy 中导入/注册(自定义连接器入口 → 信任并启用)。

能力详解见上方英文文档;品牌与全部产品目录见门户仓库。

## 许可

MIT——详见 [LICENSE](LICENSE)。

</details>
