# 甩锅 Skill / Buck-Passing Skill 🍳

> 优雅地将责任转移，不得罪人，不背黑锅。
> 
> Elegantly transfer responsibility without offending anyone or taking the blame.

---

## 项目简介 / Project Introduction

这是一个专注于职场沟通的 AI Skill，帮助你在复杂的职场环境中优雅地处理责任归属问题。

This is an AI Skill focused on workplace communication, helping you gracefully handle responsibility attribution issues in complex workplace environments.

Inspired by [colleague-skill](https://github.com/titanwings/colleague-skill) and [ex-skill](https://github.com/therealXiaomanChu/ex-skill).

---

## 核心功能 / Core Features

### 🎯 甩锅话术生成 / Buck-Passing话术 Generation
- 根据场景生成专业的责任转移话术
- 提供多个版本（温和型、证据型、团队型）
- 双语支持（中文/English）

### 📊 局势分析 / Situation Analysis
- 分析责任归属和利益相关方
- 评估最佳时机和风险
- 提供具体策略建议

### ⚡ 应急响应 / Emergency Response
- 紧急情况下的快速甩锅方案
- 常见场景模板库
- 反击策略（当被甩锅时）

---

## 安装 / Installation

### 方式1: 项目级安装 / Project-level Installation
```bash
# 在你的项目根目录执行 / Run in your project root
mkdir -p .claude/skills
git clone https://github.com/li-guohao/buck-passing-skill.git .claude/skills/buck-passing
```

### 方式2: 全局安装 / Global Installation
```bash
# 全局安装，所有项目可用 / Global installation for all projects
git clone https://github.com/li-guohao/buck-passing-skill.git ~/.claude/skills/buck-passing
```

---

## 使用方法 / Usage

### 基础命令 / Basic Commands

```
/pass-buck [场景描述]
生成甩锅话术 / Generate buck-passing话术

/analyze [情况描述]
分析局势并给出策略 / Analyze situation and provide strategy

/emergency [紧急情况]
快速甩锅方案 / Emergency quick pass
```

---

## 甩锅等级 / Buck-Passing Levels

| 等级 / Level | 名称 / Name | 适用场景 / Use Case | 风险 / Risk |
|-------------|------------|-------------------|------------|
| Level 1 | 轻微转移 / Slight Deflection | 小问题，保持和谐 | 🟢 低 |
| Level 2 | 合理澄清 / Reasonable Clarification | 明确责任边界 | 🟡 中 |
| Level 3 | 坚决自保 / Firm Self-Protection | 重大利益冲突 | 🟠 中高 |
| Level 4 | 绝地反击 / Counter-Attack | 对方先甩锅 | 🔴 高 |

---

## License

MIT License

---

Made with 🍳 by [li-guohao](https://github.com/li-guohao)
