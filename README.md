# 立党 Skill (Lidang Skill)

> 让任意 LLM 在 5 分钟内变成"立党"：直白、数据驱动、批判性强、实用至上。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-v1-blue.svg)](./CHANGELOG.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

## 这是什么

一个**结构化 Prompt 蒸馏包**，基于 57+ 条立党（@lidangzzz）真实原话（X 推文、YouTube 讲座、GitHub 笔记、直播）蒸馏而成。

加载本 skill 后，LLM 会按立党的风格回答问题：

- ✅ 直白判断，敢下绝对结论
- ✅ 数据 / 现实驱动，不讲鸡汤
- ✅ 批判性强，敢用"千万别""死路一条"
- ✅ 个人经历佐证（初中转码 / 商科被现实教育）
- ✅ 每个观点落地到"那你该怎么做"

## 目录结构

```
-skill/
├── 立党风格/              ← 直接导入 Marvis 技能广场
│   └── SKILL.md
├── 立党_skill_v1.md        ← 参考资料（独立 prompt 文件）
├── README.md
├── CONTRIBUTING.md
├── CHANGELOG.md
└── LICENSE
```

## 怎么用

### 方式一：Marvis 技能广场导入（推荐）

1. 下载整个 `立党风格/` 文件夹（含 `SKILL.md`）
2. 放入 Marvis 的 `skills/custom/立党风格/` 目录
3. 在对话中说"加载立党风格"即可使用

### 方式二：手动复制 prompt

| 步骤 | 操作 |
|---|---|
| Step 1 | 打开 [`立党_skill_v1.md`](./立党_skill_v1.md)，复制全部内容 |
| Step 2 | 粘贴到 ChatGPT / Claude / Gemini / 任何 LLM 对话开头 |
| Step 3 | 直接问问题，LLM 自动用立党风格回答 |

例如：

> "三本 CS 应不应该考研？"

LLM 会按 5 步法（先骂 → 讲底层 → 给路径 → 避坑 → 收尾）回答，**不是模仿立党说过的话，而是用立党的方法论和语气回答新问题**。

## 适用场景

| 场景 | 是否适用 |
|---|---|
| 高考志愿 / 专业选择 | ✅ 强推荐 |
| 转码 / CS 学习路径 | ✅ 强推荐 |
| 投资 / 房产 | ✅ 适用 |
| 普通人职业规划 | ✅ 强推荐 |
| 出海 / 移民 | ✅ 适用 |
| 临床医学选择 | ✅ 适用（带避坑清单）|
| 日常情感 / 闲聊 | ❌ 不推荐（立党不擅长这个）|
| 学术研究 / 论文 | ❌ 不推荐 |

## 还原度

| 版本 | 原话数 | 还原度 | 何时 |

| v1 | 57+ | 88~90% | 当前版本，含完整初中转码经历 |

完整迭代日志见 [CHANGELOG.md](./CHANGELOG.md)。

## 贡献

欢迎提 PR / issue 补充原话！

- 📝 补充立党原话（X 推文 / 讲座逐字稿 / 直播）
- 🐛 报告还原度问题（"这个回答不像立党"）
- 🌍 翻译成其他语言版本
- 💡 提出新场景的调用示例

详见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

## 资源

- **立党 YouTube**：搜索"立党 讲座 XX"或"解答世间万物"
- **立党 GitHub**：https://github.com/lidangzzz
- **立党 X/Twitter**：[@lidangzzz](https://twitter.com/lidangzzz)
- **立党转码笔记**：https://lidangzzz.github.io/How-to-run/

## 免责声明

- 本项目为**粉丝二创**，非立党本人维护
- skill 内容基于公开来源整理，版权归立党本人
- LLM 用本 skill 生成的回答仅供参考，**重大决策（高考志愿、移民、投资）请自行核实**

## Star History

如果这个项目对你有帮助，欢迎 Star ⭐

---

**License**: MIT
