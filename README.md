# project-from-idea-to-product

[中文](#中文) | [English](#english)

---

## 中文

一个面向 **真实项目交付** 的 Agent Skill。  
它的目标不是只帮你“分析需求”或“生成几段代码”，而是把一个模糊的软件 / 后台 / 系统 / 工具想法，推进成：

- 可定义
- 可拆解
- 可开发
- 可纠偏
- 可上线
- 可包装
- 可交付

它本质上不是一个普通 prompt 集，也不是一个只会讲方法论的 skill。  
更准确地说，它是一个：

> **从想法到产品的项目总控 skill / 交付导演 skill**

---

### 项目地址

- **GitHub 仓库：** `https://github.com/HachikoJ/project-from-idea-to-product`
- **项目展示页：** `https://hachikoj.github.io/project-from-idea-to-product/`

---

## 这个项目解决什么问题

很多 AI 项目做不出来，问题往往不是不会写代码，而是：

- 想法没有被定义清楚
- 需求没有被拆成系统
- 一上来就堆功能
- 做着做着陷进细节
- 出现偏差后只会重构，不会精准纠偏
- 本地能跑就误以为项目完成
- 最后没有形成 GitHub、文档、教程、演示页这些真正可交付成果

这个 skill 的目标，就是解决上面这一整条链路的问题。

---

## 它和普通项目规划 skill 的区别

普通 skill 通常只做到：
- 帮你列需求
- 帮你列页面
- 帮你列功能

这个项目额外补上了最关键的一层：

### 运行指挥层（Runtime Orchestration）

也就是：
- 当前阶段判断
- 当前唯一高优先级任务
- 当前明确不做什么
- 阶段退出条件
- 不过关不进入下一阶段
- 防止深陷细节
- 任务 → 实现 → 验收 → 纠偏 → 下一任务 的开发闭环

这使它不再只是“方法论文档”，而开始接近：

> **一个项目总控器**

---

## 核心能力

### 1. 项目定义
把模糊想法收敛成：
- 目标用户
- 系统角色
- 核心场景
- 主链路
- MVP
- 暂不做什么

### 2. 需求拆解
把一句话需求拆成：
- 页面清单
- 功能模块
- 状态流转
- 角色关系
- 数据对象意识
- 开发优先级

### 3. 产品与交互推进
帮助项目更像真实产品，而不是练习页：
- 首页定位
- 列表页定位
- 详情页定位
- 管理端秩序感
- 通知 / 状态 / 评论闭环
- UI / UX 约束提示词

### 4. 开发顺序控制
默认强调：
- 先打通主链路
- 再补协作能力
- 再做通知 / 管理增强
- 再修体验
- 最后再上线与包装

### 5. 外科手术式纠偏
项目跑偏时，默认优先：
- 判断问题层级
- 找根因
- 做最小改动
- 不顺手改 unrelated 模块
- 写清验收标准

### 6. 部署与域名意识
默认把项目视为：
- 最终要跑到真实入口上
- 可能存在子路径部署
- 需要统一页面 / API / 静态资源 / 代理路径

### 7. 交付包装
把项目继续推进成：
- GitHub 仓库
- README
- 教程
- docs 展示页
- 演示路径
- 可讲解成果

---

## 适合什么项目

这个 skill 特别适合：

- 内部工单系统
- 内部审批系统
- 售后 / 客服 / 跟进后台
- 管理后台
- 小团队工具
- 反馈 / 工作流系统
- 多角色协同产品
- 需要上线、展示、交付的 AI 产品项目

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

### 标准用法
1. 先用这个 skill 定义项目
2. 再让它判断当前阶段
3. 让它只输出一个当前最高优先级任务
4. 由龙虾只按这一小块范围实现
5. 再回到 skill 做验收与纠偏
6. 通过后再进入下一阶段

### 正确理解
这个 skill 不是替代龙虾写代码，  
而是负责：
- 定方向
- 控范围
- 防跑偏
- 拉交付

也就是：
- **skill 负责指挥**
- **龙虾负责执行**

详细使用方式见：
- `references/how-to-use-this-skill.md`

---

## 内置案例

### 1. 匿证案例
- `references/anonyproof-case-study.md`

作用：
- 真实项目经验抽象
- 子路径部署、通知逻辑、文档包装等真实踩坑沉淀

### 2. 内部售后工单系统试跑案例
- `references/internal-after-sales-ticket-system-walkthrough.md`

作用：
- 验证这套 skill 是否能从一个新题目重新跑起
- 证明它不是匿证专属 skill

---

## 当前验证状态

目前已经在实际对话中验证过：

- 从真实项目中抽方法论
- 把方法迁移到新项目题目
- 用运行指挥层控制阶段节奏
- 用交付导向思维压制细节失控
- 把项目从“分析”推进到“交付意识”

仍值得继续在更多真实项目中验证：
- 多轮真实编码协同效果
- 更复杂后台系统的迁移能力
- 更长周期项目中的稳定性

---

## 这个项目最重要的一句定义

> 它不是一个只会分析的 skill，
> 而是一个帮助你和龙虾把项目真正做成、做完、做成交付成果的项目总控 skill。

---

## English

A delivery-oriented Agent Skill for turning vague product ideas into real, shippable software projects.

This project is not just about requirement analysis or code generation. It is designed to help control the full path from idea to delivery:

- project definition
- requirement breakdown
- implementation sequencing
- runtime orchestration
- acceptance and correction loops
- deployment awareness
- documentation and delivery packaging

### Links
- **GitHub:** `https://github.com/HachikoJ/project-from-idea-to-product`
- **Showcase:** `https://hachikoj.github.io/project-from-idea-to-product/`

### What makes it different
Unlike static planning skills, this project includes a runtime control layer:

- stage detection
- one current highest-priority task
- explicit do-not-do list
- stage exit criteria
- anti-overfitting / focus control
- delivery-driven dev loop

That makes it closer to a **project director skill** than a static prompt pack.

### Best fit
- internal tools
- ticket systems
- approval systems
- admin dashboards
- workflow products
- multi-role operational products
- projects that must become deployable and presentable

### Status
Validated in conversation for:
- extracting reusable methods from a real shipped project
- migrating the method to a new internal ticket-system scenario
- runtime orchestration logic
- delivery-oriented project control
