# 🧭 project-from-idea-to-product

<div align="center">

**从想法到产品 · 运行指挥层 · 交付导向开发闭环**

[![Skill](https://img.shields.io/badge/Agent%20Skill-Project%20Director-4f46e5)](#-项目定位)
[![Mode](https://img.shields.io/badge/Mode-Delivery%20Driven-0ea5e9)](#-核心能力)
[![Focus](https://img.shields.io/badge/Focus-Runtime%20Orchestration-10b981)](#-与普通项目规划-skill-的区别)
[![Methodology](https://img.shields.io/badge/Methodology-From%20Idea%20to%20Ship-f59e0b)](#-方法论框架)

[项目定位](#-项目定位) • [核心能力](#-核心能力) • [方法论框架](#-方法论框架) • [快速开始](#-快速开始) • [内置案例](#-内置案例) • [English](#english)

</div>

---

## ✨ 项目定位

**project-from-idea-to-product** 是一个面向**真实项目交付**的 Agent Skill。
它不是只帮你分析需求，也不是只帮你生成几段代码，而是把一个模糊的软件 / 后台 / 系统 / 工具想法，持续推进成：

- 可定义
- 可拆解
- 可开发
- 可纠偏
- 可上线
- 可包装
- 可交付

> 💡 **核心区别**：它不是普通 prompt 集，也不是只会列需求的项目规划助手，而是一个带有**运行指挥层**、**阶段控制能力**、**外科手术式纠偏机制**的项目总控 skill。

### 🔗 项目地址

- **GitHub 仓库：** <https://github.com/HachikoJ/project-from-idea-to-product>
- **项目展示页：** <https://hachikoj.github.io/project-from-idea-to-product/>

---

## 🎯 这个项目解决什么问题

很多 AI 项目做不出来，问题往往不是不会写代码，而是：

- 想法没有被定义清楚
- 需求没有被拆成系统
- 一上来就堆功能
- 做着做着陷进细节
- 跑偏以后只会大重构，不会精准纠偏
- 本地能跑就误以为项目完成
- 最后没有形成 GitHub、文档、展示页、可复用方法论这些真正可交付成果

这个 skill 的目标，就是解决上面这一整条链路的问题。

### 🎯 核心价值

- **🧭 项目定义能力** - 把模糊想法收敛成目标用户、核心场景、MVP 与边界
- **🧱 结构化拆解能力** - 把需求拆成模块、页面、状态流转、角色关系与优先级
- **🎛️ 运行指挥层能力** - 持续判断当前阶段、最高优先级任务、验收标准与禁止动作
- **🩺 外科手术式纠偏** - 项目跑偏时先判断层级与根因，再做最小必要修复
- **🚀 交付导向闭环** - 不是停留在“能写”，而是推进到“能交付、能上线、能包装”

---

## 🌟 核心能力

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
这是和普通 skill 最大的区别。它会持续帮助判断：
- 当前处于哪个阶段
- 当前唯一最高优先级任务是什么
- 当前明确不要做什么
- 当前任务验收标准是什么
- 是否可以进入下一阶段

### 4. 外科手术式纠偏
当项目跑偏时，默认优先：
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

## 🧠 与普通项目规划 skill 的区别

普通项目规划 skill 往往只会：
- 帮你列需求
- 帮你列页面
- 帮你列功能

而这个项目额外补上了：

- **阶段控制**
- **运行指挥层**
- **防深陷细节机制**
- **交付导向开发闭环**
- **问题分层与最小纠偏策略**

也就是说，它不是只告诉你“应该做什么”，而是开始帮助你：

> **控制项目节奏，约束范围，防止跑偏，并持续把项目拉向交付。**

---

## 🧩 方法论框架

### Phase 1：项目定义
把模糊想法收敛成可执行问题，不让项目从一开始就歪掉。

### Phase 2：需求拆解
把场景拆成模块、页面、角色、对象、状态，不靠“想到哪做哪”。

### Phase 3：阶段推进
每次只做一个最高优先级任务，避免多线程失控和无意义铺开。

### Phase 4：验收闭环
不是“写完就算完”，而是检查是否真正达到当前阶段目标。

### Phase 5：外科手术式纠偏
当项目跑偏时，先分层定位，再最小范围修复，不把局部问题升级成系统重构。

### Phase 6：部署与包装
把项目推进到真正可上线、可展示、可交付，而不是停留在本地开发完成状态。

详细说明见：
- `references/methodology-overview.md`
- `references/phase-runtime-orchestration.md`
- `references/delivery-driven-dev-loop.md`
- `references/delivery-checklists.md`

---

## 🚀 快速开始

### 推荐使用方式

1. 先让 skill 定义项目
2. 再让 skill 判断当前阶段
3. 让 skill 只输出一个当前最高优先级任务
4. 按这一小块范围实现
5. 再回到 skill 做验收与纠偏
6. 通过后再进入下一阶段

### 正确分工

- **skill 负责：** 定方向、控范围、做验收、做纠偏、控阶段
- **执行者负责：** 实现当前任务、反馈结果、按要求回收范围

详细说明见：
- `references/how-to-use-this-skill.md`
- `SKILL.md`

---

## 📦 目录结构

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

## 🧪 内置案例

### 匿证（AnonyProof）案例
- `references/anonyproof-case-study.md`

作用：
- 提炼真实项目的通用模式
- 沉淀子路径部署、通知直达、文档包装等经验
- 证明 skill 不只是“理论规划”，而是能服务真实项目交付

### 内部售后工单系统试跑
- `references/internal-after-sales-ticket-system-walkthrough.md`

作用：
- 验证这个 skill 是否能迁移到全新项目
- 证明它不是匿证专属 skill
- 验证方法论在不同业务场景中的可迁移性

---

## ✅ 当前验证状态

已在实际对话中验证：
- 从真实项目中抽取方法论
- 将方法迁移到新项目题目
- 运行指挥层逻辑
- 交付导向的项目控制方式
- 从需求到部署包装的一体化推进方式

后续仍值得在更多真实项目中继续验证：
- 多轮真实编码协同效果
- 更长周期项目中的稳定性
- 不同后台 / 流程系统的迁移适配度
- 更复杂多角色系统中的控范围能力

---

## 📌 一句话总结

> 这不是一个只会分析需求的 skill，  
> 而是一个帮助你把项目真正做成、做完、做成交付成果的项目总控 skill。

---

## 🤝 使用建议

适合用在这些场景：

- 想做一个后台 / 平台 / 系统，但需求还比较模糊
- 项目推进过程中总是容易跑偏
- 已经开始写代码，但节奏失控、越做越乱
- 想让 AI 不是只产出代码，而是一起控项目节奏
- 希望最后拿到的不只是代码，还包括文档、部署、展示页与交付资产

不适合只拿来做：

- 单点 bug 修复
- 单个页面文案修改
- 单纯 UI 润色
- 只要一个 prompt 模板而不关心真实交付

---

## 📄 许可证

本项目采用 MIT 许可证。

---

## 👥 作者

**Wilson** - [@HachikoJ](https://github.com/HachikoJ)

> 这个项目的价值不在“又一个 skill”，而在于它把真实项目交付过程中最容易失控、最容易跑偏、最容易假完成的那部分，做成了一套可复用的方法与控制层。

---

## 📞 联系方式

- GitHub 仓库：<https://github.com/HachikoJ/project-from-idea-to-product>
- 项目展示页：<https://hachikoj.github.io/project-from-idea-to-product/>
- 问题反馈：<https://github.com/HachikoJ/project-from-idea-to-product/issues>

---

## ⭐ Star History

如果这个项目对你有帮助，给个 Star ⭐

[![Star History Chart](https://api.star-history.com/svg?repos=HachikoJ/project-from-idea-to-product&type=Date)](https://star-history.com/#HachikoJ/project-from-idea-to-product&Date)

---

## English

**project-from-idea-to-product** is a delivery-oriented Agent Skill for turning vague software ideas into real, shippable projects.

It is not just a planning prompt pack. It adds:
- runtime orchestration
- stage control
- anti-detail drift
- acceptance and correction loops
- delivery-oriented development flow

Its goal is not to generate more output, but to help keep a project focused, staged, corrected, and pushed all the way to delivery.

Links:
- GitHub: <https://github.com/HachikoJ/project-from-idea-to-product>
- Showcase: <https://hachikoj.github.io/project-from-idea-to-product/>
