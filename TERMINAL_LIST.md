# Terminal List · 研究标的控制清单

本清单是研究标的的控制面板：记录当前在跟踪哪些股票、各自所属板块、最新报告结论，以及每一次增删的历史。新增或移除标的时，同步更新「当前清单」「板块分析」，并在「变更记录」追加一行，**历史记录只追加、不删除**。

- 板块采用 GICS 行业分类（Sector / Sub-industry），括号内为中文板块。
- 评级、参考价与关键位均摘自对应日期的 `final_trade_decision.md` 与 `market_report.md`，为报告当日的数据，非实时行情。
- 状态：`Active` 跟踪中｜`Paused` 暂停｜`Removed` 已移除（移至「已移除」表，保留记录）。
- 报告由 AI 生成，仅供研究，不构成投资建议。

---

## 当前清单 / Active list

版本：v2（2026-09-25，移除银行股）｜标的数：9｜板块数：4

### 信息技术 · Information Technology（6）

| Ticker | 公司 | 细分板块 | 状态 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|---|
| [NVDA](NVDA/2026-09-07/reports/final_trade_decision.md) | NVIDIA | Semiconductors（半导体 · AI 算力 GPU） | Active | 2026-09-07 | Hold | 230.36 | 多头：价格 > 50SMA > 200SMA | 210.57（50SMA）／196.53（200SMA） | 放量站稳 236.54 | 9 月 FOMC；10 月底财报 |
| [TSM](TSM/2026-09-07/reports/final_trade_decision.md) | TSMC | Semiconductors（半导体 · 晶圆代工） | Active | 2026-09-07 | Hold | 428.91 | 长期多头；50SMA 仍缓降 | 420 → 406–410 → 371.8（200SMA） | 放量站稳 433 且回踩不破 | 利率 / CPI / 油价（宏观估值逆风） |
| [MU](MU/2026-09-07/reports/final_trade_decision.md) | Micron | Semiconductors（半导体 · 存储 DRAM/HBM） | Active | 2026-09-07 | Hold | 1016.59 | 多头，高位乖离 | 938（50SMA）+ MACD 死叉 | 放量站稳 1040 | 9 月 FOMC；9 月底 FY26Q4 财报 |
| [QCOM](QCOM/2026-09-07/reports/final_trade_decision.md) | Qualcomm | Semiconductors（半导体 · 移动 SoC / 专利授权） | Active | 2026-09-07 | Hold | 168.74 | 中性：贴 50/200SMA，底部修复中 | 165.9–166.1 先减／163 离场 | 放量站稳 170.6 | 11 月初 FQ4'26 财报 |
| [MSFT](MSFT/2026-09-07/reports/final_trade_decision.md) | Microsoft | Systems Software（软件 · 云 / AI 平台） | Active | 2026-09-07 | Hold | 499.70 | 多头；MACD 柱为负，短线修正 | 495 观察／443（50SMA）+ 基本面恶化 | 放量站稳 517.8 | 9/11 CPI；9 月 FOMC；10 月 FY27Q1 财报 |
| [AAPL](AAPL/2026-09-07/reports/final_trade_decision.md) | Apple | Technology Hardware（消费电子 · 硬件） | Active | 2026-09-07 | Hold | 319.97 | 多头：贴 10EMA，50SMA 支撑 | 313 减仓／300–303 最后防线 | 放量站稳 331 | 9/9 新品发布会 |

### 工业 · Industrials（1）

| Ticker | 公司 | 细分板块 | 状态 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|---|
| [ETN](ETN/2026-09-08/reports/final_trade_decision.md) | Eaton | Electrical Components & Equipment（电气设备 · 数据中心电气化） | Active | 2026-09-08 | Hold | 422.12 | 多头：收复 50SMA，200SMA 上行 | 410 预警／400 止损 | 放量站稳 430 | 9 月 FOMC；10 月底 Q3 财报 |

### 可选消费 · Consumer Discretionary（1）

| Ticker | 公司 | 细分板块 | 状态 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|---|
| [TSLA](TSLA/2026-09-07/reports/final_trade_decision.md) | Tesla | Automobile Manufacturers（电动车 · 自动驾驶） | Active | 2026-09-07 | Hold | 354.08 | 空头：价格 < 50SMA < 200SMA | 348 预警／323.65 止损 | 放量突破 373–376 | Q3 财报；NHTSA 审查；欧盟 FSD 投票 |

### 通信服务 · Communication Services（1）

