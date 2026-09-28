# Terminal List · 研究标的控制清单

本清单是研究标的的控制面板，只反映**当前**在跟踪哪些股票、所属板块和最新报告结论。报告由 AI 生成，仅供研究，不构成投资建议。

## 记录规则 / What to record

**记录：**
- 「当前清单」：只放正在跟踪的标的，每只一行，按 GICS 板块（Sector / Sub-industry，括号内为中文板块）分组。有新报告时原地更新该行为最新报告的日期、评级、参考价、关键位和催化剂（摘自 `final_trade_decision.md` 与 `market_report.md`，为报告当日数据，非实时行情）。
- 「板块分析」：每次增删或更新后按当前清单重写，只描述当前状态。
- 「变更记录」：每次增删标的（`ADD` / `REMOVE`）或评级变化（`RATING`）追加一行，已有行不改。

**不记录：**
- 被移除标的的详情：直接从当前清单和板块分析删掉，只在变更记录留一行；其报告目录保留在仓库中。
- 报告历史：旧的评级、价位不在清单里保留，历史以各 `<TICKER>/<YYYY-MM-DD>/` 报告目录为准；没有评级变化的新报告不写变更记录。
- 实时行情、个人持仓、账户信息或自行推测的数据。

---

## 当前清单 / Active list

版本：v4（2026-09-28）｜标的数：14｜板块数：4｜待首份报告：5

新增标的尚无报告的，报告列记为「待首份报告」，其余列留空（—），首份报告归档后原地补齐。

### 信息技术 · Information Technology（10）

| Ticker | 公司 | 细分板块 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|
| [NVDA](NVDA/2026-09-25/reports/final_trade_decision.md) | NVIDIA | Semiconductors（半导体 · AI 算力 GPU） | 2026-09-25 | Overweight | 225.07 | 多头：价格 > 10EMA > 50SMA > 200SMA；缩量整理，MACD 未创新高 | 215.79（50SMA）减仓／210.51 硬止损 | 放量站稳 230.10 且 MACD 同步抬升 | 下季财报（OCF／核心净利；日期未注明） |
| [TSM](TSM/2026-09-25/reports/final_trade_decision.md) | TSMC | Semiconductors（半导体 · 晶圆代工） | 2026-09-25 | Overweight | 450.61 | 多头：价格 > 10EMA > 50SMA > 200SMA；MACD 柱扩张，450–455 受阻 | 433 连续两日不收复减加仓／429 减底仓／419（50SMA）最终止损 | 放量突破 455 并回踩 452–455 站稳 | 10/8 月度销售数据；10 年期美债收益率 |
| AMD | Advanced Micro Devices | Semiconductors（半导体 · CPU / AI GPU） | 待首份报告 | — | — | — | — | — | — |
| INTC | Intel | Semiconductors（半导体 · CPU / 晶圆代工） | 待首份报告 | — | — | — | — | — | — |
| [QCOM](QCOM/2026-09-25/reports/final_trade_decision.md) | Qualcomm | Semiconductors（半导体 · 移动 SoC / 专利授权） | 2026-09-25 | Hold | 201.97 | 多头：价格 > 10EMA > 50SMA > 200SMA；贴布林上轨，RSI 68 | 191.02（10EMA）先减／181 硬止损 | 放量站稳 205.85 并回踩确认 | FY26Q4 财报（日期未注明） |
| [MU](MU/2026-09-25/reports/final_trade_decision.md) | Micron | Semiconductors（半导体 · 存储 DRAM/HBM） | 2026-09-25 | Underweight | 1082.28 | 多头：价格 > 10EMA > 50SMA > 200SMA；缩量修复，贴布林上轨 | 1037（10EMA）+ 1008（VWMA）失守降至 25% 以下／942（50SMA）离场 | 放量站稳 1110 再评估加回 | 未注明（仅提毛利率指引，日期未注明） |
| SKHY | SK hynix（Nasdaq ADR） | Semiconductors（半导体 · 存储 DRAM/HBM） | 待首份报告 | — | — | — | — | — | — |
| SNDK | Sandisk | Technology Hardware, Storage & Peripherals（存储 · NAND 闪存 / SSD） | 待首份报告 | — | — | — | — | — | — |
| [MSFT](MSFT/2026-09-25/reports/final_trade_decision.md) | Microsoft | Systems Software（软件 · 云 / AI 平台） | 2026-09-25 | Overweight | 516.17 | 多头：价格 > 10EMA > 50SMA > 200SMA；放量站上布林上轨，MACD 柱仍负 | 500–505 首笔／486–490 次笔／475.40（50SMA）收盘止损 | 放量站稳 525 | 下次财报验证 Copilot 数据（日期未注明） |
| [AAPL](AAPL/2026-09-25/reports/final_trade_decision.md) | Apple | Technology Hardware（消费电子 · 硬件） | 2026-09-25 | Hold | 341.07 | 多头：价格 > 10EMA > 50SMA > 200SMA；缩量新高，MACD 柱收敛 | 334–335 连续两日放量跌破减半／329.4（布林中轨）／321.7（50SMA） | 放量站稳 346 且回踩不破 | 折叠 iPhone 发布（预测市场 99% 于 10 月底前）；iPhone 预售数据 |

