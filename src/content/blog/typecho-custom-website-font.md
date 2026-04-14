---
title: 'Typecho 自定义网站字体'
publishDate: '2025-07-15'
description: '在 Typecho 网站中，自定义字体是提升网站视觉效果的重要方式之一。本文将推荐几款适合网站使用的字体，并教你如何在 Typecho 中自定义字体。 推荐字体 1. 思源黑体（Source Han Sans）  - 特点：开源字体，支持中英文，简洁现代。   - 适用场景：博客、新闻类网站。  -'
tags:
  - 随笔
draft: false
comment: true
---

在 Typecho 网站中，自定义字体是提升网站视觉效果的重要方式之一。本文将推荐几款适合网站使用的字体，并教你如何在 Typecho 中自定义字体。

## 推荐字体

**1. 思源黑体（Source Han Sans）**

 - 特点：开源字体，支持中英文，简洁现代。 
 - 适用场景：博客、新闻类网站。
 - 获取方式： [Google Fonts][1] 或 [Github][2]。

**2. 站酷字体（ZCOOL）**

 - 特点：免费商用，风格独特，适合标题。
 - 适用场景：创意类、设计类网站。

获取方式：[站酷字体][3]。

**3. 阿里巴巴普惠体（Alibaba Sans）**

 - 特点：免费商用，简洁大方，适合正文。
 - 适用场景：企业官网、电商网站。

获取方式：[阿里巴巴普惠体][4]。

**4. Google Fonts 字体**

推荐字体：

 - Roboto：现代感强，适合科技类网站。
 - Open Sans：简洁易读，适合正文。
 - Lato：圆润优雅，适合多种场景。

获取方式：[Google Fonts][1]。

**5. 本地字体**

推荐字体：

 - 苹方（PingFang SC）：苹果系统默认字体，适合中文。
 - 微软雅黑（Microsoft YaHei）：Windows
 - 系统默认字体，适合中文。 获取方式：系统自带，无需额外下载。

## 如何在 Typecho 中自定义字体

### 方法 1：使用 Fontlibs 插件

最简单的方式，插件内置字体，可以直接在后台更换字体

插件地址：https://github.com/xxhzm/FontLibs

### 方法 2：通过 CSS 引入 Google Fonts

打开 Typecho 主题的 header.php 文件。

在 <head> 标签内添加 Google Fonts 的链接：
```
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
```
在主题的 style.css 文件中设置字体：

```
body {
    font-family: 'Roboto', sans-serif;
}
```
### 方法 3：使用本地字体

将字体文件（如 .ttf 或 .woff）上传到 Typecho 主题的 fonts 文件夹中。

在主题的 style.css 文件中定义字体：

```
@font-face {
    font-family: 'MyCustomFont';
    src: url('fonts/MyCustomFont.woff2') format('woff2'),
         url('fonts/MyCustomFont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
body {
    font-family: 'MyCustomFont', sans-serif;
}
```

## 注意事项

 - 字体加载速度：使用外部字体（如 Google Fonts）时，注意加载速度，避免影响用户体验。
 - 版权问题：确保使用的字体可以免费商用，避免侵权。
 - 兼容性：为不同浏览器提供多种字体格式（如 .woff、.woff2）。


  [1]: https://fonts.google.com/
  [2]: https://github.com/adobe-fonts/source-han-sans
  [3]: https://www.zcool.com.cn/special/zcoolfonts/
  [4]: https://alibabafont.taobao.com/