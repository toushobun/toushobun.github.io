---
title: 链接
links:
  - title: GitHub
    description: GitHub 是全球最大的软件开发平台。
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
menu:
    main: 
        weight: 4
        params:
            icon: link
comments: false
draft: true
---

要使用此功能，请在 frontmatter 中添加 links 区块。

本页面的 frontmatter 示例：

```yaml
links:
  - title: GitHub
    description: GitHub 是全球最大的软件开发平台。
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: TypeScript
    description: TypeScript 是 JavaScript 的带类型超集，可编译为普通的 JavaScript。
    website: https://www.typescriptlang.org
    image: ts-logo-128.jpg
```

`image` 字段既支持本地图片，也支持外部图片。