### 工业 · Industrials（1）

| Ticker | 公司 | 细分板块 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|
| [ETN](ETN/2026-09-25/reports/final_trade_decision.md) | Eaton | Electrical Components & Equipment（电气设备 · 数据中心电气化） | 2026-09-25 | Underweight | 439.98 | 多头：价格 > 10EMA > 50SMA > 200SMA；缩量逼近布林上轨 | 428（10EMA）减第二批／414–418 破位降至 1% 以下／385.22（200SMA）趋势失效 | 放量站稳 478 为趋势再评估线（近压 450.73） | Q3/Q4 财报（日期未注明） |

### 可选消费 · Consumer Discretionary（1）

| Ticker | 公司 | 细分板块 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|
| [TSLA](TSLA/2026-09-25/reports/final_trade_decision.md) | Tesla | Automobile Manufacturers（电动车 · 自动驾驶） | 2026-09-25 | Underweight | 372.11 | 修复：50SMA < 价格 < 200SMA，两线仍下行；布林上轨放量被拒 | 365.68（布林中轨）减至 1–2%／347–348（50SMA + 布林下轨）降至观察仓，止损 344–347 下方 | 放量收盘站稳 386.83 连续 2–3 日（暂停减仓）；站稳 395.62（200SMA）才考虑上调 | 下一份财报（日期未注明）；欧盟 FSD 审批（日期未注明） |

### 通信服务 · Communication Services（2）

| Ticker | 公司 | 细分板块 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|
| META | Meta Platforms | Interactive Media & Services（互动媒体 · 社交 / AI） | 待首份报告 | — | — | — | — | — | — |
| [TTWO](TTWO/2026-09-25/reports/final_trade_decision.md) | Take-Two Interactive | Interactive Home Entertainment（游戏） | 2026-09-25 | Overweight | 201.44 | 空头：低于全部主要均线；MACD 深负，贴布林下轨 | 197.86（布林下轨）／187–193 前低区加仓观察／186 放量跌破硬止损 | 收复 VWMA 210.25 且 MACD 转强 | 11/19 GTA VI 发售 |

---

## 板块分析 / Sector view

基于 2026-09-25 报告（原 9 只）；2026-09-28 新增的 AMD、INTC、SKHY、SNDK、META 尚无报告，暂不参与评级统计与判断。

**分布**：信息技术 10／14，其中半导体（含存储）8 只：NVDA、TSM、AMD、INTC、QCOM 为逻辑／代工，MU、SKHY、SNDK 为存储；另有 MSFT、AAPL。通信服务 2（META、TTWO），工业、可选消费各 1。新增 5 只全部在科技／AI 相关方向，清单对 AI 资本开支周期的集中度进一步上升。

**评级（已有报告的 9 只）**：Overweight 4（MSFT、NVDA、TSM、TTWO）｜Hold 2（AAPL、QCOM）｜Underweight 3（ETN、MU、TSLA）｜待首份报告 5（AMD、INTC、SKHY、SNDK、META）。

