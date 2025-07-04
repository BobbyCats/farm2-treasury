## 🧱 它是什么（What is FARM2 Treasury System）

FARM2 国库系统是一个构建于 Solana 链上的**Web3 财务透明 + 社区贡献积分平台**，由 **链上收支追踪、贡献值记录、用户激励机制** 和 **Telegram机器人交互系统**构成。

它由社区自主运营，目标是解决：

* 资金使用不透明
* 贡献者缺乏可量化激励
* 社区缺乏参与感和秩序感

---

## 🚀 它能做什么（What It Can Do）

| 功能模块            | 能力                                   |
| --------------- | ------------------------------------ |
| 💼 国库钱包展示       | 显示 FARM2 国库地址，一键复制，一键发起捐款流程          |
| 📊 链上收支明细       | 自动解析 Solana 链上的入账/支出记录，支持备注与跳转查看详细记录 |
| 🧾 捐款登记与校验      | 用户连接钱包或填写地址，系统自动校验是否成功转账，防止刷分        |
| 🏆 贡献值系统        | 自动根据捐款金额（按USDT价值）分配经济贡献积分，支持技术积分扩展   |
| 🎖 徽章机制         | 不同等级贡献值自动解锁对应徽章，强化用户荣誉感              |
| 📈 贡献排行榜        | 展示本月 / 累计捐赠排名，Top10固定显示，其他滚动播报       |
| 🤖 Telegram Bot | 自动推送捐赠通知、积分更新、排行榜变动，支持指令交互           |
| 📄 月度财报生成       | 自动统计月度收支与排行榜，导出为 PDF / Markdown      |
| 🧠 Web3 轻治理接口   | 积分作为治理或提案参考基础，为未来治理做铺垫               |

---

## 🎯 有什么用（Why This Matters）

### ✅ 对社区来说：

* 真正实现**链上透明财务 + 信任建立**
* 明确贡献行为，**用积分和徽章肯定社区成员**
* 降低“割完跑”、“钱用哪儿去了”的不信任感
* 可沉淀数据资产，为 FARM2 后续治理 / 空投筛选 / 周边分发建立系统性基础

### ✅ 对 FARM2 项目本身：

* 提升品牌可信度与执行力（不像一个临时项目）
* 成为 FARM2 核心“贡献记录系统”
* 可演化为更广义的 **社区贡献资产系统（RCA）**
* 可作为 DAO 的基础设施组件输出给其他项目

---

## 🧩 还需要什么（What’s Missing / Next）

| 维度                | 当前状态                 | 下一步建议                          |
| ----------------- | -------------------- | ------------------------------ |
| 🖥 前端页面           | 主页面 `/treasury` 正在开发 | ✅ 快速收敛至正式 UI，舍弃测试页结构           |
| 🤝 钱包绑定           | 后端逻辑已定，前端未接          | ✅ 实现 connect or 手动地址逻辑，写入状态    |
| 🤖 Bot 通知         | 模版已定，Bot接口联动待完成      | ✅ 接入 Bot 推送通知与用户查询指令           |
| 🎖 NFT 铸造（可选）     | 未启动                  | 可设为第四阶段，提供徽章资产化能力              |
| 📡 数据输出           | JSON API 架构初步规划      | ✅ 开放接口供他人查询与嵌入                 |
| ⚙ 技术积分机制          | 思路已定，尚未实施            | ✅ 构建技术提案或代码行为→积分入账链路           |
| 🪙 FARM2 token实用性 | 关联度不强                | 若 FARM2 有治理/兑换等计划，应绑定此系统作为支撑工具 |

---

## 📌 项目定位一句话总结：

> FARM2 Treasury 是一个**Solana 链上可视化国库 + 贡献积分系统**，致力于让每一笔支出都有出处，每一次贡献都有价值，每一个社区成员都有参与感。

---
