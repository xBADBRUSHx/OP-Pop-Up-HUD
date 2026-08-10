# OP Pop-Up HUD 中文使用说明

## 系统要求

- Windows 10 或 Windows 11，64 位
- Adobe Photoshop 2024（25.1.0）或更高版本
- Adobe Creative Cloud Desktop

## 安装

1. 保存 Photoshop 文档并关闭 Photoshop。
2. 从 [GitHub Releases](https://github.com/xBADBRUSHx/OP-Pop-Up-HUD/releases/latest) 下载最新的 `OP Pop-Up Setup` 安装包。
3. 运行安装包并允许所需的管理员权限；安装程序会通过 Adobe Creative Cloud 的 UPIA 安装插件，不需要选择 Photoshop 目录。
4. 安装完成后重新启动 Photoshop。
5. 在 Photoshop 的“增效工具”菜单中打开 `OP Pop-Up HUD`。
6. 使用购买邮箱和激活码完成激活，或开始 14 天试用。

如果安装程序提示缺少 Adobe Unified Plugin Installer Agent（UPIA），请安装或修复 [Adobe Creative Cloud Desktop](https://helpx.adobe.com/download-install/apps/download-install-apps/creative-cloud-apps/download-creative-cloud-desktop-app-from-web.html)，然后重新运行 OP Pop-Up HUD 安装包。不要从第三方来源下载 UPIA。

## 基本操作

- 按住 `Q`：显示 OP Pop-Up HUD；松开按键时关闭。
- 按住 `S` 并水平移动鼠标或数位笔：调整当前画笔大小。
- `Shift + 鼠标中键` 点击 slot：把当前 Photoshop 画笔分配到该 slot。
- `Shift + Alt + 鼠标中键` 点击 slot：清空该 slot。
- 点击已分配的画笔或工具 slot：切换到对应内容。
- Q HUD 右下角的三个固定按钮依次用于切换画笔/混合器画笔、选择涂抹工具和水平镜像视图。
- 快捷键、HUD 尺寸、slot 数量及间距可在 `OP Pop-Up HUD` 面板中调整。

OP Pop-Up HUD 不提供主动调节画笔不透明度的控件。

## 自动更新

有新版本时，Q HUD 右上角会显示蓝色更新图标。点击后：

1. 更新器提示先保存 Photoshop 文档。
2. 更新器从 BADBRUSH 自动更新服务下载安装包并校验 SHA256。
3. 下载完成后，关闭 Photoshop 和 OP Pop-Up。
4. 点击“重试”启动安装程序并完成更新。

更新器不会强制关闭 Photoshop。也可以随时从 GitHub Releases 手动下载并安装最新版本。

## 卸载

在 Windows“设置 > 应用 > 已安装的应用”中卸载 `OP Pop-Up`。卸载会移除插件和启动组件，但会保留用户设置，以便以后重新安装时继续使用。

## 安装包校验

每个 GitHub Release 都提供 SHA256。可在 PowerShell 中校验：

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\OP Pop-Up Setup.exe'
```

输出应与对应 Release 页面公布的 SHA256 完全一致。
