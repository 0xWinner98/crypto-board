## Nostra（NSTR）· Starknet 货币市场：预言机操纵致约 $350 万借出

- **背景：** Nostra 是 Starknet 头部借贷/货币市场之一；NSTR 为其治理代币。文档显示 NSTR 喂价仅接 Pragma、无二级预言机冗余。
- **发生了什么：** 【已核实】2026-09-18 08:51 Asia/Shanghai Odaily：被操纵的 NSTR 预言机价格，使单账户以 NSTR 作抵押，从 Nostra Starknet 货币市场借出约 $350 万（ETH、STRK、USDC、USDT、WBTC、DAI）；约 $192 万（234.57 ETH + 130 万 DAI）已跨链至以太坊。【已核实】DefiLlama Hacks API 同记：Nostra Money Market · Oracle Manipulation / Spot Price Manipulation · Starknet · 损失约 $3.5M（日期窗 2026-09-17 UTC 日切）。
- **为什么重要 / 影响风险：** 属「黑客/漏洞」档。持有 Nostra 存款、NSTR 抵押仓、或 Starknet 借贷敞口者，需按坏账/暂停风险处理，别假设可正常兑出。NSTR 单源预言机是已知结构弱点。
- **事实分层：** 已核实：Odaily 快讯 518648、DefiLlama hacks（Nostra Money Market，$3.5M）。待核实：官方/审计方根因报告、是否已暂停借贷或清算、坏账是否由协议金库覆盖。未知：剩余约 $158 万借出资产是否仍在 Starknet、追回比例。
- **观察：** 仅作风控观察，不是买卖建议。

出处：
- https://www.odaily.news/zh-CN/newsflash/518648
- https://api.llama.fi/hacks （Nostra Money Market）
- https://docs.nostra.finance/lend-and-borrow/oracles （NSTR 仅 Pragma）
