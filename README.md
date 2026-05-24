# Pan-YourFriend — 盘友缘升级仓库

> 本仓库为 [盘友缘 (PYF)](https://github.com/shumyun/Pan-YourFriend) 的远程升级数据源，
> 包含频道列表、WASM 插件清单、应用更新配置等。

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

*本仓库由 [PYF-sync](https://github.com/shumyun/Pan-YourFriend) 工具自动同步维护。*
