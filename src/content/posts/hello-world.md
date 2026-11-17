---
author: Wenjie
pubDatetime: 2026-11-17T06:00:00Z
title: 你好，世界！我的第一篇博客
featured: true
draft: false
tags:
  - 博客
  - Astro
  - 折腾
description: 欢迎来到我的新博客，这是基于 AstroPaper 和 Cloudflare Pages 搭建的第一篇文章。
---

欢迎来到我的个人博客！

这是使用 **AstroPaper** 主题搭建的个人博客，托管于 **Cloudflare Pages** 与 **GitHub**。

## 为什么选择这个技术栈？

1. **Astro + AstroPaper**：
   - 极简、现代的设计风格与丝滑的阅读体验。
   - 零运行时 JS 开销（纯静态 HTML 优先）。
   - 内置全文搜索（Pagefind）、代码高亮、暗黑模式切换。
2. **Cloudflare Pages**：
   - 全球边缘 CDN 分发，秒级加载。
   - 每次推送到 GitHub 自动触发 CI/CD 极速构建。
   - 完全免费且无带宽限制。

## 如何写新文章？

在项目根目录的 `src/content/posts/` 目录下创建一个新的 `.md` 或 `.mdx` 文件，按照如下 frontmatter 格式填写即可：

```markdown
---
author: Wenjie
pubDatetime: 2026-11-17T06:00:00Z
title: 文章标题
featured: true
draft: false
tags:
  - 标签名称
description: 文章简要描述
---

正文内容...
```

祝写作愉快！
