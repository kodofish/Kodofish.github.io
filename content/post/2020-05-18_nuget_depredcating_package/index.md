---
title: "Nuget Deprecating Package"
date: 2020-05-18T19:19:13+08:00
draft: false
keywords:
  - Nuget
images:
  - img/nuget-logo.png
categories:
  - Nuget
tags:
  - Nuget
---

今天發現了 Lag 有一段時間的新功能，就是 Nuget.org 支援 `Deprecating packages` 新功能。
過去 Nuget 在還沒有支援這項功能前，開發者只能一直讓舊版軟體一直掛在 nuget.org 上, 讓使用者繼續使用，或是使用 `Unlisting`，讓使用者無法繼續搜尋到特定版本的 Package。

而在開放 Deprecating package 後, 只要你是使用 Visual Studio 2019 16.3 以後的版本，在使用 nuget manageer 時, 就可以直接在畫面上看到 Deprecating 的提示。

![Deprecating package hint](http://devblogs.microsoft.com/nuget/wp-content/uploads/sites/49/2019/09/deprecation-vs.png)

在 Nuget blog 上就有教你該如何操作 Deprecating package 的步驟，超容易操作。

若是自建 private nuget server 的話，似乎還未釋出 Deprecating package 的功能，只能先使用 enableDelisting 來處理。

## 參考資料

- [Deprecating packages on nuget.org](https://devblogs.microsoft.com/nuget/deprecating-packages-on-nuget-org/)
- [Deprecating packages](https://docs.microsoft.com/en-us/nuget/nuget-org/deprecate-packages)
- [Nuget Server - Github](https://github.com/NuGet/NuGet.Server)
