# 发布说明 · 宇宙演变论 · 完整理论

本目录（`publish/`）包含已转换好的静态站点：`index.html`。
单文件、自包含（内联 CSS、无外部依赖），GitHub Pages 原生渲染。

## 当前状态：已上线

- 站点地址：**https://pengfeiyang2006.github.io**
- 仓库：`pengfeiyang2006/pengfeiyang2006.github.io`

## 更新流程（理论文档修订后）

1. 重新生成站点：`python build_site.py`（在 `理论/` 目录下执行）
2. 把新的 `publish/index.html` 推到仓库：

```bash
cd publish
git add index.html
git commit -m "update 宇宙演变论"
git push
```

## 说明
- 本理论是**单篇长文档**，无需 Jekyll / Hugo / Hexo 这类静态生成器；直接一个 `index.html` 最轻量。
- 若以后要写系列文章，再考虑套 Jekyll（GitHub 官方支持，仓库根放 `_config.yml` 与 `_posts/`）。
- 参考资源（你的指南里链接为空，这里补上）：
  - GitHub Pages 官方文档：https://pages.github.com
  - Jekyll 官网：https://jekyllrb.com （中文：https://www.jekyll.com.cn ）
  - Hugo 官方文档：https://gohugo.io
  - Hexo 官方文档：https://hexo.io
