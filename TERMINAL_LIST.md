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

版本：v7（2026-10-02）｜标的数：14｜板块数：3

### 信息技术 · Information Technology（11）

| Ticker | 公司 | 细分板块 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|
| [NVDA](NVDA/2026-10-02/reports/final_trade_decision.md) | NVIDIA | Semiconductors（半导体 · AI 算力 GPU） | 2026-10-02 | Overweight | 233.95 | 多头：价格 > 10EMA > VWMA > 50SMA > 200SMA，五线上行；MACD 零轴上方二次加速；10/2 冲高 237.88 回落留上影 | 225.35（VWMA）收破且 MACD 柱转负减 1/3–1/2／218.12（50SMA）核心止损／200.38 全出 | 放量收盘站上 236.54 并跨越 235–238 前高区，次日守住 236.5 | 10 月非农／CPI；11 月中期选举；FY27 Q3 财报（11 月下旬，日期未注明） |
| [TSM](TSM/2026-10-02/reports/final_trade_decision.md) | TSMC | Semiconductors（半导体 · 晶圆代工） | 2026-10-02 | Overweight | 472.78 | 多头：价格 > 10EMA > 50SMA > 200SMA；RSI 71.68 贴布林上轨，缩量二次测试 6/30 前高 | 451.50（2×ATR／10EMA 453.72）首笔止损／有效跌破 440 降至半仓以下 | 放量（≥12–15M 股）站上 477.72（6/30 高点）并守住 | Q3 财报（报告称通常 10 月中旬，日期未注明）；10 年期美债；台海／出口管制 |
| [MU](MU/2026-10-02/reports/final_trade_decision.md) | Micron | Semiconductors（半导体 · 存储 DRAM/HBM） | 2026-10-02 | Underweight | 1074.89 | 多头排列未破（价格 > 10EMA > 50SMA > 200SMA），但 1108 双顶 + 10/2 长上影反转 K 线；缩量、MACD 钝化 | 1060.60 警戒／1042.79（VWMA）／收破 1025 且 MACD 柱转负离场／956.05（50SMA）回避 | 放量收盘站上 1108–1110 并回踩 1060 不破 | FY26 Q4 财报（报告称应已于 9 月下旬发布，但未纳入分析）；HBM 长协（日期未注明） |
| [QCOM](QCOM/2026-10-02/reports/final_trade_decision.md) | Qualcomm | Semiconductors（半导体 · 移动 SoC / 专利授权） | 2026-10-02 | Overweight | 184.87 | 中期多头：50SMA > 200SMA 金叉再扩张；短线转弱：价格 < 10EMA／VWMA，MACD 死叉，缩量 | 收破 181.77–183.36 减首仓 1/3／175.97／170.50 减半／167.80 清仓 | 放量收盘站上 188.35 一到两天且 MACD 柱转正 | Q4 FY26 财报（约 11 月，日期未注明） |
| [MSFT](MSFT/2026-10-02/reports/final_trade_decision.md) | Microsoft | Systems Software（软件 · 云 / AI 平台） | 2026-10-02 | Underweight | 517.53 | 多头：价格 > 10EMA > VWMA > 50SMA > 200SMA；贴布林上轨但缩量，MACD 柱 +0.33 接近死叉 | 504.00（VWMA）再减 1/3／501.67（布林中轨）续减／487.39（50SMA）压至 ≤2% | 放量站上 522.50 仅暂停减持；放量突破 553.72（52 周高点）才考虑上调 | FY27 Q1 财报（10 月下旬，日期未注明）；10 月 FOMC |
| [U](U/2026-10-02/reports/final_trade_decision.md) | Unity Software | Application Software（软件 · 游戏引擎 / 广告平台） | 2026-10-02 | Overweight | 43.61 | 多头：价格 > 10EMA > 50SMA > 200SMA（8 月中金叉，200SMA 走平）；MACD 小幅死叉，布林收窄，反弹缩量 | 41.33（50SMA）减至 0.25 单位以下／39.70 清仓 | 放量（≥1.5× 20 日均量）站上 44.82 且 MACD 金叉；突破 45.38 再加 | 10/23 APP 诉 Unity 诉讼节点（仅来自 StockTwits，未核实）；Q3 财报（日期未注明） |
| [AMD](AMD/2026-10-02/reports/final_trade_decision.md) | Advanced Micro Devices | Semiconductors（半导体 · CPU / AI GPU） | 2026-10-02 | Hold | 633.91 | 多头：价格 > 10EMA > 50SMA > 200SMA，区间新高；RSI 顶背离雏形 + 缩量新高，MACD 走平 | 605.70（10EMA）／566.49（布林中轨）回踩才分批；513.53（50SMA）跌破降 Underweight | 放量站上 645.46 后看 680.05（超配者在此区间部分止盈） | 下季财报（营收 ≥125 亿、毛利率 ≥54%、MI400 指引；日期未注明） |
| [INTC](INTC/2026-10-02/reports/final_trade_decision.md) | Intel | Semiconductors（半导体 · CPU / 晶圆代工） | 2026-10-02 | Underweight | 119.33 | 多头排列但过度延伸：高于 200SMA 约 47%；10/2 长上影反转 K 线，MACD 柱收窄至 0.44 | 117.64（10EMA）／115.76（VWMA）跌破再减 1/3／111.64（布林中轨）清战术仓／100.87（50SMA） | 124–126 反弹受阻加码减；收盘站回 132.53 则空头止损 | Q3 财报（营收增速 20%+、毛利率 ≥40%；日期未注明）；18A／14A 外部客户 |
| [SKHY](SKHY/2026-10-02/reports/final_trade_decision.md) | SK hynix（Nasdaq ADR） | Semiconductors（半导体 · 存储 DRAM/HBM） | 2026-10-02 | Overweight | 195.13 | 多头：价格 > 10EMA > VWMA > 布林中轨 > 50SMA ≈ 200SMA（200 日历史不足）；MACD 柱转负，量能低于 9 月突破期 | 188.43／186.41–186.69 分批建仓／181.50 结构止损／166.38（200SMA，可信度低）清仓 | 放量收上 200.36、回踩 198.63–200.36 不破且 MACD 柱转正 | Q3 财报（毛利率 ≥75%、存货环比 <20%；日期未注明）；10 年期美债 5.5% |
| [AAPL](AAPL/2026-10-02/reports/final_trade_decision.md) | Apple | Technology Hardware（消费电子 · 硬件） | 2026-10-02 | Overweight | 333.69 | 多头：价格 ≈ 10EMA（走平）> 50SMA > 200SMA；MACD 死叉，价格 < VWMA 335.30 | 322.36（50SMA）减至 50%–60%／317.00 硬止损（布林下轨下方） | 收盘站上 335.30 并突破 341.07，MACD 柱回正、放量 | 10/16 前后销售数据（仅来自 StockTwits，未核实）；FQ4 财报（验证库存 +94%；日期未注明） |
| [SNDK](SNDK/2026-10-02/reports/final_trade_decision.md) | Sandisk | Technology Hardware, Storage & Peripherals（存储 · NAND 闪存 / SSD） | 2026-10-02 | Underweight | 1719.99 | 中长期多头：价格 > 50SMA > 200SMA（高于 200SMA 约 50%），但跌破 10EMA 1738.43；1800–1909 两次冲高回落，MACD 死叉，RSI 顶背离 | 1708 再减 1/3／1659.02 只留观察仓／1519.12–1539.67（布林下轨／50SMA）继续退出 | 放量收盘站上 1909.48，且 FY27 指引确认收入 >250 亿、毛利率 >60% | FY27 Q1 财报（约 10 月底／11 月，日期未注明） |

