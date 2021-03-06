#[Reddit Wallpaper Changer](https://www.reddit.com/r/rwallpaperchanger/)
Based on [RWC-Source](https://github.com/JosephRobidoux/RWC-Source) originally created by [Joseph Robidoux](https://github.com/JosephRobidoux)

# About
Reddit Wallpaper Changer is a lightweight C# application for Windows that will scrape Reddit for desktop wallpapers. You can specify which subs to scrape from and how oftern to rotate your wallpaper.

# Current Version - 1.0.12.0
- Hotfix: Issue where RWC closed fully instead of minimising to System Tray

# Version 1.0.11.0 Changes 
- Added: Option to allow/prevent reuse of wallpapers
- Added: Mini 'info' popup to display wallaper title, thread & thumbnail
- Added: Wallpaper size validation (ensures wallpapers match your resolution)
- Added: Button to instantly upload log file to Pastebin
- Fixed: Monitor detection now working (supports up to 3 monitors currently)
- Fixed: Incorrect tool tip text for 'Auto Save Wallpapers' option
- Fixed: Bug where choosing 7+ days to change wallpaper caused RWC to crash
- Changed: Log file cap changed from 1Mb to 500Kb to meet Pastebin requirements
- Changed: "No results after 50 attempts" now a notification instead of message box

# Installation
Download the latest MSI installer from the [releases page](https://github.com/Rawns/Reddit-Wallpaper-Changer/releases)
