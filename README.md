# Pan-YourFriend(盘友缘)

## 一个本地高性能的网盘资源搜索软件，支持TG搜索和自定义插件搜索。

> 本仓库为 [盘友缘 (PYF)](https://github.com/shumyun/Pan-YourFriend) 的远程升级数据源，
> 包含频道列表、WASM 插件清单、应用更新配置等。
>支持的网盘类型：百度网盘 (baidu)、阿里云盘 (aliyun)、夸克网盘 (quark)、光鸭云盘 (guangya)、天翼云盘 (tianyi)、UC网盘 (uc)、移动云盘 (mobile)、115网盘 (115)、PikPak (pikpak)、迅雷网盘 (xunlei)、123网盘 (123)、磁力链接 (magnet)、电驴链接 (ed2k)、其他 (others)

---

## 仓库结构

| 文件/目录 | 说明 |
|-----------|------|
| config.json | 应用更新配置（版本号、下载地址、公告等） |
| channels.json | 搜索频道列表 |
| manifest.json | WASM 插件清单（含下载地址和校验 hash） |
| plugins/ | WASM 插件文件（*_wasm.wasm） |

## 使用方式

**PYF 主程序**在启动时会自动拉取本仓库数据：
- 频道列表 → 用于 Telegram 搜索
- 插件清单 → 用于 WASM 插件热更新
- 版本配置 → 用于检测应用更新
 
## 更新记录

<!-- 更新记录由 PYF-sync 工具自动维护 -->

## 镜像

- Gitee: git@gitee.com:shumyun/Pan-YourFriend.git
- GitHub: git@github.com:shumyun/Pan-YourFriend.git

---

## 感谢

本项目是基于原版 **PanSou** 项目的 Rust 重构实现。

在此向原项目作者致以诚挚的感谢，感谢您提供的创新理念与设计，为本项目奠定了坚实的基础。

-   **原项目名称**: PanSou
-   **原项目作者**: fish2018
-   **项目地址**: [https://github.com/fish2018/pansou](https://github.com/fish2018/pansou)

---

*本仓库由 [PYF-sync](https://github.com/shumyun/Pan-YourFriend) 工具自动同步维护。*