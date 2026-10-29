# 小胖的博客

本仓库是个人博客编译后生成的静态网站产物，所有文件由 Hexo 自动生成并部署，**请勿直接修改本仓库中的文件**。

## 技术栈

- [Hexo](https://hexo.io/) —— 快速、简洁且高效的博客框架
- [NexT](https://theme-next.js.org/) —— Hexo 主题
- 自动部署：`hexo-deployer-git`

## 说明

- 博客文章源码（Markdown）维护在 Hexo 源码仓库的 `source/_posts/` 目录中
- 每次源码仓库更新后，通过 `hexo generate` 生成静态文件，再由 `hexo deploy` 自动推送到本仓库
- 详细的本地写作与构建方法请参阅源码仓库中的 README
