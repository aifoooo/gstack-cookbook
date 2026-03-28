# gstack-cookbook

> Gstack 学习实战笔记库，从理论到实战掌握 AI 原生软件工程流水线。

## 项目背景

[Gstack](https://github.com/garrytan/gstack) 是 YC CEO Garry Tan 开源的 AI 软件工程流水线，它把 Claude Code/Codex 变成了一整个虚拟工程团队，从产品设计、架构评审、代码开发、测试验证到上线发布全流程覆盖，让单个开发者具备媲美 20 人团队的研发效率。

本项目是 Gstack 学习沉淀，持续更新中，欢迎提交 Issue 和 PR 交流。

**口号：用 AI 提升研发效率，让每个开发者都能顶一个团队。**

## 内容规划

### 第一篇：基础认知
- [Gstack README 解读](<docs/01-README解读/Gstack README 解读.md>)

### 第二篇：29 个角色深入分析
按 Gstack 官方定义的顺序逐个拆解每个虚拟角色（技能）的设计逻辑、职责边界、使用场景、核心价值：
1. [/office-hours：YC 创业导师](<docs/02-角色分析/01-office-hours.md>)
2. [/plan-ceo-review：产品 CEO](<docs/02-角色分析/02-plan-ceo-review.md>)
3. [/plan-eng-review：技术经理](<docs/02-角色分析/03-plan-eng-review.md>)
4. [/plan-design-review：资深设计师](<docs/02-角色分析/04-plan-design-review.md>)
5. [/design-consultation：设计合伙人](<docs/02-角色分析/05-design-consultation.md>)
6. [/review：资深工程师](<docs/02-角色分析/06-review.md>)
7. [/investigate：调试专家](<docs/02-角色分析/07-investigate.md>)
8. [/design-review：全栈设计师](<docs/02-角色分析/08-design-review.md>)
9. [/design-shotgun：设计探索者](<docs/02-角色分析/09-design-shotgun.md>)
10. [/qa：测试负责人](<docs/02-角色分析/10-qa.md>)
11. [/qa-only：测试专员](<docs/02-角色分析/11-qa-only.md>)
12. [/cso：首席安全官](<docs/02-角色分析/12-cso.md>)
13. [/ship：发布工程师](<docs/02-角色分析/13-ship.md>)
14. [/land-and-deploy：运维工程师](<docs/02-角色分析/14-land-and-deploy.md>)
15. [/canary：SRE](<docs/02-角色分析/15-canary.md>)
16. [/benchmark：性能工程师](<docs/02-角色分析/16-benchmark.md>)
17. [/document-release：技术文档工程师](<docs/02-角色分析/17-document-release.md>)
18. [/retro：技术经理](<docs/02-角色分析/18-retro.md>)
19. [/browse：测试工程师](<docs/02-角色分析/19-browse.md>)
20. [/setup-browser-cookies：会话管理员](<docs/02-角色分析/20-setup-browser-cookies.md>)
21. [/autoplan：评审流水线](<docs/02-角色分析/21-autoplan.md>)
22. [/codex：跨模型评审专家](<docs/02-角色分析/22-codex.md>)
23. [/careful：安全护栏](<docs/02-角色分析/23-careful.md>)
24. [/freeze：编辑锁](<docs/02-角色分析/24-freeze.md>)
25. [/guard：安全卫士](<docs/02-角色分析/25-guard.md>)
26. [/unfreeze：解锁工具](<docs/02-角色分析/26-unfreeze.md>)
27. [/connect-chrome：Chrome 控制器](<docs/02-角色分析/27-connect-chrome.md>)
28. [/setup-deploy：部署配置工具](<docs/02-角色分析/28-setup-deploy.md>)
29. [/gstack-upgrade：自动升级工具](<docs/02-角色分析/29-gstack-upgrade.md>)

### 第三篇：29 个角色官方 SKILL.md 中文全译
官方 SKILL.md 完整中文翻译，保留全部执行规则、流程、细节，作为权威参考：
1. [/office-hours 官方 SKILL 中文翻译](<docs/03-官方技能翻译/01-office-hours.md>)
2. [/plan-ceo-review 官方 SKILL 中文翻译](<docs/03-官方技能翻译/02-plan-ceo-review.md>)
3. [/plan-eng-review 官方 SKILL 中文翻译](<docs/03-官方技能翻译/03-plan-eng-review.md>)
4. [/plan-design-review 官方 SKILL 中文翻译](<docs/03-官方技能翻译/04-plan-design-review.md>)
5. [/design-consultation 官方 SKILL 中文翻译](<docs/03-官方技能翻译/05-design-consultation.md>)
6. [/review 官方 SKILL 中文翻译](<docs/03-官方技能翻译/06-review.md>)
7. [/investigate 官方 SKILL 中文翻译](<docs/03-官方技能翻译/07-investigate.md>)
8. [/design-review 官方 SKILL 中文翻译](<docs/03-官方技能翻译/08-design-review.md>)
9. [/design-shotgun 官方 SKILL 中文翻译](<docs/03-官方技能翻译/09-design-shotgun.md>)
10. [/qa 官方 SKILL 中文翻译](<docs/03-官方技能翻译/10-qa.md>)
11. [/qa-only 官方 SKILL 中文翻译](<docs/03-官方技能翻译/11-qa-only.md>)
12. [/cso 官方 SKILL 中文翻译](<docs/03-官方技能翻译/12-cso.md>)
13. [/ship 官方 SKILL 中文翻译](<docs/03-官方技能翻译/13-ship.md>)
14. [/land-and-deploy 官方 SKILL 中文翻译](<docs/03-官方技能翻译/14-land-and-deploy.md>)
15. [/canary 官方 SKILL 中文翻译](<docs/03-官方技能翻译/15-canary.md>)
16. [/benchmark 官方 SKILL 中文翻译](<docs/03-官方技能翻译/16-benchmark.md>)
17. [/document-release 官方 SKILL 中文翻译](<docs/03-官方技能翻译/17-document-release.md>)
18. [/retro 官方 SKILL 中文翻译](<docs/03-官方技能翻译/18-retro.md>)
19. [/browse 官方 SKILL 中文翻译](<docs/03-官方技能翻译/19-browse.md>)
20. [/setup-browser-cookies 官方 SKILL 中文翻译](<docs/03-官方技能翻译/20-setup-browser-cookies.md>)
21. [/autoplan 官方 SKILL 中文翻译](<docs/03-官方技能翻译/21-autoplan.md>)
22. [/codex 官方 SKILL 中文翻译](<docs/03-官方技能翻译/22-codex.md>)
23. [/careful 官方 SKILL 中文翻译](<docs/03-官方技能翻译/23-careful.md>)
24. [/freeze 官方 SKILL 中文翻译](<docs/03-官方技能翻译/24-freeze.md>)
25. [/guard 官方 SKILL 中文翻译](<docs/03-官方技能翻译/25-guard.md>)
26. [/unfreeze 官方 SKILL 中文翻译](<docs/03-官方技能翻译/26-unfreeze.md>)
27. [/connect-chrome 官方 SKILL 中文翻译](<docs/03-官方技能翻译/27-connect-chrome.md>)
28. [/setup-deploy 官方 SKILL 中文翻译](<docs/03-官方技能翻译/28-setup-deploy.md>)
29. [/gstack-upgrade 官方 SKILL 中文翻译](<docs/03-官方技能翻译/29-gstack-upgrade.md>)
