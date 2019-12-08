---
layout: post
title: テスト
tags: [Markdown, foreign]
color: brown
author: Seo
excerpt_separator: <!--more-->
---

# 새 글 작성.

이것은 본문.

これは日本語。

You can go fork and star hers too! 😉

<!--more-->

## How does it work?

Basically you need to add just one thing, the color:

```yml
---
layout: post
title: Color Post
color: brown
---
```

It can either be a html color like `brown` (which look like red to me). Or with the rgb:

```yml
---
layout: post
title: Color Post
color: rgb(165,42,42)
---
```

The background used is `lineart.png` from [xukimseven](https://github.com/xukimseven) you can edit it in the config file. 
If you want another one, put it in `/assets/img` as well. 

> ⚠️ It's a bit hacking the css in the `post.html`
