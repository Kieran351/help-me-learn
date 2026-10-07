# help-me-learn

[English](README.md) | 简体中文

通过自己推理来学懂一个概念。Agent 用苏格拉底式追问引导你，而不是直接给出答案。

## 功能

- 先摸清你已有的理解，再一次一个小问题地推进。
- 答错时不直接说“错”，而是追问暴露矛盾；答对后用变式检验是否真懂。
- 卡住时逐步给提示，多次卡住就直接讲清，不刻意卖关子。
- 你说“直接告诉我”时立即切换为讲解。
- 可选：更新主题知识地图（`topics/<主题>/map.md`）中的掌握状态。

说“考考我”“我理解对吗”“别直接告诉我”等即可触发，也可以用 `$help-me-learn` 手动调用。

## 安装

需要 Node.js 和 npm。使用 [Skills CLI](https://github.com/vercel-labs/skills)：

```bash
npx skills add Kieran351/help-me-learn
```

按提示选择 Agent 和安装范围，加 `-g` 为全局安装。

## 更新

```bash
npx skills update help-me-learn
```

按提示选择范围，或加 `-g`（全局）/ `-p`（项目）。项目级更新需在项目目录中运行。

## 卸载

项目级安装，在项目目录中运行：

```bash
npx skills remove help-me-learn
```

全局安装：

```bash
npx skills remove help-me-learn -g
```
