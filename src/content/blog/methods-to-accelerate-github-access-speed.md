---
title: '加速 Github 访问速度的方法'
publishDate: '2025-07-14'
description: 'Github镜像站 | 镜像 | 访问 | 链接 | 可用 | | --- | --- | --- | --- | | GitHub镜像站014 | 直接 | https://bgithub.xyz | 可用 | | GitHub镜像站013 | 直接 | https://kkgithub.com '
tags:
  - 网络
draft: false
comment: true
---

# Github镜像站

| 镜像 | 访问 | 链接 | 可用 |
| --- | --- | --- | --- |
| GitHub镜像站014 | 直接 | https://bgithub.xyz | 可用 |
| GitHub镜像站013 | 直接 | https://kkgithub.com | 可用 |
| GitHub镜像站012 | 直接 | https://gitclone.com | 可用 |
| GitHub镜像站011 | 直接 | https://github.hscsec.cn | 不可用 |
| GitHub镜像站010 | 直接 | https://git.homegu.com | 不可用 |
| GitHub镜像站009 | 直接 | https://github.ur1.fun | 可用 |
| GitHub镜像站008 | 直接 | https://git.homegu.com | 不可用 |
| GitHub镜像站007 | 文件加速 | https://moeyy.cn/gh-proxy/ | 可用 |
| GitHub镜像站006 | 文件加速 | https://ghp.ci/ | 可用 |
| GitHub镜像站005 | 文件加速 | https://gh-proxy.com/ | 可用 |
| GitHub镜像站004 | 文件加速 | https://ghproxy.net/  | 可用 |
| GitHub镜像站003 | 文件加速 | https://ghproxy.homeboyc.cn/  | 可用 |
| GitHub镜像站002 | 文件加速 | https://ghproxy.com/ | 不可用 |
| GitHub镜像站001 | 文件加速 | http://toolwa.com/github/ | 可用 |

感谢所有贡献者！如果无法访问了，可自行搜索Github镜像站解决。

# 通过修改电脑hosts文件获得Github加速访问

1. 首先访问 https://www.ip138.com 这个网站查询下面四个Github网站IP地址
  
  https://github.com
  
  https://assets-cdn.github.com
  
  https://global.ssl.fastly.net
  
  https://codeload.github.com
  
2. 把查询的四个网址对应的IP地址以下方式添加进hosts文件里即可
  

将开头 `110.10.240.150` 替换为你查询到的 ip

```
110.10.240.150 github.com
110.10.240.150 assets-cdn.github.com
110.10.240.150 codeload.github.com
110.10.240.150 global.ssl.fastly.net
```

3. 修改C:\Windows\System32\drivers\etc\hosts文件的权限，指定可写入：右击->hosts->属性->安全->编辑->点击Users->在Users的权限“写入”后面打勾。
  
4. 然后 win + R 输入 cmd，打开命令行界面。输入 ipconfig/flushdns 刷新 DNS 缓存即可，如果某一天发现网速又变慢了, 可以重新按上面的步骤查询最新的 ip 即可。