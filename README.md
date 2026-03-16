# Enterprise Plugin

企业级插件，提供代码审查、安全扫描、性能测试等功能。

## 使用方法

1. 安装插件
2. 配置相关设置
3. 开始使用各项功能

## 功能特性

- 代码审查
- 安全扫描
- 性能测试
- 合规检查

## 许可证

MIT

## 项目目录结构

YUQIU_PLUG_IN/
├── .yuqiu-plugin/          # 元数据目录
│   └── plugin.json
├── agents/                 # 子智能体
│   ├── compliance-checker.md    # 合规检查
│   ├── performance-tester.md    # 性能测试
│   └── security-reviewer.md     # 安全审查
├── commands/               # 简单技能
│   ├── deploy.md           # 部署命令
│   └── status.md           # 状态命令
├── hooks/                  # 事件钩子
│   ├── hooks.json          # 常规钩子
│   └── security-hooks.json # 安全相关钩子
├── scripts/                # 辅助脚本
│   ├── deploy.js           # 部署脚本
│   ├── format-code.py      # 代码格式化
│   └── security-scan.sh    # 安全扫描
├── skills/                 # Agent 技能
│   ├── code-reviewer/      # 代码审查
│   │   └── SKILL.md
│   └── pdf-processor/      # PDF 处理
│       ├── SKILL.md
│       └── reference.md
├── .commitlintrc.json      # Commit 信息规范
├── .lsp.json               # LSP 服务器配置
├── .mcp.json               # MCP 服务器配置
├── CHANGELOG.md            # 版本历史
├── LICENSE                 # 许可证
├── README.md               # 项目说明
├── docker-compose.yml      # Docker 配置
└── package.json            # 项目依赖
