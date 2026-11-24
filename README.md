# llm-trade-lab

> Experiments on LLM agents for financial market analysis.

一个探索大语言模型 Agent 在金融市场分析中能力与边界的个人实验室。
关注可评测、可复现、风控优先的 Agent 工程实践。

## Projects

| 项目 | 简介 | 状态 |
|---|---|---|
| [goldmind](./projects/goldmind) | 面向黄金合约的对话式分析 Agent，代码级风控保障不爆仓 | 🚧 开发中 |

## Principles
- **Risk first**：仓位、杠杆、爆仓价由确定性代码计算与校验，LLM 无法绕过
- **Evaluate everything**：每次改动都通过评测集量化效果
- **Forward testing only**：规避 LLM 训练数据带来的回测污染，只认前向验证
- **Read-only**：Agent 只读取行情，不连接交易权限

## Getting Started

```bash
git clone --recurse-submodules https://github.com/JasonLee-03/llm-trade-lab.git
```

已克隆但子模块为空时：

```bash
git submodule update --init --recursive
```

## Disclaimer
本仓库仅用于技术研究与学习，不构成任何投资建议。
