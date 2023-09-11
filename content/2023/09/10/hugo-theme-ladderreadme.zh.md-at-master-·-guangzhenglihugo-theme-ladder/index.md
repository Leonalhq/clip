---
title: "美丽小网站"
date: 2023-09-10T04:46:41
updated: 2023-09-10T04:46:41
taxonomies:
  tags: 
extra:
  source: https://github.com/guangzhengli/hugo-theme-ladder/blob/master/README.zh.md
  hostname: github.com
  author: 
  original_title: "hugo-theme-ladder/README.zh.md at master · guangzhengli/hugo-theme-ladder"
---

#### 🌈 简洁 | ⏩ 快速 | 📰 聚焦阅读 | 🌐 多语言 | 🌙 多种样式 | 📱 移动端支持

[Demo 网站](https://hugo-ladder.pages.dev/zh/) 包括了所有的安装文档信息，例如如何免费构建独立的博客网站，如何。你可以通过直接访问网站，来获得原生体验。

Demo 网站是通过这个仓库构建而来 [exampleSite Source Code](https://github.com/guangzhengli/hugo-ladder-exampleSite) ([https://github.com/guangzhengli/hugo-ladder-exampleSite)。](https://github.com/guangzhengli/hugo-ladder-exampleSite)%E3%80%82)

[![Hugo Version](68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d6875676f2d76657273696f6e266d6573736167653d302e39392e3026636f6c6f723d626c7565266c6f676f3d6875676f.svg)](https://github.com/gohugoio/hugo/releases/tag/v0.99.0)[![GitHub license](68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f6775616e677a68656e676c692f6875676f2d7468656d652d6c6164646572.svg)](https://github.com/guangzhengli/hugo-theme-ladder/blob/master/LICENSE)[![GitHub stars](68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f6775616e677a68656e676c692f6875676f2d7468656d652d6c6164646572.svg)](https://github.com/guangzhengli/hugo-theme-ladder/stargazers)[![GitHub forks](68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f666f726b732f6775616e677a68656e676c692f6875676f2d7468656d652d6c6164646572.svg)](https://github.com/guangzhengli/hugo-theme-ladder/network)

___

[![Ladder image](68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f6775616e677a68656e676c692f50696355524c406d61737465722f755069632f56504b4937482e706e67.png "Mockup")](https://camo.githubusercontent.com/dea326ce9fc059816bf02cc75d977f0c6173d5f486ef464d1a5d512fda6f82cf/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f6775616e677a68656e676c692f50696355524c406d61737465722f755069632f56504b4937482e706e67)

___

文档 [`docs`](https://github.com/guangzhengli/hugo-theme-ladder/blob/master/docs/home.md)
---------------------------------------------------------------------------------------

See [`docs`](https://github.com/guangzhengli/hugo-theme-ladder/blob/master/docs/home.md) folder.

### 基础使用

*   [Quick Start](https://github.com/guangzhengli/hugo-theme-ladder/blob/master/docs/quick-start.md)
*   [Configurations](https://github.com/guangzhengli/hugo-theme-ladder/blob/master/docs/configurations.md)

### 高级用法

*   [Multi Language](https://github.com/guangzhengli/hugo-theme-ladder/blob/master/docs/multi-language.md)
*   [Comment System](https://github.com/guangzhengli/hugo-theme-ladder/blob/master/docs/comment-system.md)
*   [Analytics](https://github.com/guangzhengli/hugo-theme-ladder/blob/master/docs/analytics.md)
*   [Analytics Umami](https://github.com/guangzhengli/hugo-theme-ladder/blob/master/docs/umami.md)

快速开始
----

Just click `Use this template` to create your blog site in the [exampleSite Repository](https://github.com/guangzhengli/hugo-ladder-exampleSite).

Create a new repository(GitHub Pages) from hugo-ladder-exampleSite to enter : `username.github.io`.

**replace the username by your GitHub account**

Then configure the GitHub page setting following:

[![nsrExo](68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f6775616e677a68656e676c692f50696355524c406d61737465722f755069632f6e737245786f2e706e67.png)](https://camo.githubusercontent.com/6928ef586bbfc1d5a4e56c788da37eec9da1bd9e4c0d3d29abb7a6112381c43b/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f6775616e677a68656e676c692f50696355524c406d61737465722f755069632f6e737245786f2e706e67)

🎉🎉🎉 Open the browser and enter: [https://username.github.io](https://username.github.io/) 🎉🎉🎉

最小配置
----

Clone your repository.

Build and run hugo server by `hugo server -D` and open in browser [http://localhost:1313/](http://localhost:1313/).

```yaml
baseURL: 'https://hugo-ladder.pages.dev' # set https://username.github.io
homepage: 'https://hugo-ladder.pages.dev' # set https://username.github.io
defaultContentLanguage: 'en' #default language
params:
  brand: HOME # set the brand of your site
  avatarURL: /images/avatar.png # avatar, replace your avatar in the /static/images/
  author: Hugo Ladder # name
  authorDescription: # description
  info:  this is a info # information of your blog site
  favicon: /images/avatar.png # blog site icon，replace your avatar in the /static/images/
  options:
    showDarkMode: true # is show dark mode button
    enableMultiLang: true # is show multi language button
```

Modifying the default configuration. Then push it to your repository.

ALL Configuration
-----------------

Following this [article](https://guangzhengli.com/blog/en/how-to-create-your-blog-for-free-by-hugo-ladder-in-30min/) to cofiguration.

Following this [article](https://guangzhengli.com/blog/en/how-to-integrate-umami-for-free-to-blog-site/) to configure the umami analytics

Sponsor
-------

如果这份教程对你有帮助，欢迎请作者喝杯咖啡。 [https://guangzhengli.com/sponsors](https://guangzhengli.com/sponsors)

Special Thanks
--------------

*   Hugo Ladder is inspired by [hugo-paperMod](https://github.com/adityatelange/hugo-PaperMod).
