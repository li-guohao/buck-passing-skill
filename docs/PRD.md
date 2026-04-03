# 甩锅 Skill 产品需求文档 / Buck-Passing Skill PRD

## 项目背景 / Background

在复杂的职场环境中，责任归属问题是一个永恒的话题。本项目旨在帮助职场人士优雅地处理责任转移，既不伤害人际关系，又能保护自己的利益。

In complex workplace environments, responsibility attribution is an eternal topic. This project aims to help workplace professionals gracefully handle responsibility transfer without damaging relationships while protecting their own interests.

## 产品目标 / Product Goals

### 主要目标 / Primary Goals
1. 提供专业的职场沟通话术 / Provide professional workplace communication话术
2. 帮助用户识别最佳甩锅时机 / Help users identify optimal buck-passing timing
3. 提供多层次的策略选择 / Provide multi-level strategy options

### 次要目标 / Secondary Goals
1. 教育用户职场沟通技巧 / Educate users on workplace communication skills
2. 建立职场话术模板库 / Build a workplace话术 template library
3. 形成职场生存指南社区 / Form a workplace survival guide community

## 用户画像 / User Personas

### 用户1: 职场新人 / Workplace Newbie
- **痛点**: 经常被甩锅，不知道如何应对
- **需求**: 基础的防御性话术
- **使用场景**: 日常工作中被质疑时

### 用户2: 中层管理 / Middle Manager
- **痛点**: 上下夹击，需要平衡各方利益
- **需求**: 高级的策略性话术
- **使用场景**: 跨部门会议、向上汇报

### 用户3: 技术专家 / Technical Expert
- **痛点**: 不擅长沟通，容易被误解
- **需求**: 简洁有力的表达方式
- **使用场景**: 技术评审、故障复盘

## 功能需求 / Functional Requirements

### 核心功能 / Core Features

#### 1. 话术生成 /话术 Generation
- **输入**: 场景描述
- **输出**: 3个版本的话术（温和型、证据型、团队型）
- **语言**: 中英双语

#### 2. 局势分析 / Situation Analysis
- **输入**: 详细情况描述
- **输出**: 
  - 责任分布分析
  - 利益相关方识别
  - 时机评估
  - 策略建议

#### 3. 应急响应 / Emergency Response
- **输入**: 紧急情况描述
- **输出**: 即时可用的话术
- **特点**: 快速、简洁、有效

### 扩展功能 / Extended Features

#### 1. 案例库 / Case Library
- 常见职场场景案例
- 成功/失败案例分析
- 用户投稿案例

#### 2. 话术评分 /话术 Scoring
- 用户反馈话术效果
- 话术成功率统计
- 热门话术排行

#### 3. 个性化定制 / Personalization
- 根据用户风格调整话术
- 行业特定话术
- 公司文化适配

## 技术架构 / Technical Architecture

### 文件结构 / File Structure
```
buck-passing-skill/
├── SKILL.md              # Skill 入口配置
├── README.md             # 项目文档
├── prompts/              # Prompt 模板
│   ├── main.md          # 主 Prompt
│   ├── analyzer.md      # 分析 Prompt
│   └── emergency.md     # 应急 Prompt
├── examples/             # 案例库
│   └── examples.md      # 案例集
└── docs/                 # 文档
    └── PRD.md           # 产品需求文档
```

### Prompt 设计 / Prompt Design

#### 主 Prompt 结构
1. 角色设定 / Role Setting
2. 核心能力 / Core Capabilities
3. 话术模板 /话术 Templates
4. 回应策略 / Response Strategies
5. 禁忌与法则 / Taboos and Rules

#### 分析 Prompt 结构
1. 分析维度 / Analysis Dimensions
2. 输出格式 / Output Format
3. 示例分析 / Example Analysis

## 甩锅等级体系 / Buck-Passing Level System

### Level 1: 轻微转移 / Slight Deflection
- **适用场景**: 小问题，保持和谐关系
- **策略**: 承认部分责任，引入外部因素
- **风险**: 低
- **示例**: "这个问题确实有我的疏忽，同时我们也发现..."

### Level 2: 合理澄清 / Reasonable Clarification
- **适用场景**: 明确责任边界，但不伤和气
- **策略**: 用证据说话，强调流程问题
- **风险**: 中
- **示例**: "根据当时的邮件记录，这个决策是在...情况下做出的"

### Level 3: 坚决自保 / Firm Self-Protection
- **适用场景**: 涉及重大利益时的强硬策略
- **策略**: 明确责任归属，指出对方问题
- **风险**: 中高
- **示例**: "从时间线和证据来看，主要责任在于..."

### Level 4: 绝地反击 / Counter-Attack
- **适用场景**: 当对方先甩锅时的反击策略
- **策略**: 揭露对方漏洞，转移焦点
- **风险**: 高
- **示例**: "既然提到这个，那我们就来回顾一下..."

## 话术模板分类 /话术 Template Categories

### 按场景分类 / By Scenario
1. 项目延期 / Project Delay
2. 线上故障 / Production Incident
3. 需求变更 / Requirement Changes
4. 跨部门协作 / Cross-department Collaboration
5. 资源不足 / Insufficient Resources
6. 上级决策 / Superior Decisions

### 按风格分类 / By Style
1. 温和型 / Gentle
2. 证据型 / Evidence-based
3. 团队型 / Team-oriented
4. 专业型 / Professional
5. 担当型 / Taking Responsibility (反向操作)

## 成功指标 / Success Metrics

### 定量指标 / Quantitative Metrics
- 用户活跃度 / User Activity
- 话术生成次数 /话术 Generation Count
- 用户满意度评分 / User Satisfaction Score
- 案例库规模 / Case Library Size

### 定性指标 / Qualitative Metrics
- 用户反馈质量 / User Feedback Quality
- 社区活跃度 / Community Activity
- 口碑传播 / Word-of-mouth

## 风险与应对 / Risks and Mitigation

### 风险1: 被滥用于恶意甩锅
- **应对**: 添加免责声明，强调建设性使用

### 风险2: 话术过于套路化
- **应对**: 提供个性化定制选项

### 风险3: 文化差异导致不适用
- **应对**: 提供多文化版本

## 路线图 / Roadmap

### Phase 1: MVP (当前)
- [x] 基础话术生成
- [x] 局势分析功能
- [x] 案例库建设

### Phase 2: 增强
- [ ] 应急响应功能
- [ ] 话术评分系统
- [ ] 更多案例

### Phase 3: 生态
- [ ] 社区功能
- [ ] 个性化定制
- [ ] 行业版本

## 竞品分析 / Competitive Analysis

### 直接竞品 / Direct Competitors
- 暂无直接竞品 / No direct competitors yet

### 间接竞品 / Indirect Competitors
- 职场沟通书籍 / Workplace communication books
- 职场培训课程 / Workplace training courses
- 心理咨询服务 / Psychological counseling services

### 差异化优势 / Differentiation
1. AI 驱动的即时生成 / AI-driven instant generation
2. 场景化模板 / Scenario-based templates
3. 双语支持 / Bilingual support
4. 开源免费 / Open source and free

## 附录 / Appendix

### 术语表 / Glossary
- **甩锅**: 将责任转移给他人
- **背锅**: 承担不属于自己的责任
- **话术**: 特定的表达方式
- **局势分析**: 对当前情况的全面评估

### 参考资料 / References
- [colleague-skill](https://github.com/titanwings/colleague-skill)
- [ex-skill](https://github.com/therealXiaomanChu/ex-skill)
- 职场沟通相关书籍 / Workplace communication books
