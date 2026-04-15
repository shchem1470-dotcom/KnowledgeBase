---
title: User Scripts API
sidebar_position: 8
---

:::info

这篇文章是关于 AdGuard 浏览器扩展，它只能保护用户的浏览器。 要全面保护设备，请[下载 AdGuard 应用程序](https://adguard.com/download.html?auto=true)

:::

当添加自定义过滤器或用户规则时，会出现一个通知，询问您是否启用开发者模式以在扩展中使用这些功能。

![通知 \*border](https://cdn.adtidy.org/content/Kb/ad_blocker/browser_extension/notification-allow-user-scripts.jpg)

从 5.2 版本开始，AdGuard 浏览器扩展开始使用 User Scripts API。 Chrome 要求使用这一新 API，以遵循用户安全的最佳实践。

## 什么是 User Scripts API？

User Scripts API 是一种工具，允许扩展程序在网页上运行自定义的 JavaScript 脚本。 These are often used to modify or enhance websites in ways that aren’t originally provided by the website itself.

With the shift to Chrome’s Manifest V3, many older methods of injecting scripts are limited or delayed. However, there is an exception for the User Scripts API.

更多关于 MV3 政策影响的信息，请参阅我们的[博客文章](https://adguard.com/en/blog/review-issues-in-chrome-web-store.html)。

## 如何启用开发者模式

要在「用户规则」标签页中使用自定义过滤器和 JavaScript 规则，您必须先设置好浏览器。 这将为扩展程序提供一种可靠且安全的方法，在最佳时机将脚本注入网页。 请根据您的 Chrome 版本，按照以下说明进行操作。

### 对于 138 版本之前的 Chrome

You must enable Developer mode for extensions. To do so, open the Chrome menu by clicking the three dots in the upper-right corner, go to _Extensions_ ⭢ _Manage extensions_, and toggle the _Developer mode_ switch.

![Manage Extensions \*border](https://cdn.adtidy.org/content/Kb/ad_blocker/browser_extension/developer-mode-enable1.jpg)

### For Chrome version 138 and later

You must enable the _Allow user scripts_ toggle. To do so, open the Chrome menu by clicking the three dots in the upper-right corner, go to _Extensions_ ⭢ _Manage extensions_, go to AdGuard Browser Extension’s _Details_, and toggle the _Allow user scripts_ switch.

![Manage Extensions \*border](https://cdn.adtidy.org/content/Kb/ad_blocker/browser_extension/allow-user-scripts1.jpg)
