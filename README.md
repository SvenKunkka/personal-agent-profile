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
