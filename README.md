# 卡探 更新源

这个仓库只做一件事：给「卡探」应用内的**检查更新 / 强制更新**提供匿名可读的 `update.json`，以及公开可下载的安装包。

- 更新源地址（应用内默认）：`https://raw.githubusercontent.com/xiaoyu4124/katan-release/main/update.json`
- 应用每栏读这几个字段：`versionCode`、`versionName`、`url`、`force`、`notes`
- `force: true` 时客户端弹窗不可取消，只能「立即更新」或退出应用

> 源码与开发文档在主仓库 `xiaoyu4124/katan`（私有）。本仓库**只放安装包**，不放源码。
