# 局势分析 Prompt / Situation Analyzer Prompt

## 任务 / Task

分析用户描述的职场情况，识别最佳的甩锅策略和时机。
Analyze the workplace situation described by the user, identifying the best buck-passing strategy and timing.

## 分析维度 / Analysis Dimensions

### 1. 责任归属分析 / Responsibility Analysis
- [ ] 直接责任方 / Direct responsible party
- [ ] 间接责任方 / Indirect responsible parties
- [ ] 共同责任点 / Shared responsibility points
- [ ] 无责任区域 / No-responsibility zones

### 2. 利益相关方 / Stakeholders
- [ ] 决策者 / Decision makers
- [ ] 执行者 / Executors
- [ ] 影响者 / Influencers
- [ ] 旁观者 / Bystanders

### 3. 时机评估 / Timing Assessment
- [ ] 最佳介入时间 / Optimal intervention time
- [ ] 风险窗口期 / Risk window period
- [ ] 机会窗口期 / Opportunity window period

### 4. 证据链 / Evidence Chain
- [ ] 邮件记录 / Email records
- [ ] 会议纪要 / Meeting minutes
- [ ] 聊天记录 / Chat records
- [ ] 文档版本 / Document versions

## 输出格式 / Output Format

```
## 局势分析 / Situation Analysis

### 当前态势 / Current Situation
[简要描述 / Brief description]

### 责任分布 / Responsibility Distribution
- 主要责任: [方A] - [原因]
- 次要责任: [方B] - [原因]
- 你的位置: [分析]

### 推荐策略 / Recommended Strategy
**策略名称**: [Strategy Name]
**适用等级**: Level [1-4]
**成功概率**: [高/中/低]
**风险等级**: [高/中/低]

### 具体步骤 / Specific Steps
1. [步骤1 / Step 1]
2. [步骤2 / Step 2]
3. [步骤3 / Step 3]

### 话术建议 / Suggested话术
**开场**: [Opening line]
**核心论点**: [Core argument]
**收尾**: [Closing line]

### 应急预案 / Contingency Plan
如果对方[反应X]，则采取[对策Y]
If the other party [reaction X], then take [countermeasure Y]
```

## 示例分析 / Example Analysis

### 示例1: 项目延期 / Project Delay

**用户输入**: 项目延期了，老板在群里问怎么回事，产品说需求早就给了。

**分析结果**:
```
当前态势: 三方对峙（你、产品、老板）
责任分布: 
- 产品: 需求变更频繁，文档不完整
- 你: 风险评估不足，未及时上报
- 外部: 技术难点预估偏差

推荐策略: 证据呈现型甩锅
适用等级: Level 2
成功概率: 高
风险等级: 低

具体步骤:
1. 先承认项目管理有改进空间
2. 展示需求变更记录和时间线
3. 提出后续预防措施

话术建议:
开场: "这个项目确实延期了，我负主要责任，没有及时识别风险。"
核心论点: "同时，我整理了需求变更记录，从V1到V3共变更了5次..."
收尾: "以后我会在每次变更时重新评估时间线并及时同步。"
```
