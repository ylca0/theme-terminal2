# Halo Terminal2

一款 Terminal 风格的 Halo 主题。

修改自[Halo Terminal](https://github.com/halo-dev/halo)

![screenshot](https://user-images.githubusercontent.com/27671436/203283319-32a7384f-7b46-4c9e-9ec7-4abb796fc7cf.png)

## 配置

### 设置 Google Analytics

后台-设置-代码注入-全局 head 标签，插入 Google tag

### 配置菜单

后台-菜单-新建-链接地址

可设置 tags、categories、archives

其他页面可先进入 后台-页面，添加后再添加菜单

### 配置代码高亮

后台-设置-代码注入-内容页 head 标签，填入以下内容：

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github-dark.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"></script>
<script>hljs.highlightAll();</script>
```

想使用其他配色，可在此页面选择：

[https://cdnjs.com/libraries/highlight.js](https://cdnjs.com/libraries/highlight.js)

## 特性

- 优化样式、页面标题、页脚
- 支持明暗模式切换；
- 首页公告设置；
- 备案信息设置；
- 支持 Halo 内部的大部分页面，包括文章、页面、分类、标签、归档等。
- 支持 Halo 应用市场的部分内容管理插件，包括友情链接、瞬间。

## 致谢

- [Halo Terminal](https://github.com/halo-dev/halo)：上游仓库
- [Hugo Terminal](https://github.com/panr/hugo-theme-terminal)：Terminal 风格的 Hugo 主题，提供了最初的主题思路。
- [Zola Terminimal](https://github.com/pawroman/zola-theme-terminimal)：Hugo Terminal 主题的 Zola 移植版本，使用了该主题修改后的部分样式。
- [iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes/)：iTerm 配色方案仓库，使用了该仓库中提供的配色方案。
