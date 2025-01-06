# DirectoryOpus-DFIRConfig

A config file for [Directory Opus](https://www.gpsoft.com.au/) that's curated specifically for DFIR examiners with shortcuts to common Windows artifacts and settings enabled that help make your life easier with various file management tasks.

## Change Log

| Date       | Comments                                       | Filename(s)                                                                        |
|------------|------------------------------------------------|----------------------------------------------------------------------------------|
| 2025-01-06 | Initial release for Directory Opus v13                                | [V1](https://github.com/AndrewRathbun/DirectoryOpus-DFIRConfig/tree/main/Old/V1) |

## Why Should I Care? Isn't Windows File Explorer Good Enough?

Sure it's good enough, but you don't know what you don't know if you've never used an alternative to File Explorer before, be it Directory Opus or another application ([XYPlorer](https://www.xyplorer.com/) would be my choice if DOpus didn't exist). Things Windows File Explorer cannot do that saves an immeasurable amount of time when using Directory Opus:

1. Flat View
2. Copy files from multiple folders into the same destination folder with choice to recreate (or ignore) each file's directory structure
3. Queue and stack multiple copy tasks with various unattended options (Have you ever copy something overnight only to find it stalled an hour into it when you wake up the next day?)
4. Create multiple folders all at once
5. Robust searching including but not limited to filenames and file contents
6. Calculate folder sizes, not just file sizes
7. Hash files
8. Copy filenames and full pathnames of all highlighted files in the right click context menu
9. ...and many, many more!

## Details of this Directory Opus Config File

Here's a rundown of what modifications I made to the default configuration of Directory Opus. 

* Dual Horizontal (Lister) and Dual Folder Tree

![DualHorizontalandDualFolderTree](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/refs/heads/main/Media/v13/DualHorizontalandDualFolderTree.gif)

* Enabled automatic folder size calculation

![CalculateFolderSizes](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/v13/CalculateFolderSizes.jpg)

* Enabled filter bar by default

![DisplayFilterBar](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/v13\DisplayFilterBar.png)

* Enabled Highlight Path to Selected Folder by default

![HighlightPathtoSelectedFolder](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/v13/HighlightPathtoSelectedFolder.jpg)

* New tab default opens This PC

![NewTabDefaultToThisPC](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/v13/NewTabDefaultToThisPC.pn)

* Display drive letter in tab label

![DisplayDriveLetterTabLabel](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/v13/DisplayDriveLetterTabLabel.png)

* Enabled automatic folder size enumeration for Network Drives by default

![NetworkDrivesAutoLoadonTabActivation.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media/v13/NetworkDrivesAutoLoadonTabActivation.png)


* Enabled relative graphs for File Size and Last Modified timestamp

![RelativeGraphsSizeModifiedDate.jpg](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media//v13/RelativeGraphsSizeModifiedDate.png)

* Enabled PowerShell Here (Admin) and Command Prompt Here (Admin) in the right-click context menu

Function: `CLI DOSPROMPT=powershell,admin,nocolor`
Function: `CLI DOSPROMPT=admin,nocolor`

![PSandCMDAdminAddToContextMenu.gif](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media//v13/PSandCMDAdminAddToContextMenu.gif)

* Add Seconds and Milliseconds to any Time column

![SecondsMillisecondsTimeColumn](https://raw.githubusercontent.com/AndrewRathbun/DirectoryOpus-DFIRConfig/main/Media//v13/SecondsMillisecondsTimeColumn.png)

# Feedback

What do you like? What don't you like? Let me know and I'll consider adding or changing it for the greater good!

# Resources

Want to learn more about Directory Opus and how insanely customizable it is? Look no further!

* [Directory Opus on YouTube](https://www.youtube.com/c/DirectoryOpus)
* [Directory Opus (File Manager) - Customization / Layout / Look 'n Feel](https://www.youtube.com/watch?v=x5fH2H2APOY)
* [Directory Opus: Personalize Folder Colors, Columns, Labels and more!](https://www.youtube.com/watch?v=-L8ybqqUmFo)
* [Directory Opus: Using System-Wide Hotkeys to Control Audio Output (and almost anything else)](https://www.youtube.com/watch?v=Zq7xxOla1Zk)
* [Directory Opus meets Quick Access Popup - Discussing 2 great productivity tools](https://www.youtube.com/watch?v=4HGl09aVFgA)
* [How to use your Folder's Icon in the Taskbar with Directory Opus](https://www.youtube.com/watch?v=aBiqOzHa2r8)
* [How to create buttons in Directory Opus & learn more amazing tips!](https://www.youtube.com/watch?v=vlh5XqIykLw)
* [Directory Opus 13: Highlights](https://www.youtube.com/watch?v=K57m_Ogy8Lg)
* [Directory Opus: Toolbar Editing](https://www.youtube.com/watch?v=ZM-B-YJzqjA)
* [Directory Opus YouTube Playlist by MonroeWorld](https://www.youtube.com/playlist?list=PLMcmWOVaPtGmxhrZUr10C8PBb5DGVCnEv)

# TO ADD (NEXT RELEASE)

Nothing at this time! Suggest something new in an Issue!