| Ticker | 公司 | 细分板块 | 状态 | 最新报告 | 评级 | 参考收盘 | 趋势结构 | 下方关键位（收盘） | 上方确认位 | 下一催化剂 |
|---|---|---|---|---|---|---|---|---|---|---|
| [TTWO](TTWO/2026-09-07/reports/final_trade_decision.md) | Take-Two Interactive | Interactive Home Entertainment（游戏） | Active | 2026-09-07 | Hold | 214.69 | 空头：低于全部主要均线 | 210–212 支撑／207 止损 | 放量站稳 223–229 连续三日 | 11/19 GTA VI 发售 |

---

## 板块分析 / Sector view

基于 2026-09-07 / 09-08 报告；v2 已移除金融板块（JPM、BNY）。

**分布**：信息技术 6／9（67%），其中半导体 4 只；工业、可选消费、通信服务各 1。清单明显偏重科技与 AI 链条——若把 ETN（数据中心电气化）也算作 AI 资本开支受益方，与 AI 相关的标的有 7／9。

| 板块 | 标的 | 板块共性判断 | 主要风险 |
|---|---|---|---|
| 半导体 | NVDA、TSM、MU、QCOM | AI 算力链（NVDA／TSM／MU）基本面最强：营收高增长、毛利率上行；但价格已靠近前高，均为"持有、不追高、回踩或放量突破再加"。QCOM 是反例：移动端营收下滑、苹果基带流失，处于低估值 + 趋势恶化的底部博弈。 | 同一 AI 资本开支周期驱动，彼此高度相关，一次宏观或 AI 需求冲击会同时打击；MU 为周期股，存储价格拐点风险最大。 |
| 软件 / 硬件 | MSFT、AAPL | 大盘平台股，多头结构完整，但估值已反映预期。MSFT 看 Azure 增速与资本开支回报；AAPL 看发布会后的换机周期。 | 利率上行压估值；资本开支过度（MSFT）；"卖事实"（AAPL）。 |
| 工业 | ETN | 电网与数据中心电气化受益，营收加速；但高估值、高杠杆、利润率受利息与税率拖累。 | 实质上是 AI 资本开支的延伸，与半导体板块同向波动。 |
| 可选消费 | TSLA | 唯一处于空头排列的大盘股，高 Beta（约 1.85）；叙事驱动（FSD / Robotaxi），需要监管与财报催化落地。 | 波动最大，需严格控制仓位。 |
| 通信服务 | TTWO | 单一事件驱动（GTA VI），技术面偏空，催化剂确定但已部分定价。 | 二元事件风险集中在 11/19。 |

**共同宏观变量**：利率。多份报告引用预测市场约 93% 的 2026 年美联储零降息定价，ETN、MU、NVDA、QCOM 等以 9 月 FOMC 为近期节点。利率上行对清单内高估值科技与电气设备同向承压；移除银行股后，清单内已没有受益于高利率的对冲标的。

**整体结论**：9 只全部为 Hold，没有方向性信号；共同纪律是"不追高、以收盘价确认破位、等待回踩或放量突破再加仓"。清单当前缺少防御性板块（必需消费、医疗、公用事业、能源），与 AI 链条相关性过高。

---

## 已移除 / Removed

| Ticker | 公司 | 板块 | 加入日期 | 移除日期 | 最后报告 | 移除原因 |
|---|---|---|---|---|---|---|
| [JPM](JPM/2026-09-07/reports/final_trade_decision.md) | JPMorgan Chase | 金融 · Diversified Banks（银行） | 2026-09-07 | 2026-09-25 | 2026-09-07 · Hold · 358.64 | 用户决定移除全部银行股 |
| [BNY](BNY/2026-09-07/reports/final_trade_decision.md) | BNY | 金融 · Asset Management & Custody Banks（托管银行） | 2026-09-07 | 2026-09-25 | 2026-09-07 · Hold · 164.84 | 用户决定移除全部银行股 |

---

## 变更记录 / Change log

只追加，不修改已有行。动作：`ADD` 新增｜`REMOVE` 移除｜`PAUSE` 暂停｜`RESUME` 恢复｜`REPORT` 新报告｜`RATING` 评级变化｜`INIT` 建立清单。

| 日期 | 动作 | Ticker | 板块 | 说明 |
|---|---|---|---|---|
| 2026-09-07 | REPORT | AAPL, MSFT, MU, NVDA, QCOM, TSLA, TSM, TTWO | 多板块 | 首批研究报告，评级均为 Hold |
| 2026-09-07 | REPORT | BNY, JPM | 金融 | 研究报告，评级均为 Hold |
| 2026-09-08 | REPORT | ETN | 工业 | 研究报告，评级 Hold |
| 2026-09-25 | INIT | 全部 11 只 | 5 个板块 | 按仓库已有报告建立 Terminal List v1，全部状态为 Active |
| 2026-09-25 | REMOVE | JPM, BNY | 金融 | 移除全部银行股；清单 v2 为 9 只、4 个板块。报告目录保留不动 |
