# OP Pop-Up HUD 2.0.0 User Guide

For Windows 10/11 64-bit, Photoshop 2024 (25.1.0) or later, and Adobe Creative Cloud Desktop.

See the [complete Chinese guide](User-Guide.zh-CN.md) or its [offline HTML edition](User-Guide.zh-CN.html) for detailed instructions.

## Install and activate

1. **Used a HUD version before 2.0.0?** Download the Cleaner from the [download page](../README.md), extract the entire ZIP, close Photoshop and HUD, then run `Start-Cleanup.cmd` normally. Review the list and enter uppercase `CLEAN`. Continue only after cleanup succeeds. Accept an elevation prompt if the cleaner requests it; keep using the same Windows account.
2. Save your work, close Photoshop and HUD, and run the 2.0.0 Setup normally. Do not use **Run as administrator**. If Setup offers to replace standalone OK-Record, its recording files are retained.
3. Open Photoshop, then **Plugins → OP Pop-Up HUD → OP Pop-Up HUD · 设置**. Allow the HUD launch permission when first prompted.
4. Enter your email and activation code, or enter your email to start the **7-day trial**. Old customers use their original email and code again.

The trial runs for seven consecutive days after it is first claimed. Reinstalling or clearing local activation does not restart it. Initial activation and trial registration require an internet connection.

Migration resets old shortcuts, layouts, and slots while preserving purchase rights, device identity, and artwork. Do not use the legacy cleaner on 2.0.0 or later.

If Setup reports that Adobe UPIA is missing, install or repair [Creative Cloud Desktop](https://helpx.adobe.com/download-install/apps/download-install-apps/creative-cloud-apps/download-creative-cloud-desktop-app-from-web.html), then rerun Setup.

## Default controls

Keep Photoshop in the foreground and move the pointer over the canvas. Shortcuts can be changed in settings.

| Action | Result |
| --- | --- |
| Hold **Q** | Open the cursor-near color picker. |
| Hold **W** | Open brush favorites without changing the current tool. |
| Press **E / R** | Select Eraser / Smudge; keep holding to open its favorites. |
| Hold **Z** | Open the command palette. |
| Press **F** | Restore Normal brush blend mode; keep holding for blend-mode favorites. |
| Hold **S** and move horizontally | Change brush size. |
| Hold **S + right mouse button** and move horizontally | Change opacity. |
| Hold **S + left mouse button** and move vertically | Change brush angle. |

Point to a palette slot and release the shortcut to select it, or left-click the slot. Release over the center to cancel. Use **Shift + middle-click** to assign the current brush to a brush slot and **Shift + Alt + middle-click** to clear it. While holding W or Z, press the corresponding group number to switch groups.

To use A/D for brush size, assign Photoshop's native `[`/`]` commands to A/D in Photoshop's keyboard shortcuts.

## Recording and timers

Set the save folder, sampling interval, and resolution in **Recording & Export (录制与导出)**. Click the Toolbar recording button to start, pause, or resume. **Shift + Alt + left-click** stops recording. Pause or stop before exporting a video. FFmpeg is included; no separate installation is needed.

Recording uses 8-bit output. A 16-bit source is converted for recording; 32-bit HDR documents are unsupported. The original document is unchanged.

Click a timer to start, pause, or resume it. **Hold the left mouse button for about half a second** to open its controls, choose a mode, set a countdown, or stop the timer.

## Update, uninstall, and get help

When an update is available, click **NEW** on the Toolbar. After choosing Later, you can return through **Account & Help (账户与帮助)** to install that update. Save your work and close Photoshop and HUD when the updater asks, then click Retry. Normal 2.x updates preserve settings and authorization.

To uninstall, close Photoshop and HUD, then remove **OP Pop-Up** from Windows **Settings → Apps → Installed apps**. Settings, authorization data, and recording files remain for a future reinstall. For same-version repair, run Setup again.

For help, generate a problem report from **Account & Help**, Setup, or the standalone [Report Tool](../README.md). Send the resulting ZIP and a description to **100209743@qq.com**. The tool does not send it automatically or collect artwork.

## Verify the download

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\OP-Pop-Up-HUD-Setup-2.0.0.exe'
```

Compare the result with the SHA-256 on the [download page](../README.md). The current installer is unsigned; check its source and file information before continuing.
