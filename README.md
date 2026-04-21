# Learn English

Bob 的英语学习教练项目 —— 基于 Claude Code 的个性化英语学习系统。

## 背景

作为一名 AI 工程师，我决定系统性地学习英语。这个仓库记录了我从 CEFR A2 起步的完整学习过程，包括学习计划、精讲素材、词汇卡片和每日学习日志。

## 学习体系

采用 **4 轨并行** 的学习方法：

| 轨道 | 频率 | 核心材料 |
|---|---|---|
| 📖 阅读 | 每周 3 次 | AI 博客 (Anthropic/OpenAI/HF)、Simon Willison 博客 |
| 🎧 听力 | 每周 2 次 | BBC 6 Minute English + BBC English at Work |
| 📝 词汇 | 每日 | 只记本周见过的词，Anki + FSRS |
| 📏 语法 | 每周 1 次 | 从 be 动词到从句，循序渐进 |

## 目录结构

```
learn-english/
├── CLAUDE.md                  # Claude 教练配置（角色、方法论、进度）
├── plan.html                  # 6 个月学习计划（可视化）
├── logs/                      # 每日学习日志
├── vocab/                     # 每周词汇卡片
├── anki/                      # Anki 导出文件
└── materials/                 # 学习素材
    ├── readings/              # 阅读精讲素材
    ├── bbc-eaw/               # BBC English at Work 系列
    │   ├── ep02.md            # EP02 精讲笔记
    │   └── ep02-exercises.html # EP02 练习页面
    └── methodology/           # 方法论
        └── english_methodology.html  # 英语学习方法论可视化
```

## 工具链

- **Claude Code** — AI 英语教练，负责教学、出题、纠错、追踪进度
- **Anki + FSRS** — 间隔重复记忆词汇
- **BBC Learning English** — 听力素材来源

## 目标

- **短期**：独立阅读英文技术文章和 AI 论文
- **中期**：备考雅思，申请美国远程硕士

## License

MIT
