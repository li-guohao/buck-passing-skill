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

### 使用示例 / Examples

#### 示例1: 项目延期 / Project Delay
```
用户: /pass-buck 项目延期了，老板问怎么回事

Skill: 
【局势分析】这是一个典型的多方责任场景...

【推荐话术】
版本A: "这个项目确实延期了，作为负责人我负主要责任。
回顾整个过程，我们在V1版本评估后，后续有3次需求变更..."

版本B: "延期确实发生了，我整理了一下时间线..."
```

#### 示例2: 线上故障 / Production Incident
```
用户: /analyze 系统昨晚挂了，运维说是代码问题

Skill:
【责任分析】...
【推荐策略】系统分析型 (Level 3)
【具体步骤】...
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

## 话术模板 / Templates

### 资源不足型 / Insufficient Resources
```
"这个项目确实遇到了一些挑战。我们在启动时评估的资源是X，
但实际执行中发现需要Y。我建议我们重新评估资源分配..."
```

### 需求变更型 / Requirement Changes
```
"我理解大家的担忧。需要说明的是，在M月N日需求发生了重大变更，
这直接影响了原定的时间线。我们有当时的变更记录可以确认..."
```

### 跨部门协作型 / Cross-department Issues
```
"这个问题涉及多个部门的协作。从我们这边来看，我们在T时间完成了交付，
后续的流程可能需要相关同事一起复盘一下..."
```

---

## 黄金法则 / Golden Rules

✅ **永远给对方面子** / Always save face for others  
✅ **强调"我们"而非"我"或"你"** / Emphasize "we" not "I" or "you"  
✅ **指向系统问题而非个人** / Point to system issues, not individuals  
✅ **提供建设性方案** / Provide constructive solutions  

❌ **禁忌 / Taboos**:
- 直接否认责任 / Direct denial of responsibility
- 指责具体个人 / Blaming specific individuals
- 情绪化表达 / Emotional expressions
- 没有证据的辩解 / Defense without evidence

---

## 项目结构 / Project Structure

```
buck-passing-skill/
├── SKILL.md              # Skill 入口文件 / Entry file
├── README.md             # 项目说明 / Project documentation
├── prompts/
│   ├── main.md          # 主 Prompt / Main prompt
│   ├── analyzer.md      # 分析 Prompt / Analyzer prompt
│   └── emergency.md     # 应急 Prompt / Emergency prompt
├── examples/
│   ├── examples.md      # 案例集 / Examples
│   └── fake-cases.md    # 虚构案例 / Fake cases
└── docs/
    └── PRD.md           # 产品需求文档 / PRD
```

---

## 相关项目 / Related Projects

- [colleague-skill](https://github.com/titanwings/colleague-skill) - 同事 Skill
- [ex-skill](https://github.com/therealXiaomanChu/ex-skill) - 前任 Skill
- [yourself-skill](https://github.com/notdog1998/yourself-skill) - 自己 Skill

---

## 贡献 / Contributing

欢迎提交 Issue 和 PR！
Issues and PRs are welcome!

---

## 免责声明 / Disclaimer

⚠️ 本 Skill 仅供学习和职场沟通技巧提升使用，请勿用于恶意推卸责任或伤害他人。

⚠️ This Skill is for learning and workplace communication skills improvement only. Please do not use it for maliciously evading responsibility or harming others.

---

## License

MIT License

---

Made with 🍳 by [li-guohao](https://github.com/li-guohao)

> "职场如厨房，锅是甩不完的，但我们可以优雅地甩。"
> 
> "The workplace is like a kitchen, there are endless pots to pass, but we can do it gracefully."
