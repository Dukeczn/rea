# 同步记录

2026-10-13。这份记录只保留本轮结论，不是上游文档。

## 上游

- 仓库：https://github.com/morluto/rea
- 本副本：https://github.com/Dukeczn/rea（GitHub fork，公开）
- 同步时上游 162265 star、38065 fork
- 许可证：MIT
- 默认分支：main

公开仓库不能建成私有 fork。本机访问 github.com 的 Git HTTPS 会被连接重置，已有的 GitHub SSH 公钥也被拒绝，所以这次用 GitHub API 完成 fork。

## Cursor MCP

- 包：rea-agents 6.4.0
- 注册名：rea
- 配置文件：`C:\Users\DELL\.cursor\mcp.json`
- 原有 konnect、jlceda 保留
- 安装前备份：`C:\Users\DELL\.cursor\mcp.json.rea.backup`
- 技能目录：`C:\Users\DELL\.agents\skills\reverse-engineer-anything`
- 官方自检：Cursor 注册状态为 aligned

## 下一步

- 完全退出 Cursor 后再打开，MCP 列表才会出现 rea
- Hopper、Ghidra、IDA 都还没接上。JavaScript、Electron、.NET 静态分析不依赖它们
- 之后跟上游对齐用 `gh repo sync Dukeczn/rea`
- 这个仓库没有 GitLab 远程，只在 GitHub