### 可选消费 · Consumer Discretionary（1）

| Ticker | 公司 | 细分板块 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|
| [TSLA](TSLA/2026-10-02/reports/final_trade_decision.md) | Tesla | Automobile Manufacturers（电动车 · 自动驾驶） | 2026-10-02 | Underweight | 370.59 | 修复：50SMA 347.58 < 价格 < 200SMA 393.18（下行）；10/2 放量长阳但催化剂未知，MACD 柱 -1.50 未金叉 | 370.59 先减，382.64 反弹再减／347.09–347.58（布林下轨／50SMA）放量收破清观察仓 | 放量收盘站上 393.18（200SMA）且 MACD 柱转正后重评 | Q3'26 交付／财报（毛利率、营业利润率、FCF；日期未注明） |

### 通信服务 · Communication Services（2）

| Ticker | 公司 | 细分板块 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|
| [TTWO](TTWO/2026-10-02/reports/final_trade_decision.md) | Take-Two Interactive | Interactive Home Entertainment（游戏） | 2026-10-02 | Underweight | 202.73 | 空头：价格 < 10EMA 205.32 < 200SMA 224.57 < 50SMA 226.21，死叉临近；下跌放量、反弹缩量 | 199.50 放量跌破减至 0–25%／197.25（布林下轨）／187.60–191.00 | 放量收复 209.00 只暂停减仓；站稳 225–226.20 偏空逻辑失效 | Q2 FY27 财报（预计 11 月初）；GTA VI 发售（预测市场 95% 于 11/30 前） |
| [META](META/2026-10-02/reports/final_trade_decision.md) | Meta Platforms | Interactive Media & Services（互动媒体 · 社交 / AI） | 2026-10-02 | Underweight | 728.08 | 价格 > 10EMA > 200SMA ≈ 50SMA（死叉未解但快速收窄）；9/21 放量突破后高位缩量，MACD 柱刚转负，RSI 80.55→61.54 | 728–777.59 分批减持／695.66（布林中轨）跌破减至 0.25–0.3x／624.66–627.39 跌破全面回避 | 50/200 金叉且放量突破 777.59／792.16，并需基本面改善 | 下季财报（FCF、资本开支指引；日期未注明）；10 月 FOMC |

