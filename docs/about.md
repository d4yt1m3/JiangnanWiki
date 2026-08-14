# 关于 JiangnanWiki

JiangnanWiki 是一个使用 [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) 构建的静态知识库。

## 如何贡献

1. 在 `docs/` 目录中创建或修改 Markdown 文件。
2. 更新 `mkdocs.yml` 中的导航配置。
3. 提交并推送到 `master` 分支。
4. GitHub Actions 会自动构建并部署网站。

## 本地预览

```bash
uv sync
uv run mkdocs serve
```

浏览器访问 `http://127.0.0.1:8000`。
