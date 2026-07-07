---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 627fc51878dc6f34f79713b8bf41b97c_5703abdf79f911f18b365254007bceed
    ReservedCode1: 4Qy9L5gnRwzj3GtNjpRZysLBpzrPGCl7PjUyTkZh891KiX5Ob4LVgX+8otSdB1wR2UdaNnh79wiC5VPn0g5IGtwZWRAhd7ZIkK9L1nh4gcoDMg6ATKDou/6wvVBUTLpkr0QMT3qCY3dGYkYYFK0LDfDjSaB3QUbUF55e1gF1Ihd9/BTq4wMq37GY86I=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 627fc51878dc6f34f79713b8bf41b97c_5703abdf79f911f18b365254007bceed
    ReservedCode2: 4Qy9L5gnRwzj3GtNjpRZysLBpzrPGCl7PjUyTkZh891KiX5Ob4LVgX+8otSdB1wR2UdaNnh79wiC5VPn0g5IGtwZWRAhd7ZIkK9L1nh4gcoDMg6ATKDou/6wvVBUTLpkr0QMT3qCY3dGYkYYFK0LDfDjSaB3QUbUF55e1gF1Ihd9/BTq4wMq37GY86I=
---

# 贡献指南

欢迎对立党 Skill 提 PR / Issue！下面是几种贡献方式。

## 🎯 我们最需要什么

### 1. 补充立党原话（最高优先级）

立党的内容分布在 4 个平台：

| 平台 | 怎么找 | 优先级 |
|---|---|---|
| **X / Twitter** | @lidangzzz 推文（pinned 必看）| ⭐⭐⭐ |
| **YouTube 讲座** | 01~31+ 讲座视频，"立党 讲座 XX" | ⭐⭐⭐ |
| **GitHub 笔记** | lidangzzz/How-to-run、润学笔记 | ⭐⭐ |
| **直播** | 009/028/029/030 等直播录播 | ⭐⭐ |

### 2. 报告还原度问题

如果 LLM 用本 skill 回答问题后，**你觉得"不像立党"**，提 issue 时包含：

- 问题原文
- LLM 的回答
- 你觉得哪里不像
- （可选）立党本人会怎么回

### 3. 添加新场景调用示例

v3 已有 5 个调用示例（考研 / 鸡娃 / 投资 / 高考志愿 / 小语种），欢迎补充：

- 文科生转型
- 35 岁危机
- 房产决策
- 临床医学选择
- ……

## 📝 怎么提 PR

### 补充原话的 PR 模板

```markdown
## 新增原话

**分类**：骂人/批判 / 路径推荐 / 个人经历 / 基础教育 / 其他
**场景**：日常吐槽 / 职业建议 / 讲座 / 直播 / X 推文
**内容**：（直接照搬立党原话，保留标点和语气）
**出处**：（讲座编号 / X 推文链接 / GitHub 路径）

## 还原度测试

**问题**：（用一个立党风格问题测试）
**回答**：（LLM 加载新原话后的回答）
**对比**：（与之前回答的差异）
```

### 修改 skill 结构的 PR 模板

```markdown
## 修改内容

- 修改了 [模块名] 的 [具体内容]
- 原因：
- 验证：跑了 X 个测试问题，结果是……
```

## 🐛 提 Issue 模板

### Bug 报告

```markdown
**问题描述**：用 skill 回答 XXX 时，LLM 的回答是 YYY
**期望**：应该像 ZZZ
**使用平台**：ChatGPT / Claude / Gemini / 其他
**Skill 版本**：v3
**复现步骤**：
1. 加载 skill
2. 问 XXX
3. 观察 YYY
```

### 还原度反馈

```markdown
**问题**：（原问题）
**LLM 回答**：（实际回答）
**立党本人会怎么回**：（如果知道）
**评分**：1~10 像立党
**建议**：（怎么改进）
```

## 💬 社区

- Issues：直接在 GitHub 提
- Discussions：重大方向讨论用这个

## 📋 行为准则

- ❌ 不要添加非立党的个人观点
- ❌ 不要修改原话（必须原话照搬）
- ❌ 不要添加与立党风格冲突的内容（比如鸡汤）
- ✅ 鼓励补充事实性内容（资源链接、讲座编号）
- ✅ 鼓励改进组织结构
- ✅ 欢迎新视角的调用示例

## 🎖️ 贡献者

所有贡献者都会列在 README.md 致谢区。

---

**License**: 本项目采用 MIT 协议，但其中立党原话版权归立党本人所有。
*（内容由AI生成，仅供参考）*
