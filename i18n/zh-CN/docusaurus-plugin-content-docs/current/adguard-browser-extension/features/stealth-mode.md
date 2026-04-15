---
title: 跟踪保护（隐身模式）
sidebar_position: 3
---

:::info

这篇文章是关于 AdGuard 浏览器扩展，它只能保护用户的浏览器。 要全面保护设备，请[下载 AdGuard 应用程序](https://agrd.io/download-kb-adblock)。

:::

「跟踪防护」的目的是保护您的敏感个人数据免受在线跟踪器和欺诈者的侵害。 基于 Chromium（支持 MV3）和非 Chromium（支持 MV2）的浏览器在跟踪防护功能上存在细微差异。

![基于 Chromium 的浏览器中的跟踪保护 \*border](https://cdn.adtidy.org/content/Kb/ad_blocker/browser_extension/ad_blocker_browser_extension_mv3_trackingProtection.png)

基于 Chromium 的浏览器中的「跟踪保护」

![非 Chromium 浏览器中的跟踪保护 \*border](https://cdn.adtidy.org/content/Kb/ad_blocker/browser_extension/ad_blocker_browser_extension_mv2_trackingProtection.png)

非 Chromium 浏览器中的「跟踪保护」

「跟踪防护」功能可防止网站看到您在互联网上用来找到它们的搜索查询、自动删除第三方和网站 Cookie 等。 我们有一篇[文章](/general/stealth-mode)专门介绍这些功能。

:::note

浏览器扩展仅限于特定的浏览器，并受其技术限制的约束。 因此，它们无法提供完整的广告拦截应用所具备的全部跟踪防护功能。

:::

:::caution

In AdGuard Browser Extension, the _Block WebRTC_ option works globally — it either blocks or allows WebRTC for all websites. It cannot be controlled on a per-site basis. Exception rules like `@@||example.com^$stealth=webrtc` have no effect in the browser extension because the `webrtc` option is not among the [supported `$stealth` modifier options](/general/ad-filtering/create-own-filters#stealth-modifier). If you need per-site WebRTC control, use the full-fledged AdGuard app for Windows, Mac, or Android.

:::
