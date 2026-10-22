# OP Pop-Up HUD 清理工具

普通安装和更新直接运行安装包即可。仅当安装器提示需要清理旧安装，或需要主动移除旧程序再重装时，使用配套的独立清理工具。

1. 关闭 Photoshop、OP Pop-Up HUD 和更新程序。
2. 将 ZIP 全部解压，双击 `Start-Cleanup.cmd`。
3. 查看提示，输入 `CLEAN` 确认。需要权限确认时，保持使用同一个 Windows 账户。
4. 完成后重新安装 OP Pop-Up。

默认保留授权、设置、笔刷和录制作品。程序目录中的额外文件会归档保留；备份位置为 `%LOCALAPPDATA%\BADBRUSH\HUD-Cleanup-Backups`。

- 需要同时移除独立 OK-Record：运行 `Start-Cleanup.cmd -IncludeOKRecord`，录制和个人数据保留。
- 需要重置设置：运行 `Start-Cleanup.cmd -ResetSettings`，授权和作品保留。
- 需要清除本机授权：清理前使用插件“设置 → 授权 → 管理授权”中的清除入口。

清理未完成时，请保留提示和备份，按提示处理后重新运行。仍无法完成时，将截图发至 **100209743@qq.com**。请勿使用历史版本的清理工具。
