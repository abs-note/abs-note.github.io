---
title: README
layout: about
---
# abs-note.github.io

本网站用于个人ABS知识笔记管理，使用 [Jekyll] 生成，选用的 Jekyll theme 为 [Just the Docs]。

## 网站初始化教程

[Jekyll]是一个简单的博客形态的静态站点生产机器，通过一个转换器（如 Markdown）和 Liquid 渲染器转化成一个完整的可发布的静态网站，可以运行在 [GitHub Pages] 上。但是，由于 [Just the Docs] 并非 [GitHub Pages 支持主题]，需要启用 [Github Actions] 来生成并发布网站。

以下是利用 [Just the Docs] 简易生成模板 [just-the-docs/just-the-docs-tempelate] 进行网站搭建并托管在 [GitHub Pages] 上的初始化步骤：

1. 点击 "[use this template]" 并创建一个新仓库，仓库名称为 `username.github.io` (其中`username` 为用户本人的 GitHub 账号)；
2. 仓库创建后，前往 Settings > Pages > Build and deployment > Source，选择 GitHub Actions。

## 个性化配置

初始化完毕后，`username.github.io` 应该已经生成了一个可访问的网页，并采用 [Just the Docs] 的基本配置，接下来可以进一步完善网站内容：

1. 修改 `index.md` 的内容，这将成为你的网站首页；
2. 创建 `docs/` 文件夹，存放其他页面内容，统一使用 Markdown 编写；
3. 修改 `_config.yml`，设定个性化配置（支持 Mermaid 图表）；
4. 查阅官方文档进行进一步深度配置。

## 参考文档

1. [Just the Docs 官方文档](https://just-the-docs.com/)（推荐）
2. [Just the Docs Tests 官方文档](https://just-the-docs.com/)（深度配置）
3. [Just the Docs 中文版文档](https://docs.rubyist.cn/just-the-docs/)（版本滞后）
4. [GitHub Pages 快速入门](https://docs.github.com/zh/pages/quickstart)
5. [Markdown 基本语法](https://markdown.com.cn/basic-syntax/)
6. [Mermaid 基本语法](https://mermaid.js.org/intro/)

## License

本项目采用 [MIT License]。

### [Just the Docs]

The theme is available as open source under the terms of the [MIT License].

### [just-the-docs/just-the-docs-tempelate]

This repository is licensed under the [MIT License]. You are generally free to reuse or extend upon this code as you see fit; just include the original copy of the license (which is preserved when you "make a template"). While it's not necessary, we'd love to hear from you if you do use this template, and how we can improve it for future use!

The deployment GitHub Actions workflow is heavily based on GitHub's mixed-party [starter workflows](https://github.com/actions/starter-workflows/blob/main/pages/jekyll.yml). A copy of their MIT License is available in [actions/starter-workflows](https://github.com/actions/starter-workflows/blob/main/LICENSE).

[Jekyll]: https://jekyllrb.com
[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[just-the-docs/just-the-docs-tempelate]: https://github.com/just-the-docs/just-the-docs-template
[GitHub Pages]: https://docs.github.com/cn/pages
[GitHub Pages 支持主题]: https://pages.github.com/themes/
[GitHub Actions]: https://docs.github.com/zh/actions
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
[MIT License]: http://opensource.org/licenses/MIT