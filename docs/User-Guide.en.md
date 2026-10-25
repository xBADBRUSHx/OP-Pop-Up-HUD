# OP Pop-Up HUD 2.0.6 User Guide

For Windows 10/11 64-bit and Photoshop 2024 (25.1) or later.

See the [complete Chinese guide](User-Guide.zh-CN.md) for detailed instructions.

## Install and activate

1. Save your work, close Photoshop and HUD, and run Setup.
2. Open Photoshop, then **Plugins → OP Pop-Up HUD → OP Pop-Up HUD · 设置**. Allow the HUD launch permission when prompted.
3. Enter your email and activation code, or enter your email to start the **7-day trial**.

The trial runs for seven consecutive days after it is first claimed. Reinstalling or clearing local activation does not restart it. Initial activation and trial registration require an internet connection.

Run Setup directly for normal updates and same-version repair. Settings, authorization, brushes, and recordings are preserved. Creative Cloud installation or sign-in is not required. If Setup asks you to clean an old installation, run the accompanying standalone cleaner first, then run Setup again.

If Setup reports that Photoshop or HUD is still running, keep Setup open, save your work, close the listed applications, and click **Continue installation (已关闭，继续安装)**. Click **Back (返回)** to return to the ready-to-install page. Setup does not forcibly close applications.

Keep using the same Windows account during installation and any permission prompt.

## Default controls

Keep Photoshop in the foreground and move the pointer over the canvas. Shortcuts can be changed in **Settings → General & Shortcuts (通用快捷键)**.

| Action | Result |
| --- | --- |
| Hold **Q** | Open the cursor-near color picker. |
| Hold **W** | Open brush favorites without changing the current tool. |
| Press **E / R** | Select Eraser / Smudge; keep holding to open its favorites. |
| Hold **Z** | Open the command palette. |
| Hold **F** | Immediately show blend-mode favorites. Release to select; release over the center to keep the current mode. |
| Hold **S** and move horizontally | Change brush size. |
| Hold **S + right mouse button** and move horizontally | Change opacity. |
| Hold **S + left mouse button** and move vertically | Change brush angle. |

Point to a palette slot and release the shortcut to select it, or left-click the slot. Release over the center to cancel. Use **Shift + middle-click** to assign the current brush to a brush slot and **Shift + Alt + middle-click** to clear it. While holding W or Z, press the corresponding group number to switch groups.

While holding **Q**, press **W / E** to increase / decrease lightness. To adjust hue, assign **Decrease hue (降低色相)** and **Increase hue (增加色相)** in **General & Shortcuts**; both are unassigned by default. Use them while holding Q, or keep them pressed for repeated adjustment. Set the independent lightness and hue steps in **Color Picker (颜色拾色器)** settings. Hue starts at **1°** per step, accepts **1°–360°**, and wraps around the color wheel.

To use A/D for brush size, assign Photoshop's native `[`/`]` commands to A/D in Photoshop's keyboard shortcuts.

**Alt + left-click either Toolbar color swatch** resets foreground/background colors, like Photoshop's **D**. **Shift + left-click either swatch** exchanges them, like **X**. Double-click the foreground swatch to open Photoshop's color picker.

To add either action to the command palette, hold **Z**, **Shift + middle-click** a slot, then choose **Edit (编辑) → Reset foreground/background colors (重置前后景色)** or **Exchange foreground/background colors (调换前后景色)**. You can also assign these commands in **Command Palette (命令面板)** settings. New command-palette groups start empty; existing assignments are preserved.

Brush, Eraser, Smudge, Command and Blend Mode palettes share one size setting in **General & Shortcuts → General (通用) → Quick palette size (%) (快捷面板大小)**. Follow the global HUD size or set a shared 50–200% size. In the same section, **Quick palette highlight color (快捷面板高亮颜色)** changes their slot hover fills and selected outlines. Enter a `#RRGGBB` value and confirm; the default is yellow `#FFB219`.

## Arrange the Toolbar

- Hold the middle mouse button over a tool and drag to reorder it or drag it out to remove it.
- Open **…** to bring a tool back. When the Toolbar is empty, drag a tool onto **…** to restore the first item. A short middle-click on a tool in that menu also appends it.
- In **Toolbar (工具栏) → Toolbar slots (工具栏槽位)**, choose a tool or command in **Add tool or command (添加工具或命令)**, then click **Add Toolbar slot (添加工具栏槽位)**. Existing items are excluded from the add list.
- In **Toolbar → Brush parameters (笔刷参数)**, enable opacity, flow, hardness and angle circles individually. Disabled circles leave no gaps. The main visibility switch and middle-click on the painting-tool icon retain these choices.

To restore the initial configuration, open **General & Shortcuts** and select **Restore initial settings (恢复初始设置)** at the bottom. After confirmation, interface preferences, shortcuts, brush favorites and tool/command slots are reset. Authorization, artwork, recording projects and custom icon files are retained. Review the confirmation before replacing your custom configuration.

## Recording and timers

Set the save folder, sampling interval, and resolution in **Recording & Export (录制导出)**. Click the Toolbar recording button to start, pause, or resume. **Shift + Alt + left-click** stops recording. Pause or stop before exporting a video. FFmpeg is included; no separate installation is needed.

Recording uses 8-bit output. A 16-bit source is converted for recording; 32-bit HDR documents are unsupported. The original document is unchanged.

Click a timer to start, pause, or resume it. **Hold the left mouse button for about half a second** to open its controls, choose a mode, set a countdown, or stop the timer.

Hover over the timer to see its current mode and state. Painting time displays **Waiting for painting (等待绘画)** before painting begins; it pauses after the configured idle interval and resumes when painting continues.

## Update, uninstall, and get help

When an update is available, click **NEW** on the Toolbar and open the update action in Account & Help. Read the update notes, then choose **Download and install** or **Later**. After choosing Later, you can return through **Account & Help (账户帮助)** to install that update. Wait for the download and verification; when Setup asks, keep Setup open, save your work, close the listed Photoshop and HUD processes, then click **Continue installation (已关闭，继续安装)**. Normal updates preserve settings and authorization. If Setup asks you to clean an old installation, use the accompanying cleaner before continuing.

The update-notes window keeps its action buttons visible while long notes scroll. **Later** is the default action; press **Esc** to cancel without starting installation. If the offered update changes, the old confirmation window closes. Older clients can already receive grouped update text, but the new window layout is provided by version 2.0.6 and appears for subsequent update prompts after upgrading.

To uninstall, close Photoshop and HUD, then remove **OP Pop-Up** from Windows **Settings → Apps → Installed apps**. Settings, authorization data, and recording files remain for a future reinstall. For same-version repair, run Setup again.

For help, generate a problem report from **Account & Help** or a Setup error page. Send the ZIP and a description to **100209743@qq.com**. The report is not sent automatically and does not collect artwork.

Use the [standalone cleaner](Legacy-Cleanup.zh-CN.md) when Setup asks you to clean an old installation or when you choose to remove old programs manually. It preserves settings, authorization, brushes, and recordings by default. Use the cleaner supplied with the current release.