| 板块 | 标的 | 板块共性判断 | 主要风险 |
|---|---|---|---|
| 半导体（逻辑／代工） | NVDA、TSM、QCOM；AMD、INTC 待报告 | 三只已有报告的均为完整多头排列，但结论分化：NVDA、TSM 以营收高增长和较低 Forward PE（约 14–21 倍）获 Overweight，均要求分批、突破确认后再加；QCOM 因苹果专利授权续签至 2027 消除尾部风险，但贴近阻力、RSI 偏高，维持 Hold。 | 同一 AI 资本开支周期驱动，高度相关；NVDA 核心净利与 OCF 环比走弱，TSM 库存增速快于营收；台海尾部风险（TSM）。 |
| 存储 | MU；SKHY、SNDK 待报告 | MU 被视为"周期顶部陷阱"降为 Underweight（价格接近概率加权期望值、CEO 减持、CapEx 远超折旧）。 | 存储为强周期行业，三只受同一价格周期驱动；MU 报告指出毛利率指引拐点风险最大。 |
| 软件 / 硬件 | MSFT、AAPL | MSFT 放量突破布林上轨、营收与净利加速，升为 Overweight（分三批建仓）；AAPL 盈利重新加速但 TTM PE 约 39、距 345–346 阻力近，维持 Hold、不追加。 | 10 年期美债收益率处 2007 年以来高位压估值；MSFT CapEx 压制 FCF、Copilot 付费数据缺失；AAPL 缩量新高可能是假突破。 |
| 工业 | ETN | "好公司、坏价格"：电气化与 AI 数据中心逻辑仍在，但 Q2 EPS 同比 -16.4%、毛利率下滑、净债务/EBITDA 约 3 倍、PE TTM 约 45 倍，降为 Underweight。 | Forward EPS 隐含约 64% 增长，下修叠加估值压缩的下行空间较大；与半导体同向波动。 |
| 可选消费 | TSLA | 估值与盈利脱节（TTM PE 约 338、营业利润同比 -57%、FCF 为负），价格仍在下行的 200SMA 之下且在布林上轨被拒，降为 Underweight。 | 对看空立场的风险：净现金充足，储能／FSD／Optimus 为长期期权；放量站稳 386.83／395.62 且利润率改善需回补。 |
| 通信服务 | TTWO；META 待报告 | TTWO 技术面仍为空头结构，但股价贴近 52 周低点、GTA VI 确认 11/19 发售、FCF 转正，报告以左侧分批方式给出 Overweight。 | TTWO 评级与技术面相反，未有反转确认；二元事件风险集中在 11/19，延期或放量跌破 186 即下调离场。 |

**共同宏观变量**：利率。多份报告指出 10 年期美债收益率处 2007 年以来高位、降息预期接近归零，对清单内高估值科技、电气设备与高 Beta 标的（MU、TSLA、NVDA）同向承压；清单内没有受益于高利率的对冲标的。

**整体结论**：已有报告的 9 只评级分化——AI 算力与平台龙头（NVDA、TSM、MSFT）偏多，估值透支或盈利恶化的 MU、ETN、TSLA 偏空，TTWO 为事件驱动的左侧多头。共同纪律不变："不追高、以收盘确认破位、分批进出"。新增 5 只使清单更集中于半导体与存储周期，仍缺少防御性板块（必需消费、医疗、公用事业、能源）。

---

## 变更记录 / Change log

只追加，不修改已有行。动作：`INIT` 建立清单｜`ADD` 新增｜`REMOVE` 移除｜`RATING` 评级变化。

| 日期 | 动作 | Ticker | 板块 | 说明 |
|---|---|---|---|---|
| 2026-09-25 | INIT | 全部 11 只 | 5 个板块 | 按仓库已有报告（2026-09-07 / 09-08）建立 Terminal List v1，评级均为 Hold |
| 2026-09-25 | REMOVE | JPM, BNY | 金融 | 移除全部银行股；清单 v2 为 9 只、4 个板块 |
| 2026-09-25 | RATING | NVDA | 信息技术 | Hold → Overweight（2026-09-25 报告） |
| 2026-09-25 | RATING | TSM | 信息技术 | Hold → Overweight（2026-09-25 报告） |
| 2026-09-25 | RATING | MU | 信息技术 | Hold → Underweight（2026-09-25 报告） |
| 2026-09-25 | RATING | MSFT | 信息技术 | Hold → Overweight（2026-09-25 报告） |
| 2026-09-25 | RATING | ETN | 工业 | Hold → Underweight（2026-09-25 报告） |
| 2026-09-25 | RATING | TSLA | 可选消费 | Hold → Underweight（2026-09-25 报告） |
| 2026-09-25 | RATING | TTWO | 通信服务 | Hold → Overweight（2026-09-25 报告） |
| 2026-09-28 | ADD | AMD, INTC | 信息技术 | 新增半导体标的（Semiconductors），待首份报告；清单 v4 |
| 2026-09-28 | ADD | SKHY, SNDK | 信息技术 | 新增存储标的（SKHY：Semiconductors；SNDK：Technology Hardware, Storage & Peripherals），待首份报告 |
| 2026-09-28 | ADD | META | 通信服务 | 新增，GICS 为 Interactive Media & Services（非半导体），待首份报告；清单 v4 为 14 只、4 个板块 |
