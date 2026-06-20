<div align="center">

# 力扣百题通 (LeetCode-BaiTiTong)

**Obsidian + Claudian · Python · 14 天速通**

[![GitHub](https://img.shields.io/badge/GitHub-开源仓库-181717?logo=github)](https://github.com/mo-lx/LeetCode-BaiTiTong)
[![Obsidian](https://img.shields.io/badge/Obsidian-知识库-7C3AED?logo=obsidian)](https://obsidian.md/)
[![Claudian](https://img.shields.io/badge/Claudian-AI插件-D4A574)](https://github.com/ClaudianObsidian/claudian)
[![Python](https://img.shields.io/badge/Python-刷题语言-3776AB?logo=python)](https://python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**力扣百题通** — 一套面向 **Obsidian + Claudian** 打造的 LeetCode Hot 100 个人知识库与 14 天速成刷题路线。通过 Claudian 插件将 Claude 深度集成到 Obsidian 中，实现 AI 驱动的自适应学习闭环。

融合 **labuladong 框架思维** + **代码随想录系统专题法** + **灵茶山艾府题单驱动法** 三大体系，配合 AI 自适应教学系统，帮你高效拿下算法面试。

</div>

---

## 项目简介

本项目是一个完整的 **LeetCode Hot 100 算法学习体系**（力扣百题通），以 Obsidian 知识库为载体，专为有 Python 基础的学习者设计。

核心特色：

- **Claudian 驱动的自适应教学** — 基于 Obsidian Claudian 插件，通过「学习中枢」定义 AI 教练角色（Claudian · 算法教练），每次对话自动读取学员状态、教学结束后自动更新进度，实现「学 → 练 → 记」的完整闭环
- **三大方法论融合** — labuladong（框架模板法）+ 代码随想录（五步拆解法）+ 灵茶山艾府（题单驱动法）
- **14 天结构化刷题路线** — 每天 5-10 题，从基础到进阶，难度梯度科学递进
- **Obsidian 知识图谱** — 专题总结、题目详解、学习笔记之间通过 `[[wikilink]]` 互链，形成完整知识网络
- **100 道题目详解** — 每道题包含数据范围分析、多种解法、小白版理解、易错点总结、框架提炼

![知识图谱界面参考](assets/知识图谱界面参考.png)

## 目录结构

```
LeetCode-BaiTiTong/
│
├── 学习中枢.md                          # AI 操作手册（系统总开关）
│
├── 00-配置/                             # 系统配置区
│   ├── 全局索引.md                     # 整个 Vault 的目录索引
│   ├── 学习日志.md                     # 每次学习记录（追加式）
│   ├── 学员档案.md                     # 学员背景、目标、习惯
│   └── 进度看板.md                     # 进度追踪、薄弱环节、模板掌握矩阵
│
├── 01-Raw/                              # 原始素材（只增不改）
│   ├── 01-Hot100刷题体系调研报告.md    # 三大刷题体系深度调研对比
│   ├── 02-Hot100两周速通刷题计划.md    # 14 天详细刷题计划
│   └── 03-Hot100学习教程与题目详解.md  # 算法模板与题目详解
│
├── 02-Wiki/                             # 核心知识区（结构化内容）
│   ├── 专题总结/                       # 13 个专题总结
│   │   ├── 01-哈希表.md
│   │   ├── 02-双指针与滑动窗口.md
│   │   ├── 03-数组与矩阵.md
│   │   ├── 04-链表.md
│   │   ├── 05-二叉树.md
│   │   ├── 06-栈与堆.md
│   │   ├── 07-图论.md
│   │   ├── 08-回溯算法.md
│   │   ├── 09-二分查找.md
│   │   ├── 10-动态规划.md
│   │   ├── 11-贪心算法.md
│   │   ├── 12-技巧专题.md
│   │   └── 13-复杂度速查表.md
│   └── 题目详解/                       # 100 道 Hot 100 题目详解
│       ├── 1-两数之和.md
│       ├── 3-无重复字符的最长子串.md
│       ├── ...
│       └── 994-腐烂的橘子.md
│
├── 03-学习笔记/                         # 14 天学习笔记模板
│   ├── Day01-哈希与双指针.md
│   ├── Day02-滑动窗口与子串.md
│   ├── ...
│   └── Day14-技巧与全局复习.md
│
└── 04-Outputs/                          # 输出区（知识图谱、Anki 卡片等）
```

## 14 天刷题路线

| 阶段 | 天数 | 专题 | 难度分布 | 每日题量 |
|------|------|------|---------|---------|
| **第 1 周：打基础** | Day 1 | 哈希表 + 双指针 | Easy + Medium | 7 题 |
| | Day 2 | 滑动窗口 + 子串 | Easy + Medium | 7 题 |
| | Day 3 | 数组 + 矩阵 | Easy + Medium | 7 题 |
| | Day 4 | 链表基础 | Easy + Medium | 8 题 |
| | Day 5 | 链表进阶 | Medium | 6 题 |
| | Day 6 | 二叉树基础 | Easy + Medium | 8 题 |
| | Day 7 | 二叉树进阶 + 周复习 | Medium | 7 题 |
| **第 2 周：攻难点** | Day 8 | 图论 + 栈 | Medium | 7 题 |
| | Day 9 | 单调栈 + 堆 | Medium + Hard | 5 题 |
| | Day 10 | 回溯算法 | Medium + Hard | 8 题 |
| | Day 11 | 二分查找 | Medium | 6 题 |
| | Day 12 | 动态规划入门 + 贪心 | Medium | 10 题 |
| | Day 13 | 进阶动态规划 | Medium + Hard | 9 题 |
| | Day 14 | 技巧 + 全局复习 | 全难度 | 5 题 |

**难度分布：** Easy 20 题 / Medium 65 题 / Hard 15 题

## 内容特色

### 题目详解（100 道）

每道题包含以下内容：

- **数据范围分析** — 为什么 O(n^2) 会超时、数值范围意味着什么
- **边界条件与隐藏条件** — 不容易注意到的 corner case
- **小白版直白理解** — 用生活类比解释解题思路
- **多种解法对比** — 从暴力到最优，含完整 Python 代码
- **易错点总结** — 踩坑记录
- **框架提炼** — 从具体题抽象出通用模板
- **关联题目链接** — 通过 wikilink 互链到同类题目

### 专题总结（13 个）

每个专题包含：

- **本质理解** — 一句话定义核心思想
- **应用场景分类表** — 什么时候用、怎么用
- **Python 工具/数据结构对比** — dict vs set vs defaultdict vs Counter
- **可运行的 Python 代码模板** — 直接复制使用
- **模板变体及优化** — 覆盖常见变形

### AI 教学系统（Claudian 驱动）

本项目通过 **Claudian 插件**将 Claude 深度嵌入 Obsidian，打造了一套完整的 AI 自适应教学工作流：

> **Claudian** 是一款 Obsidian AI 插件，支持 Claude 直接读取和操作 Vault 中的 Markdown 文件，实现 AI 与知识库的深度交互。

**工作原理：**

1. **对话前** — Claudian 自动读取 `学员档案`、`学习日志`、`进度看板`，AI 了解你的当前状态和薄弱环节
2. **教学中** — AI 用框架思维引导思路，遇卡壳先给提示不直接给答案，根据你的掌握程度动态调整难度
3. **对话后** — Claudian 自动将学习记录写回 `学习日志`、更新 `进度看板`、填充当日 `学习笔记`

**核心设计：** `学习中枢.md` 作为 AI 的系统提示词（System Prompt），定义了 Claudian 教练的身份、教学流程、文件操作规范和回答格式。只需将此文件内容配置到 Claudian 的 System Prompt 中，即可激活完整的 AI 教学系统。

## 快速开始

### 环境要求

- [Obsidian](https://obsidian.md/)（推荐最新版）
- [Claudian](https://github.com/ClaudianObsidian/claudian) — Obsidian AI 插件（需配置 Claude API Key）

### 使用步骤

1. **克隆仓库**
   ```bash
   git clone https://github.com/mo-lx/LeetCode-BaiTiTong.git
   ```

2. **用 Obsidian 打开**
   - 打开 Obsidian → 「打开文件夹为 Vault」→ 选择克隆的仓库目录
   - 等待 Obsidian 索引完成（首次可能需要几秒）

3. **配置学员信息**
   - 打开 `00-配置/学员档案.md`，填写你的基本信息和学习目标

4. **配置 Claudian 插件**
   - 在 Obsidian 中安装 Claudian 插件，配置 Claude API Key
   - 这样 Claudian 就会化身「算法教练」，自动读取你的学习状态并指导刷题
   
5. **开始学习**
   - 按照 `01-Raw/02-Hot100两周速通刷题计划.md` 的计划开始 Day 1
   - 在 Claudian 对话中说「开始 Day 1 的学习」，AI 教练会自动接管

6. **跟踪进度**
   - 在 Obsidian 中打开「关系图谱」视图，查看知识点之间的关联
   - 每次学习后检查 `00-配置/进度看板.md` 的更新情况

## 知识图谱预览

在 Obsidian 中打开「关系图谱」视图，可以看到：

- **专题总结** ↔ **题目详解** — 每道题关联到对应专题
- **题目详解** ↔ **题目详解** — 同类题目互相链接
- **学习笔记** ↔ **专题总结** — 每日笔记关联当天专题
- **学习笔记** ↔ **题目详解** — 做题记录关联具体题目

## 方法论来源

本项目融合了以下三大刷题体系的方法论：

| 体系 | 核心方法 | 本项目应用 |
|------|---------|-----------|
| [labuladong](https://labuladong.online/) | 框架思维 — 用模板套题型 | 专题总结中的代码模板 |
| [代码随想录](https://programmercarl.com/) | 五步法 — 系统化拆解每道题 | 题目详解的结构化分析 |
| [灵茶山艾府]([灵茶山艾府的个人空间-灵茶山艾府个人主页-哔哩哔哩视频](https://space.bilibili.com/206214/)) | 题单驱动 — 精选题目高效覆盖 | 14 天刷题计划编排 |

## 技术栈

| 工具 | 用途 |
|------|------|
| Obsidian | 知识库管理、Markdown 编辑、关系图谱 |
| Claudian | Obsidian AI 插件，Claude 深度集成，驱动自适应教学 |
| Claude (Anthropic) | 大语言模型，提供算法辅导与知识库读写能力 |
| Python | 刷题语言、代码模板 |
| Markdown + Wikilink | 内容格式、知识关联 |

## 许可证

本项目基于 [MIT License](LICENSE) 开源。

## 贡献

欢迎提交 Issue 和 Pull Request！

- 发现题目详解有误？欢迎提交 PR 修正
- 有更好的解题思路？欢迎补充
- 想增加新的专题总结？欢迎贡献

---

<div align="center">

**如果这个项目对你有帮助，欢迎 Star ⭐**

</div>
