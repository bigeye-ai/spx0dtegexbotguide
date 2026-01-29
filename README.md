# 📊 SPX 0DTE GEX 作战手册

> **让每一个中文交易员都能看懂 GexBot 数据，做好末日期权交易。**

[![GitHub stars](https://img.shields.io/github/stars/bigeye-ai/spx0dtegexbotguide?style=social)](https://github.com/bigeye-ai/spx0dtegexbotguide)
[![Website](https://img.shields.io/badge/Website-在线阅读-blue?logo=github-pages)](https://bigeye-ai.github.io/spx0dtegexbotguide/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/bigeye-ai/spx0dtegexbotguide/pulls)

---

## 🎯 这是什么？

这是一本**中文社区驱动**的 GexBot 交易实战手册，专为做 **SPX 0DTE（末日期权）** 的日内交易员设计。

市面上关于 Gamma Exposure (GEX) 的资料要么是英文的，要么太学术化。我们的目标是：

- 🎓 **零门槛**：不需要金融工程背景，看完就能用
- 🔫 **实战导向**：按市场状态分类（正Gamma/负Gamma/翻转），拿来即用
- 🤝 **社区共建**：每个人都能贡献自己的交易笔记

---

## 📚 手册目录

| 章节 | 内容 | 市场状态 |
|------|------|----------|
| [🔵 橡皮筋战术](./chapters/01-rubber-band.md) | 正Gamma环境下的震荡交易策略 | 粘性市场 |
| [🔴 冰面竞速](./chapters/02-ice-surface.md) | 负Gamma环境下的趋势跟踪策略 | 滑性市场 |
| [⚡ 零号翻转](./chapters/03-the-flip.md) | 穿越零点时的变盘信号识别 | 临界点 |
| [🎭 假动作识别](./chapters/04-fakeouts.md) | 避免被虚假突破收割 | 所有状态 |

---

## 🚀 快速开始

### 我是交易员，想学习

1. 👉 直接访问 [在线手册](https://bigeye-ai.github.io/spx0dtegexbotguide/)
2. 从「橡皮筋战术」开始阅读
3. 配合 GexBot 实时数据实践

### 我想贡献内容

**零门槛参与！** 你完全不需要会编程：

1. Fork 本仓库
2. 创建新的 Markdown 文件或编辑现有文件
3. 提交 Pull Request

你的修改会被审核并合并到主分支！ 🎉

---

## 🧠 核心概念速查

```
正 Gamma (GEX > 0)          负 Gamma (GEX < 0)
    ↓                           ↓
价格被"吸回"                 价格被"推远"
    ↓                           ↓
震荡市场                      趋势市场
    ↓                           ↓
橡皮筋战术 🔵                 冰面竞速 🔴
```

---

## 📖 延伸阅读

- [GexBot 官方 X](https://x.com/thegexbot)
- [SpotGamma 原理解读](https://spotgamma.com/)
- [末日期权交易社群](#) (Coming Soon)

---

## 🛠️ 合作伙伴

### 复盘软件

- [ContemDAO](https://contemdao.com) - 专业的交易复盘工具

---

## 🤝 贡献者

感谢所有为本手册做出贡献的交易员们！

<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

---

## 📜 许可证

本项目采用 [MIT License](./LICENSE) 开源。

欢迎分享、修改、再创作，但请保留原始出处链接。

---

<p align="center">
  <b>📈 用 GEX 读懂市场，用纪律守护账户 📉</b>
</p>
