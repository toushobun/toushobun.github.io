---
title: リンク
links:
  - title: GitHub
    description: GitHub は世界最大のソフトウェア開発プラットフォームです。
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
menu:
    main: 
        weight: 4
        params:
            icon: link

comments: false
---

この機能を使用するには、frontmatter に links セクションを追加してください。

このページの frontmatter の例：

```yaml
links:
  - title: GitHub
    description: GitHub は世界最大のソフトウェア開発プラットフォームです。
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: TypeScript
    description: TypeScript は JavaScript の型付きスーパーセットで、通常の JavaScript にコンパイルされます。
    website: https://www.typescriptlang.org
    image: ts-logo-128.jpg
```

`image` フィールドには、ローカル画像と外部画像の両方を指定できます。
