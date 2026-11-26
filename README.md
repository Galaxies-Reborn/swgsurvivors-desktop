# SWG Survivors for Windows

The desktop version of [SWG Survivors](https://swgsurvivors.gg), for players with their own Star Wars Galaxies install. It plays with enhanced graphics and music from that install. Without an install, play the free web version at [swgsurvivors.gg](https://swgsurvivors.gg).

## Download

| System | Download |
|---|---|
| Windows 10 or 11 | [SWG-Survivors-Setup.exe](https://github.com/Galaxies-Reborn/swgsurvivors-desktop/releases/latest/download/SWG-Survivors-Setup.exe) |
| Steam Deck and Linux | [SWG-Survivors-linux-x86_64.AppImage](https://github.com/Galaxies-Reborn/swgsurvivors-desktop/releases/latest/download/SWG-Survivors-linux-x86_64.AppImage), or the [.deb](https://github.com/Galaxies-Reborn/swgsurvivors-desktop/releases/latest/download/SWG-Survivors-linux-amd64.deb) for Debian and Ubuntu |
| Mac with Apple silicon | [SWG-Survivors-mac-arm64.dmg](https://github.com/Galaxies-Reborn/swgsurvivors-desktop/releases/latest/download/SWG-Survivors-mac-arm64.dmg) |
| Mac with Intel | [SWG-Survivors-mac-x64.dmg](https://github.com/Galaxies-Reborn/swgsurvivors-desktop/releases/latest/download/SWG-Survivors-mac-x64.dmg) |

Earlier versions are on the [releases page](https://github.com/Galaxies-Reborn/swgsurvivors-desktop/releases).

**Windows:** the installer sets the game up for your Windows account only and doesn't need administrator rights. It isn't code-signed yet, so Windows SmartScreen may say it protected your PC. Choose **More info**, then **Run anyway**.

**Steam Deck:** in Desktop Mode, download the AppImage, right-click it, open **Properties → Permissions**, and tick **Is executable**. To play in Game Mode, right-click it again and choose **Add to Steam**. The game supports the Deck's controls.

**Linux:** make the AppImage executable (`chmod +x SWG-Survivors-linux-x86_64.AppImage`) and run it. Only the AppImage updates itself; the .deb is updated by installing a newer one.

**Mac:** the app isn't signed by Apple, so macOS refuses to open it the first time. Drag it to Applications, then run `xattr -dr com.apple.quarantine "/Applications/SWG Survivors.app"` in Terminal, or open **System Settings → Privacy & Security** and choose **Open Anyway**.

## First start

The game asks for your Star Wars Galaxies install folder and lists any installs it finds on your computer. It only reads that folder and never changes it, so your game keeps working as before and both can run at the same time.

The first time you play, your characters and first drop site are prepared, which takes about a minute. Other drop sites are prepared the first time you pick them. Prepared files are kept in `%LOCALAPPDATA%\SWGSurvivors\cache`.

## Updates

The game checks this page for a newer version each time it starts. If one is available it installs it, then restarts.

## Requirements

Windows 10 or 11, macOS 11 or later, or a 64-bit Linux such as SteamOS, with a graphics card that supports WebGL 2. You need your own Star Wars Galaxies install for the enhanced graphics.

This repository holds releases only. The game's source is kept elsewhere.
