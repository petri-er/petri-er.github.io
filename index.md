---
title: '锦麟'
layout: home
---

> 锦麟生祥瑞

## 2022年4月

工作5年，需要总结一下自己的知识体系，古话说得好，只要行动起来，什么时候都不会为时已晚。

曾几何时，火遍大江南北的最强大脑播出流行的时候，我也一时火热，去了解了一下记忆宫殿，最强大脑也是从一砖一瓦堆砌起来。

作为一个技术工作者，自己的工具，一刀一枪更需要自己去摸索掌控好。

从现在开始，在这堆砌好自己的技术金字塔。

## 长路漫漫

> 路漫漫其修远兮，吾将上下而求索

```javascript
// 获取明天的现在时间
setTimeout(()=>{
    console.log(new Date());
}, 1000 * 60 * 60 * 24);
```

- [x]  整理javascript知识点

- [ ]  123

- [x]  123

GitBook is an amazing frontend style to present and organize contents (such as book chapters
and blogs) on Web. The typical to deploy GitBook at [Github Pages][1]
is building HTML files locally and then push to Github repository, usually to the `gh-pages`
branch. It's quite annoying to repeat such workload and make it hard for people do version
control via git for when there are generated HTML files to be staged in and out.

This theme takes style definition out of generated GitBook site and provided the template
for Jekyll to rendering markdown documents to HTML, thus the whole site can be deployed
to [Github Pages][1] without generating and uploading HTML bundle every time when there are
changes to the original repo.

This theme can be used just as other [Jekyll themes][1].

[Fork][3] this repository and add your markdown posts to the `_posts` folder.

### Deploy Locally with Jekyll Serve

This theme can be ran locally using Ruby and Gemfiles.

[Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) - GitHub

## Full-text search

The search functionality in jekyll-gitbook theme is powered by the [gitbook-plugin-search-pro][5] plugin and is enabled by default.

[https://sighingnow.github.io/jekyll-gitbook/?q=generated](https://sighingnow.github.io/jekyll-gitbook/?q=generated)

## Code highlight

The code highlight style is configurable the following entry in `_config.yaml`:

```yaml
syntax_highlighter_style: colorful
```

The default code highlight style is `colorful`, the full supported styles can be found from [the rouge repository][6]. Customized
style can be added to [./gitbook/rouge/](./gitbook/rouge/).

## How to generate TOC

The jekyll-gitbook theme leverages [jekyll-toc][4] to generate the *Contents* for the page.
The TOC feature is not enabled by default. To use the TOC feature, modify the TOC
configuration in `_config.yml`:

```yaml
toc:
    enabled: true
    h_min: 1
    h_max: 3
```

## License

This work is open sourced under the Apache License, Version 2.0.

Copyright 2019 Tao He.

[1]: https://pages.github.com
[2]: https://pages.github.com/themes
[3]: https://github.com/sighingnow/jekyll-gitbook/fork
[4]: https://github.com/allejo/jekyll-toc
[5]: https://github.com/gitbook-plugins/gitbook-plugin-search-pro
[6]: https://github.com/rouge-ruby/rouge/tree/master/lib/rouge/themes
