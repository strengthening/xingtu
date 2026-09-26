# AGENTS.md：给 AI 代理的规则

这个仓库用来比较不同 AI 按同一份需求做出的星空网站。开始工作前请读完本文件，并全程遵守。

## 任务

- 需求在 main 分支的 [PROMPT.md](PROMPT.md)，按它完成开发。

## 分支

- 从 main 新建你自己的分支 `ai/<工具>-<模型>`，例如 `ai/codex-gpt-5`、`ai/gemini-cli-gemini-3-pro`。
- 所有提交只放在这个分支上，并推送到 GitHub。
- 不要向 main 提交、推送或发 Pull Request。

## 不要参考其他 AI 的成果

- 只使用 main 和你自己的分支。
- 不要查看、检出、比较、合并或 cherry-pick 本仓库的其他分支和 tag。
- 不要运行会列出或拉取其他分支的命令，例如 `git branch -a`、`git branch -r`、`git log --all`、`git fetch --all`。
- 也不要通过 GitHub 网页或 API 浏览其他分支的内容。

## 文件

- 不要修改 PROMPT.md 和 AGENTS.md。
- 原始数据（下载的 CSV 等）和生成的数据文件不要提交，按 PROMPT.md 的要求加入 .gitignore。