---

## 板块分析 / Sector view

基于 2026-10-02 报告（14 只全部更新，模型 DeepSeek V4.1 Flash，Deep）。

**分布**：信息技术 11／14（79%），其中半导体 7 只（NVDA、TSM、MU、QCOM、AMD、INTC、SKHY），软件 2（MSFT、U），硬件／存储 2（AAPL、SNDK）；通信服务 2（TTWO、META）；可选消费 1（TSLA）。清单高度集中在 AI 算力、存储与平台链条。

**评级**：Overweight 6（NVDA、TSM、QCOM、SKHY、U、AAPL）｜Hold 1（AMD）｜Underweight 7（MU、INTC、SNDK、MSFT、TSLA、TTWO、META）。相比 09-25：QCOM、AAPL 由 Hold 升为 Overweight，MSFT、TTWO 由 Overweight 降为 Underweight，新增 6 只首次评级。

| 板块 | 标的 | 板块共性判断 | 主要风险 |
|---|---|---|---|
| 半导体 · 算力／制造 | NVDA、TSM、AMD、INTC、QCOM | 结论按估值分化：NVDA（Forward PE 约 15）、TSM（Forward PE 约 22、净现金充裕）趋势完整获 Overweight，但都贴近前高、要求放量突破后再加；AMD 基本面强但 TTM PE 约 161、缩量新高，Hold 不追；INTC 拐点为真但远期 PE 约 58、高于 200SMA 约 47% 且出现反转 K 线，Underweight；QCOM 估值与回购提供缓冲，中期金叉仍在，轻仓 Overweight。 | 同一 AI 资本开支周期，高度相关；NVDA 应收与现金转化率走弱，QCOM 最新季营收下滑、库存应收大增；TSM 台海与出口管制尾部风险。 |
| 半导体／硬件 · 存储 | MU、SKHY、SNDK | 三只都处于峰值利润率：MU、SNDK 毛利率约 85%，低 Forward PE 被视为周期顶部的价值陷阱，叠加高管集中减持和高位派发形态，均为 Underweight；SKHY 硬数据最强（营收 +257%、净现金约 480 亿美元），只在回踩时分批 Overweight。 | 存储价格拐点会同时冲击三只；SKHY 约 40% EBITDA 来自投资利得，200SMA 历史不足、数据口径混杂；MU 报告未纳入已发布的 FY26 Q4 财报。 |
| 软件／消费硬件 | MSFT、U、AAPL | MSFT"好公司、坏价格"：Forward PE 约 22 隐含的 EPS 增速高于核心增速，FCF 同比 -23%、资本开支占营收约 40%，降为 Underweight；U 现金流拐点已验证（单季 FCF 新高、首次净现金），但仍亏损、Beta 约 2，限仓 Overweight；AAPL 盈利加速、长期趋势完好，但 Forward PE 约 35、库存 +94% 待证伪，首笔 20–25% 慢建仓。 | 10 年期美债高位压估值；MSFT 管理层在 500 附近减持；U 诉讼与 AAPL 销售数据催化剂均只来自 StockTwits，未核实。 |
| 可选消费 | TSLA | 营业利润率降至约 1.4%、FCF 为负、Forward PE 约 171，价格仍在下行的 200SMA 之下，维持 Underweight，降至 0–0.5% 但不主动做空。 | 现金约 434 亿、储能与 Semi 增长；ATR 大且有单日 -14.5% 跳空前科，放量站上 393.18 需回补。 |
| 通信服务 | TTWO、META | TTWO 由 Overweight 降为 Underweight：空头排列、死叉临近、内部人零买入、递延收入下降，仅保留 GTA VI 事件仓并对冲；META 营收 +28% 但营业利润率由 43% 降至约 31%，资本开支吃掉约 94% 经营现金流、回购停止、债务大增，价格近 52 周高点，Underweight。 | TTWO 二元事件集中在 GTA VI 发售（官方 11/19），成功可能快速逼空；META 广告主业与约 81% 毛利率是下行缓冲。 |

