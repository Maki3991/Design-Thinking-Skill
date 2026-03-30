---
name: dt
description: 将 Design Thinking 问题路由到正确的内置课程参考文档，并基于这套课程材料而不是泛化知识进行回答。适用于用户询问 Design Thinking 概念、课程结构、课程路由、将 DT 用于产品/项目/人生设计，或希望答案基于这个 DT 课程包时。
---

# DT
使用这个 skill 时，先把用户问题路由到正确的内置 reference，再基于课程材料综合回答。

## 核心工作流
1. 先读 `references/router.md`。它是整套课程的一级路由入口，也是每个问题的默认导航表。
2. 把问题归类到一个或多个 DT 阶段。使用下面这些阶段桶：
   - `intro/life-design`
   - `define`
   - `hmw/ideate`
   - `prototype`
   - `test/mvp`
3. 路由完成后，再读取最少必要的 lesson 文件。默认映射：
   - `intro/life-design` -> `references/DT1.md`
   - `define` -> `references/define-problem.md`
   - `hmw/ideate` -> `references/hmw-ideate.md`
   - `prototype` -> `references/prototype.md`
   - `test/mvp` -> `references/test-mvp.md`
4. 把 `DT1.md` 当成“导论补充 reference”，不要把它当成通用背景文件。只有当用户在问下面这些内容时，才默认读取 `DT1.md`：
   - `DT 是什么 / 为什么学 DT / DT 和人生设计的关系`
   - `grow zone / 迷茫 / 发散与收敛 / understand 自己`
   - 整套课的大图景
   - 人生设计端到端
5. 对于单阶段问题，除非问题明显回到了 Lesson 1 的概念层，否则不要带上 `DT1.md`。尤其适用于：
   - `define`
   - `hmw/ideate`
   - `prototype`
   - `test/mvp`
6. 当问题跨阶段时，再组合多个 reference。常见组合：
   - `understand self` -> `router + DT1 + define`
   - `POV to ideas` -> `router + define + hmw/ideate`
   - `idea to low-cost validation` -> `router + hmw/ideate + prototype`
   - `prototype vs MVP` -> `router + prototype + test/mvp`
   - `life design end-to-end` -> `router + DT1 + all stages in order`
7. 回答时优先使用这套课程自己的 framing。如果补充了课程外的一般 DT 知识，要明确标注为推断或泛化。

## 阶段识别提示

可用下面这些线索快速路由：
- `intro/life-design`
	- DT 是什么、为什么 DT 重要、发散/收敛、grow zone、人生设计、理解自己、为什么迷茫是正常的
- `define`
	- 根因、痛点、共情、访谈、insight、POV、5 whys、5 W 1 H、如何定义真正的问题
- `hmw/ideate`
	- HMW、brainstorming、ideation、idea generation、idea filtering、什么时候该发散、什么时候该收敛
- `prototype`
	- Prototype、CFP、CEP、funky prototype、dark horse、box prototype、vision prototype、低成本验证
- `test/mvp`
	- Test、MVP、minimum loop、A/B testing、iteration、验证支付意愿、验证关键假设

## 回答结构

除非用户另有要求，优先按这个结构回答：
1. 先指出当前问题处在 DT 的哪个阶段。
2. 用大白话解释概念。
3. 映射到用户语境：
	- 人生决策
	- 产品/项目
	- 课程理解
4. 如果合适，指出下一步应该进入哪个阶段。
5. 标明你使用了哪些 reference 文件。

如果问题比较宽泛，要明确说出：
- 用户当前大致在哪个阶段
- 最相关的 lesson references 是哪些
- 最实际的下一步动作是什么

## 护栏

- 如果问题还在 `define`，不要直接跳进解决方案模式。
- 不要过度读取；先路由，再选择性读取。
- 不要把 `DT1.md` 默认塞进每个回答。
- 如果问题明显跨阶段，不要硬写成单阶段答案。
- 除非用户明确要整套课总览，否则不要一次把所有 lessons 都展开。
- 要清楚区分：哪些内容是课程直接表达，哪些内容是你的综合归纳。

## 可选的工作区补充

如果当前 workspace 里还有额外的 DT 文件，可以在读完内置 references 后，把它们当作补充材料使用。
常见补充文件名：
- `DT1 - Router.md`
- `Design thinking 1 - The Awakening.md`
- `DT2-4 - How to Define a Problem.md`
- `DT4 - From HMW to Ideate.md`
- `DT5-6 - Prototype.md.md`
- `DT7 - Test.md`
这些是 workspace 里的补充文件，不是这个 skill 内置 reference 的正式命名。
这个 skill 仍然以内置 references 作为默认事实来源。