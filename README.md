# project-from-idea-to-product

> 一个面向真实项目交付的 Agent Skill。  
> 它不是只负责分析需求，而是负责把一个模糊的软件 / 系统 / 后台 / 工具想法，推进成**可开发、可纠偏、可上线、可包装、可交付**的完整项目。

<p align="center">
  <a href="https://github.com/HachikoJ/project-from-idea-to-product">GitHub 仓库</a> ·
  <a href="https://hachikoj.github.io/project-from-idea-to-product/">项目展示页</a>
</p>

---

## 中文 | English

- [中文说明](#中文说明)
- [English](#english)

---

## 中文说明

## 项目定位

`project-from-idea-to-product` 不是普通 prompt 集，也不是只会讲方法论的 skill。  
它更接近一个：

- **项目总控 skill**
- **交付导演 skill**
- **运行指挥层 skill**

它解决的核心问题不是“写某一段代码”，而是：

- 如何把一个模糊想法定义成真实项目
- 如何收敛 MVP，而不是一开始就堆功能
- 如何在开发过程中持续纠偏，而不是反复重构
- 如何防止自己或 AI 深陷于局部细节
- 如何把项目持续推到上线、文档、GitHub、教程、展示页这些真正的交付成果

---

## 核心能力

### 1. 项目定义
把一句模糊需求收敛成：
- 目标用户
- 系统角色
- 核心场景
- 主链路
- MVP
- 暂不做什么

### 2. 需求拆解
把项目拆成：
- 页面清单
- 模块清单
- 状态流转
- 角色关系
- 数据对象意识
- 开发优先级

### 3. 运行指挥层
这是和普通 skill 最大的区别。

它会持续帮助判断：
- 当前处于哪个阶段
- 当前唯一最高优先级任务是什么
- 当前明确不要做什么
- 当前任务的验收标准是什么
- 是否可以进入下一阶段

### 4. 外科手术式纠偏
当项目跑偏时，优先：
- 先判断问题层级
- 再找根因
- 做最小修改
- 不顺手改 unrelated 模块
- 明确修复完成标准

### 5. 交付导向开发闭环
默认循环：
- 任务
- 实现
- 验收
- 纠偏
- 下一任务

它的目标不是“写得更多”，而是“更稳地把项目做完”。

---

## 最适合什么项目

- 内部工单系统
- 内部审批系统
- 管理后台
- 售后 / 客服 / 跟进系统
- 小团队业务工具
- 工作流产品
- 多角色协同系统
- 需要上线、展示、交付的 AI 产品项目

---

## 与普通项目规划 skill 的区别

普通项目规划 skill 往往只会：
- 帮你列需求
- 帮你列页面
- 帮你列功能

而这个项目额外补上了：

- **阶段控制**
- **运行指挥层**
- **防深陷细节机制**
- **交付导向开发闭环**

也就是说，它不是只告诉你“应该做什么”，而是开始帮助你：

> **控制项目节奏，约束范围，防止跑偏，并持续把项目拉向交付。**

---

## 目录结构

```text
project-from-idea-to-product/
├── SKILL.md
├── README.md
├── references/
│   ├── methodology-overview.md
│   ├── how-to-use-this-skill.md
│   ├── phase-1-project-definition.md
│   ├── phase-2-requirement-breakdown.md
│   ├── phase-5-surgical-debugging.md
│   ├── phase-6-deployment-and-domain.md
│   ├── phase-runtime-orchestration.md
│   ├── anti-overfitting-and-focus-control.md
│   ├── delivery-driven-dev-loop.md
│   ├── delivery-checklists.md
│   ├── prompt-patterns.md
│   ├── anonyproof-case-study.md
│   └── internal-after-sales-ticket-system-walkthrough.md
└── docs/
    └── index.html
```

---

## 推荐使用方式

### 标准工作流
1. 先让 skill 定义项目
2. 再让 skill 判断当前阶段
3. 让 skill 只输出一个当前最高优先级任务
4. 由龙虾只按这一小块范围实现
5. 再回到 skill 做验收与纠偏
6. 通过后再进入下一阶段

### 正确分工
- **skill 负责：** 定方向、控范围、做验收、做纠偏、控阶段
- **龙虾负责：** 实现当前任务、反馈结果、按要求回收范围

详细说明见：
- `references/how-to-use-this-skill.md`

---

## 内置案例

### 匿证案例
- `references/anonyproof-case-study.md`

作用：
- 提炼真实项目的通用模式
- 沉淀子路径部署、通知直达、文档包装等经验

### 内部售后工单系统试跑
- `references/internal-after-sales-ticket-system-walkthrough.md`

作用：
- 验证这个 skill 是否能迁移到全新项目
- 证明它不是匿证专属 skill

---

## 当前验证状态

已在实际对话中验证：
- 从真实项目中抽取方法论
- 将方法迁移到新项目题目
- 运行指挥层逻辑
- 交付导向的项目控制方式

后续仍值得在更多真实项目中继续验证：
- 多轮真实编码协同效果
- 更长周期项目中的稳定性
- 不同后台 / 流程系统的迁移适配度

---

## 一句话总结

> 这不是一个只会分析需求的 skill，  
> 而是一个帮助你和龙虾把项目真正做成、做完、做成交付成果的项目总控 skill。

---

## English

`project-from-idea-to-product` is a delivery-oriented Agent Skill for turning vague software ideas into real, shippable projects.

It is not just a planning prompt pack. It adds:
- runtime orchestration
- stage control
- anti-detail drift
- acceptance and correction loops
- delivery-oriented development flow

Project links:
- GitHub: `https://github.com/HachikoJ/project-from-idea-to-product`
- Showcase: `https://hachikoj.github.io/project-from-idea-to-product/`
