# gstack-cookbook

> 用 OpenClaw（龙虾）学习 Gstack，边学边写，边练边会。

## 项目背景

[Gstack](https://github.com/garrytan/gstack) 是 YC CEO Garry Tan 开源的 AI 软件工程流水线，它把 Claude Code/Codex 变成了一整个虚拟工程团队，从产品设计、架构评审、代码开发、测试验证到上线发布全流程覆盖，让单个开发者具备媲美20人团队的研发效率。

本项目是我学习 Gstack 的实战笔记库，我用 OpenClaw（龙虾）作为学习工具，通过「以写促学 + 实操落地」的方式，把 Gstack 的使用经验、踩坑记录、二次开发技巧沉淀下来，分享给所有想要提升 AI 研发效率的开发者。

## 我的学习思路
我不追求快速上手工具，而是先吃透底层原理，把Agent构建能力打扎实，学习分为三个阶段：

### 第一阶段：基础认知
读透 Gstack 官方README，理解它的设计理念、整体研发流程、适用场景，搞清楚它到底解决了什么问题，和其他AI编程工具有什么区别。

### 第二阶段：角色拆解
逐个深入学习 Gstack 28个技能（虚拟角色）的定义、职责、输入输出、工作逻辑和使用场景，搞清楚每个角色在整个研发流程中扮演什么角色，如何和其他角色协作。这部分是核心，掌握了Agent角色设计的方法论，以后可以迁移到任何AI项目中。

### 第三阶段：落地实践
等把所有角色和流程都吃透之后，再根据实际需求选择落地载体：可以在 Claude Code 中使用，也可以把这套角色体系适配到 OpenClaw 中，最终应用到自己的工作和项目里。

### 学习方法
1. **以写促学**：每学习一个技能，就输出一篇对应的学习笔记，把原理、使用方法、实操案例、踩坑记录都写清楚，倒逼自己彻底吃透每个功能点。
2. **实操落地**：不做纸上谈兵，所有学习内容都要实际跑通验证，真正把学到的Agent构建能力变成自己的东西。

## 项目目录

```
├── docs/
│   ├── 00-入门系列/        # Gstack 入门安装、配置、快速上手
│   ├── 01-技能详解/        # 每个 Gstack 技能的原理、用法、实战案例
│   ├── 02-进阶实践/        # 多并行 sprint、自定义技能、二次开发
│   ├── 03-落地案例/        # 结合实际项目使用 Gstack 的实战案例
│   └── 04-深度解读/        # 对 Gstack 设计理念、架构原理的深度分析
├── scripts/                # 自用的 Gstack 配置、扩展脚本
└── README.md               # 项目说明
```

## 目录规划

### 入门系列
- [Gstack 快速安装指南](docs/00-入门系列/Gstack快速安装指南.md)
- [Gstack 核心概念扫盲](docs/00-入门系列/Gstack核心概念扫盲.md)
- [我的第一个 Gstack 实战项目](docs/00-入门系列/我的第一个Gstack实战项目.md)

### 技能详解
> 覆盖 Gstack 全部 28 个技能的详细用法
- [产品设计类技能：/office-hours /plan-ceo-review /plan-design-review](docs/01-技能详解/产品设计类技能.md)
- [架构开发类技能：/plan-eng-review /review /investigate /codex](docs/01-技能详解/架构开发类技能.md)
- [设计类技能：/design-consultation /design-review /design-shotgun](docs/01-技能详解/设计类技能.md)
- [测试安全类技能：/qa /qa-only /cso /canary /benchmark](docs/01-技能详解/测试安全类技能.md)
- [上线发布类技能：/ship /land-and-deploy /document-release /retro](docs/01-技能详解/上线发布类技能.md)
- [工具类技能：/browse /setup-browser-cookies /autoplan /careful /freeze /guard /gstack-upgrade](docs/01-技能详解/工具类技能.md)

### 进阶实践
- [Gstack 多并行 Sprint 配置实战](docs/02-进阶实践/Gstack多并行Sprint配置实战.md)
- [自定义 Gstack 技能开发指南](docs/02-进阶实践/自定义Gstack技能开发指南.md)
- [Gstack + OpenClaw 组合使用技巧](docs/02-进阶实践/Gstack+OpenClaw组合使用技巧.md)
- [Gstack 性能优化与故障排查](docs/02-进阶实践/Gstack性能优化与故障排查.md)

### 深度解读
- [Gstack README 深度解读](docs/04-深度解读/Gstack-README深度解读.md)
- [Gstack 架构设计原理分析](docs/04-深度解读/Gstack架构设计原理分析.md)
- [Garry Tan 的 AI 编程哲学](docs/04-深度解读/Garry-Tan的AI编程哲学.md)

## 关于我
本项目由我和 OpenClaw（龙虾）共同维护，所有内容均为实战沉淀，欢迎提交 Issue 和 PR 交流。

**口号：用 AI 提升研发效率，让每个开发者都能顶一个团队。**
