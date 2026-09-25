> ⚠️ **本仓库已废弃**：内容已并入 [agent-deploy](https://github.com/hpsks416/agent-deploy) 的 skills/agents-md-skill-layering/ 子目录，请以 agent-deploy 为准。本仓库保留仅供历史归档。

# agents-md-skill-layering

把「每次都要自动触发」的内容放进全局 AGENTS.md，把「需要时才展开的流程」留在 skill，两层不重复。

## 环境依赖

- 操作系统：Windows
- 运行时：无（纯指令型 skill，由 agent 直接执行）
- 第三方软件：无（仅依赖系统自带的 PowerShell / 标准库）

## 目录结构

    agents-md-skill-layering/
    ├── SKILL.md    技能入口与工作流

## 安装

    # GitHub
    git clone https://github.com/hpsks416/agents-md-skill-layering.git "$env:USERPROFILE\.dsh\skills\agents-md-skill-layering"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/agents-md-skill-layering.git "$env:USERPROFILE\.dsh\skills\agents-md-skill-layering"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).

