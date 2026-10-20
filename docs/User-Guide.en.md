# OP Pop-Up HUD 2.0.2 User Guide

For Windows 10/11 64-bit and Photoshop 2024 (25.1) or later.

See the [complete Chinese guide](User-Guide.zh-CN.md) for detailed instructions.

## Install and activate

1. Save your work, close Photoshop and HUD, and run Setup.
2. Open Photoshop, then **Plugins → OP Pop-Up HUD → OP Pop-Up HUD · 设置**. Allow the HUD launch permission when prompted.
3. Enter your email and activation code, or enter your email to start the **7-day trial**.

The trial runs for seven consecutive days after it is first claimed. Reinstalling or clearing local activation does not restart it. Initial activation and trial registration require an internet connection.

Setup automatically handles old programs and installation remnants. Existing settings and authorization are preserved. Creative Cloud installation or sign-in is not required. There is no need to uninstall first or run the standalone cleaner.

Keep using the same Windows account during installation and any permission prompt.

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

**Alt + left-click either Toolbar color swatch** resets foreground/background colors, like Photoshop's **D**. **Shift + left-click either swatch** exchanges them, like **X**. Double-click the foreground swatch to open Photoshop's color picker.

To add either action to the command palette, hold **Z**, **Shift + middle-click** a slot, then choose **Edit (编辑) → Reset foreground/background colors (重置前后景色)** or **Exchange foreground/background colors (调换前后景色)**. You can also assign these commands in **Commands & Toolbar (命令与工具栏)** settings. New command-palette groups start empty; existing assignments are preserved.

## Recording and timers

Set the save folder, sampling interval, and resolution in **Recording & Export (录制与导出)**. Click the Toolbar recording button to start, pause, or resume. **Shift + Alt + left-click** stops recording. Pause or stop before exporting a video. FFmpeg is included; no separate installation is needed.

Recording uses 8-bit output. A 16-bit source is converted for recording; 32-bit HDR documents are unsupported. The original document is unchanged.

Click a timer to start, pause, or resume it. **Hold the left mouse button for about half a second** to open its controls, choose a mode, set a countdown, or stop the timer.

## Update, uninstall, and get help

When an update is available, click **NEW** on the Toolbar. After choosing Later, you can return through **Account & Help (账户与帮助)** to install that update. Wait for the download and verification; when Setup asks, save your work, close Photoshop and HUD, then continue installation. Normal 2.x updates preserve settings and authorization. No previous installer is required.

To uninstall, close Photoshop and HUD, then remove **OP Pop-Up** from Windows **Settings → Apps → Installed apps**. Settings, authorization data, and recording files remain for a future reinstall. For same-version repair, run Setup again.

For help, generate a problem report from **Account & Help** or a Setup error page. Send the ZIP and a description to **100209743@qq.com**. The report is not sent automatically and does not collect artwork.

The [standalone cleaner](Legacy-Cleanup.zh-CN.md) is for manual maintenance. Normal installation and updates do not require it. It preserves settings, authorization, brushes, and recordings by default.
