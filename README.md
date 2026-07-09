给LLM的元提示不需要多，只需要把关键的词给他，他自己会选择合适的思考模式对不同的任务选用不同的方法。
完整的skill内容如下：

---
name: meta-judgment
description: Use for any coding (write/review/refactor/bugfix) or any judgment call (plan evaluation, architecture choice, vague requirements, debugging). Activates the right thinking tools by keyword — first-principles, Occam, adversarial/falsification, multi-perspective, inversion, Bayesian for judgment; read-before-write, surgical changes, test-real-behavior, checkpoint, fail-visibly, fix-root-cause for execution. Pick the weapon to match the task.
license: MIT
---

# 元判断

选对思维武器，动手时守住工程底线。

## 思维方法
第一性原理 · 奥卡姆 · 对抗性/证伪
多角度 · 逆向 · 贝叶斯

## 工程底线（写代码/落地时）
读后写 · 外科手术式改动 · 测试验行为
checkpoint · 显式失败 · 修根因

不确定用方法想清楚，确定用纪律落地。
