# Codex AI Productivity Toolkit

这是一个独立的 Codex 项目子目录，用于安全地安装、审查和验证精选 Agent Skills。**此文件存在不代表第三方技能已经安装。**

## 项目目标

- 安装 7 个项目级 Skills：find-skills、skill-creator、frontend-design、planning-with-files、agent-browser、baoyu-xhs-images、last30days。
- 在 Codex 插件系统中单独处理 Superpowers。
- 区分可安装技能与 n8n、Make、NotebookLM、Claude Cowork 等独立应用和云服务。
- 生成真实的安装报告、测试结果、风险与依赖检查。

## 开始

1. 在 Codex 中打开此仓库的 `projects/codex-ai-productivity-toolkit` 目录。
2. 阅读 `CODEX_TASK.md`，按任务清单执行，不要直接批量信任第三方代码。
3. 先审查来源再使用 Node.js 22.20+ 环境运行 `npx skills add <source> --skill <name> -a codex --copy -y`。
4. 保持项目级安装，不使用 `-g`；高权限、联网抓取、账号登录、全局安装依赖须另行批准。
5. 运行验证并填写 `INSTALL_REPORT.md`。

完整的 Python 安装/验收脚手架可在 ChatGPT 生成的 ZIP 附件中获取。此仓库中的 `CODEX_TASK.md` 是 Codex 任务入口。
