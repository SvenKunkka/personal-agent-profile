<!-- SVENKUNKKA-README-NAV:BEGIN -->
[中文项目说明](#project-overview-zh) · [English overview](#project-overview-en) · [维护者 X / Maintainer on X](https://x.com/Svenu1s5)
<!-- SVENKUNKKA-README-NAV:END -->

# Personal Agent Profile

一份可迁移、与模型和账号无关的个人 AI 协作约定。

**唯一规则正文：[AGENTS.md](./AGENTS.md)**

- 版本：1.0.0
- 语言：简体中文
- 公开正文：https://github.com/SvenKunkka/personal-agent-profile/blob/main/AGENTS.md
- 原始 Markdown：https://raw.githubusercontent.com/SvenKunkka/personal-agent-profile/main/AGENTS.md

## 换工具或账号时怎么使用

1. 获取 `AGENTS.md` 的完整正文并确认版本。
2. 将正文放入目标工具实际支持的个人指令、项目指令或本地规则文件。保留已有的必要设置；不要只贴一个工具无法访问的链接。
3. 如果工具支持文件引用，可以按该工具的方式接入；否则直接复制正文。不同工具不一定识别同一种文件名或 `@` 语法。
4. 开启一个新会话，让它说明适用的个人规则版本，并分别解释“先给方案”“继续执行”和“其他 AI 报告完成”时应如何处理。再用一项小任务检查实际行为。

导入是一个版本快照，不会自动同步本仓库更新。修改以仓库中的 `AGENTS.md` 为准，随后更新各工具的副本或引用，并重新验证。

## Codex

Codex 支持从全局 `~/.codex/AGENTS.md` 读取个人指令。导入前备份并检查现有文件；如果存在优先级更高的 `AGENTS.override.md`，应先确认它的用途。将本仓库正文合并进实际生效的入口，保留原有工具约定，再开始新会话验证。

详见 [OpenAI 官方 AGENTS.md 指南](https://learn.chatgpt.com/docs/agent-configuration/agents-md)。

## 内容边界

本文面向仓库所有者主动配置的助手，记录稳定的沟通、执行和交付偏好。其他人可以参考结构，按自己的需要调整。

具体项目状态、内部文档地址、账号、凭证、私人路径和工作日志不放入公开文件；工具配置和项目业务流程单独管理。


---

<!-- SVENKUNKKA-PROJECT-INFO:BEGIN -->

<a id="project-overview-zh"></a>
## 中文项目说明

一份可迁移、与模型和账号无关的个人 AI 协作约定，记录沟通、执行、来源判断和交付偏好。AGENTS.md 是唯一规则正文，可用于主动配置支持自定义指令的助手。

**使用入口：** 读取 [AGENTS.md](AGENTS.md)，合并到目标工具实际支持的指令入口，保留原设置，并在新会话中检查规则版本与行为。

**范围说明：** 导入只是版本快照，不会自动同步；文件名与引用语法需按目标工具处理，不包含账号或项目运行状态。

<a id="project-overview-en"></a>
## English project overview

A portable personal AI collaboration profile independent of models and accounts. AGENTS.md is the canonical policy for communication, execution, evidence and delivery preferences in assistants configured by the user.

**Getting started:** Read [AGENTS.md](AGENTS.md), merge it into the instruction entry supported by the target tool while preserving existing settings, then check the version and behavior in a new session.

**Scope:** Imports are snapshots and do not sync automatically. File names and reference syntax depend on the target tool; account details and project runtime state are excluded.

**仓库维护者 / Repository maintainer:** [SvenKunkka](https://github.com/SvenKunkka) · [X / Twitter](https://x.com/Svenu1s5)

<!-- SVENKUNKKA-PROJECT-INFO:END -->
