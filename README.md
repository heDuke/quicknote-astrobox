# QuickNote · AstroBox resource

当前资源包：**1.0.1 / versionCode 4**，包名 `com.heduke.quicknote`。

## 下载映射（仅按官方屏幕规格匹配）

| 资源设备 ID | 安装包 | 屏幕 |
| --- | --- | --- |
| xmws3 / xmws4 / xmws441 | qn-round-release.rpk | 圆屏 466×466 |
| xmb9 | qn-band9-release.rpk | 胶囊屏 192×490 |
| xmb10 / xmb10nfc | qn-band10-release.rpk | 胶囊屏 212×520 |

圆屏和 Band 10 发布包已在对应分辨率的模拟器安装、检查；Band 9 仅构建与包体校验。**未逐型号完成真机验证**，分辨率匹配不等于完整设备兼容认证。本次不提供 Pro 方屏包；S5 46mm 的480×480也不匹配466包。尚未核实的 S4 XRING、S5 41mm、Band 11 NFC 暂不列入下载映射。

官方屏幕规格：
- [Watch S3](https://www.mi.com/global/product/xiaomi-watch-s3/specs/)
- [Watch S4](https://www.mi.com/global/product/xiaomi-watch-s4/specs/)
- [Watch S4 41mm](https://www.mi.com/global/product/xiaomi-watch-s4-41mm/specs/)
- [Band 9](https://www.mi.com/global/product/xiaomi-smart-band-9/specs/)
- [Band 10](https://www.mi.com/global/product/xiaomi-smart-band-10/specs/)
- [Band 10 NFC（官方台湾规格同时列出NFC型号）](https://www.mi.com/tw/product/xiaomi-smart-band-10/specs/)

## 图像与来源

- `media/3939.png` 是从本次发布包导出的紫色便笺图标，与包内图标一致。
- v7封面沿用已确认的版式与AI生成通用手表外壳；显示内容替换为本次1.0.1圆屏模拟器真实截图，不是真机照片，也未粘贴小米产品照。保留 `Designed with Grok Bot` 设计署名。
- `media/01.png`、`04.png`、`06.png` 使用本次发布包模拟器截图重新排版，未重绘或修改UI文字；不再展示未提供的Pro方屏。
- `02.png`、`03.png`、`05.png`、`07.png` 为已有展示素材，本轮未重拍。
- 应用的到期清理在打开/回到前台或列表前台刷新时执行，不是后台定时提醒。

源码仓库：https://github.com/heDuke/vela-quicknote-wm3
本次源码本地分支：`fix/astrobox-quicknote-name`；发布前需由作者确认源码公开分支与版本对应关系。

本次构建对应源码提交：`197d9a8a6192f441cb87a56c288efc5f2c9e34ae`。
