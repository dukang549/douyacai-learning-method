# 豆芽菜学习法 GitHub 仓库结构建议

## 推荐结构

```text
douyacai-learning-method/
├── README.md
├── LICENSE
├── docs/
│   ├── philosophy.md
│   ├── trigger-levels.md
│   └── design-notes.md
├── prompts/
│   ├── universal/
│   │   ├── douyacai-universal-full.md
│   │   ├── douyacai-universal-short.md
│   │   └── douyacai-universal-mini.md
│   ├── codex/
│   │   └── SKILL.md
│   ├── claude/
│   │   └── claude-project-instructions.md
│   └── chatgpt/
│       └── custom-gpt-instructions.md
├── examples/
│   ├── quick-explain.md
│   ├── beginner-learning.md
│   ├── systematic-learning.md
│   ├── problem-solving.md
│   └── deep-research.md
├── versions/
│   ├── v1-original.md
│   ├── v2-lite.md
│   ├── v2-product.md
│   └── v2-unified.md
└── assets/
    └── cover.png
```

## 每个目录放什么

`README.md`
- 门面文件
- 讲清楚这是什么、适合谁、核心方法是什么、怎么开始用

`docs/`
- 放方法论说明，而不是平台提示词本体
- 适合存放：
  - 为什么强调复述
  - 为什么分学习层级
  - 为什么路线图 / Anki / 思维导图按需触发

`prompts/`
- 放真正可用的版本
- 按平台拆开，避免一个文件同时服务所有平台

`examples/`
- 放真实用例
- 这是让别人一眼理解你这套方法怎么工作的关键

`versions/`
- 保存演进版本
- 方便别人理解你的设计如何从“完整但偏重”进化到“统一且可执行”

`assets/`
- 放封面图、流程图、示意图

## 最低可上传版本

如果你不想一开始搞太大，最小可上传结构可以是：

```text
douyacai-learning-method/
├── README.md
├── prompts/
│   └── douyacai-universal.md
├── examples/
│   ├── quick-explain.md
│   └── systematic-learning.md
└── versions/
    └── v2-unified.md
```

这个版本已经足够体面，也足够说明问题。

## 我建议你第一版就体现的三个重点

1. 这不是普通 prompt，而是一套学习工作流
2. 核心不是“解释”，而是“讲解 + 复述 + 评估”
3. 它支持不同学习层级，并按需触发增强模块
