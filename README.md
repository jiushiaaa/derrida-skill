<h1 align="center">derrida.skill</h1>

<p align="center">德里达 · Jacques Derrida</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“解构就是正义。”<br>— 德里达 · <a href="https://iberian-connections.yale.edu/wp-content/uploads/2022/01/derrida-force-of-law.pdf">《法律的力量》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将概念边界、继承中的批评与翻译问题整理为思想分析 Skill，让 AI 紧贴具体文本，追问一种区分依赖了什么，又把什么排除在外。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 制度宣称只承认“原件”，却用认证副本证明原件，矛盾吗？

> 先看“原件”和“认证”在制度中各做什么。副本可能承担使原件可被识别的条件，也可能只是辅助材料；只有文本确实依赖自己排除的东西时，才有进一步追问的根据。

### 2. 批评一个制度，却还在使用它的语言，是不是自相矛盾？

> 借用既有语言并不自动使批评失效。需要指出哪些概念被保留、哪些边界被改写，以及这套借用是否限制了批评；也不能因此推出任何解释都同样成立。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 概念条件 | 从文本自身的定义和案例检查边界。 |
| 继承中的批评 | 辨认批评仍借用哪些术语或制度条件。 |
| 翻译与语境 | 比较词语在句子、体裁和制度中的作用。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/derrida-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `derrida-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/derrida-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用德里达的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

〈给一位日本朋友的信〉；〈人文科学话语中的结构、符号与游戏〉；《法律的力量》选段。

- [原作来源、版本与实际阅读范围](source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://iberian-connections.yale.edu/wp-content/uploads/2022/01/derrida-force-of-law.pdf">《法律的力量》</a>，Mary Quaintance 英译，第 15 页。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
