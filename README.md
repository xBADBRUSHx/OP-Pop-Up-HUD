# OP Pop-Up HUD

Photoshop 绘画快捷 HUD：拾色、笔刷预设、工具与命令、笔刷参数，以及录制、导出和计时器。

A Photoshop painting HUD for color, brush presets, tools, brush controls, recording, export, and timers.

当前版本 / Current version: **2.0.1** · 试用 / Trial: **7 天 / 7 days**

## 下载 / Downloads

| 文件 / File | 用途 / Use |
| --- | --- |
| [OP Pop-Up HUD 2.0.1 Setup](https://downloads.badbrush.org/op-popup-hud/2.0.1/installer-20261020/OP-Pop-Up-HUD-Setup-2.0.1.exe) | 2026-10-20 安装器修订，已集成旧版迁移 / Installer revision dated 2026-10-20, with legacy migration included |
| [Pre-2.0.0 Cleaner 2.0.3](https://downloads.badbrush.org/op-popup-hud/2.0.0/OP-Pop-Up-HUD-Pre-2.0.0-Cleanup-2.0.3.zip) | 历史独立维护工具；正常安装无需运行 / Historical standalone maintenance tool; not required for normal installation |
| [Report Tool 2026-10-20](https://downloads.badbrush.org/op-popup-hud/2.0.1/installer-20261020/OP-Pop-Up-HUD-Report-20261020.zip) | 独立诊断工具，包含 Adobe 安装日志和权限信息 / Standalone diagnostics, including Adobe installation logs and permission context |

安装包 / Installer: **18,991,814 bytes**

SHA-256:

```text
d06e8fe31c9e090997fb946c50b67e6bcd05b7f7a3da965299b17a9fe0681bd3
```

[GitHub Releases](https://github.com/xBADBRUSHx/OP-Pop-Up-HUD/releases) · [产品页面 / Product page](https://badbrush.org/op-popup-hud/)

本次仅修订安装器和诊断工具，插件版本仍为 **2.0.1**。已安装且使用正常的用户无需重复安装；此前安装失败的用户可下载本次修订重试。同版本不会弹出新版本提醒。

This revision changes the installer and diagnostics only; the plugin remains **2.0.1**. Existing users with a working installation do not need to reinstall. If installation previously failed, retry with this revision. There is no new-version notification for the same version.

## 安装与迁移 / Install and migrate

首次安装：保存作品，退出 Photoshop 和 HUD，双击 Setup。安装完成后，从 Photoshop **增效工具 → OP Pop-Up HUD → OP Pop-Up HUD · 设置** 打开，用邮箱和激活码激活，或领取 7 天试用。

用过 2.0.0 之前的 HUD：直接运行 Setup，按提示确认迁移。安装器会自动备份、清理并继续安装，通常无需单独运行 Cleaner。旧配置会重置，购买权益、设备身份和作品保留；安装后使用原邮箱和激活码。正常 2.x 升级保留设置与授权。

检测到已识别的独立 OK-Record（已验证 1.0.9、1.0.15）时，可选择在 HUD 安装成功后移除旧插件；录制数据和备份保留。独立 Cleaner 仅用于手动维护旧版 HUD，详见[说明](docs/Legacy-Cleanup.zh-CN.md)。

First install: save your work, close Photoshop and HUD, then run Setup normally. Open **Plugins → OP Pop-Up HUD → OP Pop-Up HUD · 设置** in Photoshop, then activate or start the 7-day trial.

Upgrading from a version before 2.0.0: run Setup and confirm migration when prompted. Setup backs up and cleans the old installation before continuing; the standalone Cleaner is normally unnecessary. Old settings reset; purchase rights, device identity, and artwork remain. Use your original email and activation code again. Normal 2.x updates retain settings and authorization.

For recognized standalone OK-Record installations (verified versions: 1.0.9 and 1.0.15), Setup offers to remove the old plugin after HUD installs successfully. Recording data and backups remain. The standalone Cleaner is only for manual maintenance of pre-2.0.0 HUD installations.

## 用户指南 / Guides

- [中文完整指南](docs/User-Guide.zh-CN.md) · [离线 HTML 指南](docs/User-Guide.zh-CN.html)
- [English quick guide](docs/User-Guide.en.md)
- [2.0.1 更新说明](docs/release-notes-2.0.1.zh-CN.md) · [2.0.0 历史说明](docs/release-notes-2.0.0.zh-CN.md)

## 系统要求 / Requirements

- Windows 10 or Windows 11, 64-bit
- Adobe Photoshop 2024 (25.1.0) or later
- Adobe Creative Cloud Desktop

## 支持 / Support

在 **设置 → 账户与帮助** 点击 **生成问题报告**；安装出错时，Setup 的错误页面会显示该按钮，正常页面不显示。插件打不开时，也可使用上面的独立 Report Tool。将生成的 ZIP 发到 **100209743@qq.com** 并说明问题。报告工具不会自动发送。

Create a report from **Account & Help (账户与帮助)**, a Setup error page, or the standalone Report Tool. Setup shows the report button only when an error occurs. Send its ZIP and a short description to **100209743@qq.com**. The tool does not send reports automatically.

## 公开范围 / Public scope

本仓库仅发布用户文档、版本说明和正式安装包，不包含产品源码、构建系统、激活服务私密数据或内部工程资料。

This repository publishes user documentation, release notes, and production installers only. OP Pop-Up HUD is proprietary software; no open-source license is granted by this repository.
