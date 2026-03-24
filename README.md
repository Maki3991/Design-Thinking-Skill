# DT Skill

一个基于本地课程总结整理的 `Design Thinking` 技能包，用来帮助 AI 在回答 DT 相关问题时，先判断问题所处阶段，再读取对应课程内容进行回答，而不是只依赖泛化知识。

## 这个 Skill 能做什么

- 识别用户问题属于 DT 的哪个阶段
- 在 `Understand / Define / HMW / Ideate / Prototype / Test / MVP` 之间做路由
- 优先读取打包好的课程参考内容，再综合输出回答
- 支持把 DT 用在产品、项目和人生设计场景中

## 仓库结构

- `dt/SKILL.md`
  - Skill 主说明和路由规则
- `dt/agents/openai.yaml`
  - Skill 的显示信息
- `dt/references/`
  - 打包好的课程摘要与路由文档

## 适用场景

- 想问 `Design Thinking` 概念
- 想知道某个问题属于 DT 的哪个阶段
- 想把 DT 用在人生设计、项目设计、产品验证中
- 想让 AI 基于这套课程资料回答，而不是泛泛而谈

## 安装方式

如果 `dt/` 是仓库中的 skill 目录，可以让 Codex 使用类似方式安装：

```text
请使用 skill-installer 安装这个 skill：
https://github.com/Maki3991/Design-Thinking-Skill/tree/main/dt
```

安装完成后，重启 Codex 以加载新 skill。

## 使用方式

可以直接对 Codex 说：

- `使用 DT 回答这个问题`
- `用 DT 分析我现在处在哪个阶段`
- `用 DT 解释 prototype 和 MVP 的区别`

## 说明

这份 skill 目前是一个自包含版本，核心课程摘要已经打包进 `references/`，因此不依赖作者本地路径即可使用。
