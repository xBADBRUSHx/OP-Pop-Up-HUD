# OP Pop-Up HUD User Guide

## System Requirements

- Windows 10 or Windows 11, 64-bit
- Adobe Photoshop 2024 (25.1.0) or later
- Adobe Creative Cloud Desktop

## Installation

1. Save your Photoshop documents and close Photoshop.
2. Download the latest `OP Pop-Up Setup` installer from [GitHub Releases](https://github.com/xBADBRUSHx/OP-Pop-Up-HUD/releases/latest).
3. Run the installer and allow the requested administrator permission. The installer uses Adobe Creative Cloud UPIA and does not require a Photoshop folder.
4. Restart Photoshop after installation completes.
5. Open `OP Pop-Up HUD` from the Photoshop Plugins menu.
6. Activate the product with your purchase email and activation code, or start the 14-day trial.

If the installer reports that Adobe Unified Plugin Installer Agent (UPIA) is missing, install or repair [Adobe Creative Cloud Desktop](https://helpx.adobe.com/download-install/apps/download-install-apps/creative-cloud-apps/download-creative-cloud-desktop-app-from-web.html), then run the OP Pop-Up HUD installer again. Do not download UPIA from third-party sources.

## Basic Controls

- Hold `Q`: show the OP Pop-Up HUD; release the key to close it.
- Hold `S` and move the mouse or pen horizontally: adjust the current brush size.
- `Shift + middle-click` a slot: assign the current Photoshop brush to that slot.
- `Shift + Alt + middle-click` a slot: clear that slot.
- Click an assigned brush or tool slot: switch to its assigned content.
- The three fixed buttons at the lower right of the Q HUD switch Brush/Mixer Brush, select Smudge, and mirror the view horizontally.
- Shortcuts, HUD size, slot count, and spacing can be changed in the `OP Pop-Up HUD` panel.

OP Pop-Up HUD does not provide an active brush-opacity control.

## Automatic Updates

When a newer version is available, a blue update icon appears at the upper right of the Q HUD. Click it to start the update flow:

1. The updater asks you to save your Photoshop documents.
2. It downloads the installer from the BADBRUSH automatic-update service and verifies its SHA256.
3. After the download completes, close Photoshop and OP Pop-Up.
4. Click Retry to launch the installer and complete the update.

The updater does not force-close Photoshop. You can also download and install the latest version manually from GitHub Releases.

## Uninstallation

Uninstall `OP Pop-Up` from Windows Settings > Apps > Installed apps. Uninstallation removes the plugin and startup components but preserves user settings for a future reinstall.

## Verifying the Installer

Each GitHub Release publishes a SHA256 value. Verify a downloaded installer in PowerShell with:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\OP Pop-Up Setup.exe'
```

The result must exactly match the SHA256 published on the corresponding Release page.