**共同宏观变量**：利率。多份报告引用 10 年期美债收益率处多年高位，并以 10 月 FOMC、CPI／非农为近期节点；高估值与高 Beta 标的（AMD、INTC、TSLA、U、NVDA）同向承压，清单内仍无受益于高利率的对冲标的。

**整体结论**：本轮偏空多于偏多——估值与基本面匹配、趋势完整的 NVDA、TSM、SKHY 等维持或给出 Overweight，但都只在回踩或放量突破时分批；峰值利润率的存储股（MU、SNDK）、资本开支挤压现金流的平台股（MSFT、META）和高估值的 INTC、TSLA、TTWO 被下调或首评 Underweight。共同纪律不变："不追高、以收盘确认破位、分批进出"。清单仍缺少防御性板块（必需消费、医疗、公用事业、能源），与 AI 链条相关性高。

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
| 2026-10-02 | REMOVE | ETN | 工业 | 移除；清单 v5 为 13 只、3 个板块 |
| 2026-10-02 | ADD | U | 信息技术 | 新增；尚无报告，未评级；清单 v6 为 14 只、3 个板块 |
| 2026-10-02 | RATING | QCOM | 信息技术 | Hold → Overweight（2026-10-02 报告） |
| 2026-10-02 | RATING | MSFT | 信息技术 | Overweight → Underweight（2026-10-02 报告） |
| 2026-10-02 | RATING | U | 信息技术 | 未评级 → Overweight（首份报告，2026-10-02） |
| 2026-10-02 | RATING | AMD | 信息技术 | 未评级 → Hold（首份报告，2026-10-02） |
| 2026-10-02 | RATING | INTC | 信息技术 | 未评级 → Underweight（首份报告，2026-10-02） |
| 2026-10-02 | RATING | SKHY | 信息技术 | 未评级 → Overweight（首份报告，2026-10-02） |
| 2026-10-02 | RATING | AAPL | 信息技术 | Hold → Overweight（2026-10-02 报告） |
| 2026-10-02 | RATING | SNDK | 信息技术 | 未评级 → Underweight（首份报告，2026-10-02） |
| 2026-10-02 | RATING | TTWO | 通信服务 | Overweight → Underweight（2026-10-02 报告） |
| 2026-10-02 | RATING | META | 通信服务 | 未评级 → Underweight（首份报告，2026-10-02）；清单 v7 全部 14 只更新至 2026-10-02 报告 |
