# 拾光管家

面向大学生的 AI 生活管家（Windows 桌面版 / 安卓版）。

## 下载

前往 [Releases](https://github.com/fk-M/shiguang-butler/releases) 下载最新安装包：

| 设备 | 文件 |
| --- | --- |
| Windows 10 / 11（x64） | `ShiguangButler-Setup-*.exe` |
| 安卓 / 鸿蒙 4.x 及以下 | `ShiguangButler-Android-*.apk` |
| 纯血鸿蒙 HarmonyOS NEXT | `ShiguangButler-Harmony-NEXT-*.zip`（ArkWeb 工程 + 未签名 HAP，需用 DevEco Studio 登录华为账号自动签名后安装） |

- 数据保存在 `%APPDATA%\shiguang-butler\data`，桌面版升级安装不会删除；新版本安装包会自动关闭正在运行的旧版。
- 安卓版覆盖安装不会删除数据；卸载或清除应用数据会删除本地内容。
- HarmonyOS 4.x 仍运行 Android APK，若被「纯净模式」拦截，请在系统设置中允许安装外部应用；HarmonyOS NEXT 不运行 APK，两者无法共用同一个安装包。
- HAP 必须使用华为签名证书，本仓库附带的 HAP 为未签名产物，请在 DevEco Studio 中完成签名后再安装。
- 本仓库仅发布安装包。