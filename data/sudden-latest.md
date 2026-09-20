## MultiversX（EGLD）：主网暂停 — 攻击者尝试利用 VM 级原子性问题

- **背景：** MultiversX（原 Elrond）为公链 L1，原生资产 EGLD，生态含 ESDT 资产、xExchange/跨链桥等。9 月 19 日官方曾称「主网潜在问题调查中」，status 为 Partially Degraded；本岗此前标 near_miss，等确认停机/共识暂停再推。
- **发生了什么：** 【已核实】Odaily 519067（约 08:57 Asia/Shanghai）与律动 BlockBeats 368045：MultiversX 称已确认攻击者尝试利用一项 **VM 级原子性问题**，导致网络出现**无效状态变更**；为防扩大，**网络已暂停运行**。团队已准备修复，将先在影子分叉验证，再与验证者、交易所及基础设施伙伴协调部署主网；恢复方案拟保留已确认交易历史与正常用户状态，仅处理本次相关无效状态变更。官方要求：恢复通知前勿提交/重播交易，勿经交易所或跨链桥充提 EGLD 及 ESDT。【已核实】status.multiversx.com 仍为 indicator=`minor` Partially Degraded，多组件（API/Wallet/Bridge/xExchange 等）`degraded_performance`，当前 unresolved incidents=0（状态页未另开新 incident 卡）。【待核实】官方 X/博客原文链、是否已有交易所同步冻结 EGLD/ESDT 充提、影子分叉验证结果与恢复 ETA、是否有可量化资金损失。【未知】无效状态变更涉及地址/金额、是否需定向状态修复以外的措施。
- **为什么重要 / 影响风险：** 属「头部协议暂停」档（L1 主网暂停 + 攻击面确认）。持有 EGLD、ESDT、跨链桥或 CEX 充提敞口者，按链停机/充提冻结处理，勿假设可正常进出。EGLD 现价约 $3.85–3.87（Coinbase/OKX），OKX 24h 约 −4.8%（相对 open24h），非本条主因但加重流动性摩擦。
- **事实分层：** 已核实：Odaily 519067、BlockBeats 368045（均引官方口径）、status 组件 degraded。待核实：官方原文 permalink、交易所公告、损失金额、DefiLlama 是否记入、恢复时间。未知：根因代码细节、攻击者是否已获利。
- **观察：** 仅作风控观察，不是买卖建议。

出处：
- https://www.odaily.news/zh-CN/newsflash/519067
- https://www.theblockbeats.info/flash/368045
- https://status.multiversx.com/
